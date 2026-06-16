# Slices and &str vs String understood

User completed Lesson 4 (Slices) with 6/6 on the quiz. Understands &str as a fat pointer (ptr + len), that string literals are &'static str, the String vs &str distinction (owned/growable vs borrowed/read-only), why &str is preferred over &String in function signatures, &[T] as the slice equivalent for arrays/Vecs, and how slices enforce the aliasing rule (making stale-index bugs into compile errors).

**Implications:** Owns the full ownership + borrowing + slices foundation. Ready for lifetimes — specifically why the compiler can't always infer reference validity from context, and what lifetime annotations actually say. This is the last piece of the ownership puzzle.

**Evidence:** Quiz 6/6 on first attempt. Four consecutive perfect scores across lessons 1-4.
