Robert C. Martin: Clean Code

---

> *Clean Code is a practical guide to writing software that is easy to read, understand, maintain, and extend. The code is read far more often than it is written, so clarity and simplicity should be treated as first-class design goals.*

> *Clean code is not about being clever — it’s about being clear.*

> *Writing clean code is a **discipline and a mindset**, requiring continuous refactoring, attention to detail, and respect for future maintainers. The cost of messy code compounds over time, while clean code enables speed, confidence, and longevity.*

> *Clarity beats cleverness. Always.*

## One-page cheat sheet

**Clean Code**
→ Readable, simple, and easy to change without fear.

**Names**
→ Reveal intent; avoid noise; if it needs a comment, rename it.

**Functions**
→ Small, do one thing, one abstraction level, few parameters.

**Comments**
→ Explain *why*, not *what*; bad code is not fixed with comments.

**Formatting**
→ Consistent layout shows structure and guides the reader.

**Objects & Data**
→ Objects hide data behind behavior; data structures expose data—don’t mix.

**Error Handling**
→ Use exceptions; keep the happy path clear; handle errors at the right level.

**Boundaries**
→ Isolate third-party code behind your own interfaces.

**Unit Tests**
→ Fast, independent, readable tests enable safe refactoring.

**Classes**
→ Small, cohesive, single responsibility, low coupling.

**Systems**
→ Separate construction from use; grow systems incrementally.

**Emergence**
→ Good design emerges from tests, clarity, simplicity, and no duplication.

**Concurrency**
→ Separate concurrent concerns; minimize shared state.

**Refinement**
→ Clean code comes from continuous refactoring, not upfront perfection.

**Case Studies**
→ Real systems improve through disciplined cleanup.

**Smells & Heuristics**
→ Duplication, size, and complexity are warning signs—use judgment.

## Rules of Thumb

### General
* Write code for **humans first**, machines second.
* If code is hard to read, it is **already broken**.
* Leave the code **cleaner than you found it**.

### Naming
* Choose names that **reveal intent immediately**.
* Avoid abbreviations unless they are universally understood.
* Names should answer: *why it exists, what it does, how it’s used*.
* If you need a comment to explain a name, the name is wrong.

### Functions
* Keep functions **small**—smaller than you think.
* A function should **do one thing** and do it well.
* Functions should work at **one level of abstraction**.
* Prefer **few parameters**; group related data into objects.
* Read functions top-down like a **story**.

### Comments
* Don’t comment **bad code**—rewrite it.
* Comments should explain **why**, not **what**.
* Remove outdated or redundant comments aggressively.
* The best comment is **no comment**.

### Formatting
* Format code to show **structure and intent**.
* Keep related code **close together**.
* Be consistent; formatting is a **team decision**.
* Let whitespace guide the reader’s eye.

### Objects & Data
* Objects should **hide data and expose behavior**.
* Data structures should **expose data with minimal behavior**.
* Don’t mix object and data-structure styles.
* Design to **reduce coupling**, not cleverness.

### Error Handling
* Use **exceptions**, not error codes.
* Keep the **happy path** easy to read.
* Handle errors at the right abstraction level.
* Don’t let error handling obscure business logic.

### Boundaries
* Isolate third-party code behind your own interfaces.
* Treat external APIs as **volatile dependencies**.
* Don’t let library details leak into your domain.

### Tests
* Write tests that are **fast, independent, and repeatable**.
* One test should test **one thing**.
* Test code deserves the same care as production code.
* If code is hard to test, its design is wrong.

### Classes
* Classes should be **small and focused**.
* A class should have **one reason to change**.
* Favor **high cohesion** and **low coupling**.
* If a class name needs “And,” it’s doing too much.

### Design & Systems
* Separate **construction** from **use**.
* Prefer simple designs that can evolve.
* Dependency injection beats global setup.
* Build systems that can grow without pain.

### Code Smells & Refactoring
* Duplication is the **root of many evils**.
* Long functions and large classes are warning signs.
* Refactor continuously, not occasionally.
* Rules are guides—**judgment matters more**.

### Mindset
* Clean code is a **professional responsibility**.
* Speed comes from cleanliness, not shortcuts.
* Every change is a chance to improve the codebase.