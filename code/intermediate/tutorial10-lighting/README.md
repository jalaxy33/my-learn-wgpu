# Tutorial 10: Working with Lights

Tutorial: [Working with Lights](https://sotrh.github.io/learn-wgpu/intermediate/tutorial10-lighting/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial10-lighting
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/intermediate/tutorial10-lighting
     ```

  2. Launch a web server:

     Open `code/intermediate/tutorial10-lighting/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/intermediate/tutorial10-lighting
     ```

     Then open `http://localhost:8080` in web browser.
