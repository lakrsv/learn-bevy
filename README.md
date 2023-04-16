# Introduction
This repository contains code produced to learn Bevy, the game engine for Rust.

## WASM Build
```
rustup target install wasm32-unknown-unknown
cargo install wasm-server-runner
```

```
cargo run --release --target wasm32-unknown-unknown
```
OR (because of .cargo/config.toml)

```
cargo install cargo-watch
cargo watch -cx "run --release"
```

With cargo watch, you only have to refresh the browser