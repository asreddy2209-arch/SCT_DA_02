# Task 2 - Data Cleaning Using Pandas

## Project Overview

This project demonstrates data cleaning using **Python and Pandas** on the **Global Superstore dataset**.

The notebook loads a CSV dataset, checks missing values and duplicate records, converts date and numerical columns, handles missing values, and exports the cleaned dataset as a CSV file.

## Objectives

* Load the CSV dataset
* Display the original data
* Check for missing values
* Check and remove duplicate rows
* Convert date columns to datetime format
* Convert numerical columns to numeric format
* Handle missing numerical values
* Handle missing text values
* Verify the cleaned dataset
* Export the cleaned dataset

## Technologies Used

* Python
* Pandas
* Google Colab
* Jupyter Notebook
* CSV

## Data Cleaning Steps

### 1. Dataset Loading

The dataset is uploaded and loaded using Pandas.

### 2. Missing Value Detection

The notebook checks the number of missing values in each column.

### 3. Duplicate Detection

Duplicate rows are identified and removed.

### 4. Date Conversion

The following columns are converted into datetime format:

* Order Date
* Ship Date

### 5. Numerical Conversion

The notebook converts applicable columns such as:

* Sales
* Quantity
* Discount
* Profit
* Postal Code

into numeric data types.

### 6. Missing Value Handling

* Missing numerical values are replaced using the column median.
* Missing text values are replaced with `"Unknown"`.

### 7. Data Verification

The cleaned dataset is checked again for missing values and duplicate rows.

### 8. Export

The cleaned dataset is saved as:

`Cleaned_Global_Superstore.csv`

## How to Run

### Google Colab

1. Open `Task2.ipynb` in Google Colab.
2. Run the notebook.
3. Upload the required CSV dataset when prompted.
4. The notebook performs the data-cleaning operations.
5. The cleaned CSV file is generated.

## Project Structure

```text
Task2/
│
├── Task2.ipynb
├── requirements.txt
├── README.md
└── train.csv
```

## Output

The final output is a cleaned CSV file:

```text
Cleaned_Global_Superstore.csv
```

## Author
ANNREDDY SAAKETH REDDY

Future Improvements
The project can be extended with:

Profit and profit-margin analysis when profit data is available.
Customer segmentation.
Product performance analysis.
Advanced statistical analysis.
Interactive Power BI dashboard.
Streamlit web dashboard.
Additional sales KPIs.
Interactive filters.
Automated data-quality reports.
Advanced visualizations.
Predictive sales analysis using Machine Learning.

👩‍💻 GitHub Profile
Annreddy Saaketh Reddy
B.Tech Student |Python & Data Analytics Enthusiast

I use GitHub to showcase my work in:

Python
Artificial Intelligence
Machine Learning
Data Analytics
Data Visualization
Exploratory Data Analysis
Pandas
NumPy
Scikit-learn
Excel Automation
Dashboard Development

📬 Connect With Me

GitHub
https://github.com/asreddy2209-arch

LinkedIn
https://www.linkedin.com/in/saaketh-reddy-annreddy-22434937b/

Replace the placeholder with your actual LinkedIn profile.

⭐ Support
If you find this project useful:

⭐ Give the repository a star 🍴 Fork the repository 📢 Share the project 💬 Provide feedback
Task 2 - Data Cleaning Using Pandas

