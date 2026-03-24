# B22AI050-A2
This repository contains solutions for two problems, organized into separate directories.

## Project Structure

* **Prob1/**
    * `Corpus/`: Directory containing 40 source text files.
    * `B22AI050_prob1.ipynb`: Jupyter notebook containing the solution for Problem 1.
* **Prob2/**
    * `TrainingNames.txt`: Dataset containing 1000 Indian names.
    * `B22AI050_prob2.ipynb`: Jupyter notebook containing the solution for Problem 2.

---

## Problem 1: Learning Word Embeddings

### Dependencies
* Python 3.x
* Jupyter Notebook / Lab
* numpy
* torch
* scikit-learn

### Execution
To run the code for Problem 1, navigate to the `Prob1` directory and execute the notebook. The script reads documents from the `Corpus` folder, generates a `preprocessed_corpus.txt` file in the same directory, and displays the results within the notebook.

```bash
cd Prob1
jupyter notebook B22AI050_prob1.ipynb
```

---

## Problem 2: Generating Indian Names

### Dependencies
* Python 3.x
* Jupyter Notebook / Lab
* numpy
* torch

### Execution
To run the code for Problem 2, navigate to the `Prob2` directory and execute the notebook. The script reads the names from TrainingNames.txt file, and displays the results within the notebook for various hyperparameters.

```bash
cd Prob2
jupyter notebook B22AI050_prob2.ipynb
```
