# Running wasm with node

Direction from: https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_Wasm

### Running the site with rust and js

The packages are precompiled, and called from `index.html` so running this is quite easy:

in the `hello-wasm` root dir: `python3 -m http.server`

### Running the site using npm

Install [node version manager](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)

Use `nvm` to install npm v20 `nvm install 20`

In the `hello-wasm/site` dir: `npm install to install all the required packages`

In the `hello-wasm/site` dir: `npm run serve`
