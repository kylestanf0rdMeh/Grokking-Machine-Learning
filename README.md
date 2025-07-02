# Grokking Machine Learning

This repository is a code-along companion to the book **Grokking Machine Learning** by Luis Serrano.

## Overview

Here, you'll find:
- **Jupyter Notebooks (`.ipynb`)**: Interactive notebooks containing code snippets, exercises, and explanations from each chapter of the book.
- **Standalone Scripts**: Occasional Python scripts for specific tasks or experiments.

The goal is to provide hands-on, practical examples to reinforce the concepts covered in the book.

## Structure

- `chapter_X/`: Each chapter has its own folder containing relevant notebooks and scripts.
- Example: `chapter_3/linear_regression.ipynb`

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Grokking-Machine-Learning.git
cd Grokking-Machine-Learning
```

### 2. Set Up a Python Environment

It's recommended to use a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install Jupyter and any other required packages:

```bash
pip install jupyter notebook
```

### 4. Create and Activate a Jupyter Kernel

Create a new kernel for this project:

```bash
python -m ipykernel install --user --name grokking-ml --display-name "Python (Grokking ML)"
```

When you open a notebook, select the "Python (Grokking ML)" kernel.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```


> **Note:**  
> Turi Create is not supported on Apple Silicon (ARM) Macs or with Python versions above 3.8.  
> This repository uses `scikit-learn`, `pandas`, and other modern libraries for all code examples.

## Contributing

Feel free to open issues or submit pull requests for improvements or additional content!

---

Happy learning!