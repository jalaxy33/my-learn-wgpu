# Tutorial 8: The Depth Buffer

Tutorial: [The Depth Buffer](https://sotrh.github.io/learn-wgpu/beginner/tutorial8-depth/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial8-depth
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/beginner/tutorial8-depth
     ```

  2. Launch a web server:

     Open `code/beginner/tutorial8-depth/index.html` in a web browser.
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i --nocache -p 8080 code/beginner/tutorial8-depth
     ```

     Then open `http://localhost:8080` in web browser.
