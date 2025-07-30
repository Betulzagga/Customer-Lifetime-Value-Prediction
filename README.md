# CLTV Calculation with BG/NBD and Gamma-Gamma Models

This script calculates Customer Lifetime Value (CLTV) using transaction data. It leverages probabilistic models like BG/NBD for purchase frequency and Gamma-Gamma for monetary value prediction. Ideal for customer segmentation and retention strategies.

## Requirements
- pandas
- lifetimes
- matplotlib

## Usage
Prepare your dataframe with columns: `customer_id`, `invoice_date`, `total_price`. Then run the script to obtain CLTV scores and segments.
