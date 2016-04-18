# rgo

`rgo` is a **work-in-progress** (i.e. unfinished) Go compiler, written in Rust.

## Goals

- providing a Rust library for parsing Go code, which may be useful for tool
  writers
- being a production-ready alternate implementation of the Go compiler, using
  LLVM as a backend

## Why?

- writing compilers is fun, and a good way to learn new things
- Go's reference implementation uses a custom backend for optimization and
  codegen, while `rgo` will use LLVM
- competition is healthy, and should `rgo` grow into a production-ready
  alternative to the official Go toolchain, it might serve as a testing ground
  for new features.
- I chose to target Go specifically because C compilers have been written over
  and over, and Go's spec is pretty simple.
