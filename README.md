# Deep Averaging Network (DAN) for Sentiment Analysis

This project implements a **Deep Averaging Network (DAN)** for sentiment analysis. The model can be initialized with either **pre-trained GloVe embeddings** or **randomly initialized embeddings**. The code allows for experimentation with various hyperparameters, such as the number of hidden layers, hidden layer sizes, dropout rates, and nonlinearity.

## Key Features

- **Embedding Initialization**: Use pre-trained GloVe embeddings or initialize embeddings randomly.
- **Varying Hidden Layer Sizes**: Experiment with different sizes of hidden layers (e.g., 50, 100, 200 units).
- **Dropout**: Apply dropout after the embedding or hidden layers to prevent overfitting.
- **Nonlinearity**: Choose from different activation functions (ReLU, Tanh, Leaky ReLU).
- **Optimizer**: Use Adam or SGD for optimization.
- **Weight Initialization**: Experiment with random initialization or Xavier initialization for hidden and output layers.

## Requirements

- Python 3.x
- PyTorch
- NumPy
- GloVe embeddings (e.g., `glove.6B.300d.txt`)

### Installation

Install the required packages using `pip`:

```bash
pip install torch numpy

