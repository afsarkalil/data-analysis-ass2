# data-analysis-ass2
# 📊 Product Dataset – Data Cleaning & Preparation

## 📌 Project Overview

This project demonstrates the process of **data cleaning and preparation using Microsoft Excel**.

The objective is to transform a raw product dataset into a clean, consistent, and analysis-ready dataset by identifying missing values, correcting inconsistencies, removing duplicates, transforming columns, formatting data, and applying conditional formatting.

This project is part of my **Data Analytics Portfolio** and demonstrates my practical skills in spreadsheet-based data preparation.

---

## 📂 Dataset

The dataset contains product information with the following attributes:

| Column       | Description                       |
| ------------ | --------------------------------- |
| Product ID   | Unique product identifier         |
| Product Name | Name of the product               |
| Brand Name   | Brand associated with the product |
| Quantity     | Quantity of the product           |
| Category     | Product category                  |
| Price        | Product price                     |

---

## 🎯 Project Objectives

The main objectives of this project were:

* Handle missing values
* Standardize inconsistent text
* Correct category errors and typos
* Identify and remove duplicate records
* Split the Product ID into meaningful columns
* Merge Brand Name and Product Name
* Apply appropriate number and date formatting
* Use conditional formatting to highlight important values
* Prepare the dataset for further analysis

---

## 🧹 Data Cleaning Process

### 1. Missing Value Handling

The dataset was checked for missing values in:

* **Price**
* **Category**

Appropriate handling strategies were applied to ensure the dataset was suitable for further analysis.

---

### 2. Data Standardization

The **Product Name** column was reviewed for inconsistent text formats.

Excel's **Find and Replace** feature was used to standardize the product names.

The **Category** column was also checked for spelling mistakes and inconsistent values, which were corrected using Find and Replace.

---

### 3. Duplicate Removal

The dataset was checked for duplicate rows using the complete row information.

Duplicate records were identified and removed using Excel's **Remove Duplicates** feature.

This improves data quality and prevents duplicate records from affecting analysis.

---

### 4. Data Transformation

#### Product ID Splitting

The **Product ID** column was split into:

* Manufacturing Date
* Country Code

Unnecessary characters were removed during the transformation.

#### Product Brand

The **Brand Name** and **Product Name** columns were merged into a new column:

**Product Brand**

This creates a more useful combined product identification field.

---

### 5. Data Formatting

#### Price

The **Price** column was formatted as currency.

#### Manufacturing Date

The **Manufacturing Date** column was formatted using:

`DD-MM-YYYY`

This ensures consistent date representation.

---

### 6. Conditional Formatting

Conditional formatting was applied to improve the visual understanding of the dataset.

#### Price

A **Data Bar / Color Scale** was applied to the Price column to visually compare product prices.

#### Category

A custom conditional formatting rule was applied to highlight products belonging to the:

**Electronics**

category.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* **GitHub**

### Excel Skills Demonstrated

* Data Cleaning
* Missing Value Handling
* Find & Replace
* Duplicate Removal
* Column Splitting
* Column Merging
* Currency Formatting
* Date Formatting
* Conditional Formatting
* Data Preparation

---

## 📁 Repository Structure

```text
Product-Dataset-Data-Cleaning/
│
├── README.md
│
├── Product_Dataset_Cleaned.xlsx
│
└── Documentation/
    └── Product_Dataset_Cleaning.pdf
```

---

## 📸 Project Documentation

The documentation PDF contains screenshots demonstrating:

* Missing value handling
* Find and Replace
* Data standardization
* Duplicate removal
* Product ID splitting
* Column merging
* Number formatting
* Date formatting
* Conditional formatting

Each step is supported with a brief explanation of the data-cleaning process.

---

## 📈 Key Skills Demonstrated

This project demonstrates practical knowledge of:

**Data Cleaning → Data Preparation → Data Transformation → Data Quality → Data Formatting → Data Visualization**

These are fundamental skills required in the data analytics workflow.

---

## 🚀 Future Improvements

This cleaned dataset can be used for further analytics projects, such as:

* Exploratory Data Analysis (EDA)
* Sales and product analysis
* Price analysis
* Category-wise analysis
* Data visualization using Power BI
* Dashboard development
* SQL-based analysis
* Python-based data analysis

---

## 👨‍💻 About Me

**Afsar**

Aspiring Data Analyst | B.Com Student | Data Analytics Learner

Currently developing practical skills in:

* Excel
* SQL
* Python
* Power BI
* Data Cleaning
* Data Visualization
* Data Analysis

This repository is part of my journey toward building a **Data Analytics Portfolio**.

---

## 📌 Project Status

**Completed ✅**

This project demonstrates the complete basic data-cleaning and preparation workflow using Excel.
