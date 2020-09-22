### rust-secp256k1-zkp-wasi
> Fork of `rust-secp256k1-zkp` that compiles to WebAssembly System Interface.

`rust-secp256k1-zkp-wasi` was created to enable compilation of `mimblewimble/rust-secp256k1-zkp` down to WASI. This allows us to use the binary on various smart contract platforms like Oasis Protocol. By having access to `rust-secp256k1-zkp-wasi` inside a contract, you can create a Grin wallet that's decentralized which also gets around the Asynchronous Transaction Building problem that Grin has.

`rust-secp256k1-zkp-wasi` is a rebase of `mimblewimble/rust-secp256k1-zkp` on `rust-bitcoin/rust-secp256k1` which compiles to WASM.

### Related

[mimblewimble/rust-secp256k1-zkp](https://github.com/mimblewimble/rust-secp256k1-zkp): ZKP fork for rust-secp256k1, adds wrappers for range proofs, pedersen commitments, etc.  
[rust-bitcoin/rust-secp256k1](https://github.com/rust-bitcoin/rust-secp256k1): Rust language bindings for Bitcoin secp256k1 library.

