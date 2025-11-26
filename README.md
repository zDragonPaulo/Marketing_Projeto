# EzPower™ — Smart Retractable Power Outlet (Marketing Report)

## Overview

EzPower™ is a concept for a multifunctional smart outlet that combines a retractable cable (like a built-in extension reel) with smart-home features such as Wi‑Fi/Bluetooth connectivity, energy monitoring, scheduling, virtual assistant integration, and an accompanying mobile app. This repository contains the project report describing product design, market analysis, operations, financial plan, and team contributions.

## Awards

- 1st Prize — PoliEmpreende contest at Instituto Politécnico de Beja.

## Key features (from the report)

- Retractable cable mechanism built into the outlet (available in multiple lengths)
- Smart outlet functionality (remote control, scheduling)
- Wi‑Fi and Bluetooth connectivity for mobile control
- Energy consumption monitoring
- Integration with virtual assistants (Google Assistant, Amazon Alexa)
- Real-time notifications and customizable scenarios (e.g., "vacation mode", "night mode")
- Intended retail channels: direct online store, marketplaces (Amazon, Fnac, Worten) and large physical retailers

## Contents

- Relatorio.tex — Main LaTeX source of the marketing/project report
- Recursos/ — Images, figures, and bibliography (referenced in the LaTeX file)
  - referencias.bib — bibliography file used by the report
  - several PNG/JPG graphics used by the PDF

## Build / Compile the report (English)

This project uses LaTeX with biblatex (backend=biber). To compile the PDF from Relatorio.tex locally:

Prerequisites
- A LaTeX distribution (TeX Live or MiKTeX)
- biber (for bibliography)
- Recommended: latexmk (automates the build steps)

Manual commands (run from the repository root):

1. pdflatex Relatorio.tex
2. biber Relatorio
3. pdflatex Relatorio.tex
4. pdflatex Relatorio.tex

Or using latexmk:

- latexmk -pdf -pdflatex="pdflatex -interaction=nonstopmode" -use-biber Relatorio.tex

After successful compilation you'll get Relatorio.pdf in the repository folder.

Note: If images are missing, check Recursos/ paths and ensure image files exist.

## Project structure

- Relatorio.tex — LaTeX report
- Recursos/ — images and referencias.bib used by the report
- (You can add other materials such as Excel projections, raw market data, or design sketches to the repo.)

## Contribution

This repository is currently a report/document. If you want to:
- Improve the report text or formatting: edit Relatorio.tex
- Replace or add images: update Recursos/
- Add English translations or a separate README in Portuguese: create new files

Suggested workflow:
1. Fork the repository.
2. Create a branch (feature/cleanup-or-english-translation).
3. Commit changes and open a pull request.

Authors:
- João Eduardo Sara Sousa — 23916
- Martinho José Novo Caeiro — 23917
- Paulo António Tavares Abade — 23919

Project advisor:
- Eunice Duarte

## Notes & acknowledgements

- The report was prepared in Portuguese and includes market, operational, and financial analysis. The LaTeX source uses biblatex with biber.
- This project was awarded 1st Prize at the PoliEmpreende contest hosted by the Instituto Politécnico de Beja — a recognition of the concept's innovation and market potential.

## License

- This repository is licensed under the GNU General Public License v3.0 (GPL-3.0).
