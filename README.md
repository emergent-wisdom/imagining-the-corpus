# Imagining the Corpus

**Turning Text into Video for Language Model Training**

*Imagining the Corpus* proposes a language-model training paradigm in which
the text corpus is compiled into synchronized explanatory video and one shared
predictive model learns to continue both the exact native text and its evolving
visual world. Its distinctive target is the unvisualized abstract corpus:
mathematics, code, scientific mechanisms, protocols, and conceptual systems
for which no adequate video currently exists.

This is an architecture proposal. It defines a training-data pipeline,
candidate model designs, matched controls, and falsification criteria; it does
not report an empirical outcome.

## Paper

- [`imagining-the-corpus.pdf`](imagining-the-corpus.pdf) — compiled preprint
- [`imagining-the-corpus.tex`](imagining-the-corpus.tex) — LaTeX source
- [`references.bib`](references.bib) — bibliography

## Build

From this directory, run:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error \
  -auxdir=tmp/pdfs -outdir=. imagining-the-corpus.tex
```

## License

The reusable LaTeX style material is available under the [MIT License](LICENSE).
The paper, its source, bibliography, and documentation are available under
[Creative Commons Attribution 4.0](LICENSE-CONTENT), except where third-party
terms apply.
