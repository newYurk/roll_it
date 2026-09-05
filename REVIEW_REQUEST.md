This is an initial architectural review of the repository.

Please use the full repository context, not only the README change in this pull request.

This project is an early prototype. I need an honest technical and conceptual assessment, not only style feedback.

Focus especially on:

1. The mathematical and geometric model:
   - correctness and consistency of formulas;
   - coordinate systems, units, angle conventions, and transformations;
   - numerical stability, floating-point edge cases, division by zero, NaN/Infinity propagation;
   - boundary cases, degeneracies, and assumptions that are not encoded or documented.

2. Architecture and prototype direction:
   - whether the current structure supports iteration on the prototype;
   - duplicated or contradictory logic;
   - overly coupled systems or abstractions that may make experimentation harder;
   - parts where the implementation appears to diverge from the apparent intent.

3. Testing and verification:
   - missing tests for mathematical invariants and geometric edge cases;
   - the highest-value tests to add first;
   - concrete examples of inputs that could expose bugs.

Please provide:
- a short overall assessment of the codebase;
- prioritized findings: critical, important, and optional;
- file and line references where possible;
- a candid opinion about whether the current technical direction looks sound for a prototype.
