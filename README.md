# Excel Data Analysis Practice

## 📌 Project Overview

This project contains a collection of **Excel Data Analysis practice exercises** designed to build practical skills required for a **Data Analyst** role.

The practice dataset contains sales information such as:

* Order ID
* Order Date
* Customer Name
* Region
* Product
* Sales Amount
* Sales Representative

The exercises cover commonly used Excel functions, dynamic filtering, duplicate handling, and Pivot Tables.

---

## 📊 Dataset Columns

| Column          | Description                                    |
| --------------- | ---------------------------------------------- |
| `Order_ID`      | Unique identifier for each order               |
| `Order_Date`    | Date when the order was placed                 |
| `Customer_Name` | Name of the customer                           |
| `Region`        | Sales region                                   |
| `Product`       | Product purchased                              |
| `Sales_Amount`  | Total sales amount                             |
| `Sales_Rep`     | Sales representative responsible for the order |

---

# 🧠 Practice Exercises

## 1. XLOOKUP — 5 Practice Questions

### Questions

1. Find the `Sales_Rep` for customer **Sara Ahmed**
2. Get the `Sales_Amount` for `Order_ID 1005`
3. Find the `Region` for **David Lee**
4. Return the `Product` for `Order_ID 1010`
5. Find the `Order_Date` for **Omar Hassan**

### Skills Practiced

* XLOOKUP
* Lookup values
* Returning values from another column
* Working with dates

---

## 2. FILTER — 5 Practice Questions

### Questions

1. Show all records where `Region = East`
2. Filter all `Laptop` sales
3. Show data where `Sales_Amount > 3000`
4. Get all records for `Emma` as Sales Rep
5. Filter `West` region + `Mobile` sales

### Skills Practiced

* FILTER
* Multiple conditions
* Logical AND using `*`
* Dynamic array formulas

---

## 3. IF / SUMIF / SUMIFS — Practice

### Questions

1. Categorize sales as **High** (>3000) or **Low**
2. If Region is East → **Priority**, else **Normal**
3. If Product is Laptop → **Premium**, else **Standard**
4. If Sales_Amount < 1000 → **Low Value**, else **High Value**
5. If Sales_Rep is John → **Top Performer**, else **Other**
6. Calculate total sales in the East region
7. Calculate total Laptop sales
8. Calculate total sales by Emma
9. Calculate total sales where Region = West AND Product = Laptop
10. Calculate total sales where Sales_Amount > 1000

### Skills Practiced

* IF
* SUMIF
* SUMIFS
* Conditional logic
* Multiple criteria
* Sales aggregation

---

# 🔄 4. Duplicate & Unique Data Practice

### Questions

1. Remove duplicate values from `Customer_Name`
2. Remove duplicates from the `Product` column
3. Remove duplicates based on `Customer + Product` combination
4. Count how many unique customers exist after removing duplicates
5. Check whether any duplicate `Order_ID` values exist

### Skills Practiced

* UNIQUE
* COUNTIF
* Duplicate detection
* Data cleaning
* Data validation

---

# 📈 5. Pivot Table Practice

Create Pivot Tables for the following:

### 1. Total Sales by Region

**Rows:** Region
**Values:** Sales_Amount → Sum

---

### 2. Total Sales by Product

**Rows:** Product
**Values:** Sales_Amount → Sum

---

### 3. Sales by Sales Representative

**Rows:** Sales_Rep
**Values:** Sales_Amount → Sum

---

### 4. Region vs Product

Determine which product generates the highest sales in each region.

**Rows:** Region
**Columns:** Product
**Values:** Sales_Amount → Sum

---

### 5. Count of Orders per Customer

**Rows:** Customer_Name
**Values:** Order_ID → Count

---

# 🛠️ Excel Skills Covered

This project covers the following Excel skills:

* XLOOKUP
* FILTER
* IF
* SUMIF
* SUMIFS
* UNIQUE
* COUNTIF
* Dynamic Arrays
* Multiple-condition filtering
* Duplicate detection
* Data cleaning
* Pivot Tables
* Sales analysis
* Data aggregation
* Conditional logic

---

# 📁 Project Structure

```text
Excel-Data-Analysis-Practice/
│
├── Excel_Data_Analysis_Practice.xlsx
├── README.md
└── solutions/
    └── Excel_Practice_Solutions.xlsx
```

---

# 🎯 Learning Objectives

The main objectives of this project are to:

* Understand commonly used Excel functions
* Practice data cleaning techniques
* Work with lookup and filtering functions
* Analyze sales data using conditional formulas
* Build Pivot Tables for business analysis
* Develop practical Excel skills for Data Analyst roles
* Create a portfolio project that demonstrates Excel proficiency

---

# 📌 Key Excel Functions

| Function  | Purpose                              |
| --------- | ------------------------------------ |
| `XLOOKUP` | Find and return related data         |
| `FILTER`  | Filter records dynamically           |
| `IF`      | Apply conditional logic              |
| `SUMIF`   | Sum values using one condition       |
| `SUMIFS`  | Sum values using multiple conditions |
| `UNIQUE`  | Extract unique values                |
| `COUNTIF` | Count values matching a condition    |

---

# 📊 Project Outcome

After completing these exercises, the project demonstrates practical experience with:

**Data Cleaning → Data Filtering → Lookup → Conditional Analysis → Aggregation → Pivot Table Analysis**

These are fundamental Excel skills used in many entry-level **Data Analyst** tasks.
