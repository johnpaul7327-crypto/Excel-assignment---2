# 📊 Product Dataset – Data Cleaning & Preparation in Excel

## 📌 Project Overview

This project demonstrates the use of **Microsoft Excel for data cleaning, preparation, transformation, and formatting**.

As part of my journey toward becoming a **Data Analyst**, I worked on a Product Dataset containing information such as Product ID, Product Name, Brand Name, Quantity, Category, and Price.

The objective of this project was to transform a raw and potentially inconsistent dataset into a **clean, structured, and analysis-ready dataset** using Excel's built-in data cleaning and formatting features.

---

## 🎯 Project Objectives

The main objectives of this project were:

* Handle missing values
* Identify and correct inconsistent text formats
* Fix category spelling errors and inconsistencies
* Identify and remove duplicate records
* Split the Product ID into meaningful columns
* Merge Brand Name and Product Name
* Apply appropriate number and date formatting
* Use conditional formatting to highlight important information
* Prepare the dataset for further analysis

---

## 🗂️ Dataset Description

The dataset contains the following attributes:

| Column       | Description                                              |
| ------------ | -------------------------------------------------------- |
| Product ID   | Unique identifier containing product-related information |
| Product Name | Name of the product                                      |
| Brand Name   | Brand associated with the product                        |
| Quantity     | Available quantity                                       |
| Category     | Product category                                         |
| Price        | Product price                                            |

---

# 🧹 Data Cleaning Process

## 1. Handling Missing Values

### Price

I checked the **Price** column for missing values.

For products with missing price information, the appropriate approach is to avoid randomly assigning a value. Depending on the business context, missing prices can be:

* Investigated using the original source
* Replaced using a reliable reference value
* Temporarily marked as `N/A`
* Excluded from price-based analysis if the value cannot be verified

### Category

Missing values in the **Category** column can be handled by:

* Checking the Product Name for category information
* Checking similar products
* Using the Brand/Product information where appropriate
* Assigning an `Unknown` or `Uncategorized` value when the category cannot be reliably determined

This prevents unsupported assumptions from being introduced into the dataset.

---

## 2. Correcting Inconsistent Data

### Product Name

The **Product Name** column was checked for inconsistent text formatting.

Examples of issues that may occur include:

* Different capitalization
* Extra spaces
* Inconsistent naming formats
* Minor spelling variations

Excel's **Find & Replace** functionality was used to standardize inconsistent values where applicable.

### Category

The **Category** column was reviewed for spelling mistakes and inconsistent category names.

Find & Replace was used to correct identified typos and standardize category names.

This ensures that the same category is represented consistently throughout the dataset.

---

## 3. Removing Duplicate Records

The dataset was checked for duplicate rows using the complete row information.

### Excel Method

**Data → Remove Duplicates**

All relevant columns were selected so that only rows that were identical across the entire dataset were treated as duplicates.

Duplicate records were removed to improve data quality and prevent duplicate entries from affecting future analysis.

---

## 4. Splitting and Merging Columns

### Splitting Product ID

The **Product ID** column contains information that needs to be separated into:

* Manufacturing Date
* Country Code

Excel's **Text to Columns** functionality was used to split the information where appropriate.

Unnecessary characters were removed during the transformation.

### Merging Brand Name and Product Name

The **Brand Name** and **Product Name** columns were combined into a new column:

**Product Brand**

Example:

```text
Brand Name + Product Name
```

This creates a more user-friendly field for reporting and analysis.

---

## 5. Number Formatting

### Price

The **Price** column was formatted as currency to improve readability and ensure that monetary values are clearly represented.

Example:

```text
₹1,500.00
```

The exact currency format depends on the dataset and analysis requirements.

### Manufacturing Date

The **Manufacturing Date** column was formatted using:

```text
DD-MM-YYYY
```

Example:

```text
15-08-2026
```

This provides a consistent date format throughout the dataset.

---

# 🎨 6. Conditional Formatting

Conditional formatting was applied to make important information easier to identify.

### Price Column

A **Data Bar / Color Scale** was applied to the Price column.

This provides a visual representation of price differences and makes higher and lower values easier to compare.

### Category Column

A custom conditional formatting rule was created for the **Category** column.

Cells containing:

```text
Electronics
```

were highlighted.

This makes it easier to identify Electronics products within the dataset.

---

# 🛠️ Tools & Technologies

* **Microsoft Excel**
* Data Cleaning
* Find & Replace
* Remove Duplicates
* Text to Columns
* Excel Formulas
* Number Formatting
* Date Formatting
* Conditional Formatting

---

# 📁 Project Structure

```text
Product-Dataset-Data-Cleaning/
│
├── 📊 Product_Dataset_Cleaned.xlsx
│
├── 📄 Data_Cleaning_Report.pdf
│
└── 📖 README.md
```

### Files

**Product_Dataset_Cleaned.xlsx**

Contains the cleaned and transformed dataset, including:

* Corrected text
* Removed duplicates
* Split columns
* Merged Product Brand column
* Currency formatting
* Date formatting
* Conditional formatting

**Data_Cleaning_Report.pdf**

Contains screenshots and explanations demonstrating:

* Missing value handling
* Find & Replace corrections
* Duplicate removal
* Column splitting
* Column merging
* Conditional formatting

---

# 📸 Project Documentation

The PDF report documents the major data-cleaning operations performed in Excel.

The screenshots demonstrate the transformation process from the original dataset to the cleaned dataset.

---

# 📈 Key Data Analyst Skills Demonstrated

Through this project, I practiced the following fundamental Data Analyst skills:

| Skill                | Application                                  |
| -------------------- | -------------------------------------------- |
| Data Cleaning        | Handling missing and inconsistent data       |
| Data Quality         | Identifying and removing duplicates          |
| Data Standardization | Correcting text and category inconsistencies |
| Data Transformation  | Splitting and merging columns                |
| Data Formatting      | Applying currency and date formats           |
| Data Visualization   | Applying conditional formatting              |
| Excel                | Using Excel tools for data preparation       |

---

# 💡 Key Learning Outcomes

This project helped me understand that **data cleaning is an important step before performing analysis**.

I learned how to:

* Inspect raw datasets for quality issues
* Identify missing and inconsistent values
* Standardize text fields
* Remove duplicate records
* Transform columns using Excel
* Apply appropriate formatting
* Use conditional formatting to improve data readability
* Prepare a dataset for further analysis

---

# 🚀 Future Improvements

As I continue developing my Data Analyst skills, I plan to extend this project by:

* Performing **Exploratory Data Analysis (EDA)**
* Creating Excel dashboards
* Building Pivot Tables
* Creating charts and KPIs
* Analyzing product and category performance
* Performing statistical analysis
* Recreating the cleaning process using **SQL**
* Automating data cleaning using **Python/Pandas**
* Building an interactive **Power BI dashboard**

---

# 👨‍💻 About Me

I am an aspiring **Data Analyst** developing my skills in:

* Microsoft Excel
* SQL
* Power BI
* Python
* Data Cleaning
* Data Visualization
* Exploratory Data Analysis

This project is part of my **Data Analytics portfolio**, where I document practical projects and demonstrate my progress from data cleaning to analysis and visualization.

---

## ⭐ Portfolio

More Data Analytics projects will be added as I continue learning and building my portfolio.

**Skills → Practice → Projects → Portfolio → Data Analyst**


