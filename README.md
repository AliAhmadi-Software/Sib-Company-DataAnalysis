# Sib Company Sales Data Analysis

This project involves analyzing sales data from Sib, a leading exporter of non-oil products worldwide, to help enhance the company’s business performance. As a data analyst, you will process, explore, and analyze historical sales data to answer key business questions and gain insights into customer retention and valuation.

## Project Overview

Sib company has provided sales data in an Excel file (`sales.xlsx`). The project consists of five main stages:

1. **Data Pre-Processing**: Prepare and pre-process the data to make it suitable for analysis. This includes cleaning and organizing the dataset.
   
2. **Exploration**: Answer key questions and gain a visual understanding of the company’s financial performance over the years.
   
3. **Examining Target Markets**: Analyze the company's target markets, focusing on countries with high customer counts but low sales, to identify areas for improvement.
   
4. **Customer Valuation**: Using the RFM (Recency, Frequency, Monetary) model, categorize customers into seven segments, each providing valuable insights for marketing strategies.
   
5. **Customer Retention Analysis**: Determine what percentage of customers return to make additional purchases in subsequent months after their first purchase.

## Libraries Used

This project requires the following Python libraries:

- **numpy**: For numerical operations.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For visualizations.
- **seaborn**: For enhanced data visualization.

## Data Columns

The dataset contains the following columns:

- **InvoiceNumber**: A unique 6-digit number assigned to each invoice. If the invoice number starts with the letter 'C', it indicates the invoice has been canceled.
- **ProductCode**: A unique 5-digit code assigned to each product type.
- **ProductName**: The name of the product.
- **Quantity**: The number of units of each product in the invoice.
- **InvoiceDate**: The date the invoice was created.
- **UnitPrice**: The price of one unit of the product.
- **CustomerId**: A unique 5-digit number assigned to each customer.
- **Country**: The country of residence of the customer.

## How to Run the Project

1. Clone the repository to your local machine.
2. Install the required libraries by running:
   ```bash
   pip install numpy
   pip install pandas
   pip install matplotlib
   pip install seaborn
   ```
3. Open the project notebook or script file, and ensure that `sales.xlsx` is in the correct directory.
4. Run each stage in sequence to complete the analysis.

## Project Structure

- `Data/`: Contains the `sales.xlsx` file with the raw sales data.
- `notebooks/`: Contains Jupyter notebooks with code for each stage of analysis.
- `README.md`: This file, providing an overview of the project.

## Conclusion

This analysis provides insights into Seeb's sales performance, target markets, customer value segmentation, and customer retention trends. It helps identify strategic areas for growth and informs targeted marketing approaches.

---
