# Sales Dataset Analysis – README

## Project Overview

This project performs basic data cleaning and analysis on a sales dataset using Python and Pandas in Jupyter Notebook.

## Files

* **sales_dataset og.csv** – Original sales data containing order details.
* **sales_dataset.ipynb** – Jupyter Notebook with data cleaning and analysis steps.

## Dataset Information

The dataset contains **125 records** and **8 columns**:

| Column Name | Description             |
| ----------- | ----------------------- |
| OrderID     | Unique order identifier |
| OrderDate   | Date of order           |
| Region      | Sales region            |
| Product     | Product name            |
| SalesPerson | Sales representative    |
| Quantity    | Quantity sold           |
| UnitPrice   | Price per unit          |
| TotalAmount | Total sales amount      |

## Tasks Performed

1. Loaded the sales dataset using Pandas.
2. Checked for missing values.
3. Filled missing values in:

   * **Region** using the mode.
   * **Product** using the mode.
4. Verified data after cleaning.
5. Performed exploratory analysis on sales data.

## Tools Used

* Python
* Pandas
* Jupyter Notebook

## How to Run

1. Open `sales_dataset.ipynb` in Jupyter Notebook.
2. Ensure `sales_dataset og.csv` is available in the correct path.
3. Run all notebook cells sequentially.

## Output

The notebook generates a cleaned dataset and provides insights into sales performance across regions, products, and sales representatives.

---

**Author:** Rudra Bharat
**Project Type:** Sales Data Analysis using Python & Pandas
# sales_dataset
