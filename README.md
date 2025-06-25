# African Trade Data Analysis (Kenya & Mali)

This repository hosts data analysis notebooks focusing on trade statistics for Kenya and Mali. The analysis delves into commodity trade, particularly for commodity codes like 7108 and 710812 (often associated with gold), examining trade volumes, values, and primary trading partners over various periods.

## Project Overview

The project aims to:
- Load and inspect cleaned trade datasets for Kenya and Mali.
- Provide descriptive statistics of the trade data.
- Analyze trade values by reporting country and partner.
- Identify top trading partners and their associated trade values.

## Data Source

The datasets used in these notebooks are assumed to be sourced from national statistical bureaus, as indicated by the "DSB" prefix in the original filenames, and are provided as Excel files (e.g., `DSB_Kenya_Cleaned_Dataset.xlsx`, `DSB_Mali_Cleaned_Dataset.xlsx`).

## How to Run the Notebooks

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd African-Trade-Analysis
    ```
3.  **Ensure you have Jupyter Notebook or JupyterLab installed.** If not, you can install it via pip:
    ```bash
    pip install notebook  # or pip install jupyterlab
    ```
4.  **Place your cleaned datasets** (e.g., `DSB_Kenya_Cleaned_Dataset.xlsx` and `DSB_Mali_Cleaned_Dataset.xlsx`) in the `/content/drive/MyDrive/dataset/` path as referenced in the notebooks, or update the `path` variable in each notebook to reflect your local data location.
5.  **Open Jupyter Notebook/Lab and run the `.ipynb` files:**
    ```bash
    jupyter notebook DSB_kenya.ipynb
    jupyter notebook DSB_mali.ipynb
    ```

## Technologies Used

* Python
* Pandas (for data manipulation and analysis)
* Jupyter Notebook / Google Colab
