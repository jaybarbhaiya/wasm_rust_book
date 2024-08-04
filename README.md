# Intro

This repository contains code snippit from the book **[Programming WebAssembly with Rust - Unified Development for Web, Mobile and Embedded Applications](https://amzn.eu/d/10qbFpn)**.

## Compiling WAT to WASM

1. Install [`wat2wasm`](https://github.com/WebAssembly/wabt)
2. Compiling to WASM
```console
wat2wasm <path/to/file.wat> -o <path/to/file.wasm>
```