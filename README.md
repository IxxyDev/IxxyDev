# Yaroslav Denisenko

Senior engineer — **TypeScript / React** in production, **Rust** and developer tooling in public.

📍 Tbilisi, Georgia · Open to relocation · Senior IC roles · BSc Applied Maths & Physics (MIPT)

I build high-performance UI and Canvas-based rendering — shipped editors, real-time analytics dashboards, and banking tools across AdTech, enterprise software, and EdTech. Full work history on [LinkedIn](https://www.linkedin.com/in/yaroslav-denisenko/).

## Pinned work

- **[yoptascript-rs](https://github.com/IxxyDev/yoptascript-rs)** — A full compiler frontend from scratch in Rust: lexer, recursive-descent parser, AST, tree-walking interpreter. Built alongside my Biome contributions — Biome is a large, mature JS/TS parser/linter, so I wanted a small from-scratch counterpart to understand each layer end-to-end.

- **[financial-rust](https://github.com/IxxyDev/financial-rust)** — Multi-format financial transaction parser (CSV ↔ text ↔ custom binary), with a library and two CLIs designed around `Read`/`Write` traits and a versioned binary format.

- **[v8-simple-profiler](https://github.com/IxxyDev/v8-simple-profiler)** — A profiler that measures how V8 deoptimizes monomorphic vs polymorphic code paths, using V8 intrinsics and proper statistics for honest measurement.

- **[task-tracker-elysia](https://github.com/IxxyDev/task-tracker-elysia)** — A task API on Bun + Elysia with strict Clean Architecture / DDD layering, typed error handling via `Result` unions, and a scheduled worker for due-date notifications.

## What I'm exploring

- 🦀 Contributing to [Biome](https://github.com/biomejs/biome) — Rust-based JS/TS linter & formatter. Recent work in its **type-inference engine**:
  - Fixed overloaded-function resolution ([#10585](https://github.com/biomejs/biome/pull/10585) + [#10586](https://github.com/biomejs/biome/pull/10586)) — models TypeScript's overload sets in the module graph and selects the matching signature at the call site, so `noFloatingPromises` stops misfiring on overloaded calls.
  - Expanded [`noUnnecessaryConditions`](https://github.com/biomejs/biome/pull/10108) to flag type-aware dead conditions: nullish/optional chaining on non-nullable types, always-falsy negations, unreachable `switch` cases.
  - Earlier: ported [`noAriaUnsupportedElements`](https://github.com/biomejs/biome/pull/9491) and added [`noRedundantRoles`](https://github.com/biomejs/biome/pull/9276) for HTML a11y.

## Contact

📧 [denisenkoforwork@gmail.com](mailto:denisenkoforwork@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/yaroslav-denisenko/)
