# xtp: A rust binding for [XTP SDK](http://xtp.zts.com.cn) ![travis]

This library is a binding for the [XTP SDK](http://xtp.zts.com.cn), which is an interface for trading on the Chinese stock market.

## Current status

All APIs are implemented but not tested/documented. USE AT YOUR OWN RISK!

## Dependencies

This crate depends on `libxtpquoteapi` and `libxtptraderapi` from the [**bundled** XTP SDK](http://xtp.zts.com.cn). Please install them first. 
(The **Installation** here means add the path to the correponding libs to `LD_LIBRARY` on linux, or `%PATH%` on windows.)
The version of the installed lib should be same as the one in the [bundled sdk](http://github.com/dovahcrow/xtp-sdk) in case of incompatibility.

Only 64 bit of the SDK is implemented. Especially for windows users, 
please install 64bit rust compiler and llvm (required by [rust-bindgen](https://rust-lang.github.io/rust-bindgen/requirements.html)).

## Usage

This project is currently in its *alpha* stage.

Check the `examples` folder for usages.

[travis]: https://img.shields.io/travis/dovahcrow/xtp-rs/master?style=flat-square
