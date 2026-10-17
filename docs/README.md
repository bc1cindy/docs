---
type: Readme
description: The mdbook these chapters form, its introduction and its table of contents.
---

This directory holds the chapters of an mdbook published at
<https://fungi-protocol.github.io/docs/>. Its introduction is
[../README.md](../README.md), the repository's entry point, and its table of
contents is [index.md](index.md).

To preview the book, build its source from these chapters and serve it from
the development shell, at the root of the repository:

```sh
nix develop
python3 contrib/book.py .
mdbook serve
```

mdbook watches `src/`, so rerun `book.py` after editing a chapter.
