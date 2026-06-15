# Ownership mental model established — why the rules exist

User completed Lesson 1 (The Memory Problem) and scored 5/5 on the quiz. Understands the three-way contrast: C (manual, unsafe), Go (GC, safe but runtime cost), Rust (compile-time ownership, no GC, no manual free). Understands the single foundational rule — every value has exactly one owner at a time — and why it prevents double-free and use-after-free.

**Implications:** The *why* is now solid. Lesson 2 can introduce actual Rust syntax for ownership (move semantics, Copy vs non-Copy types) without needing to re-motivate the model. The foundation holds.

**Evidence:** Quiz 5/5 on first attempt.
