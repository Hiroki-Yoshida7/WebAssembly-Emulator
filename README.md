# nes-rust

[![Crate](https://img.shields.io/crates/v/nes_rust.svg)](https://crates.io/crates/nes_rust)
[![npm version](https://badge.fury.io/js/nes_rust_wasm.svg)](https://badge.fury.io/js/nes_rust_wasm)

nes-rust is a NES emulator written in Rust. It can be compiled to WebAssembly.

## Online Demos / Videos

- [Online Singleplay Demo](https://hirokiyoshida.github.io/nes-rust/wasm/web/index.html)
- [Online Multiplay Demo](https://hirokiyoshida.github.io/nes-rust/wasm/web/multiplay.html) / [Video](https://twitter.com/superhoge/status/1205427421010247680)
- [Online VR Multiplay Demo](https://hirokiyoshida.github.io/nes-rust/wasm/web/vr.html) / [Video](https://twitter.com/superhoge/status/1209685614074875906)

## Screenshots

[nestest](http://wiki.nesdev.com/w/index.php/Emulator_tests)

![nestest](./screenshots/nestest.png)

[Sgt. Helmet Training Day](http://www.mojontwins.com/juegos_mojonos/sgt-helmet-training-day-nes/)

![Sgt. Helmet Training Day](./screenshots/Sgt_Helmet.png)

## Features

- Audio support with SDL2 / WebAudio
- WebAssembly support
- Remote multiplay support with WebRTC

## How to import into your Rust project

The emulator module and document are released at [crates.io](https://crates.io/crates/nes_rust).

## How to build core library locally

```
$ cd nes-rust
$ cargo build --release
```

## How to run as desktop application

Prerequirements
- Install [Rust-SDL2](https://github.com/Rust-SDL2/rust-sdl2#rust)

```
$ cd nes-rust/cli
$ cargo run --release path_to_rom_file
```

## How to import and use WebAssembly NES emulator in a web browser

See [wasm/web](https://github.com/hirokiyoshida/nes-rust/tree/master/wasm/web)

## How to install and use WebAssembly NES emulator npm package

See [wasm/npm](https://github.com/hirokiyoshida/nes-rust/tree/master/wasm/npm)
