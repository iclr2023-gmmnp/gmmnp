# Source Code for GMM-NP (ICLR 2023)
Dear reviewers, 

this is the source code accompanying the ICLR 2023 submission
"Accurate Bayesian Meta-Learning by Accurate Task Posterior Inference"!

Thanks a lot for your effort!

The authors

## Installation
Please clone this repository and run

```pip install .```

from the source directory to install all necessary packages. We recommend to create a new conda environment (python >= 3.10) for this purpose.

## Run
We provide a jupyter notebook 

```scripts/run_experiment.ipynb```

to reproduce the results on the synthetic function classes (Sinusoid1D, LineSine1D) within error bounds and to visualize some predictions. We load the optimal hyperparameters determined according to the experimental protocol described in the paper.

## License
This code is published to supplement our submission during peer review and shall not be used for any other purposes.
