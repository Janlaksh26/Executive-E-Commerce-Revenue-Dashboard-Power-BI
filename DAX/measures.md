## DAX Measures

1.Total Sales
Total Sales = SUM(Sheet1[Sales])

Calculates the total revenue generated from all sales transactions.

2.Total Profit
Total Profit = SUM(Sheet1[Profit])

Calculates the total profit generated from the sales transactions.

3.Total Orders
Total Orders = COUNT(Sheet1[Order ID])

Calculates the total number of order records.

4.Average Delivery Days
Average Delivery Days = AVERAGE(Sheet1[Delivery Days])

Calculates the average number of days taken for delivery.

## Profit Margin

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

DIVIDE() is used instead of a direct division operation because it safely handles division-by-zero situations.

## DAX Concepts Demonstrated

* Aggregation functions
* Measures
* Filter context
* Dynamic calculations
* SUM()
* COUNT()
* AVERAGE()
* DIVIDE()
