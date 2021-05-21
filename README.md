# About this workspace

The Github repository for this project can be found 
[here](https://github.com/avahoffman/DESeq2-viz-demo).

This experiment uses *Arabidopsis thaliana* RNA-seq data. We are
interested in how growing condition and plant type has changed counts of
different genes.

## What kind of visualizations are we using?

Principal Component Analysis (PCA) lets us look at variation in the
dataset. Points that appear far apart on a PCA plot are very different
compared to those closer together.

![Principal components of the RNA-seq study by condition](https://drive.google.com/uc?id=1juIuUWjJKqbeFbPnPA-F4mLK26lh4B7T)

*Image 1: Principal component analysis showing the variation among samples in this
RNA-seq study. Note how samples cluster together by condition, meaning that gene 
expression in samples with shared condition are more similar.*

MA-plots compare the counts a given gene has to the difference in
expression for the given gene. “Counts” usually refer to the mean number
of times the gene was expressed among all samples. The “log fold change”
describes the log-transformed difference between conditions or types.

![MA Plot of the RNA-seq study](https://drive.google.com/uc?id=1gDx49uABJc7dcZPGR1cNuo9LzdpATmGR)

*Image 2: Mean gene counts (expression) among individuals versus log
fold change in expression. Each point represents a gene. Genes deemed
significantly different between conditions are blue. Positive log-fold change genes
have greater expression in the ABA treatment compared to the Mock condition.*
