# Some slide decks using [quarto](https://quarto.org)

View at https://pvgenuchten.github.io/slides

slides are prepared in markdown, quarto renders markdown to [revealjs]() in a github action.

support for [mermaidjs]() for rendering diagrams

## render as powerpoint

In case you want to render a deck as powerpoint, use (first [install quarto](https://docs.posit.co/resources/install-quarto.html)):

```
quarto render example.qmd -t pptx
```