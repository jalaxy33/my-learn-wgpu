# Tutorial 11: Normal Mapping

Tutorial: [Normal Mapping](https://sotrh.github.io/learn-wgpu/intermediate/tutorial11-normals/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial11-normals
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/intermediate/tutorial11-normals
     ```

  2. Launch a web server:

     Open `code/intermediate/tutorial11-normals/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/intermediate/tutorial11-normals
     ```

     Then open `http://localhost:8080` in web browser.
