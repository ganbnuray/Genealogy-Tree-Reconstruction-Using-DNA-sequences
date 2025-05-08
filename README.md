# Gene Genealogy Tree Construction Using Longest Common Subsequence (LCS)

This project implements the **Longest Common Subsequence (LCS)** algorithm and applies it to construct **gene genealogy trees** using both **local** and **global** approaches.

## 🧬 Project Overview

Genetic sequences are analyzed to infer evolutionary relationships. The project uses the LCS method to compute similarity matrices and builds hierarchical relationships (trees) based on the resulting scores.

## 📁 Contents

- **LCS Implementation**: Calculates the length matrix for gene sequences.
- **Local Approach**: Constructs genealogy trees using pairwise similarity and a bottom-up strategy.
- **Global Approach**: Constructs trees using a global similarity matrix and dynamic programming techniques.
- **Visualization**: Displays hierarchical trees and similarity matrices for interpretation.
- **Probability Calculation**: Calculates the probabilities of insertion, deletion, and mutation in gene sequences using the edit distance algorithm.

## 📌 Features

- Efficient LCS matrix computation.
- Dynamic programming-based similarity inference.
- Modular code with a focus on clarity and tree construction logic.
- Includes annotated explanations in markdown cells.

## 🛠️ Technologies

- Python 3
- Jupyter Notebook
- `matplotlib` (for visualization)
- Standard libraries like `itertools` and `numpy`

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ganbnuray/Genealogy-Tree-Reconstruction-Using-DNA-sequences.git
2. Install required packages (if not already available):
   ```bash
   pip install matplotlib numpy
3. Open the notebook:
   ```bash
   jupyter notebook genetreereconstruction.ipynb
