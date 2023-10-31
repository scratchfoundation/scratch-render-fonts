# scratch-render-fonts

Fonts for Scratch SVG rendering

[![CI/CD](https://github.com/scratchfoundation/scratch-render-fonts/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/scratchfoundation/scratch-render-fonts/actions/workflows/ci-cd.yml)

## Committing

This project uses [semantic release](https://github.com/semantic-release/semantic-release) to ensure version bumps
follow semver so that projects depending on it don't break unexpectedly.

In order to automatically determine version updates, semantic release expects commit messages to follow the
[conventional-changelog](https://github.com/bcoe/conventional-changelog-standard/blob/master/convention.md)
specification.

Use the [commitizen CLI](https://github.com/commitizen/cz-cli) to make commits formatted in this way:

```bash
npm install -g commitizen
```

Now you're ready to make commits using `git cz`.
