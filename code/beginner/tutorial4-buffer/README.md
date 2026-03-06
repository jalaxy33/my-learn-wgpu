# Tutorial 4: Buffers and Indices

Tutorial: [Buffers and Indices](https://sotrh.github.io/learn-wgpu/beginner/tutorial4-buffer/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial4-buffer
  ```

- Build webassembly:

  1. Build the wasm:

      ```sh
      wasm-pack build --target web code/beginner/tutorial4-buffer
      ```

  2. Serve the files
   
      Open `code/beginner/tutorial4-buffer/index.html` in a web browser. Or run a local HTTP server:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial4-buffer 
      ```

      Then open `http://localhost:8080` in web browser.

