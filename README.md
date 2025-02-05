# Uncommon Assembly Code Errors

This repository demonstrates some uncommon but potentially serious errors that can occur in assembly language programming.  These errors are often subtle and difficult to debug.

The `bug.asm` file contains examples of these errors, while `bugSolution.asm` provides potential solutions or safer alternatives.

**Errors covered:**

* **Out-of-bounds memory access:** Accessing memory locations outside the allocated array or memory space.
* **Stack overflow:** Pushing too much data onto the stack, resulting in a stack overflow.
* **Jumping to invalid memory addresses:** Attempting to jump to a memory location that is not valid executable code.

Understanding these errors is crucial for writing robust and secure assembly programs.