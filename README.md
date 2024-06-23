# US Superstore Data Analysis Project

## Introduction

This project involves analyzing a fictional dataset from a fictional US Superstore. The dataset contains detailed information about customer orders, including sales, profits, customer demographics, shipping details, and product categories. The primary objective of using this data is to gain insights into various business operations and performance metrics, which can help in making informed business decisions.

### Why Use This Data?

The US Superstore dataset provides a comprehensive view of a retail business's operations. By analyzing this data, we can uncover trends, patterns, and insights that are crucial for strategic planning and decision-making. The data analysis covers various aspects such as sales performance, profit margins, customer demographics, and product categories, providing a holistic view of the business.

## Data Description

### Columns in the Excel File

The dataset consists of the following columns:

- **Customer ID**: Identifier for customers.
- **Customer Name**: Name of the customer.
- **Order Priority**: Priority of the order (e.g., High, Medium, Low).
- **Discount**: Discount applied to the order.
- **Unit Price**: Price per unit of the product.
- **Shipping Cost**: Cost of shipping the order.
- **Ship Mode**: Mode of shipping (e.g., Regular Air, Delivery Truck).
- **Customer Segment**: Segment to which the customer belongs (e.g., Small Business, Consumer).
- **Product Category**: Category of the product (e.g., Furniture, Technology).
- **Product Sub-Category**: Sub-category of the product.
- **City, State, Postal Code**: Shipping address details.
- **Order Date**: Date when the order was placed.
- **Ship Date**: Date when the order was shipped.
- **Profit**: Profit from the order.
- **Quantity ordered new**: Quantity of the product ordered.
- **Sales**: Total sales amount.
- **Order ID**: Identifier for the order.
- **Total**: Total amount for the order.
- **Manager**: Manager responsible for the order.

### Potential Analysis

From this dataset, the following types of analyses can be performed:

1. **Sales Analysis**:
   - Identify top-performing products and customer segments.
   - Analyze sales trends over time.
   - Explore regional sales performance.

2. **Profit Analysis**:
   - Determine the most profitable products and customer segments.
   - Examine profit trends over time.
   - Explore regional profit performance.

3. **Demographic Analysis**:
   - Acknowledging most active and most valuable customers based on the purchases and sales.
   - Explore regional customer demographics and preferences.
   - Examine trend of orders made over time based on different customer segments.

## Steps Followed

### Data Preparation

1. **Upload Data**:
    - Uploaded the Excel file containing the raw data to Power BI Desktop.

2. **Data Transformation and Formatting**:
    - Transformed the data to ensure it was in the correct format.
    - Formatted columns containing prices to currency format.
    - Removed rows with all blank values.
    - Calculated necessary measures and added new columns by implementing formulas.

3. **Data Cleaning**:
    - Handled missing values by either filling them with appropriate values or removing them.
    - Ensured consistency in data formats (e.g., dates, currency).
    - Validated data accuracy by cross-checking with expected ranges and values.

### Data Visualization

1. **Creating Visualizations**:
    - Developed visualizations for Sales Analytics, Profit Analytics, and Demographic Analytics.
    - Used bookmarks and a navigation pane to help viewers navigate through the three segments of the report:
        - **Sales Analytics**: Visualizations include bar charts, line charts, and pie charts to represent sales data.
        - **Profit Analytics**: Visualizations include bar charts and pie charts to analyze profitability.
        - **Demographic Analytics**: Visualizations include maps and bar charts to analyze customer demographics.
    - Added slicers for regions and filters to provide insights into top sales, top profits, and the number of orders for different product categories and customer segments.
    - Analyzed trends for sales, profits, and the number of orders over the available period of data.

2. **Customizing the Report**:
    - Downloaded a required theme and made custom changes to fit the visual style of the report.
    - Ensured that the visualizations were intuitive and easy to understand.

### Technical Details

- **Data Transformation**:
  - Used Power Query Editor to clean and transform data.
  - Implemented DAX formulas to create calculated columns and measures.
  - Applied data type transformations for accurate analysis.

- **Visualization Techniques**:
  - Used bar charts to compare sales and profits across categories.
  - Employed line charts to show trends over time.
  - Utilized pie charts to display the proportion of sales and profits by category.

### Visual Examples

Here are some screenshots of the key visualizations from the Power BI report:

- **Sales Analytics Dashboard**:
  ![Sales Analytics](https://github.com/vythrey/US_Superstore_Data_Dashboard/assets/153704808/c916c8f8-eb2b-4424-89d3-63012732208e)

- **Profit Analytics Dashboard**:
  ![Profit Analytics](https://github.com/vythrey/US_Superstore_Data_Dashboard/assets/153704808/a389a4e7-f462-49cb-96e8-e034a0fd9eb5)

- **Demographic Analytics Dashboard**:
  ![Demographic Analytics](https://github.com/vythrey/US_Superstore_Data_Dashboard/assets/153704808/00c6081c-748e-4404-8e86-71970f499f4d)

## Results

The analysis provided the following key insights:

- **Sales Analytics**:
    - Identified the best-selling products and customer segments that contributed in high sales.
    - Recognized seasonal sales trends and peak sales periods.
    - Analyzed regional sales performance to identify high-performing regions.

- **Profit Analytics**:
    - Determined the most  profitable products and high profit making customer segments.
    - Recognized seasonal profit trends and peak profit periods.
    - Analyzed profit margins across different regions and customer segments.

- **Demographic Insights**:
    - Analyzed customer segments to understand buying patterns and preferences.
    - Explored regional customer demographics and preferences.
    - Identified key customer segments that contribute significantly to sales and profits.

## Conclusion

The analysis of the US Superstore dataset provided valuable insights into the business's sales performance, profitability, and customer demographics. These insights can be used to make data-driven decisions to improve business operations, enhance customer satisfaction, and increase profitability. The visualizations and interactive elements created in Power BI make it easy to explore and understand the data, enabling stakeholders to make informed decisions based on the analysis.


### References

- Power BI Documentation: [Microsoft Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- Power Query : [Power Query User Interface](https://learn.microsoft.com/en-us/power-query/power-query-ui)

---

### Files in the Repository

- **Vythrey_Narayanam_US_Superstore_Analysis.pbix**: Power BI file containing the complete analysis and visualizations.
- **Superstore Raw Data.xlsx**: Excel file containing the raw data used for analysis.


### Files in the Repository

- **Vythrey_Narayanam_US_Superstore_Analysis.pbix**: Power BI file containing the complete analysis and visualizations.
- **Superstore Raw Data.xlsx**: Excel file containing the raw data used for analysis.

### How to Use

1. Download the Power BI file (`.pbix`) and the raw data file (`.xlsx`).
2. Open the Power BI file in Power BI Desktop.
3. Explore the visualizations and insights by navigating through the bookmarks and using the slicers and filters provided.

---

### Contact

For any queries or further information, please contact [Vythrey Narayanam](vythrey.narayanam@gmail.com)
