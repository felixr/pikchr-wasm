# Pikchr WASM

> Pikchr (pronounced "picture") is a PIC-like markup language for diagrams in technical documentation.  https://pikchr.org/

This repo provides an example on how to compile Pikchr to WASM and use it in the browser.

In this repo:

* `Makefile` to download `pikchr.c` and use Emscripten (https://emscripten.org) to compile it to WASM
* `pikchr.js` the WASM module
* `pikchr.mjs` same as above but as ES6 module
* `example.html` see https://felixr.github.io/pikchr-wasm/example.html
