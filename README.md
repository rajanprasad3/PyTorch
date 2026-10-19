## PyTorch

A comprehensive collection of **PyTorch notebooks, practical implementations, and deep learning experiments** documenting my learning journey. This repository covers essential PyTorch concepts, tensor operations, automatic differentiation, neural network development, model training, and other important deep learning fundamentals through hands-on coding and practical examples.

## 📌 About This Repository

This repository is designed to build a strong understanding of PyTorch and its role in developing deep learning models. It contains Jupyter notebooks, code implementations, experiments, and practical examples that demonstrate how to work with tensors, build neural networks, calculate gradients, optimize model parameters, and train deep learning models using PyTorch.

The primary goal is to understand the concepts behind PyTorch, strengthen implementation skills, and develop a solid foundation for working on real-world deep learning and AI projects.

## 📚 Topics Covered

### 1. Introduction to PyTorch
- Introduction to PyTorch and its core features
- Understanding the PyTorch ecosystem
- PyTorch compared with other deep learning frameworks
- Core components and applications of PyTorch
- Understanding tensors and their role in deep learning

### 2. Tensor Operations
- Creating tensors from different data sources
- Tensor attributes, shapes, dimensions, and data types
- Indexing, slicing, and reshaping tensors
- Mathematical and element-wise operations
- Matrix multiplication and broadcasting
- Tensor concatenation and stacking
- Reshaping, squeezing, and unsqueezing tensors
- CPU and GPU tensor operations

### 3. Automatic Differentiation and Autograd
- Introduction to automatic differentiation
- Understanding computational graphs
- Working with `requires_grad`
- Calculating gradients using `backward()`
- Understanding gradient accumulation
- Managing gradients with `zero_grad()`
- Disabling gradient tracking
- Understanding the role of gradients in neural network training

### 4. Building Neural Networks
- Introduction to neural network architecture
- Understanding the `torch.nn` module
- Creating neural network models using `nn.Module`
- Defining layers and learnable parameters
- Implementing forward propagation
- Understanding activation functions
- Building multilayer neural networks
- Understanding model parameters and their initialization

### 5. Loss Functions and Optimization
- Understanding loss functions
- Regression and classification loss functions
- Mean Squared Error (MSE)
- Cross-Entropy Loss
- Understanding gradient descent
- Working with PyTorch optimizers
- Stochastic Gradient Descent (SGD)
- Adam optimizer
- Updating model parameters during training

### 6. Dataset and DataLoader
- Understanding the PyTorch data pipeline
- Creating custom datasets using `Dataset`
- Implementing `__len__()` and `__getitem__()`
- Loading data using `DataLoader`
- Understanding batch size and shuffling
- Iterating through batches of data
- Preparing datasets for model training

### 7. Training Neural Networks
- Implementing a complete training loop
- Forward propagation and loss calculation
- Backpropagation and gradient computation
- Updating model parameters
- Understanding epochs, batches, and iterations
- Monitoring training loss
- Evaluating model performance
- Understanding the difference between training and evaluation modes

### 8. Model Evaluation and Prediction
- Making predictions with trained models
- Evaluating model performance
- Using `model.eval()`
- Understanding `torch.no_grad()`
- Comparing predictions with actual values
- Understanding the importance of evaluation data
- Basic model performance analysis

### 9. Saving and Loading Models
- Saving model parameters using `state_dict()`
- Loading saved model weights
- Using `torch.save()` and `torch.load()`
- Understanding model checkpoints
- Restoring trained models for inference
- Reusing trained models for future predictions

### 10. GPU Acceleration
- Understanding CPU and GPU computation
- Checking CUDA availability
- Moving tensors and models to a device
- Using `.to(device)` for device management
- Training models with GPU acceleration
- Handling device compatibility during model training

## 🛠️ Technologies and Libraries

- **Python** for programming and implementation
- **PyTorch** for tensor computation and deep learning
- **NumPy** for numerical operations
- **Jupyter Notebook** for interactive experimentation
- **Matplotlib** for data visualization

## 🎯 Learning Objectives

Through this repository, I aim to:

- Develop a strong understanding of PyTorch fundamentals.
- Understand tensor computation and automatic differentiation.
- Implement neural networks using PyTorch.
- Understand forward propagation, backpropagation, and optimization.
- Build custom datasets and efficient data-loading pipelines.
- Develop complete model-training and evaluation workflows.
- Learn to save, load, and reuse trained models.
- Understand GPU-based computation for deep learning.
- Strengthen practical coding skills for deep learning projects.
- Build a foundation for advanced topics such as Computer Vision, Natural Language Processing, and Transformer-based architectures.

## 📂 Repository Structure

The repository is organized into Jupyter notebooks and practical implementations covering different PyTorch concepts.

```text
PyTorch/
│
├── Notebooks/
│   ├── Introduction_to_PyTorch.ipynb
│   ├── Tensor_Operations.ipynb
│   ├── Autograd_and_Gradients.ipynb
│   ├── Neural_Networks.ipynb
│   ├── Loss_Functions_and_Optimizers.ipynb
│   ├── Dataset_and_DataLoader.ipynb
│   ├── Training_Neural_Networks.ipynb
│   ├── Model_Evaluation.ipynb
│   ├── Saving_and_Loading_Models.ipynb
│   └── GPU_Computation.ipynb
│
└── README.md
```

*Note: The structure above is illustrative. The actual repository structure may differ depending on the notebooks and files included.*

## 🚀 Getting Started

### Prerequisites

Basic knowledge of Python, functions, classes, and numerical computing is recommended.

### Installation

Install PyTorch using the official installation instructions:

https://pytorch.org/get-started/locally/

Install the additional libraries:

```bash
pip install numpy matplotlib jupyter
```

### Clone the Repository

```bash
git clone https://github.com/rajanprasad3/PyTorch.git
```

Navigate to the repository directory:

```bash
cd PyTorch
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and execute the cells sequentially to understand the concepts and implementations.

## 💡 Practical Approach

The notebooks emphasize learning through implementation rather than memorizing theoretical definitions. They focus on understanding how PyTorch operations work, how neural networks learn through gradients, how optimizers update parameters, and how individual components combine into a complete training pipeline.

## 📈 Future Learning

This repository represents an important step in my deep learning journey. With a strong foundation in PyTorch, I aim to explore more advanced architectures and applications, including:

- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs), LSTMs, and GRUs
- Attention mechanisms and Transformers
- Computer Vision applications
- Natural Language Processing applications
- Transfer learning and pretrained models
- End-to-end deep learning projects

## 📖 References

- [Official PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [PyTorch Official GitHub Repository](https://github.com/pytorch/pytorch)

## 👨‍💻 Author

**Rajan Prasad**

Bachelor of Science in Computer Science and Data Analytics

Interested in Machine Learning, Deep Learning, Natural Language Processing, and Artificial Intelligence.

- GitHub: https://github.com/rajanprasad3
- LinkedIn: https://www.linkedin.com/in/rajanprasad3/

---

⭐ If you find this repository useful for learning PyTorch and deep learning, consider giving it a star!

