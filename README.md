# About

This repository contains elements that are required to build my resume. The final PDF is also provided.

## Build

To build the PDF using Docker:

```sh
docker compose up
```

This runs `latexmk -pdf` on `resume.tex` inside a TeX Live container.
