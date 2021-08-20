# R-to-Pandas

I'm a long time R user moving to Python. This repo compiles some useful examples
that demonstrate the equivalent Pandas functionality for R tidyverse/ggplot2
functionality.

The examples are contained within the same Markdown files, using
[{reticulate}](https://rstudio.github.io/reticulate) to run Python within the R
environment.

The `local_setup.R` file that is sourced in the Rmarkdown documents sets the 
local version of Python that is to be used, using the `reticulate::use_python()`
function. It is not included here, but you may wish to create your own that
points R to the correct version of Python.