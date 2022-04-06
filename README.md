# SimEngAr: A simple Beamer template for slides with English and Arabic script

Mixing English and Arabic script in Beamer slides can be complicated. This
simple Beamer/RMarkdown template is aimed to make that task a little easier.

## Preview

![](./screenshots/title_slide.png)

![](./screenshots/slide_w_arabic.png)

![](./screenshots/two_column_slide.png)

## Prerequisites

- A working [Latex](https://www.latex-project.org/get/) installation
- [R](https://www.r-project.org) and an R IDE such as [RStudio](https://www.rstudio.com)
- An Arabic font such as [Scheherazade](https://fontlibrary.org/en/font/scheherazade), [Amiri](https://fontlibrary.org/en/font/amiri), or [Noto Sans Arabic]

The code has been tested on Windows 10 and Ubuntu 20.04.

## Use

1) Download `beamerthemeSimEngAr.sty` and `simple_english_arabic.Rmd` (or clone
the repository)
2) Edit the content of the `.Rmd` file to your needs.
3) Knit the `.Rmd`. Note that `beamerthemeSimEngAr.sty` must be accessible to R
by being either a) in the same folder as the `.Rmd` or b) in a folder below your
TeX home directory.

If you prefer a navigation sidebar instead of a navigation footer, follow the
instructions in the `.sty` file.
