# power bi -assignment-1

Data Transformation (Power Query)

* Analyzed datasets (list orders,order details, sales targets).
  Restricted rows number into 500
* changed the “Order Date” column in the “List of Orders” table  to data type 'Date'.
* Changed the data type of “Amount” and “Target” columns to ‘Fixed Decimal Number’.
* changed the "CustomerName" column into proper case,  capitalized for each word.
* Merged the "State" and "City" columns to a new column named "Location" in the format ‘City, State’.
* Create a new custom column named "Profit Margin" as the percentage of "Profit" divided by "Amount".
   Added a new conditional column named "Profit Status" based on the values in the
  "Profit" column.  if the profit is less than 0, the label
   should be "Loss"; if the profit equals 0, the label should be "Break-Even"; and if the
   profit is greater than 0, the label should be "Profit" given like this
* Merge the "List of Orders" and "Order Details" tables into a new single table named
 "Orders Data" based on the "Order ID" relationship.
* Handling Missing Data & Duplicate Data
  Identified missing values in the data and determine a strategy to address them.
  Checked for duplicate rows and define a strategy to handle duplicates.
* Sorted data in descending order and filter it only to show "Tamilnadu"
* Duplicated the “Order Details” table and calculated the count of each Order ID, average
  profit by Category or total amount by Sub-Category.
* Duplicated the “Sales Target” table and aggregated the total target amount by Month of
Order Date
* Established a relationship between the “List of Orders” and “Order Details” tables using
  the ‘Order ID’ column.
* created a relationship between the “Order Details” and “Sales Target” tables based on
  the ‘Category’ column. Click "Manage relationships" and ensured this relationship is
  active
