# Basic Website Template

This is a basic website template for use in PROG209. It is a copy of the homework for assignment #2.

## Releases

Releases are automated with [release-please](https://github.com/googleapis/release-please).
Write commit messages in the [Conventional Commits](https://www.conventionalcommits.org/) format:

- `fix: ...` makes a patch release
- `feat: ...` makes a minor release
- `feat!: ...` or a `BREAKING CHANGE:` footer makes a major release

After each push to `main`, release-please opens or updates a release PR.
Merging that PR updates `CHANGELOG.md` and `version.txt`, tags the version and publishes a GitHub release.
