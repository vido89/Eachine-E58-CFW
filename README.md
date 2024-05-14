# Eachine E58 CFW

This project aims to build a custom firmware for the Eachine E58 quadcopter.

* [Eachine E58 Info](Docs/Info.md)


## Building
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

https://developer.arm.com/downloads/-/gnu-rm/9-2020-q2-update

Build rust library: go to `CFW/drone_rs` and run `cargo build`

Build application: go to `CFW`, `mkdir build`, `cd build`, `cmake ..`
