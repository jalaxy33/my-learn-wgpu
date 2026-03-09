# Tutorial 5: Textures and bind groups

Tutorial: [Textures and bind groups](https://sotrh.github.io/learn-wgpu/beginner/tutorial5-texture/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial5-texture
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/beginner/tutorial5-texture
     ```

  2. Launch a web server:

     Open `code/beginner/tutorial5-texture/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/beginner/tutorial5-texture
     ```

     Then open `http://localhost:8080` in web browser.
