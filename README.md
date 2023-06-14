This repository contains the set of generic [Embassy](https://embassy.dev)
examples adjusted for the [Blues Swan](https://blues.io/products/swan) board.

## Running examples

- Install [rustup](https://rustup.rs/)

- Install the cross compiler target

```bash
rustup target add thumbv7em-none-eabi
```

- Install `probe-rs-cli` with defmt support.

```bash
cargo install probe-rs-cli
```

- Run the example

For example:

```bash
cargo run --release --bin blinky
```

## License

This work is licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

