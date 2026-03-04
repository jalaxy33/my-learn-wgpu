# Tutorial 1: Window

Tutorial: [Dependencies and the window](https://sotrh.github.io/learn-wgpu/beginner/tutorial1-window/)

## Usage

- Run native Rust app:

  ```sh
  cargo run --release --bin tutorial1-window
  ```

- Build webassembly:

  ```sh
  wasm-pack build --target web code/beginner/tutorial1-window
  ```

  Then open `code/beginner/tutorial1-window/index.html` in a web browser.
