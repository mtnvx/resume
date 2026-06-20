# Resume

LaTeX source for my personal resume. The PDF is built automatically by GitHub Actions on every push that modifies `resume.tex` and committed back to the repository as `resume.pdf`.

## Build locally

Requires [TeX Live](https://tug.org/texlive/) or any full LaTeX distribution.

```bash
latexmk -pdf resume.tex
```

To clean up auxiliary files:

```bash
latexmk -c
```
