# Diwali Sales Data Analysis

This repository contains a Jupyter Notebook that analyzes Diwali sales data to extract valuable insights. The analysis is performed using Python libraries such as NumPy, pandas, Matplotlib, and Seaborn.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this project is to analyze sales data during the Diwali festival. The analysis includes understanding the purchasing patterns of different demographics such as gender, age group, and state, and identifying the top-selling product categories and states with the highest sales.

## Dataset

The dataset used for this analysis is `Diwali Sales Data.csv`, which contains the following columns:
- `Status`
- `unnamed1`
- `Gender`
- `Age`
- `Age Group`
- `State`
- `Marital_Status`
- `Occupation`
- `Product_Category`
- `Product_ID`
- `Orders`
- `Amount`

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Diwali_sales_data_anlysis.git
```

2. Change the directory:

```bash
cd Diwali_sales_data_anlysis
```

3. Create a virtual environment:

```bash
python -m venv env
```

4. Activate the virtual environment:

- For Windows:
  ```bash
  .\env\Scripts\activate
  ```
- For macOS/Linux:
  ```bash
  source env/bin/activate
  ```

5. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Open the `Diwali_Sales_Analysis.ipynb` file in the Jupyter Notebook interface.

3. Run the cells sequentially to perform the analysis.

## Analysis

The analysis includes the following steps:

1. **Data Loading and Cleaning:**
   - Load the dataset using pandas.
   - Remove unnecessary columns (`Status`, `unnamed1`).
   - Handle missing values by dropping rows with null values.
   - Convert the `Amount` column to integer type.

2. **Exploratory Data Analysis (EDA):**
   - Analyze the distribution of buyers by gender.
   - Analyze the distribution of buyers by age group.
   - Analyze the distribution of sales by state.
   - Analyze the distribution of buyers by marital status and occupation.
   - Analyze the top-selling product categories and products.

## Results

The analysis reveals the following insights:
- Most of the buyers are female, and their purchasing power is greater than that of males.
- The majority of buyers belong to the age group of 26-35.
- Uttar Pradesh, Maharashtra, and Karnataka are the states with the highest number of orders.
- Most of the buyers are married women.
- The IT sector, aviation, and healthcare sector have the highest number of buyers.
- The highest revenue is generated in the Food category, followed by Footwear & Shoes, and Clothing & Apparel.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines on contributing to this project.
