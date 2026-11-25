AI-Assisted Data Cleaning & Analysis Pipeline

Dataset: Cafe Sales - Dirty Data for Cleaning Training, 10,000 rows and 8 columns (Transaction ID, Item, Quantity, Price Per Unit, Total Spent, Payment Method, Location, Transaction Date), deliberately dirty with blanks and ERROR/UNKNOWN values.

Cleaning: checked every column for missing values and types, converted Quantity, Price and Total Spent from text to numbers, then recovered missing quantities where Total Spent / Price Per Unit was available, dropping missing quantities from 479 to 38 rows. The 38 remaining rows were left blank rather than guessed. UNKNOWN and ERROR item names (344 and 292 rows) were kept in the data but excluded from the item-level charts.

Findings: coffee was the top seller by units at 3,534, while salad brought in the most revenue at $16,605, so the best-selling item is not the highest-earning one.