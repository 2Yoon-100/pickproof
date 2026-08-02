# pickproof — tamper-proof seals for internal forward-tested picks

This repository stores **only SHA-256 hashes** of internal paper-pick files, one line
per file, appended the moment each file is created and never edited afterward.

`manifest.jsonl` — one JSON object per pick file:
`{ "date", "file", "sha256", "rules_version" }`

The pick files themselves are kept private. Publishing their hashes here, timestamped by
each commit, makes it impossible to alter a pick after the fact without the hash changing.
No pick content, no methodology, no probabilities are published here — hashes only.

_Pre-launch internal validation record. Not an official track record._
