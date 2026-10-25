---
name: simplify-design
description: Simplify software design when implementing requirements, refactoring code, or removing complexity. Use when a requirement should shape the design from first principles or an existing solution needs simplification.
---

# Simplify Design

Treat the requirement as a foundational assumption from day one, not something bolted onto the existing design.

Optimize for simplicity. First, look for anything that can be deleted, simplified, or consolidated. Prefer removing complexity over adding code, and make the smallest change that produces the simplest maintainable solution. Rethink the design from first principles when necessary rather than layering fixes onto a flawed structure.

Fewer lines are a means, not an end. Optimize for code that is easy to read, understand, modify, and debug. Preserve correctness, necessary safeguards, and existing behavior.

Challenge every abstraction, dependency, layer, and special case. Keep what earns its complexity; remove what doesn't.

Apply these principles within the requested scope; broader redesign requires its own justification and authorization.

Before finishing, ask: **Would a new team member understand this faster than the original?** If not, simplify further.
