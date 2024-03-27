# Learnings

https://doc.rust-lang.org/book/

## Cargo

Cargo is the default build tool and package manager for rust applications.

- `cargo new` initializes a new project
- `cargo build` builds the program
- `cargo run` (builds) and runs the program
- `cargo check` checks whether the program compiles

## Functions vs Macros

Calls with an `!` appended are "macros" rather than functions. e.g

```rust
// this is a call to a function
println("hello world");

// this is a call to a macro
println!("hello world");
```
