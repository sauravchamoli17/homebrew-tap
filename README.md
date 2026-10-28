# homebrew-tap

Homebrew casks for my own tools.

```bash
brew tap sauravchamoli17/tap
brew trust --cask sauravchamoli17/tap/vulnradar
brew install --cask sauravchamoli17/tap/vulnradar
```

Homebrew 6 refuses casks from a third-party tap until you trust them, so the middle
step is not optional.

| Cask | What it is |
|------|------------|
| [`vulnradar`](https://github.com/sauravchamoli17/vulnradar) | Tells you which of the latest CVEs actually affect your projects |

The build is ad-hoc signed rather than notarised, so the cask strips the quarantine flag
on install.
