# github-actions

Centralized GitHub Actions for reuse across repositories

Events and Actions

# Dependabot auto-approve

- Auto-merge
- Template workflow for each repository to call auto-merge, and then run release-please if appropriate

  Fix title

# Push (Commit)

- Verify Prettier formatting
- Salesforce Code Analyzer
- ~~PMD Analysis (download?)~~

# Pull Request (any branch)

- Verify Prettier formatting
- Code Analyzer
- Lint & Test LWCs & upload to codecov

- ~~PMD Analysis (action?)~~

  Needs LWC upload

- Apex compile
- Apex Tests & upload to codecov
- Scratch org
  
  Adjust namespace if necessary?

# Release Please

- Run without packaging to npm action

# Packaging

- On demand or from merged R-P PR or on package creation?

# Extras

- SFDX Scanner (runs on PR only)

# Configs

- Renovate [shareable config file](.github/renovate.json5)
