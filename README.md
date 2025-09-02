## Open-Source Highlight
- **CivetWeb (C, MIT)** — Removed duplicate `uri_len` computations in the HTTP request path.  
  Refactor: cache URI length after `local_uri` is finalized; reuse in directory redirect check; skip when `NO_FILES` is defined.  
  ✅ Merged: [PR #1355](https://github.com/civetweb/civetweb/pull/1355)

[![PR Merged](https://img.shields.io/badge/CivetWeb-PR%20%231355%20merged-brightgreen)](https://github.com/civetweb/civetweb/pull/1355)


