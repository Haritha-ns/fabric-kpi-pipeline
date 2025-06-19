
-- Sample DAX Measures

Total Sales = SUM(FactSales[Amount])
Profit Margin = DIVIDE(SUM(FactSales[Profit]), SUM(FactSales[Amount]), 0)
