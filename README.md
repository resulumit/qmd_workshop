# Reproducible Research with Quarto and GitHub

This repository holds the materials for a workshop on writing reproducible research papers with Quarto, and on version-controlling and collaborating on them with Git and GitHub, first taught at the [Lucerne Master in Computational Social Sciences (LUMACSS)](https://www.unilu.ch/en/study/study-programmes/masters-degrees/faculty-of-humanities-and-social-sciences/lucerne-master-in-computational-social-sciences-lumacss/) in November 2026.

Unless otherwise noted, all material is copyright Resul Umit, licensed [CC BY-SA 4.0](https://github.com/resulumit/qmd_workshop/blob/main/LICENCE.md). An easy to read summary of this permissive licence is available on the [Creative Commons website](https://creativecommons.org/licenses/by-sa/4.0/).

You are welcome to use these materials for your own teaching --- simply credit the source. I would also really appreciate a short email to let me know that you are using them, at [resulumit@gmail.com](mailto:resulumit@gmail.com).

## Contents

The workshop is divided into ten parts. Most parts include exercises &mdash; 51 in total.

|[]() |      |
|------|------|
| **Part 1. Getting the Tools Ready** <br /> - e.g., downloading course material | **Part 6. Adding Code, Figures, and Tables** <br /> - e.g., plotting data |
| **Part 2. Introducing Quarto** <br /> - e.g., creating a new document | **Part 7. Fine-Tuning** <br /> - e.g., referring to tables |
| **Part 3. Setting Metadata** <br /> - e.g., defining output formats | **Part 8. Using Version Control** <br /> - e.g., integrating Git and GitHub |
| **Part 4. Writing Text** <br /> - e.g., adding emphasis to text | **Part 9. Collaborating with Others** <br /> - e.g., working simultaneously with co-authors |
| **Part 5. Managing References** <br /> - e.g., citing sources | **Part 10. Going Further** <br /> - e.g., using journal formats |

## Slides

The slides for the workshop are available to view at <https://resulumit.com/teaching/qmd_workshop.html>. These HTML slides are created with Quarto (Allaire et al., 2022), using its `revealjs` format.

See `presentation/qmd_workshop.qmd` for the source file underlying the slides.

## Materials

The remaining materials are available in a separate branch of this repository, called [materials](https://github.com/resulumit/qmd_workshop/tree/materials). It includes the following:

- `preparation/preparation_guide.pdf`
    - instructions for installing the required software before the workshop

- `preparation/the_test.qmd`
    - a Quarto document to check that everything is installed and works together

- `manuscript/reproduce_this.pdf`
    - a document, rendered with Quarto, to be re-created during the workshop
    - the parts that the exercises are about are in black, and the rest of the text is greyed out
    - margin notes show paragraph and exercise numbers
    - figures and tables are based on a fabricated dataset (`journals.csv`, see below)

- `manuscript/journals.qmd`
    - a Quarto document to work on during the workshop
        - includes unformatted text from `reproduce_this.pdf` to save time
        - major components, such as paragraphs and tables, are numbered and marked in comments to facilitate navigation

- `solutions/journals_after_part3.qmd` to `solutions/journals_after_part7.qmd`
    - Quarto documents showing how `journals.qmd` should look at the end of Parts 3 to 7
        - useful for catching up, or for checking your work, e.g., after missing an exercise
        - `journals_after_part7.qmd` has all exercises on the mock paper completed

- `manuscript/references.bib`
    - a BibTeX document with three fabricated references

- `manuscript/apa_7th.csl`
    - a Citation Style Language document, with APA (7th edition) referencing style (Wiernik, 2020)

- `data/journals.csv`
    - a dataset created with the `fabricatr` package (Blair et al., 2019), imagined to explore the Google Scholar rankings of fictitious journals
    - includes the following variables
        - **name**: journals (1091 random titles)
        - **origin**: geographic origins (five continents)
        - **branch**: major discipline of journals (four branches)
        - **since**: time of first publication (years)
        - **h5_index**: H5 Index (integers)
        - **h5_median**: H5 Median (integers)
        - **english**: English (1) *vs.* other-language (0) journals
        - **subfield**: subfield (1) *vs.* generalist (0) journals
        - **issues**: number of issues published per year (integers)

- `image/google_scholar.png`
    - a screenshot of the Google Scholar homepage, copyright Google, LLC

## References

Allaire, J. J., Teague, C., Xie, Y. and Dervieux, C. (2022). [Quarto](https://doi.org/10.5281/zenodo.5960048). Computer software.

Blair, G., Cooper, J., Coppock, A., Humphreys, M., Rudkin, A. and Fultz, N. (2019). [fabricatr: Imagine your data before you collect it](https://cran.r-project.org/web/packages/fabricatr/index.html). R package, version 0.10.0.

Wiernik, B. M. (2020). [American Psychological Association 7th edition (no ampersand)](https://www.zotero.org/styles/apa-no-ampersand). Citation style language file, version 1.0.
