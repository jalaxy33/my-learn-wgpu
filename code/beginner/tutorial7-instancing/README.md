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

  2. Serve the files
   
      Open `code/beginner/tutorial7-instancing/index.html` in a web browser. Or server the project directory:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial7-instancing 
      ```

      Then open `http://localhost:8080` in web browser.

