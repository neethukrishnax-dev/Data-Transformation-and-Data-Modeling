The project uses the following datasets  :List of orders, order details, sales target

*Home>Keep rows>keep top rows>500 rows selected.
*click order date column>change data type to date.
*amount column convert to fixed decimal number then repeat step target column.
*Converted customer names to proper case.
*Combined City and State columns into a Location column(Merge colums)
*Created a Profit Margin column(Add column>Custom column>[profit]/[Amount]).
*Created a Profit Status column to identify profit and los(Order details table >Add column>Conditional column>apply conditions>ok)
*Create order ID column:List of orders>Merge queries as new)
*Checked data quality and removed duplicate rows(home.>remove rows>remove duplicates)
*Sorted order dates in descending order(order date>sort decending>).
* Filtered the data by State( state>filter>gujarat>ok)
*  Duplicated the Order Details table for analysis(order details query>duplicate> groupb).
*Calculated average profit by category.
*Calculated total amount by sub-category.
*Duplicated the Sales Target table.
*Aggregated target amounts by month of order date.
* Created a relationship between List of Orders and Order Details using Order ID.
*Created a relationship between Order Details and Sales Target using Category.
*Checked the relationships using Manage Relationships and ensured they were active.
