# Neural Latents

Neural latent models for online, real-time experiments.

## Overview

Neural latent models are a valuable tool for understanding and interpreting high-dimensional neural data in only a few dimensions. There are several models that are available for this, for example GLDS, PLDS, GPFA, LFADS, and XFADS.

Below is a list of models for analysis of neural latents.

* XFADS - Exponential family dynamical systems
    * Paper: https://arxiv.org/abs/2403.01371
    * Code: https://github.com/catniplab/xfads
    * Written in Python, PyTorch


* GPFA - Gaussian process factor analysis
    * Paper: https://journals.physiology.org/doi/epdf/10.1152/jn.90941.2008
    * Code: https://users.ece.cmu.edu/~byronyu/software/gpfa0203.tgz
    * Written in MATLAB


* PLDS - Poisson linear dynamical systems
    * Paper: https://www.cambridge.org/core/services/aop-cambridge-core/content/view/FAB8634C2790F3461E3E86BB632EAE6F/9781139941433c6_p137-159_CBO.pdf/estimating-state-and-parameters-in-state-space-models-of-spike-trains.pdf
    * Paper: https://proceedings.neurips.cc/paper_files/paper/2012/file/d58072be2820e8682c0a27c0518e805e-Paper.pdf
    * Code: https://bitbucket.org/mackelab/pop_spike_dyn/src/master/
    * Written in MATLAB


* LFADS - Latent factor analysis via dynamical systems
    * Paper: https://arxiv.org/abs/1608.06315
    * Paper: https://arxiv.org/abs/2309.01230
    * Paper: https://www.nature.com/articles/s41592-018-0109-9
    * Code: https://github.com/arsedler9/lfads-torch/tree/main
    * Written in Python, PyTorch


* AutoLFADS - Automated model-tuning LFADS
    * Paper: https://www.biorxiv.org/content/10.1101/2021.01.13.426570v2
    * Docs: https://snel-repo.github.io/autolfads/


* Hierarchical LFADS
    * Code: https://github.com/lyprince/hierarchical_lfads
    * Very little documentation, writtin in PyTorch


* gpSLDS - Gaussian process switching linear dynamical systems
    * Paper: https://arxiv.org/abs/2408.03330
    * Code: https://github.com/lindermanlab/gpslds
    * Written in Python, JAX


# Datasets

* Neural latents benchmark
    * Site: https://neurallatents.github.io/