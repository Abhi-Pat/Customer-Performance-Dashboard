# Power BI Project: Customer Insights Dashboard

## Overview
This project involves creating a Power BI dashboard to analyze customer data, providing insights into customer demographics, behavior, and purchasing patterns. The goal is to assist businesses in making data-driven decisions and identifying key customer segments.

## Data Transformation
The data transformation process involved the following steps:

1. **Data Extraction and Loading**:
   - Pulled dataframes from the source file.
   - Loaded and extracted the required tables.

2. **Data Cleaning and Selection**:
   - Deleted unrequired columns and selected only the necessary columns.
   - Checked the datatypes of each column, using ChatGPT to verify and maintain data integrity.
   - Verified that there were no empty values in the data.

3. **Column Enhancements**:
   - Used DAX queries to:
     - Create new columns.
     - Develop calculated and conditional columns.
     - Join tables to derive additional required columns.

## Reports and Insights
The following reports were developed to provide actionable insights:

1. **Average Age of Customers**:
   - Calculated the average age of all customers.

2. **Total Customer Count**:
   - Determined the total number of customers in the dataset.

3. **Customer Categorization**:
   - Categorized customers based on their total orders and purchases:
     - **VIP Customers**: Total Orders ≥ 15
     - **Loyal Customers**: Total Orders ≥ 7
     - **Periodic Buyers**: All others

4. **Revenue Analysis by Parental Status**:
   - Analyzed revenue based on whether customers have children or not.

5. **Dynamic Ranking System**:
   - Implemented a dynamic ranking system to identify the top-performing customers.

6. **Revenue Analysis by Gender**:
   - Examined revenue distribution based on customer gender.

## Key Features
- Interactive visuals to explore customer segmentation and revenue breakdown.
- Dynamic filters and slicers for age, gender, parental status, and customer category.
- Conditional formatting to highlight key insights (e.g., top customers and revenue trends).

## Technical Details
- **Tools Used**: Power BI Desktop
- **Data Modeling**: Leveraged DAX functions for calculated fields and dynamic measures.
- **Data Cleaning**: Utilized Power Query Editor for efficient data transformation.


## Usage Instructions
1. Clone the repository and download the `.pbix` file.
2. Open the file in Power BI Desktop.
3. Refresh the data to load it into the model (ensure the source file is accessible).
4. Explore the dashboard using interactive filters and slicers.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for suggestions and improvements.

## Contact
For questions or collaboration, please reach out via [ mailabhishekpatro@gmail.com ].

