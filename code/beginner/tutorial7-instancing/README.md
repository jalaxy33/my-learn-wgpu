# Tutorial 7: Instancing

Tutorial: [Instancing](https://sotrh.github.io/learn-wgpu/beginner/tutorial7-instancing/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial7-instancing
  ```

- Build webassembly:
  1. Build the wasm:

     ```sh
     wasm-pack build --target web code/beginner/tutorial7-instancing
     ```

  2. Launch a web server:

     Open `code/beginner/tutorial7-instancing/index.html` in a web browser. 
     Or run a local HTTP server:

     ```sh
     # install `simple-http-server` if you don't have it
     cargo install simple-http-server

     simple-http-server -i -p 8080 code/beginner/tutorial7-instancing
     ```

     Then open `http://localhost:8080` in web browser.
