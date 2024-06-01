 Grocery Sales Data Analysis
The aim of this project is to perform a comprehensive analysis of grocery sales data. Using SQL queries, various insights and metrics are derived from the dataset stored in the `sql_project` table. This table contains multiple attributes related to grocery items and their sales across different outlets. The analysis covers various aspects of the data such as item identifiers, weights, prices, fat content, outlet characteristics, and sales performance. Below is a step-by-step breakdown of the queries and their purposes:

1.Item Identification:
   - Display all item identifiers.
   - Count the total number of unique item identifiers.
2. Item Weight Analysis
   - Find the maximum, minimum, and average weights of the items.
3. Item Fat Content Analysis:
   - Count the number of items with "Low Fat" and "Regular" fat content.
4. Item MRP (Maximum Retail Price) Analysis:
   - Find the maximum and minimum MRP values.
   - Display details of items with MRP greater than 200.
   - Find maximum and minimum MRP for items with "Low Fat" content.
5. Price Range and Unique Values:
   - Display all data for items with MRP between 50 and 100.
   - Show all unique values for `Item_Fat_Content`, `Item_Type`, `Outlet_Size`, `Outlet_Location_Type`, and `Outlet_Type`.
6. Ordering and Filtering Data:
   - Order data by `Item_MRP`, `Item_Outlet_Sales`, and `Item_Type` in ascending or descending order.
   - Filter data for specific item types (e.g., dairy and meat).
7. Group by and Aggregate Functions:
   - Count items by `Item_Type`, `Outlet_Size`, `Outlet_Type`, and `Outlet_Location_Type`.
   - Find maximum, minimum, and average MRP grouped by `Item_Type`, `Outlet_Establishment_Year`, and `Outlet_Size`.
   - Find maximum and minimum item weights grouped by `Item_Type` and `Outlet_Establishment_Year`.
   - Calculate average item weights grouped by `Outlet_Location_Type`.
8. Sales Performance Analysis:
   - Determine maximum and minimum `Item_Outlet_Sales` grouped by `Item_Type` and `Outlet_Establishment_Year`.
   - Calculate average `Item_Outlet_Sales` grouped by `Outlet_Size` and `Outlet_Type`.
   - Find maximum and total `Item_Outlet_Sales` grouped by `Outlet_Type`, `Item_Type`, and `Item_Fat_Content`.
   - Analyze visibility of items by finding maximum and minimum `Item_Visibility` grouped by `Item_Type`.
9. Targeted Sales Analysis:
    - Calculate total `Item_Outlet_Sales` for items in `Tier 1` outlets.
    - Calculate total `Item_Outlet_Sales` for items with specific fat content ("Low Fat" and "LF").
This structured approach ensures a detailed understanding of the grocery sales data, providing valuable insights into sales trends, product characteristics, and outlet performance. The use of SQL queries allows for efficient data manipulation and retrieval, enabling informed decision-making based on the analysis results.
