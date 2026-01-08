# Recommender Systems and Matrix Factorization

This repository contains materials for the study and implementation of recommender systems using matrix factorization techniques. This project was developed as part of the Data Mining Algorithms (ADM) course at the Czech Technical University (CVUT) in Prague, during an academic exchange from the Universitat Politècnica de Catalunya (UPC).

The primary goal of the project is to provide a comprehensive understanding of how sparse recommender systems are stored and how to effectively utilize sparse matrices and matrix factorization algorithms.

## Project Structure

The repository contains the following files:

* **ADM_Tutorial_03_Matrix_Factorization.ipynb**: The main Jupyter Notebook containing the implementation of matrix factorization, handling of sparse matrices, and the recommendation logic.

**Data Files**

* **ROMEGA.npy**: A NumPy binary file containing the interaction data used for training and evaluating the recommender model.

## Getting Started

### Prerequisites

To run the analysis, you will need a Python environment with the following libraries installed:

```bash
pip install numpy scipy scikit-learn matplotlib jupyter

```

### Usage

1. **Clone the repository:**
```bash
git clone https://github.com/JairoRY/CVUT-ADM-Recommender-Systems.git
cd CVUT-ADM-Recommender-Systems

```


2. **Launch the Jupyter Notebook:**
```bash
jupyter notebook ADM_Tutorial_03_Matrix_Factorization.ipynb

```



## Analysis Overview

The project covers the following technical areas:

* **Sparse Matrix Representation**: Utilizing the Compressed Sparse Row (CSR) format via SciPy to efficiently store and manipulate large-scale user-item interaction data.
* **Matrix Factorization**: Implementing algorithms to decompose the sparse interaction matrix into latent factor matrices for users and items.
* **Rating Prediction**: Using the learned latent factors to predict missing values in the user-item matrix.
* **Model Evaluation**: Assessing the performance of the factorization approach to ensure the accuracy of the generated recommendations.
