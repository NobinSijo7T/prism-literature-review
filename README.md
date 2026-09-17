# PrismSpace - Literature Review Presentation Deck

This repository contains the LaTeX Beamer presentation slides, architectural diagrams, literature survey modules, and compiled slide decks for the **PrismSpace** B.Tech Project (Group 01, CEK).

## Repository Overview

- **`ppt/`**: Core presentation assets, literature review sections, and LaTeX Beamer decks:
  - `prismspace_deck.tex`: Comprehensive presentation deck.
  - `Detailed_Explanation[1-5].tex`: In-depth concept and architecture explanations.
  - `Lr[2-7].tex`: Literature review chapters and comparative analyses.
  - `Proposed Solution.tex` / `Implementation.tex`: System architecture and implementation details.
  - `ppt/`: Compiled deliverables (`main.pdf`, `_arch_preview.pdf`), master Beamer source (`main.tex`), and modular slide components (`slides/`).
  - Architecture diagrams, Gantt charts, workflows, and visual assets (`.png`, `.jpg`).

## Compilation

To build the presentation from source using `pdflatex` or `latexmk`:

```bash
cd ppt/ppt
latexmk -pdf main.tex
```
