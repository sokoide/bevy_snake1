# Bevy Snake

* Snake tutorial in Rust at <https://mbuffett.com/posts/bevy-snake-tutorial/>

## Prereq

* Follow <https://bevy-cheatbook.github.io/platforms/wasm/cargo-make.html> and set up the env

```bash
# https://github.com/rustwasm/wasm-bindgen/issues/2559
cargo install -f wasm-bindgen-cli --version 0.2.69
```

## Run Local

```bash
cargo make run
```

## Make Wasm

```bash
cargo make serve
# visit localhost:4000
```

## Demo Site

* <https://lab.sokoide.com/snake/index.html>
