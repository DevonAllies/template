# template

This document outlines the setup and requirements for generating the `template.pdf` file. It leverages both R and Python for data manipulation, analysis, and visualization.

## Prerequisites

Before attempting to render this document, ensure that the following software and packages are installed on your system:

**1. R:**

   - Ensure you have R installed. You can download it from [The Comprehensive R Archive Network (CRAN)](https://cran.r-project.org/).

**2. R Packages:**

   The following R packages are required and will be automatically installed if not found:

   - `tidyverse`: A collection of R packages designed for data science, including `dplyr` for data manipulation, `ggplot2` for data visualization, and more.
   - `reticulate`: Provides tools for interoperability between R and Python.
   - `scales`: Provides functions for numeric and color scales.
   - `readxl`: Enables reading data from Excel files.
   - `REDCapR`: Facilitates interaction with REDCap (Research Electronic Data Capture) databases (note: this package might have additional system dependencies).

**3. Python:**

   - Ensure you have Python installed. It is recommended to use a distribution like Anaconda ([https://www.anaconda.com/](https://www.anaconda.com/)) which includes many useful scientific libraries.

**4. Python Packages:**

   The following Python packages are required and will be automatically installed if not found by `reticulate`:

   - `numpy`: Fundamental package for numerical computation in Python.
   - `pandas`: Provides data structures and data analysis tools.
   - `seaborn`: A data visualization library based on matplotlib.
   - `matplotlib`: A comprehensive library for creating static, interactive, and animated visualizations in Python.
   - `statsmodel`: Provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration.
   - `scienceplots`: A library of scientific plotting styles for matplotlib.
   - `tensorflow`: An open-source software library for numerical computation using data flow graphs.

**5. Python and R figure generation:**

   The code chunks for python and r figure generation has been include:

## Installation

The R code within the document will automatically attempt to install any missing R and Python packages when the document is rendered.

**To render the `template.pdf`:**

1.  Ensure you have Quarto installed. You can find installation instructions at [https://quarto.org/docs/install/](https://quarto.org/docs/install/).
2.  Navigate to the directory containing the `template.qmd` file (assuming the source file is named `template.qmd`).
3.  Open your terminal or command prompt and run the following command:

    ```bash
    quarto render template.qmd
    ```

   This command will execute the R and Python code chunks within the Quarto document and generate the `template.pdf` file.

## Acknowledgement

This template was built using resources from Stellenbosch University
