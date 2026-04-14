# Deep Learning Assignment

This repository contains a deep learning lab assignment focused on image classification and representation learning using the MNIST and CIFAR-10 datasets.

The main notebook walks through dataset loading, exploratory analysis, multilayer perceptrons, gradient descent variants, optimizer comparisons, regularization techniques, convolutional neural networks, autoencoders, and feature-map visualization.

## Datasets

- MNIST handwritten digits
	- 60,000 training images and 10,000 test images
	- 28 x 28 grayscale images across 10 classes
- CIFAR-10 natural images
	- 50,000 training images and 10,000 test images
	- 32 x 32 RGB images across 10 classes

The notebook expects the datasets to be available in Google Drive when run in Colab.

## Notebook Coverage

The notebook is organized into the following sections:

1. Dataset loading and preprocessing for MNIST and CIFAR-10
2. Dataset exploration with sample images and class distributions
3. MLP experiments with learning rate and weight initialization analysis
4. Gradient descent convergence analysis using a NumPy implementation
5. Hyperparameter exploration for MLP architectures
6. Comparison of gradient-based optimizers
7. Regularization methods such as L2, dropout, data augmentation, and early stopping
8. CNN training and evaluation on MNIST and CIFAR-10
9. Autoencoder experiments, including dense and convolutional variants
10. Feature map and intermediate representation visualization

## Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## How to Run

### In Google Colab

1. Open the notebook in Colab.
2. Mount Google Drive when prompted.
3. Update the dataset paths in the notebook if your Drive folder structure differs.
4. Run the cells from top to bottom.

### Locally

If you want to run the notebook outside Colab, install the dependencies first:

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

Then adjust the dataset-loading paths so they point to your local copies of MNIST and CIFAR-10.

## Project Notes

- The notebook compares how MLPs and CNNs behave on simple and complex image datasets.
- It includes manual experimentation with learning rate, initialization, batch size, and optimizer choice.
- Several sections use plots and visualizations to explain training behavior and model performance.

## Files

- [DL_ASSIGNMENT.ipynb](DL_ASSIGNMENT.ipynb)
- [DL-WEEK1,2,3.ipynb](DL-WEEK1,2,3.ipynb)
- [DLLAB_4,5,6.ipynb](DLLAB_4,5,6.ipynb)

## License

No license has been specified for this repository.