# Task 15 – Product Count Analysis

## Objective
Count products by category and identify the category with the largest number of unique products using Microsoft Excel.

## Dataset
Superstore Sales Dataset.

The analysis uses:
- Category
- Product Name

## Tools Used
- Microsoft Excel

## Analysis Performed

### Unique Product Count
Unique products were counted for each category using Excel's `UNIQUE` and `FILTER` functions.

### Category Record Count
`COUNTIF` was used to calculate the total number of records for each category.

### Top Category
`MAX` and `INDEX/MATCH` were used to identify the category with the highest unique product count.

## Results

| Category | Unique Product Count |
|---|---:|
| Furniture | 842 |
| Office Supplies | 2,071 |
| Technology | 876 |

### Top Category
**Office Supplies**

### Highest Unique Product Count
**2,071**

## Key Insights
- Office Supplies has the highest number of unique products.
- Furniture has the lowest number of unique products.
- Office Supplies also has the highest number of total records.
- Unique product count and total record count are different because the same product can appear in multiple records.

## Methodology
1. Prepared the Category and Product Name fields from the Superstore dataset.
2. Used `UNIQUE` and `FILTER` to identify distinct products within each category.
3. Used `COUNTIF` to count total records for each category.
4. Compared the unique product counts.
5. Identified Office Supplies as the top category.
6. Created a column chart to visualize unique product counts.

## Conclusion
Office Supplies has the largest product variety among the three categories, with 2,071 unique products. This analysis demonstrates the use of Excel functions including `COUNTIF`, `UNIQUE`, `FILTER`, `MAX`, and `INDEX/MATCH`.
