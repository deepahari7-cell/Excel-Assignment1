Excel Data Analysis Project
Overview

This project demonstrates how to perform essential data analysis operations in Excel, including basic aggregation, conditional logic, and text manipulation functions. The dataset contains product-related information such as Product ID, Category, and Price.

📊 1. Sum, Count, and Average

Objective:
To compute basic statistical measures on the product price data.

Tasks:

Total Price: Calculate the sum of all product prices using the SUM function.

=SUM(B2:B100)


Number of Products: Count the total number of products using the COUNT function.

=COUNT(B2:B100)


Average Price: Find the average product price using the AVERAGE function.

=AVERAGE(B2:B100)


Expected Outcome:
A clear understanding of total, count, and mean product prices in the dataset.

📈 2. Minimum and Maximum

Objective:
Identify the range of product prices.

Tasks:

Minimum Price: Find the lowest product price using MIN.

=MIN(B2:B100)


Maximum Price: Find the highest product price using MAX.

=MAX(B2:B100)


Expected Outcome:
Determine the price spread and identify outliers or top-priced items.

⚙️ 3. IF Function – Price Range Classification

Objective:
Categorize products based on their price.

Task:
Create a new column named Price Range to classify products as:

High Price if the price ≥ $500

Standard Price otherwise

Formula:

=IF(B2>=500, "High Price", "Standard Price")


Expected Outcome:
A new column displaying product price categories for segmentation and filtering.

 4. Conditional Functions – SUMIF and COUNTIF

Objective:
Perform conditional aggregation and counting based on specific criteria.

Tasks:

Total Price for 'Electronics' Category:

=SUMIF(C2:C100, "Electronics", B2:B100)


Count of Products Priced Below $100:

=COUNTIF(B2:B100, "<100")


Expected Outcome:
Insights into category-based sales and identification of lower-priced products.

 5. Text Functions – LEFT, RIGHT, MID

Objective:
Extract meaningful parts of the Product ID using text functions.

Tasks:

Day: Extract the first 2 characters of the Product ID.

=LEFT(A2, 2)


Country Code: Extract the last 2 characters of the Product ID.

=RIGHT(A2, 2)


Month: Extract the 4th to 6th characters of the Product ID.

=MID(A2, 4, 3)


Expected Outcome:
Three new columns — Day, Month, and Country Code — that help decode or organize Product ID components.
