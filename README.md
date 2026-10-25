# Task 16 — Load a CSV Dataset Using Pandas


## 1. Project Overview

This project demonstrates how to load a Comma-Separated Values (CSV) dataset using Python's Pandas library. The program displays the first five and last five records and examines the dataset's dimensions, column names, data types, and missing values.

The project introduces an important first step in data analysis and machine-learning workflows: importing and inspecting structured data.

## 2. Objective

The objectives of this project are:

- To load a CSV dataset using Pandas.
- To display the first five records using `head()`.
- To display the last five records using `tail()`.
- To inspect the number of rows and columns.
- To identify column names and data types.
- To check missing values in the dataset.

## 3. Technologies Used

- Python 3
- Pandas
- CSV
- Google Colab
- Jupyter Notebook
- GitHub

## 4. Project Files

- `Task_16_Load_CSV_Dataset.ipynb` — Jupyter Notebook containing the program and its outputs.
- `dataset.csv` — Sample student dataset.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `screenshots/program_output.png` — Screenshot of the notebook output.
- `screenshots/dataset_preview.png` — Screenshot of the dataset preview.

## 5. Dataset Description

The project uses a manually created sample dataset containing 12 student records and five columns:

| Column | Description |
|---|---|
| `student_id` | Unique student identifier |
| `name` | Student name |
| `department` | Academic department |
| `age` | Student age |
| `marks` | Student marks |

The records are fictional and are used only to demonstrate CSV loading and inspection.

## 6. How to Run

1. Open the notebook in Google Colab.
2. Run the cell that creates `dataset.csv`.
3. Run the cell that loads the dataset using `pd.read_csv()`.
4. Execute the cells that display the first and last five records.
5. Run the cells that inspect column names, data types, and missing values.

The notebook can also be downloaded and run in a local Jupyter Notebook environment after installing Pandas.

## 7. Pandas Functions Used

- **`pd.read_csv()`** — Loads a CSV file into a Pandas DataFrame.
- **`df.head()`** — Displays the first five rows by default.
- **`df.tail()`** — Displays the last five rows by default.
- **`df.shape`** — Returns the number of rows and columns.
- **`df.columns`** — Returns the column names.
- **`df.dtypes`** — Displays the data type of each column.
- **`df.isnull().sum()`** — Counts missing values in each column.

## 8. Expected Results

The sample dataset contains 12 rows and five columns.

The program displays:

- The first five student records.
- The last five student records.
- The dataset's dimensions.
- Column names and data types.
- Missing-value counts for every column.

The provided sample dataset contains no missing values.

## 9. Learning Outcomes

This project provides practical experience in:

- Loading structured data with Pandas.
- Working with CSV files.
- Inspecting DataFrames.
- Understanding rows, columns, and data types.
- Checking missing values.
- Preparing data for further analysis.

## 10. Conclusion

This project demonstrates how Pandas can load and inspect CSV datasets efficiently. The use of `read_csv()`, `head()`, and `tail()` provides a foundation for data cleaning, exploratory data analysis, and machine-learning workflows.
