# PyTorch Tensors


## Introduction
This is my official learning about learning PyTorch.   

Tensors are the core data structures in PyTorch. They are multi-dimensional arrays similar to NumPy’s ndarrays but can run on GPUs for faster computation.

### What are Tensors?
A tensor can be:
- A 0-dimensional tensor called a scalar (e.g., `torch.tensor(7)`).
- A 1-dimensional tensor called a vector (e.g., `torch.tensor([7, 7])`).
- A 2-dimensional tensor called a matrix (e.g., `torch.tensor([[7, 8], [9, 10]])`).
- An n-dimensional tensor for higher dimensions.
 
Tensors are used for storing data and performing mathematical operations efficiently on GPUs. To check the dimensions of a tensor, use the `.ndim` attribute. For the shape of a tensor, use the `.shape` attribute.

To check if a GPU is available, use `torch.cuda.is_available()`.

### Why Tensors Win Over NumPy Arrays for Deep Learning

1. **GPU Acceleration**: Tensors can be easily moved to a GPU to leverage the parallel processing capabilities of GPUs. This makes training deep neural networks significantly faster compared to NumPy arrays which only run on CPUs.

2. **Automatic Differentiation (autograd)**: PyTorch tensors support automatic differentiation through the `autograd` module. This makes it easy to compute gradients automatically, which is a key part of training deep learning models through backpropagation. NumPy arrays do not have a built-in mechanism for automatic differentiation.

3. **Optimized Operations for Deep Learning**: PyTorch provides a rich set of functions specifically designed for deep learning operations such as convolutions, pooling, loss functions, and more. These operations are highly optimized for neural network training and inference.

4. **Integration with Deep Learning Frameworks**: Tensors are a fundamental part of the PyTorch deep learning framework which provides a comprehensive ecosystem for building and training neural networks. NumPy arrays, while powerful for general scientific computing, do not have such a deep integration with a deep learning framework.

For more details, visit the [PyTorch Tensor Documentation](https://docs.pytorch.org/docs/stable/tensors.html).
