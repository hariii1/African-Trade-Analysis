# African Trade Insights: Kenya & Mali Trade Data Analysis

This repository contains Python scripts for analyzing the trade dynamics of Kenya and Mali. The project focuses on understanding trade values, identifying key trading partners, and visualizing these trends for the period between 2017 and 2023.

## Project Overview

The objective of this analysis is to:
* Load and inspect cleaned trade datasets for both Kenya and Mali.
* Filter data for a specific period (2017-2023) to focus on recent trends.
* Handle missing values (specifically in Mali's dataset).
* Generate descriptive statistics to summarize trade data.
* Aggregate trade values by partner countries.
* Identify and visualize the top 10 trade partners by total trade value for each country.

## Data Source

The datasets used are assumed to be "cleaned datasets" in Excel format, likely sourced from national statistical bureaus, and are named:
* `DSB_Kenya_Cleaned_Dataset.xlsx`
* `DSB_Mali_Cleaned_Dataset.xlsx`

These files are expected to contain columns such as 'Period', 'Partner', and 'Value', which are central to the analysis.

## How to Run the Analysis

These scripts are designed to be run in a Python environment, ideally within a Jupyter Notebook or Google Colab, given the `drive.mount` command.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/African-Trade-Insights.git](https://github.com/your-username/African-Trade-Insights.git)
    cd African-Trade-Insights
    ```
2.  **Install Required Libraries:**
    ```bash
    pip install pandas matplotlib seaborn openpyxl
    ```
3.  **Data Location:**
    * Ensure your `DSB_Kenya_Cleaned_Dataset.xlsx` and `DSB_Mali_Cleaned_Dataset.xlsx` files are placed in the `/content/drive/MyDrive/dataset/` directory if you are using Google Colab.
    * If running locally, update the `path` variable in both `dsb_kenya (1).py` and `dsb_mali (1).py` to the correct location of your Excel files.

4.  **Execute the Scripts:**
    * **For Kenya:**
        ```bash
        python "dsb_kenya (1).py"
        ```
    * **For Mali:**
        ```bash
        python "dsb_mali (1).py"
        ```
    The scripts will print descriptive statistics and top partners to the console, and display bar plots for the top 10 trade partners.

## Analysis Highlights

* **Data Cleaning:** Explicit handling of missing 'Value' data in the Mali dataset ensures robust analysis.
* **Time-Series Filtering:** Focus on recent trade trends from 2017 to 2023.
* **Key Partner Identification:** Clearly identifies the most significant trade partners based on total value.
* **Visualizations:** Bar plots provide an intuitive understanding of trade partner importance and value distribution.

These analyses provide valuable insights into the economic relationships and trade priorities of Kenya and Mali over the specified period.

## Technologies Used

* Python
* Pandas: For data loading, manipulation, and aggregation.
* Matplotlib: For creating static, animated, and interactive visualizations.
* Seaborn: For drawing attractive and informative statistical graphics.
* Google Colab (original development environment, compatible with local Python execution)
