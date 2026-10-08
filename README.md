# Power-BI-Assignment_1
Power BI Assignment 1 – Data Transformation and Data Modeling
# Power BI Data Analytics Assignment

This repository contains a comprehensive data cleaning, transformation, modeling, and analysis project built using *Power Query* and *Power BI Desktop*.

## 🚀 Project Overview
The primary objective of this project is to process raw order datasets, clean and transform data using Power Query, establish a robust relational data model, and set up calculations to derive business insights.

## 🛠️ Tools & Technologies Used
* *Power BI Desktop:* For data modeling, relationship management, and visual analytics.
* *Power Query Editor:* For ETL (Extract, Transform, Load), data cleaning, and custom column creation.
* *Git & GitHub:* For version control and project documentation.

## 📊 Step-by-Step Implementation & Key Tasks

### 1. Data Cleaning & Transformation (Power Query)
* *Row & Column Management:* Restricted rows and handled data formats (Order Date to Date format, Amount and Target to Fixed Decimal Number).
* *Text Standardization:* Applied "Capitalize Each Word" to customer names.
* *Custom & Conditional Columns:* 
  * Merged City and State into a single Location column.
  * Created a custom Profit Margin percentage column.
  * Added a *Profit Status* conditional column (Loss, Break Even, Profit) based on profit values.
* *Merging & Grouping:* 
  * Merged List of Orders and Order Details tables using Order ID.
  * Checked for missing values (Data Quality checks) and handled duplicate rows.
  * Used Group By transformations to analyze counts, average profits by category, and total amounts by sub-category.
* *Sorting & Filtering:* Sorted Order Date in descending order and filtered data for regional analysis (e.g., Tamil Nadu).

### 2. Data Modeling & Relationships
Established an active and accurate relational schema in Power BI Model View:
* *List of Orders* $\leftrightarrow$ *Order Details*: Connected via Order ID (One-to-Many / Many-to-One relationship).
* *Order Details* $\leftrightarrow$ *Sales Target*: Connected via Category (Many-to-Many relationship based on target mappings).

## 📂 Dataset Structure
* List of Orders: Contains order-level details, dates, customer names, and geographical locations.
* Order Details: Contains item-level sales, amounts, quantities, and profit breakdowns.
* Sales Target: Contains category-wise and month-wise performance targets.

## 👨‍💻 How to View This Project
1. Download or clone this repository.
2. Open the .pbix file using *Power BI Desktop*.
3. Explore the *Power Query Editor* to review transformation steps or switch to the *Model View* to inspect table relationships.

---
Created as part of the Data Analytics learning journey.
