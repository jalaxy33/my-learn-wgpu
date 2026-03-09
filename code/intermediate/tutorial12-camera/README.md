# Tutorial 12: A Better Camera

Tutorial: [A Better Camera](https://sotrh.github.io/learn-wgpu/intermediate/tutorial12-camera/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial12-camera
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/intermediate/tutorial12-camera
     ```

  2. Launch a web server:

     Open `code/intermediate/tutorial12-camera/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/intermediate/tutorial12-camera
     ```

     Then open `http://localhost:8080` in web browser.
