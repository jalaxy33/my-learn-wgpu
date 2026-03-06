# Tutorial 1: Window

Tutorial: [Dependencies and the window](https://sotrh.github.io/learn-wgpu/beginner/tutorial1-window/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial1-window
  ```

- Build webassembly:

  1. Build the wasm:

      ```sh
      wasm-pack build --target web code/beginner/tutorial1-window
      ```

  2. Serve the files
   
      Open `code/beginner/tutorial1-window/index.html` in a web browser. Or server the project directory:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial1-window 
      ```

      Then open `http://localhost:8080` in web browser.

