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

For more details, visit the [PyTorch Tensor Documentation](https://docs.pytorch.org/docs/stable/tensors.html).
