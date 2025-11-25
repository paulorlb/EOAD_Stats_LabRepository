# 📈 Statistics and Optimization for Decision Support - Block 1 Repo

## Project Overview

This repository contains the practical Jupyter Notebooks for **Block I: Inferential Statistics** of the course **"Statistics and Optimization for Decision Support"** (EOAD).

The course is part of the **Master in Data Science for Social Sciences** at the **University of Aveiro**, designed to provide students from humanities and social sciences with a strong foundation in statistical thinking and practical data analysis using Python.

This repo emphasizes **conceptual understanding, visualization, and application** over theoretical proofs, using real-world social science-relevant datasets.

---

## 🛠️ Setup and Installation

For a consistent and reproducible experience across all operating systems, we **highly recommend** setting up the environment using **Miniforge** (a minimal installer for **conda**). This process ensures all students are running the exact same package versions used for developing the course.


### Step 1: Install Miniforge

1.  Download and install the appropriate Miniforge installer for your operating system (Windows, macOS, or Linux) from the [Miniforge GitHub releases page](https://github.com/conda-forge/miniforge#miniforge).
2.  Follow the standard installation prompts.

### Step 2: Create the Course Environment

The necessary libraries (pandas, numpy, seaborn, etc.) are explicitly defined in the **`eoad_env_2526.yml`** file located in the **`envs`** folder of this repository.

1.  **Navigate** to the root directory of this repository in your terminal or command prompt.
2.  Run the following command to create and populate the environment based on the specification file:

    ```bash
    conda env create -f envs/eoad_env_2526.yml
    ```

3.  Once the environment creation is complete, **activate** the new environment:

    ```bash
    conda activate eoad_env
    ```

### Libraries
The content of this repo requires the following core Python libraries:

| Library | Purpose |
| :--- | :--- |
| **pandas** | Data manipulation and descriptive statistics |
| **numpy** | Numerical operations and random number generation |
| **matplotlib** | Basic plotting library |
| **seaborn** | High-level statistical data visualization |
| **statsmodels** | Statistical models and statistical tests |
| **scikit-learn** | Includes utility functions like data loading (e.g., Iris dataset) |
