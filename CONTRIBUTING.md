# Contributing to altertable-lakehouse-cli

## Development Setup

1. Fork and clone the repository
2. Install dependencies: `chmod +x bin/altertable`
3. Run tests: `./bin/altertable --help`

## Making Changes

1. Create a branch from `main`
2. Make your changes
3. Add or update tests
4. Run the full check suite: `shellcheck bin/altertable`
5. Commit using [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, etc.)
6. Open a pull request

## Code Style

This project uses `ShellCheck` for linting and `shfmt` for formatting. Run `shellcheck bin/altertable` before committing.

## Tests

- Unit tests are required for all new functionality
- Integration tests run in CI when credentials are available
- Run tests locally: `./bin/altertable --help`

## Pull Requests

- Keep PRs focused on a single change
- Update `CHANGELOG.md` under `[Unreleased]`
- Ensure CI passes before requesting review
