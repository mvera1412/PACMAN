# PACMAN: PAC-style Bounds for Accuracy-Log-loss Mismatch

Welcome to the repository for PACMAN, the implementation of PAC-style bounds accounting for the Mismatch between Accuracy and Negative log-loss. This codebase serves as a comprehensive resource for reproducing the results presented in our journal publication.

## Overview

The repository includes three Jupyter notebooks, each designed to replicate specific experiments conducted in the study titled "PACMAN: PAC-style bounds accounting for the Mismatch between Accuracy and Negative log-loss." The experiments cover the following scenarios:

1. **ResNet18 on CIFAR-10 Dataset**: Utilizing a pre-trained ResNet18 model, originally sourced from [Harvard Machine Learning's Double Descent repository](https://gitlab.com/harvard-machine-learning/double-descent/tree/master), this notebook reproduces the experiment on the CIFAR-10 dataset.

2. **Fully Connected Neural Network on FashionMNIST Dataset**: This notebook replicates the experiment involving a fully connected deep neural network trained on the FashionMNIST dataset.

3. **LeNet-5 on MNIST Dataset**: The third notebook focuses on reproducing the experiment involving a LeNet-5 model trained on the MNIST dataset.

## Getting Started

To reproduce the experiments, follow these steps:

1. Clone this repository to your local machine.
2. Open the respective Jupyter notebooks for the desired experiment.
3. Execute the cells within each notebook to replicate the experiments and obtain results.

Please note that for the ResNet18 experiment, the training data was obtained from the [Harvard Machine Learning Double Descent repository](https://gitlab.com/harvard-machine-learning/double-descent/tree/master). For the other two experiments, the training sessions are embedded within the notebooks.

## Citation

If you find this code helpful in your research, please consider citing our paper. Here is the BibTeX entry:

```bibtex
@article{your-pacman-paper,
  title={PACMAN: PAC-style bounds accounting for the Mismatch between Accuracy and Negative log-loss},
  author={Vera, Matias and Rey Vega, Leonardo and Piantanida, Pablo},
  journal={Information and Inference: A Journal of the IMA},
  year={2024},
  publisher = {Oxford University Press}
}'''




Feel free to reach out if you have any questions or need further assistance. We appreciate your interest in our work!
