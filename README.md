# Name - Alan Garcia
# Course - CS4379G

## Description:
This repository contains a Jupyter notebook file that reads, cleans, and analyses  data from `netflix_titles.csv` from the data folder.

## How to run the notebook
1. **Prerequisites:** Ensure you have Python installed on your system. You will also need the following libraries, which are used for data cleaning and visualization in this project:

    - pandas
    - numpy
    - matplotlib

You can install these using pip if you don't have them:
`pip install pandas numpy matplotlib`

2. **Setup**
- Clone the Repository: Use `git clone https://github.com/AlantheG21/4379_Assignment1.git` to download the project to your local machine.

- Dataset: Ensure the netflix_titles.csv file is in the data directory.

3. **Execution**
- Navigate to the `notebooks/` folder

- Open the analysis.ipynb file using Jupyter Notebook or VSCode.

- Run the cells sequentially from top to bottom. This will perform the data loading, cleaning (using the custom helper function), and generate the required analysis and plots.

## What was found?
- **Country Contribution:** The top 10 countries were found using the `value_counts()` method on the country column. The analysis revealed that the United States, India, and the UK are the largest contributors.

- **Trend over time:** The line graph revealed the United States having a strong and steep growth starting in 2015 in contribution. India had similar growth but at a smaller scale starting in 2016. The UK had some growth but minimal compared to India and United States.