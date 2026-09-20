# Contributing

Thank you for contributing to Rebel Federation projects.

## Before you start

1. Check the repository README and existing issues.
2. Open an issue before starting a large change so the approach can be discussed.
3. Keep changes focused and explain the user impact.

## Branching Strategy

- Create feature branches from `develop` for implementation work.
- Open pull requests against `develop`.
- When `develop` is stable and ready for production deployment, create a release branch from `develop`.
- The release branch's CI/CD pipeline deploys the repository to production.
- After a successful release, merge the release branch into `main`.

## Pull requests

- Use a clear title that describes the change.
- Include tests or explain why tests are not applicable.
- Update documentation when behavior or public interfaces change.
- Keep unrelated formatting and refactoring out of the change.
- Respond to review feedback and keep the branch up to date when requested.

By participating, you agree to follow the project's Code of Conduct.