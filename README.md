# Resume

LaTeX source for my personal resume. The PDFs are built automatically by GitHub Actions on every push that modifies a `.tex` file and committed back to the repository.

There are three variants that differ only in the summary:

| PDF | Source | Target |
| --- | --- | --- |
| `resume.pdf` | `resume.tex` | Software development |
| `resume-ai.pdf` | `resume-ai.tex` | AI / LLM roles |
| `resume-analyst.pdf` | `resume-analyst.tex` | Data / business analyst |

Everything except the summaries lives in `resume.tex`; the variant files just set `\variant` and `\input` it.
