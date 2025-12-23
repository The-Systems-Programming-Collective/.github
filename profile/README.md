## Core Principles

1. **Human-written code only** — **No AI code generation**. Systems programming requires direct authorship and a clear understanding of what is built and why.

2. **Correctness is non-negotiable** — Software must work reliably and predictably. Bugs are failures, not features.

3. **Understand your dependencies** — Know what every dependency does. Every dependency is a potential point of failure. Build it yourself when you need control or deeper understanding.

4. **Performance through design** — Data-oriented, cache-friendly, manual memory management. Performance isn't an afterthought; it's a core design constraint for **systems programmers\***.

5. **Explicit over magic** — Code should be clear about what it does. No hidden behavior, no clever tricks that obscure intent.

6. **Test comprehensively** — Correctness doesn't happen by accident. Rigorous testing is mandatory, not optional, though software need not be test-driven.

7. **Quality documentation or none** — Bad documentation is worse than no documentation. Write simple, readable code and document non-obvious invariants and design decisions.

8. **Build for longevity** — Code should be maintainable and understandable decades from now. Future **systems programmers\*** should not need archaeology to understand your work.

9. **Systems languages** — Statically typed, compiled languages with explicit control over memory and execution (Jai, Rust, C, C++, Zig, etc). These are the main tools of **systems programmers\***.

10. **Be responsible for your software** — Once you release software, keep it maintained or provide a better alternative. Don't abandon your work.

#### \* **Systems Programmer**
A systems programmer is someone who builds software with an explicit understanding of how it executes on real hardware. **They reason directly about memory, data layout, data flow, control flow, and performance characteristics**. This definition is inspired by ideas expressed by Jon Blow and Andrew Kelley, emphasizing responsibility, predictability, and deep understanding over convenience or automation.

**Systems Programmers** are the people keeping civilization from collapsing.

---

## **AI Code Generation Principle**

**We don't use AI to write our software**. When AI writes your code, you lose understanding of the details. You cannot be a **systems programmer\*** if you don't understand the system you're building. AI-generated code creates confusion, obscures bugs, and accumulates technical debt that nobody fully comprehends.
