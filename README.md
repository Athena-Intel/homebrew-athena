# Homebrew tap for the Athena CLI

```bash
brew install athena-intel/athena/athena
athena login
```

Or in two steps:

```bash
brew tap athena-intel/athena
brew install athena
```

Upgrades follow the normal `brew upgrade athena`. The formula is regenerated
from each [athena-cli release](https://github.com/Athena-Intel/athena-cli/releases)
and its published `SHA256SUMS` by the `bump` workflow, which polls for new
releases every 30 minutes. Do not edit `Formula/athena.rb` by hand; change
`scripts/render-formula.sh` instead.

Source, issues, and the non-Homebrew installer: https://github.com/Athena-Intel/athena-cli
