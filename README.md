# Test_Resume_CV
Rstudio environment for testing TinyTex. Both Rmd files utilize the [vitae package](https://github.com/mitchelloharawild/vitae) and produce a resume and CV respectively in pdf. Both work on my old Windows machine (Windows 10 Home, R Studio V 1.3.959, R V 4.0.0, tinytex V 0.24), but not on my new Windows machine (Windows 11 Pro, RStudio 2023.12.1 Build 402, R V 4.3.3, tinytex V 0.5) as of 05Apr2023.

## Master_Resume

RMarkdown code produces a pdf of a resume from education, experience, and awards stored as CSV files and publications stored as BibTeX file. Code depends on vitae package. Template is combination of [vitae::hyndman](https://github.com/robjhyndman/CV) and [vitae::natbprice](https://github.com/natbprice/cv).

## Master_CV

RMarkdown code produces a CV in pdf using the [vitae::hyndman](https://github.com/robjhyndman/CV) template.
