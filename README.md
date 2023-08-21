# Write your dissertation in Rmarkdown

The UiB dissertation template was created by PhD student Marius Saltvedt. The template was created by combining Rmarkdown with the official UiB LaTeX template <https://avhandling.uib.no/>.

All the `.Rmd` files here correspond to the different sections of the dissertation.

You may render the template through knitting the file `main.Rmd` to create the complete dissertation structure.

The YAML section in the `main.Rmd` provides proper format of the dissertation, so it can be shrunken to the smaller book-format (17 x 24 cm) before print (you don't have to worry about this). Additionally, this section loads in the bibliography file containing the references written in `BibTex` format, and it loads in the `preamble.tex` file that loads in necessary LaTeX commands and packages.

Check out the file called `chX_examples.Rmd` to see some nice examples of useful commands.

This work is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).