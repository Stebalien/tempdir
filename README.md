tempdir
=======

A Rust library for creating a temporary directory and deleting its entire
contents when the directory is dropped.

[![Build Status](https://travis-ci.org/rust-lang-nursery/tempdir.svg?branch=master)](https://travis-ci.org/rust-lang-nursery/tempdir)

[Documentation](https://doc.rust-lang.org/tempdir)

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies]
tempdir = "0.3"
```

and this to your crate root:

```rust
extern crate tempdir;
```
