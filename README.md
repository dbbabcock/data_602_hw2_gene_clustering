# DATA 602 Homework 2: Gene Clustering

<h1>Purpose:</h1>

Blue Genes Pharmaceuticals is interested in improving their cancer fighting drugs by targetting the expression of specific genes.<br>
<br>
They recently received gene expression data across 20,531 different genes from 801 samples taken from patients who were presenting with tumors from one of five different categories.
<br>
In the interest of directing future treatments, they have decided to apply unsupervised clustering algorithims to this dataset in order to locate genes or groups of genes that might play a role in development of tumors.

(This is a fictional scenario using real gene expression data donated to the UCI Machine Learning Repository. This project is for the DATA 602 Homework 2 that requires solving a clustering problem)

<h1>Goal:</h1>

The goal of this exercise is to see if the expressions of these 20,531 genes can be clustered meaningfully by sample and/or by expression levels.<br>

In other words: Do the samples from patients with the same type of tumor cluster together well? Do the genes cluster together by expression levels?<br>

If the gene expression levels cluster meaningfully across the samples, as in the clusters appear to correspond to the tumor labels, then those genes with higher expression should be looked at more closely to see if they might be a good target for future cancer treatments.<br>

If the gene expression levels cluster meaningfully across the different genes, as in some genes tend to increase in expression together, then we might be able to find groups of genes that are relevant to tumor growth and should be researched further.<br>

Both of these outcomes could prove very useful to Blue Genes Pharmaceuticals and their future treatments.

<h1>Dataset Used:</h1>

https://archive.ics.uci.edu/ml/datasets/gene+expression+cancer+RNA-Seq#

<h1>Data Features:</h1>

This dataset contains the expression levels of 20,531 genes from 801 samples from patients with one of five different kinds of tumors:

BRCA = Breast Carcinoma (300 samples)<br>
COAD = Colon Adenocarcinoma (78 samples)<br>
KIRC = Kidney Renal Clear Cell Carcinoma (146 samples)<br>
LUAD = Lung Adenocarcinoma (141 samples)<br>
PRAD = Prostate Adenocarcinoma (136 samples)<br>

Tumor information from:

Cancer Genome Atlas Research Network, Weinstein JN, Collisson EA, et al. The Cancer Genome Atlas Pan-Cancer analysis project. Nat Genet. 2013;45(10):1113-1120. doi:10.1038/ng.2764

<h1>Packages and Versions Used:</h1>

Pandas version used: 1.0.5
<br>Matplotlib version used: 3.2.2
<br>Numpy version used: 1.18.5
<br>Scikit-learn version used: 0.23.1
<br>Yellowbrick version used: 1.1
