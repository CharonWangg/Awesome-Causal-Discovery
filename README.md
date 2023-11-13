# Awesome Causal Discovery

An awesome list of Causality and Machine Learning related papers, books and other resources. Currently, this list
is focused on Causal Discovery and Causal Representation Learning, starting from classical ones. More causality-related topics coming soon!

# [Table of Contents]()

* [Books](#Books)
* [Papers](#Papers)
* [Workshops(Coming soon)](#Workshops)
* [Datasets(Coming soon)](#Datasets)

## [Books]()
- [Causality](http://bayes.cs.ucla.edu/BOOK-2K/)
- [Causal Inference in Statistics: A Primer](https://www.wiley.com/en-us/Causal+Inference+in+Statistics%3A+A+Primer-p-9781119186847)
- [Elements of Causal Inference](https://library.oapen.org/bitstream/id/056a11be-ce3a-44b9-8987-a6c68fce8d9b/11283.pdf)
- [Causation, Prediction and Search](https://www.researchgate.net/publication/242448131_Causation_Prediction_and_Search)

## [Papers]()

### Review:
- [Towards Causal Representation Learning](https://arxiv.org/abs/2102.11107)
- [Causality for Machine Learning](https://arxiv.org/abs/1911.10500)
- [Causal Machine Learning: A Survey and Open Problems](https://arxiv.org/abs/2206.15475)
- [Review of Causal Discovery Methods Based on Graphical Models](https://www.frontiersin.org/articles/10.3389/fgene.2019.00524/full)
- [Causal discovery and inference: concepts and recent methodological advances](https://applied-informatics-j.springeropen.com/articles/10.1186/s40535-016-0018-x)
- [Learning causality and causality-related learning: some recent progress](https://academic.oup.com/nsr/article/5/1/26/4638533)
- [Causal Inference for Time series Analysis: Problems, Methods and Evaluation](https://arxiv.org/pdf/2102.05829.pdf)

### Causal Discovery
#### Conditional-Independence-based:

- (SGS/PC/FCI) [Causation, Prediction and Search (chapter 5, chapter 6)](https://www.researchgate.net/publication/242448131_Causation_Prediction_and_Search)
- (FCI) [Causal Inference in the Presence of Latent Variables and Selection Bias ](https://arxiv.org/pdf/1302.4983.pdf)
- (KCI) ​​[Kernel-based Conditional Independence Test and Application in Causal Discovery](https://arxiv.org/abs/1202.3775)
- (CD-NOD) [Causal Discovery from Heterogeneous/Nonstationary Data](https://www.jmlr.org/papers/volume21/19-232/19-232.pdf)

#### Score-based:

- (GES) [Optimal Structure Identification With Greedy Search](https://www.jmlr.org/papers/volume3/chickering02b/chickering02b.pdf)
- (GES) [Generalized score functions for causal discovery](https://pubmed.ncbi.nlm.nih.gov/30191079/)
- (NOTEARS) [DAGs with NO TEARS: Continuous Optimization for Structure Learning](https://arxiv.org/pdf/1803.01422.pdf)

#### Functional-causal-model based:

- LiNGAM
  - (Direct-LiNGAM) [A linear non-Gaussian acyclic model for causal discovery](https://www.jmlr.org/papers/volume7/shimizu06a/shimizu06a.pdf)
  - (ICA-LiNGAM) [A direct method for learning a linear non-Gaussian structural equation model.](https://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf) 
  - (VAR-LiNGAM) [Estimation of a structural vector autoregression model using non-gaussianity](https://www.jmlr.org/papers/volume11/hyvarinen10a/hyvarinen10a.pdf)

- Non-linear
  - (PNL) [On the Identifiability of the Post-Nonlinear Causal Model](https://arxiv.org/pdf/1205.2599.pdf)
  - (ANM) [Nonlinear causal discovery with additive noise models](https://papers.nips.cc/paper_files/paper/2008/file/f7664060cc52bc6f3d620bcedc94a4b6-Paper.pdf)

#### Independent Component Analysis:

- (Linear) [Independent Component Analysis: Algorithms and Applications](https://www.cs.helsinki.fi/u/ahyvarin/papers/NN00new.pdf)
- (iVAE) [Variational Autoencoders and Nonlinear ICA: A Unifying Framework](https://arxiv.org/pdf/1907.04809.pdf)
- (Auxiliary Info) 
  - [Nonlinear Independent Component Analysis for Principled Disentanglement in Unsupervised Deep Learning ](https://arxiv.org/pdf/2303.16535.pdf)
  - [Nonlinear ICA Using Auxiliary Variables and Generalized Contrastive Learning](https://proceedings.mlr.press/v89/hyvarinen19a/hyvarinen19a.pdf)
- (Temporal Info) 
  - [Unsupervised Feature Extraction by Time-Contrastive Learning and Nonlinear ICA](https://proceedings.neurips.cc/paper_files/paper/2016/file/d305281faf947ca7acade9ad5c8c818c-Paper.pdf)
  - [Nonlinear ICA of Temporally Dependent Stationary Sources](https://proceedings.mlr.press/v54/hyvarinen17a/hyvarinen17a.pdf)
  - [Towards Nonlinear Disentanglement in Natural Data with Temporal Sparse Coding](https://arxiv.org/abs/2007.10930)
  - [Hidden Markov Nonlinear ICA: Unsupervised Learning from Nonstationary Time Series](https://arxiv.org/abs/2006.12107)
  - [Disentangling Identifiable Features from Noisy Data with Structured Nonlinear ICA](https://arxiv.org/pdf/2106.09620.pdf)
- (Sparsity Constraint) 
  - [Disentanglement via Mechanism Sparsity Regularization: A New Principle for Nonlinear ICA](https://arxiv.org/abs/2107.10098)
  - [On the Identifiability of Nonlinear ICA: Sparsity and Beyond](https://arxiv.org/abs/2206.07751)
  - [Generalizing Nonlinear ICA Beyond Structural Sparsity](https://arxiv.org/pdf/2311.00866.pdf)

More nonlinear ICA work can be found at [Aapo’s website](https://www.cs.helsinki.fi/u/ahyvarin/papers/udl.shtml)

### Causal Discovery Dealing with Latent Variables (some are in ICA section):

- (Conditional-Independence)

  - [FCI](https://www.researchgate.net/publication/242448131_Causation_Prediction_and_Search)
  - [Learning high-dimensional directed acyclic graphs with latent and selection variables](https://arxiv.org/abs/1104.5617) 
  - [Recursive Causal Structure Learning in the Presence of Latent Variables and Selection Bias](https://arxiv.org/pdf/2110.12036.pdf)

- (Tetrad Condition) 

  - [Learning the Structure of Linear Latent Variable Models](https://www.jmlr.org/papers/volume7/silva06a/silva06a.pdf)
  - [Causal Clustering for 1-Factor Measurement Models](https://dl.acm.org/doi/10.1145/2939672.2939838)

- (Noise Condition) 

  - [Generalized Independent Noise Condition for Estimating Latent Variable Causal Graphs](https://proceedings.neurips.cc/paper/2020/file/aa475604668730af60a0a87cc92604da-Paper.pdf)
  - [Identifying Weight-Variant Latent Causal Models](https://arxiv.org/pdf/2208.14153.pdf)

- (Overcomplete ICA) 

  - [Estimation of linear non-Gaussian acyclic models for latent factors](https://www.sciencedirect.com/science/article/abs/pii/S0925231208005390)
  - [ParceLiNGAM: A causal ordering method robust against latent confounders](https://arxiv.org/pdf/1303.7410.pdf)
  - [Learning linear non-Gaussian causal models in the presence of latent variables](https://dl.acm.org/doi/abs/10.5555/3455716.3455755)

- (Matrix decomposition)

  - [Rank-Sparsity Incoherence for Matrix Decomposition](https://arxiv.org/abs/0906.2220)
  - [Latent variable graphical model selection via convex optimization](https://arxiv.org/pdf/1008.1290.pdf)
  - [Learning Linear Bayesian Networks with Latent Variables](https://proceedings.mlr.press/v28/anandkumar13.pdf)

- (Structural Constraint) 

  - [Latent Hierarchical Causal Structure Discovery with Rank Constraints](https://arxiv.org/abs/2210.01798)
  - [Identification of Nonlinear Latent Hierarchical Models](https://arxiv.org/abs/2306.07916)

- (Sparsity Constraint)

  - [Identification of Partially Observed Linear Causal Models: Graphical Conditions for the Non-Gaussian and Heterogeneous Cases](https://proceedings.neurips.cc/paper_files/paper/2021/file/c0f6fb5d3a389de216345e490469145e-Paper.pdf)
  - [Triad Constraints for Learning Causal Structure of Latent Variables](https://proceedings.neurips.cc/paper_files/paper/2019/file/8c66bb19847dd8c21413c5c8c9d68306-Paper.pdf)

- (Oracle) [Learning latent causal graphs via mixture oracles](https://arxiv.org/pdf/2106.15563.pdf)

- (Temporal Info) 

  - [Learning Temporally Causal Latent Processes from General Temporal Data](https://arxiv.org/pdf/2110.05428.pdf)
  - [Temporally Disentangled Representation Learning](https://arxiv.org/pdf/2210.13647.pdf)


### Causal Discovery for Time-series data

#### Granger Causality
#### Conditional-Independence-based
#### Score-based
#### Functional Causal Model-based

### Causal Machine Learning

#### Transfer Learning
#### Reinforcement Learning
#### Explainable AI
#### Large Language Model

### Causal Effect Estimation

#### Causal Inference from Structured Data
#### Causal Inference from Unstructured Data
#### Instrumental Variable

