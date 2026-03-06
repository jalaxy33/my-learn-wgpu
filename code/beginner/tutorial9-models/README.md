# Tutorial 9: Model Loading

Tutorial: [Model Loading](https://sotrh.github.io/learn-wgpu/beginner/tutorial9-models/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial9-models
  ```

- Build webassembly:

  1. Build the wasm:

      ```sh
      wasm-pack build --target web code/beginner/tutorial9-models
      ```

  2. Serve the files
   
      Open `code/beginner/tutorial9-models/index.html` in a web browser. Or run a local HTTP server:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial9-models 
      ```

      Then open `http://localhost:8080` in web browser.

