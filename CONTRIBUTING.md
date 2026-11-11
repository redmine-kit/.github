# Contributing

Thank you for your interest in the projects of [redmine-kit](https://github.com/redmine-kit). This guide applies to repositories that have no contributing guide of their own; a repository's own `CONTRIBUTING.md` or `AGENTS.md` takes precedence.

## Before you start

- **Issues first** for anything larger than a small fix, so that the approach can be agreed on before you spend time on it.
- **Security issues** are not reported in public; see [SECURITY.md](SECURITY.md).
- **Design-stage projects** (Serverless, Redmine AWS, Redmine AWS Lambda, Redmine AWS S3, Redmine AWS SES, Redmine AWS SQS, Redmine GitHub) accept corrections and questions about their design documents.

## Pull requests

- One purpose per pull request, and one purpose per commit.
- Commit messages in English, imperative mood, 72 characters or fewer in the first line, no trailing period.
- Add or update tests for code changes, and run the repository's checks before opening the pull request.
- Do not edit Redmine's own files; use Redmine's extension points.
- Do not commit secrets.

## Documentation

- English is the source (`README.md`, `docs/`). The Japanese translation is in `README.ja.md` and `docs/ja/`, with the same file names; update both when you can, or say in the pull request that the translation is missing.
- State only what has been checked, and mark what has not.

## License

By contributing, you agree that your contribution is released under the license of the repository you contribute to.
