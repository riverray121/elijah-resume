# elijah-resume

LaTeX source for my resume. Source lives in `main.tex`.

## Build locally

```sh
latexmk -pdf main.tex   # outputs build/main.pdf
```

## Automated publishing

On every push to `main` that changes `main.tex`, a GitHub Action
([build-resume.yml](.github/workflows/build-resume.yml)) compiles the PDF and
publishes it as the `latest` release asset. Stable download URL:

```
https://github.com/riverray121/elijah-resume/releases/latest/download/resume.pdf
```

My personal site's "Download Resume" button points at this URL.
