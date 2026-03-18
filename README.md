# Supplementary Material for "A Survey on Tensor-Based Spatiotemporal Data Imputation: Knowledge Engineering Perspectives and Modeling Strategies"

This document summarizes the supplementary material provided in "Supplemental Material.pdf." This repository contains the supplemental material for the survey paper titled "A Survey on Tensor-Based Spatiotemporal Data Imputation: Knowledge Engineering Perspectives and Modeling Strategies."

## Applications, Resources, and Decision Guideline

This section discusses the applications of tensor decomposition-based methods for spatiotemporal data imputation, the available resources (datasets and code), and a guideline for selecting the appropriate method.

### A. Downstream applications

Tensor decomposition-based methods are effective for handling missing data in various downstream applications:

*   **Intelligent Transportation System (ITS):** Improves traffic prediction, network optimization, and incident early warnings by addressing data loss from sensor malfunctions or communication interruptions.
*   **Environment monitoring:** Helps in imputing missing environmental data (e.g., air quality, meteorological data) and trajectory data, which is crucial for pollutant tracking, disaster early warning, and ecological preservation.
*   **Climate science:** Recovers the intrinsic structure and dynamics of high-dimensional, heterogeneous spatiotemporal climate data, providing more complete and reliable inputs for climate models. This is crucial for improving the accuracy of climate predictions and understanding the climate system.
*   **Other applications:** Includes shared mobility demand prediction, energy systems state imputation, and medical and health monitoring (e.g., imputing EEG signals).

### B. Code and datasets

A wealth of high-quality public datasets and open-source code resources are available for tensor decomposition-based spatiotemporal data imputation. The document provides tables with links to publicly available datasets and code.

*   **Datasets:** The datasets are categorized into two main types: time-dynamic, spatial-static, and time-dynamic, spatial-dynamic. The tables include dataset names, data types, sampling rates, data dimensions, and links.
*   **Code:** The document provides links to publicly available code for various tensor decomposition-based methods, including LRTC-3DST, Meta-TD, BGCP, BTTF, BATF, BTMF, and LRTC-TNN.

### C. Comparative performance synthesis

The paper provides a systematic classification of representative works in tensor imputation through the lens of spatiotemporal effect modeling. It summarizes the advantages and limitations of various methods and their applicability across different missing patterns (RM/BM/TM/MM).

The document includes a table that provides a comparative synthesis of representative tensor-based spatiotemporal imputation methods. The table compares the methods based on the spatiotemporal effect they model (SC, SH, or GS), whether they require external data, and their performance on different missing patterns.

### D. Method selection decision guidelines

The document provides a priority-based decision framework to help users select the appropriate method for their specific data scenario. The framework is designed as a “bottleneck-driven” heuristic logic, aimed at identifying an appropriate modeling path based on the primary source of imputation difficulty.

The framework suggests three paths based on the dominant modeling bottleneck:

*   **Path A: Spatiotemporal heterogeneity (SH) modeling:** Prioritized when the data exhibit strong non-stationarity and local variation.
*   **Path B: Geographical similarity (GS) modeling:** Preferred when the intrinsic structural information of the tensor is insufficient, but rich and informative external spatial priors are available.
*   **Path C: Spatiotemporal correlation (SC) modeling:** Offers the most efficient and interpretable solution when the tensor possesses significant intrinsic dependencies.

The framework also emphasizes that these paths are not mutually exclusive and a hybrid strategy can be used for complex datasets.

## References

The document includes a comprehensive list of references to the papers and resources mentioned in the text.
