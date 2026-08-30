# rusty_ansi

> **This repository has moved.** `rusty_ansi` now lives at
> [`crates/rusty_ansi`](https://github.com/Rusty-Mill/rusty_mill/tree/main/crates/rusty_ansi)
> in the [`rusty_mill`](https://github.com/Rusty-Mill/rusty_mill) monorepo, with full commit
> history preserved. This repository is kept for historical reference and is no longer
> developed; please open issues and pull requests against `rusty_mill` instead.

[![CI](https://github.com/baileyrd/rusty_ansi/actions/workflows/ci.yml/badge.svg)](https://github.com/baileyrd/rusty_ansi/actions/workflows/ci.yml)

A zero-allocation, `#![no_std]` VT100 / CSI / OSC ANSI escape sequence parser core for Rust.

`rusty_ansi` parses text streams into explicit ANSI tokens (`AnsiToken::Text`, `AnsiToken::Csi`, `AnsiToken::Osc`), strips ANSI color codes, and calculates visible display width (`visible_width`).

## License

Licensed under either of [Apache License, Version 2.0](./LICENSE-APACHE) or [MIT license](./LICENSE-MIT) at your option.
