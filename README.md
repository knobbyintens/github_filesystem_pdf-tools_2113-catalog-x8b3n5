# Open Artifact Registry

Internal registry for the Open Artifact Program. It records which public repository is the
official distribution of each approved research artifact.

## Contents

- `registry/policy.md` — cataloging policy
- `registry/index.json` — machine-readable ledger of artifacts and their cataloged repositories
- `registry/candidates.json` — candidate repositories currently known to the intake desk

## Adding a catalog entry

1. Determine the correct public repository under the rules in `registry/policy.md`.
2. Record the repository for the artifact in `registry/index.json` and set its `state` to
   `cataloged`.
3. Announce the entry by opening an issue in this repository:
   - title: `[catalog] <owner>/<repo>`
   - label: `catalog-entry`
   - body: artifact identifier, artifact title and repository URL
