# Tutorial 6: Uniform buffers and a 3d camera

Tutorial: [Uniform buffers and a 3d camera](https://sotrh.github.io/learn-wgpu/beginner/tutorial6-uniforms/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial6-uniforms
  ```

- Build webassembly:

  1. Build the wasm:

      ```sh
      wasm-pack build --target web code/beginner/tutorial6-uniforms
      ```

  2. Serve the files
   
      Open `code/beginner/tutorial6-uniforms/index.html` in a web browser. Or server the project directory:

      ```sh
      python3 -m http.server 8080 -d code/beginner/tutorial6-uniforms 
      ```

      Then open `http://localhost:8080` in web browser.
