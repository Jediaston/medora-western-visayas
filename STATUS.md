# Status: Ready for facility JSON shards

Waiting to receive base64 payloads for:

- `part-0.json`
- `part-1.json`
- `part-2.json`
- `part-3.json`

Will overwrite/create those root files with the decoded exact contents (no truncation, no invented facilities), verify sizes/counts, remove stubs and `_staging/` if present, then commit.
