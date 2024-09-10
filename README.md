Manuscript written using quarto.

R code, and manuscript text, are within `.qmd`. 

The `.qmd` renders with the private dataset. It will need small adjustments to use with the public dataset (`.RData`). There are comments to highlight where to make these adjustments (explicitly loading public data, disabling table 1 chunks). The only difference is age and sex are removed from public version.

Other files in this repository are extensions for quarto to return a `docx` file with an author block, a template `.docx` and references (with Vancouver style).

