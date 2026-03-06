# Tutorial 3: Pipeline

Tutorial: [The Pipeline](https://sotrh.github.io/learn-wgpu/beginner/tutorial3-pipeline/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial3-pipeline
  ```

- Build webassembly:

  1. Build the wasm:

      ```sh
      wasm-pack build --target web code/beginner/tutorial3-pipeline
      ```

  2. Serve the files
   
      Open `code/beginner/tutorial3-pipeline/index.html` in a web browser. Or server the project directory:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial3-pipeline 
      ```

      Then open `http://localhost:8080` in web browser.

