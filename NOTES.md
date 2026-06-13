# Teaching Notes

## User profile
- 4 years SWE: TypeScript, Node.js, Next.js, backend
- Solid Go (goroutines, channels, static typing, compiled) — this is the primary mental model to build from
- Poked at C — understands pointers exist, not deeply fluent
- Some DevOps/cloud, frontend, Android/iOS
- Enjoys systems-level depth in free time

## Known failure point
Previous Rust attempt stalled on ownership/borrowing/lifetimes. Root cause: didn't have a mental model for *why* the rules exist — was fighting the compiler without understanding what it was protecting against. Go slower here than any standard tutorial.

## Teaching preferences
- Comparisons to Go and C are high-signal — use liberally to build intuition
- Hands-on exercises after each concept, not just explanations
- Multi-session curriculum with tracked progress
- Explain the *problem* before the solution

## Curriculum plan (high-level)
1. **The Memory Problem** — why memory management matters; C vs Go vs Rust's approach (no syntax yet)
2. **Ownership rules** — the three rules, move semantics, `Copy` types
3. **Borrowing** — shared (`&`) and mutable (`&mut`) references, the aliasing rule
4. **Slices** — the first real "lifetime-adjacent" concept with slices
5. **Lifetimes** — naming what the compiler already infers; when annotations are needed
6. **Structs + Enums** — Rust's type system building blocks
7. **Traits** — behaviour abstraction vs TS structural typing vs Go interfaces
8. **Error handling** — `Result`, `Option`, `?` operator vs Go's `if err != nil`
9. **CLI project** — put it all together
