# Unofficial ISS LaTeX Template — Downloads

Ready-to-use LaTeX templates for the Istituto Superiore di Sanità: a 16:9 beamer deck and a matching A0 poster, both with optional dual branding for a partner institution.

> **This is not an official ISS template** and is not endorsed by the institute. It is an independent re-skin of the [SINTEF Presentation theme](https://github.com/federicozenith/sintefbeamer) by Federico Zenith, by way of [Andrea Gasparini's Sapienza template](https://github.com/andrea-gasparini/sapienza-beamer-template).

## Download

Download the zip you need straight from this repository:

- **[`latex_presentation_template_ISS.zip`](latex_presentation_template_ISS.zip)** — the beamer deck. Unzip, then compile `presentation.tex` with `latexmk -pdf presentation.tex` (or `pdflatex`, run twice).
- **[`latex_poster_template_ISS.zip`](latex_poster_template_ISS.zip)** — the A0 poster. Same idea, compile `poster.tex`.

Each zip is self-contained: the theme files, the colour palette (`isscolor.sty`), a demo bibliography, the logo assets, and the licence. Unzip either one into your own LaTeX project (or point `TEXINPUTS` at it) and start editing — see the comments at the top of `presentation.tex` / `poster.tex` for the available options (dual branding, footline colour, dark slides, and so on).

## Licence

GNU General Public License v3.0 — see [LICENSE](LICENSE). Both template files carry a GPL-3.0 header, inherited from the SINTEF/Sapienza chain of templates this project descends from.
