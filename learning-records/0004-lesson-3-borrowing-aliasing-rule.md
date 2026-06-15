# Borrowing and the aliasing rule fully understood

User completed Lesson 3 (Borrowing) with 6/6 on the quiz. Understands shared (&T) vs mutable (&mut T) references, the aliasing rule (many readers XOR one writer), why it prevents data races and iterator invalidation, Non-Lexical Lifetimes, and why dangling references are a compile error. Correctly mapped the borrow checker's role vs Go's runtime race detector.

**Implications:** The three-lesson ownership foundation (why/what/how) is solid. Ready for slices — the first type that *is* a reference by definition, and the natural bridge into why lifetimes need names. Can introduce &str vs String distinction here.

**Evidence:** Quiz 6/6 on first attempt.
