# SDNCMV
Simultaneous Differential Network Analysis and Classification for High-dimensional Matrix-variate Data

In the article, we propose a method which achieves Simultaneous Differential Network analysis and Classification for Matrix-Variate data (SDNCMV). The SDNCMV is indeed an ensemble learning algorithm, which involves three main steps. Firstly, we propose an individual-specific spatial graphical model to construct the between-region network measures (connection strengths. In practice, we measure the between-region network strengths by a specific transformation function of the partial correlations in order to separate their values between two groups well. In the second step, with the constructed individual between-region network strengths and confounding factors, we adopt the bootstrap technique and train the Penalized Logistic Regression (PLR) models with bootstrap samples. Finally, we ensemble the results from the bootstrap PLRs to boost the classification accuracy and network comparison power.


Reference:

Chen H., Guo Y., He Y., Ji J., Liu L., Shi Y., Wang Y., Yu L., Zhang X. and for the Alzheimer’s Disease Neuroimaging Initiative. (2020). Simultaneous Differential Network Analysis and Classification for High-dimensional Matrix-variate Data, with application to Brain
Connectivity Alteration Detection and fMRI-guided Medical Diagnoses of Alzheimer’s Disease, arxiv:2005.08457

Please see https://arxiv.org/abs/2005.08457
