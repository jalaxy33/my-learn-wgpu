# Tutorial 6: Uniform buffers and a 3d camera

Tutorial: [Uniform buffers and a 3d camera](https://sotrh.github.io/learn-wgpu/beginner/tutorial6-uniforms/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial6-uniforms
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/beginner/tutorial6-uniforms
     ```

  2. Launch a web server:

     Open `code/beginner/tutorial6-uniforms/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/beginner/tutorial6-uniforms
     ```

     Then open `http://localhost:8080` in web browser.
