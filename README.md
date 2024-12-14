# learning_rust 🦀

![Ai Mie reading The Rust Programming Language book](./assets/Ai_Mie_Reading_The_Rust_Programming_Language.png)

This repo is more or less my journal on my daily effort to learn rust
i try to update this maarkdown file with every progress i make in learning rust, daily.

## day 0
started reading the official rust book for newbies; **"The Rust Programming Language"**

With its direction, i installed rust and its build system, cargo, with the rustup cli tool, wrote my first rust program (_of course its a "Hello, world!" program_) and compiled with the "rustc" command

got introduced to cargo(very neat tool and it is very similar to ~~npm~~ imo) and learnt how to initialize my rust projects with cargo 

## day 1

Completed first Rust project (guessing game) and started rustlings exercises. Used `std::io` for I/O operations and Result type for error handling. Learned about mutable variables, String type, and installing crates via cargo.toml.
used the rust's `std::io` lib and learnt how to collect user input from StdIn with `read_line()` method.
i found that types in Rust are kinda similar to how it is in typescript, it has its own methods and can share with other types, kinda like classes
Result type has Ok (successful) and Err (unsuccessful) variants - similar to JS Promises. Used `.expect()` for basic error handling and println!() macro for output.

> _Another neat feature of Cargo is that you can run the cargo doc --open command, 
which will build documentation provided by all of your dependencies locally and 
open it in your browser_

also this. very, very helpful

learnt how to use external crates and learnt a little about traits like `rand::Rng`

```rs
extern crate rand;

use std::io;
use std::cmp::Ordering;
use rand::Rng;

fn main{
    //...
}

```
Used std::cmp::Ordering with .cmp() for number comparison and match expressions. Implemented loop with break statements for program control.
learnt a lot in this chapter, having fun reading this book
well here is the link to the code on github
Completed rustlings exercises 1-11

well here is the [link](https://github.com/eghosaclinton/rust_guessing_game) to the code on github

## day 2

began learning how common programming concepts are handled in rust.

