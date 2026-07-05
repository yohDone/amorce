# Contributing to Amorce

First off, thank you for considering contributing to Amorce! It's people like you that make the open-source community such a great place.

## 🛠️ Development Setup

1. Fork the repository and clone it locally.
2. Ensure you have the latest stable version of Rust installed.
3. Run tests before submitting any code: `cargo test`
4. Ensure your code is properly formatted: `cargo fmt`
5. Run the linter to catch common mistakes: `cargo clippy -- -D warnings`

## 📝 Commit Convention

We strictly follow the [Conventional Commits](https://www.conventionalcommits.org/) specification coupled with [Chris Beams](https://chris.beams.io/git-commit) recommendations. This allows us to automatically generate the `CHANGELOG.md` and manage versioning.

Examples of valid commit messages:

- `feat: add interactive prompt for typescript setup`
- `fix: resolve issue with git hook installation on windows`
- `docs: update readme with new commands`
- `chore: update dependencies`

## 🚀 Pull Request Process

1. Create a new branch from `main` (`git checkout -b feature/my-new-feature`).
2. Make your changes and commit them using the convention above.
3. Push your branch and open a Pull Request.
4. The CI pipeline will automatically check your code. Ensure all checks pass!
