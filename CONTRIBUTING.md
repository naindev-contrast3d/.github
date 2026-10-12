# Contributing to Contrast3D & NainDev

Thank you for your interest in contributing to the **Contrast3D & NainDev** ecosystem. We build deterministic conformance engines, interactive 3D Web Components, and decoupled enterprise software.

---

### Core Engineering Invariants

1. **Decoupled Architecture:** Systems maintain zero runtime coupling. Interactions occur strictly across versioned schemas, REST APIs, or cryptographic seals (`dse-hash`).
2. **Determinism over Heuristics:** In our validation systems, verdicts are mathematically auditable facts. We do not use probabilistic or subjective heuristics to compute conformance verdicts.
3. **Strict Typing:** All TypeScript code is compiled under strict mode. All Python modules are validated using `mypy` and strict Pydantic v2 schemas.
4. **Test-Driven Integrity:** Features and bugfixes must include automated tests verifying edge cases and invariants before merging.

---

### Commit Message Conventions

We enforce [Conventional Commits](https://www.conventionalcommits.org/) in English:

- `feat(<scope>): description` — New functionality.
- `fix(<scope>): description` — Bug fixes.
- `docs(<scope>): description` — Documentation changes.
- `refactor(<scope>): description` — Structural code improvements without behavioral change.
- `test(<scope>): description` — Adding or correcting automated tests.

---

### Pull Request Guidelines

1. **Focused Scope:** Keep pull requests focused on a single responsibility or feature.
2. **Evidence:** Provide local test execution results or reproducible commands in the PR description.
3. **Confidentiality:** Never include proprietary client models, credentials, API keys, or NDA materials in git history.
