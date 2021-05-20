# About this workspace

This experiment uses *Arabidopsis thaliana* RNA-seq data. We are
interested in how growing condition and plant type has changed counts of
different genes.

**What kind of visualizations are we using?**

Principal Component Analysis (PCA) lets us look at variation in the
dataset. Points that appear far apart on a PCA plot are very different
compared to those closer together.

![Principal components analysis of the Italian
population](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Principal_Component_Analysis_of_the_Italian_population.png/600px-Principal_Component_Analysis_of_the_Italian_population.png)

*Image 1: Principal component analysis showing the genetic structure of
the human population of Italy. Individuals are color coded by region.
Individuals from Sardinia are genetically different compared to the rest
of Italy based on genomic loci.*

MA-plots compare the counts a given gene has to the difference in
expression for the given gene. “Counts” usually refer to the mean number
of times the gene was expressed among all samples. The “log fold change”
describes the log-transformed difference between conditions or types.

![MA Plot](https://hbctraining.github.io/DGE_workshop/img/MA_plot.png)

*Image 2: Mean gene counts (expression) among individuals versus log
fold change in expression. Each point represents a gene. Genes deemed
significantly different between conditions are red.*
