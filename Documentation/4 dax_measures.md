# DAX Measures

## Total Revenue

SUM(Sales[Revenue])

## Total Orders

DISTINCTCOUNT(Sales[Order ID])

## Average Order Value

DIVIDE([Total Revenue],[Total Orders])

## Conversion Rate

DIVIDE([Purchases],[Visitors])