## Integrating Histology Imaging and Spatial Transcriptomics through Low-Dimensional Embeddings to Predict Gene Expression Patterns
# Authors 
 - Susie Avagyan: savagyan@stanford.edu
 - Gaurav Anand: gauvand9@stanford.edu
 - Lauren Cooper: cooperlc@stanford.edu


## Abstract

Spatial transcriptomics (ST) is emerging as a powerful
tool for understanding biological information at the tissue, cellular,
or sub-cellular scale. On the flip side, existing technologies
to obtain and analyze this data can be complex and costly. Here,
we present multiple approaches for **predicting gene expression
from histology images**, which are cost-effective to obtain, along
with spatial adjacency information. We calculated embeddings of
our input data with ResNet50 and k-nearest neighbors. We then
utilized various regression methods (linear, negative binomial)
and deep learning models (a simple neural network, graph neural
network). Upon further improvements, these results could be used
to reduce the cost of spatial sequencing by using histology images
to predict gene expression.

## Repository Content

This repository contains scripts for preprocessing of the different modalities, model training, and prediction, as well as evaluation and validation. The poster used to present the results of the project, as well as the write-up are also included in the repository.
