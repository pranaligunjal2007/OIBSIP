#  DataAnalytics-L1-customer Segmentation Analysis

## OASIS INFOBYTE - Data Analytics Internship

### Project Overview

This project performs customer segmentation using the Online Retail dataset. The main objective is to analyze customer purchasing behavior and group customers into different segments using RFM analysis and K-Means clustering.

## Dataset

The project uses the Online Retail dataset containing transaction information such as:

- Invoice Number
- Stock Code
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Loaded the Online Retail dataset.
2. Inspected the dataset structure and data types.
3. Checked and handled missing values.
4. Removed invalid transactions.
5. Performed RFM analysis:
   - Recency
   - Frequency
   - Monetary
6. Standardized the RFM features.
7. Applied the Elbow Method to determine the number of clusters.
8. Applied K-Means clustering.
9. Analyzed customer segments.
10. Visualized customer segment distribution and RFM metrics.
11. Exported the customer segmentation results to CSV.

## Customer Segmentation

Customers were grouped into five clusters using K-Means clustering.

The final analysis includes:

- Customer Segment Distribution
- RFM Analysis by Customer Segment
- Cluster Profile
- Highest-value customer segment

## Output

The processed customer segmentation results are saved as:

`customer_segmentation_results.csv`

## Project Files

- `Customer_Segmentation.ipynb` - Main analysis notebook
- `Online Retail.xlsx` - Dataset
- `customer_segmentation_results.csv` - Final segmentation results
- `README.md` - Project documentation

## Conclusion

The project successfully segments customers based on their purchasing behavior using RFM analysis and K-Means clustering. These customer segments can help businesses understand different customer groups and support data-driven marketing and customer relationship strategies.

## Author

**Pranali Gunjal**

OASIS INFOBYTE Data Analytics Internship
