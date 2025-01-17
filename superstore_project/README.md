# Superstore Data Visualization Project

## Link to Tableau visualizations
You can view all the visualizations for this project on [Tableau Public here](https://public.tableau.com/app/profile/tiffany.tiff/viz/Superstore_17294123059530/Dashboard1).

## Part 1: Profits & Losses
### Question 1: Which Subcategory-Region Pairs are the Biggest Profit Centers and Loss Makers?
- **Top Profit Centers**:
  1. **Copiers - West**: Profit of $19,327.24
  2. **Copiers - East**: Profit of $17,022.84
  3. **Accessories - West**: Profit of $16,484.60
  4. **Binders - West**: Profit of $16,096.80
  5. **Copiers - Central**: Profit of $15,608.84

- **Top Loss Makers**:
  1. **Tables - East**: Loss of $11,025.38
  2. **Tables - South**: Loss of $4,623.06
  3. **Furnishings - Central**: Loss of $3,906.22
  4. **Tables - Central**: Loss of $3,559.65
  5. **Appliances - Central**: Loss of $2,638.62

### Question 2: Which Products Should the Superstore Stop Selling?
- Based on profit analysis at the product level, products with significant negative profits are suggested to be discontinued. (Details visualized in Tableau)

### Question 3: Which Product Subcategories Should the Store Focus On and Which Should They Stop Selling?
- **Focus On**:
  - Copiers,phones  and Accessories show consistent profitability.
- **Stop Selling**:
  - Tables, Supplies, and BookCases have recurring losses across regions.

## Part 2: Advertising
### Question: Identify the 3 Best Combinations of States and Months to Advertise In

Based on the analysis of **average profit per unit**, the **top 3 combinations of state and month** for advertising are:

1. **Indiana in October**: Average Profit Per Unit of $187.59
2. **Minnesota in October**: Average Profit Per Unit of $170.58
3. **Vermont in November**: Average Profit Per Unit of $148.99

To justify advertising expenses, we assume the budget should be **1/5 of the average profit per unit**:
- **Indiana in October**: $37.52
- **Minnesota in October**: $34.12
- **Vermont in November**: $29.80

These amounts represent a reasonable budget for advertising in these states during the identified months, maximizing the return on ad spend (ROAS).

### Visualization
A visualization of the average profit per unit for each month of the year for **Indiana**, **Minnesota**, and **Vermont** is available on the Tableau dashboard. This visualization helps to explain why these specific combinations are chosen for advertising.


## Part 3: Returned Items
### Question 1: Which Products Have the Highest Return Rate?
The top 5 products with the highest return rates are:
1. **Avery 500**: 100% return rate
2. **Acco Glide Clips**: 100% return rate
3. **Okidata B401 Printer**: 100% return rate
4. **Cisco SPA 501G IP Phone**: 100% return rate
5. **Canon Color ImageCLASS MF8580Cdw Wireless Laser All-In-One Printer, Copier, Scanner**: 100% return rate

### Question 2: Which Customers Have the Highest Return Rate?
The top 5 customers with the highest return rates are:
1. **Roland Murray**: 100% return rate
2. **Hilary Holden**: 100% return rate
3. **Sandra Glassco**: 97.59% return rate
4. **Joni Blumstein**: 94.74% return rate
5. **Ted Butterfield**: 94.44% return rate


### Question 3: Average Profit vs. Average Return Rate by Sub-Category
The subcategory analysis shows:
- **Tables**: Average Profit of **-$56.96** with a return rate of **28.64%**.
- **Machines**: Average Profit of **$29.4** with a return rate of **35.03%**.

A scatter plot of **average profit vs. return rate by sub-category** is available on the Tableau dashboard. This visualization highlights subcategories that are both unprofitable and have a high return rate, suggesting potential areas for improvement.

### Visualization
The visualizations are available on the **Tableau dashboard**:
1. **Product Return Rate** by Product Name/ID.
2. **Customer Return Rate** by Customer name/ID.
3. **Scatter Plot**: Average Profit vs. Return Rate by Sub-Category.


## Part 4: Submission
- All visualizations and data files are included in this ZIP archive.
