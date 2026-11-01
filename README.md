# Lab 1 · Tensors in PyTorch

Introduction to tensors, the basic data structure of PyTorch, and to the raw operations behind a neural network.

**File:** [`01_tensors_pytorch.py`](01_tensors_pytorch.py). It is a Colab notebook exported as a Python script, so the Markdown cells appear as comments and docstrings.

## What I worked on

- Creating tensors and checking their shape and size
- Casting between data types (`float64`, `float16`, `int16`, `int64`)
- Converting between NumPy arrays, Python lists and PyTorch tensors
- In-place vs. out-of-place operations
- Implementing a single neuron (weights, bias, ReLU) with raw tensor operations on a 100,000-feature input
- Reshaping tensors: `transpose`, `view`, `chunk`, `cat`, `squeeze` / `unsqueeze`

## Stack

Python · PyTorch · NumPy · Google Colab

## How to run

Open the script in [Google Colab](https://colab.research.google.com/) or run it locally:

```bash
pip install torch numpy
python 01_tensors_pytorch.py
```

## Credits

Lab template created by Santiago Pascual and Xavier Giró-i-Nieto (UPC) as course material. The original authors are credited at the top of the file. The exercise solutions are my own work.

---
Part of my [GDSA labs](https://github.com/Pedrom-GH/GDSA_PEDRO) · B.Sc. in Telecommunications Systems Engineering, UPC – ESEIAAT · Pedro Muñoz Álvarez
