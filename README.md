# SCKIT <img src="https://github.com/rstatistics/SCKIT/blob/main/inst/figures/SCKIT_logo.png" align="right" height=142 width=164/>

SCKIT is an R package designed for single-cell gene expression data _importation_, _integration_, _clustering_, _differential analysis_, _functional analysis_, and _visualization_. Since SCKIT does not change the default data structure of Seurat, it can be easily integrated into most existing scRNA-seq workflows. 

SCKIT can be used to read other information (such as gene mutation-by-cell matrix, pathogen count-by-cell matrix) and store them as additional data in the Seurat obj@metadata slot. In addition, SCKIT also has the function of reading and distinguishing the source of cells from the scRNA-seq data of xenografts samples (PDX model).

When there are many points in the vector diagram, editing becomes difficult. To this end, most visualization functions in SCKIT have the option to rasterize the _geom_point_ layer of ggplot2 and keep all axes, labels, and text in vector format.

## Installation

SCKIT package can be easily installed under the following instruction:

```
devtools::install_github("rstatistics/SCKIT")
```

## Vignettes

Please check the following link to get a rapid understanding about SCKIT:

[Walkthrough - Exploring Intracellular Pathogens of H3N2 at Single-Cell level using PathogenTrack and SCKIT](https://htmlpreview.github.io/?https://github.com/rstatistics/SCKIT/blob/main/vignettes/SCKIT_example.html)

## Help

If you have any problems, comments or suggestions, please feel free to contact _**Wei Zhang**_, [admin@ncrna.net](mailto:admin@ncrna.net).

## How to cite

**Decoding Intracellular Pathogens of scRNA-seq experiments with PathogenTrack and SCKIT.**








