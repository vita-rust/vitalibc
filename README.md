# `vitalibc`

*A minimal `libc` for Rust using the kernel PS Vita functions*.

[![TravisCI](https://img.shields.io/travis/vita-rust/vitalibc/master.svg?maxAge=600&style=flat-square)](https://travis-ci.org/vita-rust/vitalibc/builds)
[![Source](https://img.shields.io/badge/source-GitHub-303030.svg?maxAge=86400&style=flat-square)](https://github.com/vita-rust/vitalibc)
[![Changelog](https://img.shields.io/badge/keep%20a-changelog-8A0707.svg?maxAge=86400&style=flat-square)](http://keepachangelog.com/)
[![Crate](https://img.shields.io/crates/v/vitalibc.svg?maxAge=86400&style=flat-square)](https://crates.io/crates/vitalibc)
[![Documentation](https://img.shields.io/badge/docs-latest-4d76ae.svg?maxAge=86400&style=flat-square)](https://docs.rs/vitalibc)
[![CargoMake](https://img.shields.io/badge/built%20with-cargo--make-yellow.svg?maxAge=86400&style=flat-square)](https://sagiegurari.github.io/cargo-make)


## Usage

This crate provides functions which LLVM often lowers intrinsic calls to
and will be required to link correctly.

This crate depends on [`psp2-sys`](https://crates.io/crates/psp2-sys),
so you'll need the [`vitasdk`](https://vitasdk.org) set up and the
`$VITASDK` environment variable set.


## Credits

* [**VitaSDK team**](http://vitasdk.org/) for the `arm-vita-eabi` toolchain, `psp2` headers, ...
* [**Team Molecule**](http://henkaku.xyz/) for the `Henkaku` hard work.
* [**Alex Crichton**](https://github.com/alexcrichton) for the `rlibc` implementation.


## Disclaimer

*`vitalibc` is not affiliated, sponsored, or otherwise endorsed by Sony
Interactive Entertainment, LLC. PlayStation and PS Vita are trademarks or
registered trademarks of Sony Interactive Entertainment, LLC. This software
is provided "as is" without warranty of any kind under the MIT License.*
