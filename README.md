## E-commerce Data Analysis Project

---

## Overview
This project involves analyzing an e-commerce dataset to derive insights into sales and profit performance across different customer segments. The analysis is performed using Python in a Jupyter Notebook (`E-comm_DA.ipynb`), leveraging libraries such as Pandas for data manipulation and Plotly for data visualization.

---

## Dataset
The dataset (`dataset.csv`) contains e-commerce transaction data with the following columns:

- `Row ID`: Unique identifier for each row
- `Order ID`: Unique identifier for each order
- `Order Date`: Date the order was placed
- `Ship Date`: Date the order was shipped
- `Ship Mode`: Shipping mode (e.g., Second Class, Standard Class)
- `Customer ID`: Unique identifier for each customer
- `Customer Name`: Name of the customer
- `Segment`: Customer segment (Consumer, Corporate, Home Office)
- `Country`: Country of the transaction
- `City`: City of the transaction
- `State`: State of the transaction
- `Postal Code`: Postal code of the transaction
- `Region`: Region of the transaction
- `Product ID`: Unique identifier for each product
- `Category`: Product category (e.g., Furniture, Office Supplies)
- `Sub-Category`: Product sub-category (e.g., Bookcases, Chairs)
- `Product Name`: Name of the product
- `Sales`: Sales amount for the transaction
- `Quantity`: Quantity of items ordered
- `Discount`: Discount applied to the transaction
- `Profit`: Profit from the transaction

---

## Prerequisites
To run the Jupyter Notebook, you need the following installed:

- Python 3.12 or higher
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - plotly

You can install the required libraries using pip:
  
  ```bash
  pip install pandas plotly
  ```

---

## Project Structure
- E-comm_DA.ipynb: Jupyter Notebook containing the data analysis code.
- dataset.csv: The e-commerce dataset (ensure it is placed in the correct directory as specified in the notebook).
- README.md: This file, providing an overview and instructions for the project.

---

## Analysis Performed
The Jupyter Notebook performs the following tasks:

### 1. Data Loading and Inspection:
  - Loads the dataset using Pandas.  
  - Displays the first few rows and summary statistics.  
  - Checks data types and non-null counts.

### 2. Data Preprocessing:
  
  1. Converts Order Date and Ship Date columns to datetime format.  
  2. Adds new columns for analysis:    
    - Order Month: Month of the order.    
    - Order Year: Year of the order.    
    - Order Day of Week: Day of the week the order was placed.

### 3. Sales and Profit Analysis by Customer Segment:  
  - Groups data by customer segment (Consumer, Corporate, Home Office).  
  - Calculates total sales and profit for each segment.  
  - Visualizes sales and profit using a bar chart with Plotly.

### 4. Sales-to-Profit Ratio Analysis:  
  - Computes the sales-to-profit ratio for each customer segment.  
  - Displays the results in a table.

---

## Results
### 1.Sales and Profit by Segment:
  - A bar chart visualizes total sales and profit for each customer segment.
  - The Consumer segment typically shows the highest sales and profit, followed by Corporate and Home Office.

### 2.Sales-to-Profit Ratio:
  - The ratio indicates how much sales contribute to profit for each segment.

---

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/kpoornasai121/E-Commerce_Python_Project.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the **Jupyter notebook** or **Python script**:
   ```bash
   jupyter notebook E-comm_DA.ipynb
   ```

---

## License
This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code.

---
