# Applied-Statistics assessment

This repository contains my submission for the Applied Statistics module.
The project is written in a single Jupyter notebook in Python.
The repository includes everything needed to run the notebook.

## Quick look

- You can click on `problems.ipynb` in this repository and GitHub will display it in static format.
- You can view and run the notebook in [Google Colab](https://colab.research.google.com/).
- You can view the notebook using [nbviewer](https://nbviewer.org/) also.

## Running the notebook
 
To run `problems.ipynb`, you can follow these steps:

1. Clone the repository using [git](https://git-scm.com/).
    ```bash
   git clone <repository-url>
   cd Applied-statistics

2. Ensure you have [Python](https://www.python.org/) installed. An easy way to get Python is to use [uv](https://docs.astral.sh/uv/) or [Anaconda](https://www.anaconda.com/download).

3. Install the required dependencies by running:
    Bash
    pip install -r requirements.txt

4. Launch Jupyter Notebook or VS Code, open problems.ipynb, and select Restart Kernel and Run All.

## Dependencies

The notebook depends on several key Python packages listed in requirements.txt, including:

numpy (for numerical arrays)

pandas (for data manipulation and dataframes)

matplotlib (for plotting and visualizations)

seaborn (for statistical data visualization)

statsmodels (for statistical modeling)

## About the Notebook

The notebook provides an exploratory and statistical analysis of the classic Iris dataset, focusing on petal length and width characteristics. It investigates data distributions through histograms with normal curves, examines linear relationships and correlation coefficients both globally and per species, and utilizes independent-samples t-tests to evaluate pairwise differences. Finally, it applies a one-way ANOVA to compare group means simultaneously while controlling for type I error rates across multiple comparisons.

## About the Author

I am a final-year student studying applied statistics and data analysis. This project reflects my practical application of statistical methods, data visualization, and reproducible research workflows using Python and Jupyter Notebooks.