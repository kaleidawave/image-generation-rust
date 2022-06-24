# Generative metatag images in Rust

Code from https://www.shuttle.rs/blog/2022/06/23/generative-metatag-images

### Usage

- Run with `cargo run`
- Enter text when prompted
- Get cool ferris picture:

![](image.webp)

### Performance

Get tracing results when run with the `tracing` feature flag. `cargo run --features tracing`. **Note release builds are around 10x faster**.