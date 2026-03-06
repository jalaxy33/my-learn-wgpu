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

  2. Serve the files
   
      Open `code/beginner/tutorial2-surface/index.html` in a web browser. Or server the project directory:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial2-surface 
      ```

      Then open `http://localhost:8080` in web browser.

