# resume

[![pdf](https://github.com/roytsmart/resume/actions/workflows/pdf.yml/badge.svg)](https://github.com/roytsmart/resume/actions/workflows/pdf.yml)

The resume of Roy T. Smart.

📄 **[Read the resume (pdf)](https://roytsmart.github.io/resume/resume_smart.pdf)**

## Building

The pdf is not committed. GitHub Actions builds it on every push, and pushes
to `master` publish it to the `gh-pages` branch, which serves the link above.
Each pull request gets a preview of its own, linked in a comment on the pull
request and removed once the pull request is closed.

To build it locally, with a TeX Live installation that includes `biber`:

```bash
latexmk -pdf resume_smart.tex
```
