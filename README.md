# grasm-lang.github.io

The Grasm website: 24 pages, a scorecard whose numbers come from gate runs, and
a playground that compiles in the browser against `grasm.wasm`.

This repository holds **only the built site**. It is generated from the compiler
repository by `scripts/site.py`, which refuses to build when a page states a
figure no run recorded — every number on the site is traceable to the gate that
produced it.

Serve it locally with any static server:

```sh
python3 -m http.server 8080
```
