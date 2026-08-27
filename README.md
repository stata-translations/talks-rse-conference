# Presentation Slides for Stata Con London 4th September 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22124105.svg)](https://doi.org/10.5281/zenodo.22124105)

Slides for a presentation to Stata conference 

You can build locally with `quarto render` or use the publish [action](.github/workflows/publish.yml).

## Related Work
[Stata2R](https://github.com/stata-translations/Stata2R)

[Quarto Template](https://github.com/UCL-ARC/assets-and-templates/tree/main/quarto-slides)

## People

[Stephen](https://github.com/thompson318).

## Making a pdf
It's quite tricky to make a meaningful pdf of this. This is the best I've done so far
```
sudo apt-get install wkhtmltopdf
pandoc _output/logo-slides.html -t html -o talk_slides.pdf

