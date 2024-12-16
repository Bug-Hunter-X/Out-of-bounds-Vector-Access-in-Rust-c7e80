This repository contains a simple Rust program that demonstrates a common error: out-of-bounds access to a vector.  The `bug.rs` file contains the erroneous code, which may panic at runtime if an invalid index is used to access the vector.  The `bugSolution.rs` file provides a corrected version that uses safe indexing techniques to prevent panics. This example highlights the importance of careful index handling in Rust to ensure program stability.