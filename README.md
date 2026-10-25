# Yaroslav Denisenko

Senior engineer — **TypeScript / React** in production, **Rust** and developer tooling in public.

📍 Tbilisi, Georgia · Open to relocation · Senior IC roles · BSc Applied Maths & Physics (MIPT)

I build high-performance UI and Canvas-based rendering — shipped editors, real-time analytics dashboards, and banking tools across AdTech, enterprise software, and EdTech. Full work history on [LinkedIn](https://www.linkedin.com/in/yaroslav-denisenko/).

## Open source

🦀 Contributor to [Biome](https://github.com/biomejs/biome) — Rust-based JS/TS linter & formatter. Merged work in its **type-inference engine**:

- Fixed overloaded-function resolution ([#10585](https://github.com/biomejs/biome/pull/10585) + [#10586](https://github.com/biomejs/biome/pull/10586)) — models TypeScript's overload sets in the module graph and selects the matching signature at the call site, so `noFloatingPromises` stops misfiring on overloaded calls.
- Expanded [`noUnnecessaryConditions`](https://github.com/biomejs/biome/pull/10108) to flag type-aware dead conditions: nullish/optional chaining on non-nullable types, always-falsy negations, unreachable `switch` cases.
- Earlier: ported [`noAriaUnsupportedElements`](https://github.com/biomejs/biome/pull/9491) and added [`noRedundantRoles`](https://github.com/biomejs/biome/pull/9276) for HTML a11y.

## Projects

- **[yoptascript-rs](https://github.com/IxxyDev/yoptascript-rs)** — A JS-like language implemented from scratch in Rust: lexer, parser, tree-walking interpreter and a bytecode VM that a conformance suite keeps byte-for-byte in sync, plus LSP, DAP, formatter, linter, a VS Code extension and a [WASM playground](https://ixxydev.github.io/yoptascript-rs/).

- **[cachelens](https://github.com/IxxyDev/cachelens)** — Prompt-cache economics for LLM agent pipelines: cost per step, cache hit rate, byte-level root cause for each cache miss, and a CI gate that fails the build when the numbers regress.

- **[v8-simple-profiler](https://github.com/IxxyDev/v8-simple-profiler)** — Measures how V8 treats monomorphic vs polymorphic code paths: warm-up, median/p95/p99 with outlier handling, a Welch t-statistic for the comparison, and the optimizer's actual decisions read via V8 intrinsics.

## Contact

📧 [denisenkoforwork@gmail.com](mailto:denisenkoforwork@gmail.com)
