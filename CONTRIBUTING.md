# Contributing to Conserve

Contributions are very welcome.

## Git hooks

A git pre-commit hook is provided in the `githooks` directory of the repo. Git
doesn't activate hooks by default for good security reasons.

You can optionally install it so that git will check the tests pass before
committing, by

    cp githooks/pre-commit .git/hooks/

(There's no Windows equivalent yet, but it could be ported.)
