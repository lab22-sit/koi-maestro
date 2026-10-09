# Contributing to koi-maestro

Thanks for your interest in contributing.

- **Canonical repository**: development happens exclusively at
  [notLukeshi/koi-maestro](https://github.com/notLukeshi/koi-maestro).
  Mirrors and forks (including organizational showcases) are read-only views
  of this repository — please do not open issues or pull requests there.
- **Issues and pull requests**: submit them against the canonical repository.
- **Review policy**: every change requires review by the code owner
  (`@notLukeshi`, see `.github/CODEOWNERS`). Direct pushes to `main` are not
  accepted.
- **CI**: pull requests must pass the `check` job on all platforms
  (see `.github/workflows/ci.yml`).

## Development

- Rust toolchain: pinned in `rust-toolchain.toml`.
- Gate scripts: `./scripts/check.sh` (Linux) or `./scripts/check.ps1`
  (Windows) — run before opening a PR.
