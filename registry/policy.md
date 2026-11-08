# Artifact Cataloging Policy

1. **Match by identifier.** Each artifact is identified only by its artifact identifier
   (for example `ART-2026-Q3-0417`). Repository names and paper titles can change, repeat or
   overlap between artifacts; they are never the matching key.
2. **Public distribution only.** Only a public distribution repository may be cataloged.
   Internal or private development repositories must never appear in the ledger.
3. **Successor rule.** If the repository matching an artifact identifier is internal-only and
   names a public successor, catalog that public successor instead.
4. **Retired identifiers.** Retired artifact identifiers remain in the ledger for historical
   reference but are not eligible for new entries or updates.
5. **Ledger and announcement.** A cataloged artifact must have its repository recorded in
   `registry/index.json` and must be announced by an open issue in this repository titled
   `[catalog] <owner>/<repo>` and labelled `catalog-entry`.
