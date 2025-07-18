# Eigen-Face

A comprehensive implementation and exploration of **Eigenface**—an application of Principal Component Analysis (PCA) for human face recognition.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Overview

Eigenface is a face recognition technique based on PCA, which reduces the dimensionality of facial images and identifies the most significant features for classification. This project demonstrates how PCA can be applied to a dataset of human faces to visualize eigenfaces and perform face recognition.

## Features

- **Face Dataset Preparation:** Load and preprocess facial images.
- **PCA Implementation:** Compute eigenfaces and project images onto reduced feature space.
- **Face Reconstruction:** Visualize reconstructed images using selected principal components.
- **Face Recognition:** Classify and compare faces using PCA features.
- **Interactive Notebook:** Step-by-step explanation with code in Jupyter Notebook.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Shashankkusu/Eigen-Face.git
   cd Eigen-Face
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   > **Note:** If `requirements.txt` is missing, the main dependencies are likely:
   > - numpy
   > - matplotlib
   > - scikit-learn
   > - opencv-python
   > - jupyter

   You can install them directly:

   ```bash
   pip install numpy matplotlib scikit-learn opencv-python jupyter
   ```

## Usage

1. **Open the Jupyter Notebook**

   ```bash
   jupyter notebook "EigenFace .ipynb"
   ```

2. **Follow the notebook instructions**  
   The notebook is self-contained and walks through all steps from data loading to PCA, visualization, and recognition.

## Project Structure

```
├── EigenFace .ipynb          # Main Jupyter Notebook
├── requirements.txt          # Python dependencies (add if missing)
├── README.md                 # Project documentation
└── data/                     # (Optional) Directory for face images
```

> **Note:** Ensure you have a dataset of facial images in the appropriate directory, or update the notebook paths as needed.

## Results

- Visualizations of eigenfaces (principal face components)
- Example face reconstructions using PCA
- Face recognition accuracy and sample predictions

## Contributing

Contributions are welcome! Please open issues for bugs or suggestions, and submit pull requests for improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Principal Component Analysis (PCA)](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [Eigenfaces](https://en.wikipedia.org/wiki/Eigenface)
- scikit-learn, NumPy, Matplotlib, OpenCV

---

**Author:** [Shashankkusu](https://github.com/Shashankkusu)
