# imecos_software_guide

Shared materials on how to use software for the courses in IMECOS. Hosted as a website at [https://olivierbonte.github.io/imecos_software_guide/](https://olivierbonte.github.io/imecos_software_guide/)

Software requirements to use this repository

- [Quarto](https://quarto.org/docs/get-started/) (1.10 or higher)
- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) (to install Python)
- [R](https://cran.r-project.org/)(4.3 or higher)

See the respective guides on the website for more info. Reproducible package management for R is done via [renv](https://rstudio.github.io/renv/). 

## Brief installation guide for developers

With the tools listed above installed:

- R environment install: open R and run `renv::restore()`
- Python environmental install: open a terminal and run `conda env create -f environment.yml` to create a conda environment with the required packages. 
- Run `quarto check` and see that both the R and Python3 installations are detected. 

