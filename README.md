# Eachine E58 CFW

This project aims to build a custom firmware for the Eachine E58 quadcopter.

* [Eachine E58 Info](Docs/Info.md)


## Building

wget https://armkeil.blob.core.windows.net/developer/Files/downloads/gnu-rm/9-2020q2/gcc-arm-none-eabi-9-2020-q2-update-x86_64-linux.tar.bz2

https://forum.dfinity.org/t/hello-world-rust-error-e0463-cant-find-crate-for-core/9214

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

https://developer.arm.com/downloads/-/gnu-rm/9-2020-q2-update

https://github.com/jobroe/cmake-arm-embedded/tree/35a969878d3e6a979a0c61f0bf07327bac3aad1e

Build rust library: go to `CFW/drone_rs` and run `cargo build -r`

Build application: go to `CFW`, `mkdir build`, `cd build`, `cmake ..`
