# Global Sales Year Bins Analysis

## Overview
This project focuses on analyzing global video game sales by creating 5-year bins for the `Year` field to categorize sales trends over time. I used Tableau for visualization and custom calculations, including comparing global sales to EU sales. The analysis covers video game sales data from 1990 to 2015, sourced from Kaggle.

## Project Details
### 1. Year Bins Creation
- Grouped the `Year` field into 5-year bins to better analyze trends.
- Transformed the `Year` field from a numeric value to a categorical dimension (`Year (bin!)`).
- Excluded null values to work only with valid sales data from 1990 to 2015.

### 2. Percent of Total Calculation
- Created a quick table calculation to compute the percentage of total global sales by year bins.
- Saved the calculation to the measures table for reuse in other visualizations.

### 3. Global Sales vs. EU Sales
- Created a custom calculated field to subtract EU sales from global sales.
- Visualized the comparison to observe differences between global sales and EU sales for deeper insights.

## Tools Used
- **Tableau**: For visualizing sales data, creating bins, applying filters, and performing custom calculations.
- **Kaggle CSV Dataset**: Used as the data source for video game sales.

## How to Use
1. **Open Tableau Workbook**: Use the provided Tableau workbook file to explore the visualizations.
2. **Examine Year Bins**: The workbook includes a `Year (bin!)` field used in the columns for categorizing data.
3. **View Custom Calculations**: The workbook features calculated fields such as `Percent of Total Global Sales` and `Global Sales - EU Sales` to visualize key insights.

## Visualizations Included
- **Year Bins and Global Sales**: Displaying global sales as a percentage of total sales across 5-year intervals.

[viz](https://public.tableau.com/app/profile/marlenecodes/viz/GlobalSalesvsEUSales/GlobalSalesvs_EUSales?publish=yes)

![vg_bins](https://github.com/user-attachments/assets/9249417e-4115-4721-9d15-71ef9e6215eb)

- **Global Sales vs. EU Sales**: Comparing global sales with EU sales by year bins for a clearer understanding of the differences.

![vg_globalvsEU](https://github.com/user-attachments/assets/633d1384-47b6-47af-b6e2-e86317ea0ca3)


**Tableau Public Link**: [Visualization]()

## Future Improvements
- Adding further regional comparisons (e.g., North America vs. EU vs. Global).
- Expanding the analysis to newer data (post-2015) and deeper insights into platform-specific sales.
