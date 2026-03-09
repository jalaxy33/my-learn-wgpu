# Tutorial 2: Surface

Tutorial: [The Surface](https://sotrh.github.io/learn-wgpu/beginner/tutorial2-surface/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial2-surface
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/beginner/tutorial2-surface
     ```

  2. Launch a web server:

     Open `code/beginner/tutorial2-surface/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i -p 8080 code/beginner/tutorial2-surface
     ```

     Then open `http://localhost:8080` in web browser.
