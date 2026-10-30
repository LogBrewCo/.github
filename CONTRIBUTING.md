# Contributing to LogBrew

Thanks for helping. Bug reports, fixes, and docs changes are all welcome.

## Report a bug

Open an issue in the repository the bug is in and fill in the form. Include
the package or CLI version, your runtime and OS, what you did, what you
expected, and what happened. Remove API keys, tokens, and personal data from
logs and screenshots first.

For a security problem, follow the [security policy](SECURITY.md) instead.

## Send a change

1. Open an issue first for anything bigger than a small fix, so we can agree
   on the approach before you write code.
2. Fork the repository and create a branch from `main`.
3. Keep the change to one topic, and add or update tests for any change in
   behavior.
4. Run the checks that the repository's README describes. CI runs the same
   checks on your pull request.
5. Write commit messages in the Conventional Commits style, for example
   `fix(cli): keep the project flag when paging`.
6. Open a pull request that says what changed and why, and how you tested it.

Every pull request runs a public guard scan that blocks secrets, private
paths, and similar content. If it flags your change, remove the flagged text.

By contributing, you agree that your work is licensed under the license of
the repository you contribute to.
