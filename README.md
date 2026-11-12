# Hanuman Chalisa Reader

**Live site: https://hariongithub.github.io/hanuman-chalisa/**

All 40 verses plus the opening and closing couplets in Devanagari, Telugu and English sounds, with plain meanings, a practice mode and a quiz.

- `index.html` is the whole site.
- `audio/` holds the per-verse clips: `01.m4a` to `40.m4a`, and `D1.m4a` to `D4.m4a` (the opening and closing couplets and the closing cries).
- Recording shown on the page: M. S. Subbulakshmi and Radha Vishwanathan, Samarpanam (Saregama India), embedded from YouTube.

Text by Tulsidas (public domain). Meanings are plain-English renderings. Telugu spellings are machine-converted and not proofread.

## Recording from the page

At the bottom of the page, "Recorder tools" adds a record button and a bin next to each verse's play button. A recording is committed to `audio/` in this repo, using a fine-grained GitHub token (Contents: Read and write, limited to this repository) that is stored only in the recorder's own browser. Never put a token in the repo.
