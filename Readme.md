from https://www.fullstackreact.com/articles/rust-react-and-web-assembly/

### Install node dependencies
```
npm install
```

## Setup rust:
```
rustup default nightly
rustup target add wasm32-unknown-unknown
cargo install wasm-bindgen-cli
```

### Then build
```
npm run build
```
