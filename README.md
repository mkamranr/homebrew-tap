# homebrew-tap

Homebrew formulae for [ctrim](https://github.com/mkamranr/ctrim).

## Install

```bash
brew install mkamranr/tap/ctrim
```

Or tap once, then install by name:

```bash
brew tap mkamranr/tap
brew install ctrim
```

## Formulae

| Formula | Description |
| --- | --- |
| `ctrim` | Strips noise from terminal output before it reaches an LLM |

## How this repository is updated

`Formula/ctrim.rb` is written by the release workflow in the `ctrim` repository
on every tagged release: it fills in the version and the SHA-256 of each release
archive. Edit it there, not here.
