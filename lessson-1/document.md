## Install
### You should Install Rust, Npm on your computer firstly!
Install wasm-pack
```
cargo install wasm-pack
```
Install Cargo Project Template Generate 
```
cargo install cargo-generate
```
[-- Requirements For MAC new CPU, should run commands below before do install cargo-generate  ---]
```
brew install pkg-config
brew install openssl
```

```
cargo generate --git https://github.com/rustwasm/wasm-pack-template
```

```
cd lesson-1
wasm-pack build
```

```
npm init wasm-app www
```

```
cd www
npm install
npm run start
```

