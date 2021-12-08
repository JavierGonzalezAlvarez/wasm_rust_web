# wasm & rust (library)

- get/post data from javascript without using api rest using WASM & RUST
- using a library from rust lang

## install wasm
$ cargo install wasm-pack

## create a library
$ cargo new --lib input

## communicate js with rust. crate
use wasm_bindgen::prelude::*;

## wasm-pack build
-target is a  html file to run n a browser(web)
$ wasm-pack build --target web

## create a file html
index.html

## run server to see index.html
$ python3 -m http.server





