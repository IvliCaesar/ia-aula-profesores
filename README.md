# IA en el Aula — Universidad Panamericana

Slides (Beamer, in Spanish) for a hands-on workshop on artificial intelligence for university faculty, with an exam template in LaTeX.

## Contents

| File | What it is |
|---|---|
| `IA_aula_profesores.tex` / `.pdf` | Workshop slides (16:9, 46 frames) |
| `plantilla-examen.tex` / `.pdf` | Exam template using the `exam` class: points, grade table, multiple choice, solutions |
| `plantilla-examen-clave.pdf` | The same template compiled with `\printanswers` (answer key) |

## Topics

1. What generative AI is and is not; hallucinations.
2. Tool map: general assistants (Claude, ChatGPT, Gemini, Copilot), teaching tools (NotebookLM, MagicSchool, Diffit, Curipod, Canva), research tools, and professional tools — what each is for and how it helps.
3. Claude with an institutional (Team) account: privacy, Projects, Artifacts, Research, connectors.
4. Writing prompts: role, task, context, format, criterion.
5. Deep research: Claude Research, ChatGPT and Gemini deep research, Perplexity, Elicit, Consensus, Semantic Scholar; a discover → verify → synthesize workflow.
6. Bloomberg Terminal and ASKB; Bloomberg Market Concepts; Excel and BQL in finance courses.
7. LaTeX for exams: the `exam` class, A/B versions, answer keys, Overleaf.
8. GitHub for teachers: versioned exam banks, GitHub Education (free Team plan and Copilot for verified teachers), Classroom, Pages.
9. The professional context: WEF *Future of Jobs Report 2025* and the tools used in finance, engineering, law, consulting, research and health.
10. Risks, academic integrity, and good practice.

## Building

```
pdflatex IA_aula_profesores.tex
pdflatex IA_aula_profesores.tex
pdflatex plantilla-examen.tex
pdflatex plantilla-examen.tex
```

Requires `beamer`, `tcolorbox`, `fontawesome5`, `listings` and `exam`. For the answer key, uncomment `\printanswers` in `plantilla-examen.tex`.

## References

- World Economic Forum, *The Future of Jobs Report 2025*. <https://www.weforum.org/publications/the-future-of-jobs-report-2025/>
- Anthropic, *Introducing Claude for Education*. <https://www.anthropic.com/news/introducing-claude-for-education>
- Bloomberg, *Bloomberg introduces ASKB* (2026). <https://www.bloomberg.com/company/press/>
- Bloomberg for Education, certificate courses. <https://www.bloomberg.com/professional/products/bloomberg-terminal/education/certificate-courses/>
- GitHub Docs, *About GitHub Education for teachers*. <https://docs.github.com/en/education/about-github-education/github-education-for-teachers/about-github-education-for-teachers>
- P. Hirschhorn, *Using the exam document class*. <https://ctan.org/pkg/exam>

## Author

César Galindo, Universidad Panamericana.
