# Contributing to porto-metro-map

Thanks for your interest in contributing! This guide explains how to propose changes.

## Reporting bugs and suggesting features

Open a [GitHub issue](../../issues) before starting on anything substantial, so we can agree on the approach first. For bugs, include:

- what you expected to happen and what happened instead
- steps to reproduce it
- your browser and device, if relevant

Small fixes such as typos can go straight to a pull request.

## Making changes

1. Fork the repository and create a branch from `main`.
2. Name the branch after the change, for example `feat/station-search` or `fix/arrival-times`.
3. Keep each pull request focused on one change.
4. Open a pull request against `main` and describe what changed and why.

## Commit messages

This project follows [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): short description
```

The scope is optional and names the area of the app, such as `map`, `stations`, `arrivals` or `api`.

| Type       | Use for                                    |
|------------|--------------------------------------------|
| `feat`     | a new feature                              |
| `fix`      | a bug fix                                  |
| `docs`     | documentation only                         |
| `refactor` | code changes that don't change behavior    |
| `test`     | adding or updating tests                   |
| `style`    | formatting only                            |
| `chore`    | tooling, configuration, dependencies       |
| `ci`       | continuous integration setup               |

Examples:

```
feat(map): show station markers
fix(arrivals): handle missing departure times
docs: add setup instructions to README
```

If a commit resolves an issue, reference it in the commit body or footer, for example `Closes #12`.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
