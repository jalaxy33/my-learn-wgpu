# Tutorial 13: High Dynamic Range Renderinga

Tutorial: [High Dynamic Range Rendering](https://sotrh.github.io/learn-wgpu/intermediate/tutorial13-hdr/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial13-hdr
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/intermediate/tutorial13-hdr
     ```

  2. Launch a web server:

     Open `code/intermediate/tutorial13-hdr/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/intermediate/tutorial13-hdr
     ```

     Then open `http://localhost:8080` in web browser.

     > Note: Please enable `--enable-unsafe-webgpu` to support WebGPU in Chromium browsers to run the app.
