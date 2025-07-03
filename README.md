# Supplemental Material for "A Survey on Tensor-Based Spatiotemporal Data Imputation: Knowledge Engineering Perspectives and Modeling Strategies"

This repository contains the supplemental material for the survey paper "A Survey on Tensor-Based Spatiotemporal Data Imputation: Knowledge Engineering Perspectives and Modeling Strategies."

The main component of this supplemental material is `Supplemental Material.pdf`, which provides an extended summary and classification of representative tensor imputation methods.

## Table A1: Summary of Tensor Imputation Methods

**Table A1** (included in `Supplemental Material.pdf`) systematically categorizes tensor imputation methods based on their modeling of spatiotemporal effects. It offers a detailed overview, summarizing the **advantages, limitations, and applicability** of each method category under various missing patterns. This table is designed to provide theoretical support for selecting appropriate imputation methods for different data types.

The methods are primarily classified into two main groups:

* **Tensor Decomposition-based methods (TD)**
* **Tensor Nuclear Norm-based methods (NN)**

Within these groups, methods are further organized by three key spatiotemporal effect modeling strategies:

* **Spatiotemporal Correlation**: These methods often focus on extracting periodic features or enhancing local spatial correlations. Examples include Truncated Nuclear Norm (TNN-HTV) for periodic features and Graph Laplacian Matrix (GT-SVD) for local spatial correlation. They are generally suitable for **Random Missing (RM)** and **Block Missing (BM)** scenarios.
* **Spatiotemporal Heterogeneity**: These approaches often involve multi-view or generative models to adapt to diverse data distributions.
* **Geographical Similarity**: Methods in this category explicitly model geographic context or leverage dynamic geographic similarities.

For complex missing patterns such as **Temporal Missing (TM)** and **Mixed Missing (MM)**, especially in data exhibiting strong temporal and spatial dynamics (e.g., ship trajectories), the supplemental material also highlights the necessity of jointly modeling coupled changes. Approaches like sequential modeling and Generative Adversarial Networks (GANs) are introduced for these more challenging scenarios.

We hope this supplemental material provides valuable insights and a comprehensive reference for researchers and practitioners in the field of spatiotemporal data imputation.
