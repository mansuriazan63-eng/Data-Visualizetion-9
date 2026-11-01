# Pandas Analyzer & Data Visualization

A Python-based, menu-driven Sales Data Analysis and Visualization Toolkit built using **Pandas, NumPy, Matplotlib, Seaborn, and Object-Oriented Programming (OOP)**.

This project helps users load, explore, clean, analyze, manipulate, and visualize sales datasets through an interactive menu-driven interface.

## 🚀 Features

### 1. Dataset Management

- Load sales data from CSV files.
- Generate a synthetic sales dataset.
- Display dataset shape, columns, and data types.
- Explore the first and last five rows.

### 2. Data Cleaning

- Detect missing values.
- Display rows containing missing values.
- Fill missing numeric values using column means.
- Remove rows containing missing values.
- Replace missing values with a specific value.

### 3. Mathematical Operations

- Perform addition, subtraction, multiplication, and division.
- Perform operations between two numeric columns.
- Perform operations between a column and a scalar.
- Store calculation results in new DataFrame columns.

### 4. NumPy Array Operations

- Convert DataFrame columns into NumPy arrays.
- Perform array indexing and slicing.
- Perform element-wise mathematical operations.
- Concatenate two arrays.
- Split arrays into multiple parts.
- Calculate summary statistics.

### 5. DataFrame Operations

- Combine DataFrames using concatenation.
- Merge DataFrames using a common column.
- Join DataFrames using their indexes.
- Split datasets by Region, Product, Year, or equal-sized chunks.

### 6. Search, Sort & Filter

- Search for specific values.
- Sort datasets in ascending or descending order.
- Filter records using comparison operators.
- Filter records using a date range.

### 7. Statistical Analysis

- Generate descriptive statistics.
- Calculate standard deviation and variance.
- Calculate percentiles and quantiles.
- Generate correlation matrices.

### 8. Aggregation & Pivot Tables

- Calculate sum, mean, count, minimum, maximum, median, and standard deviation.
- Group data by categorical columns.
- Create customizable pivot tables.

### 9. Data Visualization

The project supports the following charts:

- Bar Plot
- Line Plot
- Scatter Plot
- Pie Chart
- Histogram
- Stack Plot
- Correlation Heatmap
- Box Plot
- Subplots Dashboard (2×2)

### 10. Save Visualizations

- Save generated charts as image files.
- Export plots in PNG format.
- Save images with high resolution (300 DPI).

## 🛠️ Technologies Used

| Technology | Purpose                             |
| ---------- | ----------------------------------- |
| Python     | Core programming language           |
| Pandas     | Data manipulation and analysis      |
| NumPy      | Numerical computations              |
| Matplotlib | Data visualization                  |
| Seaborn    | Statistical visualization           |
| OOP        | Code organization and encapsulation |

## 📦 Installation

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

**Step 2: Open the project folder**

```bash
cd YOUR-REPOSITORY-NAME
```

**Step 3: Install required libraries**

```bash
pip install numpy pandas matplotlib seaborn
```

**Step 4: Run the Python program**

```bash
python pandas_analyzer.py
```

## 📂 Project Structure

```text
Pandas-Analyzer/
│
├── pandas_analyzer.py
├── README.md
├── requirements.txt
│
└── data/
    └── sales_data.csv
```

*Note: The `data/sales_data.csv` file is generated automatically when you create the sample dataset.*

## ▶️ How to Use

1. Run the Python program.
2. Select **Load Dataset** from the main menu.
3. Enter the path of your CSV file.
4. If you do not have a CSV file, create a synthetic sales dataset.
5. Explore and clean the dataset.
6. Perform mathematical and statistical operations.
7. Generate different visualizations.
8. Save your generated charts.

## 🧠 OOP Concepts Demonstrated

This project demonstrates important Python Object-Oriented Programming concepts:

- **Class:** `SalesDataAnalyzer`
- **Object:** Instance of the `SalesDataAnalyzer` class.
- **Constructor:** `__init__()`
- **Destructor:** `__del__()`
- **Encapsulation:** Organizing data and methods inside a class.
- **Private Helper Methods:** Methods prefixed with a single underscore (`_`).
- **Class Method:** `get_instance_count()`
- **Static Methods:** `dataframe_info()` and `create_sample_dataset()`.

## 📊 Sample Dataset

The project can automatically generate a sample sales dataset containing:

- SalesID
- Date
- Product
- Region
- Units
- UnitPrice
- Sales
- Profit

The generated dataset includes some missing values to demonstrate data-cleaning operations.

## 🎯 Learning Objectives

This project is designed to practice:

- Python programming.
- Object-Oriented Programming.
- Pandas DataFrame operations.
- NumPy array manipulation.
- Data cleaning and preprocessing.
- Statistical analysis.
- Data visualization.
- Working with CSV files.

## 👨‍💻 Author

**Your Name : kaif**

## 📅 Project Information

**Project:** Pandas Analyzer & Data Visualization
**Language:** Python
**Category:** Data Analysis & Visualization
