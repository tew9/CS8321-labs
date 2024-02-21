# Environment Setup for CS8930 Class Labs with PyTorch

This guide will walk you through setting up the environment on your machine to work on CS8930 class labs using PyTorch.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Anaconda](https://www.anaconda.com/products/distribution)
- [Git](https://git-scm.com/)

## Steps

### 1. Clone the Repository

First, clone the repository containing the code for building the text classification model:

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create Conda Environment

Next, create a Conda environment using the provided environment.yml file. This environment includes all the necessary dependencies for the project.

```bash
conda env create -f environment.yml
```

### 3. Activate the Environment

Activate the Conda environment to use the installed dependencies.

```bash
conda activate pytorch-bert-classification
```

### 4. Run the Code

You're now ready to run the code and build your text classification model! Follow the instructions provided in the project's notebook or documentation to train and evaluate the model.

### 5. Deactivate the Environment (Optional)

Once you're done working on the project, you can deactivate the Conda environment.

```bash
conda deactivate
```