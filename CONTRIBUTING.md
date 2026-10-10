# Contributing to FreeTheAI

Thanks for helping. This file applies to every repository in the [Free-The-Ai](https://github.com/Free-The-Ai) organization. A repository can add its own file with more detail, and that file wins for that repository.

## Before you start

- Search [existing issues](https://github.com/search?q=org%3AFree-The-Ai+is%3Aissue&type=issues) first.
- For questions about using the API, ask in [Discord](https://discord.gg/secrets). Issues are for bugs and feature requests.
- Small fixes (typos, broken links, clearer wording) can go straight to a pull request.
- For anything bigger, open an issue first so the approach can be agreed before you write code.

## Making a change

1. Fork the repository and create a branch from the default branch.
2. Make the change and keep it focused on one thing.
3. Run the repository's checks locally. Each repository's README and CI workflow say which commands to run.
4. Update the docs and the changelog entry if the change is visible to users.
5. Open a pull request. Fill in the template, and link the issue it fixes.

## Commit messages

Write short, plain messages in the present tense, for example `Fix retry delay for busy models`. Describe what changed and why.

## Code rules

- Match the style of the code around your change.
- Add or update tests for behaviour you change. CI must not call the live API; use mocks and fixtures.
- Never commit secrets: API keys, tokens, passwords, or private config. Use placeholders such as `ftai_...` in examples.
- Keep documentation and examples accurate for the public API. Do not describe internal mechanics.

## Review

A maintainer reviews every pull request. Expect questions or requests for changes; that is normal. Pull requests that stay inactive for a long time may be closed.

## License

By contributing, you agree that your contribution is released under the MIT license of the repository you contribute to.

## Code of conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
