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

  2. Serve the files
   
      Open `code/beginner/tutorial8-depth/index.html` in a web browser. Or run a local HTTP server:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial8-depth 
      ```

      Then open `http://localhost:8080` in web browser.
