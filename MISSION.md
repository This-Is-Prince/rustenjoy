# Mission: Rust

## Why
You're a polyglot engineer (TypeScript, Go, some C) who got burned by the borrow checker once and wants a second attempt — this time armed with a real mental model rather than memorized rules. The deeper goal is to be productive enough in Rust to ship a small CLI tool or backend service, and to genuinely understand what the language is doing at the memory level.

## Success looks like
- Explain — without looking anything up — why ownership exists and what problem it prevents (compared to C's manual memory and Go's GC)
- Write a small CLI tool in Rust that compiles cleanly, handles errors with `Result`/`Option`, and doesn't fight the borrow checker
- Read unfamiliar Rust code and understand what the lifetime annotations and trait bounds are doing
- Know when to reach for `clone()`, a reference, or a lifetime annotation — and why each choice has a cost

## Constraints
- Previous attempt stalled on ownership/borrowing/lifetimes — these need to go slower and deeper than a typical tutorial
- Comparisons to Go and C are high-signal for building intuition; use them wherever they illuminate
- Exercises after every concept — not just reading
- Multi-session curriculum with tracked progress

## Out of scope
- Async Rust / `tokio` (for now — comes after sync fundamentals are solid)
- Unsafe Rust
- WebAssembly
- Embedded / no-std targets
