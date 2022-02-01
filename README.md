# Rust optnone proof-of-concept implementation

This repository contains the code accompanying our [blog post about exploring LLVM optnone to improve the state of cryptography implementations in Rust](https://blog.trailofbits.com/2022/02/01/part-2-rusty-crypto/). The blog post discusses the implementation of this feature as well as the general problems with constant-time cryptography implementations in high-level languages such as Rust and C/C++.

This is a vanilla fork of the Rust codebase, [except for this commit](https://github.com/trailofbits/rust-optnone/commit/f0798cbb779fef4d4e34f9c6a2482063552b1a46). The original README for the Rust project can be found [here](README.orig.md).

## WARNING

This code is not intended for production use! In fact, the conclusion from [our blog post](https://blog.trailofbits.com/2022/02/01/part-2-rusty-crypto/) was that it might not even be a good idea to add to Rust. That is why we have not attempted to upstream the code into Rust. It is included here solely for instructional purposes.

## License
Rust optnone is licensed and distributed under the [Apache v2.0](LICENSE-APACHE) license. [Contact us](mailto:opensource@trailofbits.com) if you're looking for an exception to the terms.

See [LICENSE-APACHE](LICENSE-APACHE), [LICENSE-MIT](LICENSE-MIT), and
[COPYRIGHT](COPYRIGHT) for licenses and copyright of the Rust project.
