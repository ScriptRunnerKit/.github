# Contributing to ScriptRunnerKit

Thanks for taking the time to contribute! This guide applies to every repository of the organization; a repository may
add its own `CONTRIBUTING.md` with build and test instructions.

## Before you start

- Read and follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- For anything bigger than a small fix, **open an issue first** to agree on the approach. Projects are specification
  driven: new behavior starts from an agreed description and acceptance criteria.
- Security problems must **not** go into public issues — see the [security policy](SECURITY.md).

## Making a change

1. Fork the repository and create a branch from `main` (for example `fix/memory-limit` or `feat/stage-filter`).
2. Keep the change focused: one topic per pull request.
3. Add or update tests. Every acceptance criterion and every fixed bug has a test.
4. Run the full build and test suite locally (see the repository's README or `CONTRIBUTING.md`).
5. Write commits following [Conventional Commits](https://www.conventionalcommits.org/) — `feat:`, `fix:`, `docs:`,
   `test:`, `build:`, `ci:`, `chore:` — and explain *why* in the body when it is not obvious.
6. Open a pull request using the template, link the issue, and describe how you verified the change.

## Pull request checklist

- [ ] The build passes with no warnings (warnings are errors) and the code is formatted.
- [ ] Tests cover the change and the whole suite passes.
- [ ] Public APIs have XML documentation; user-facing behavior is documented in the README.
- [ ] Breaking changes are called out in the description.

## Review

Maintainers review pull requests as soon as they can. A pull request is merged once the CI is green and a maintainer
approves it. Thank you for helping make the tools better!
