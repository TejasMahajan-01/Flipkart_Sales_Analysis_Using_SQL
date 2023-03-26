<blockquote> <h3> Project Title </h3> </blockquote>
<h1 style = 'color:#0C73D1;' >  Flipkart Sales Analysis Using SQL </h1>
<h3> Summary: </h3>
In this portfolio project, I conducted an analysis of Flipkart sales data using SQL queries and visualized the results using matplotlib and seaborn. The analysis focused on exploring the distribution of products across main and sub-categories, identifying the most expensive and best-selling products, and examining the product rating and pricing trends. The data included information such as the product's title, category, rating, selling price, maximum retail price, seller name and rating, description, and highlights. By visualizing the data, I was able to gain insights into the sales patterns and product trends on Flipkart.  The project showcases the power of SQL for data analysis and the importance of data visualization for communicating insights effectively.

## Insights & Inferences: 
1. Sales table has total 12041 rows and total 11 columns.
2. There are null values in few columnss like product name, product rating, selling price, mrp, seller name, seller rating, description and highlights column.
3. Description have the highest null values about to 7020 as compared to total 12041 values, followed by 5481 null values in highlights column.
4. Most unique values are around 10478 in product name, followed by highlights, description and seller name.
5. The data includes 6 main product categories, 76 sub categories and 300 product types and 10478 products with 3317 unique sellers and 1816 different price variations.
6. Most of the units sold are in the women's clothing category at around 2422, followed by men's clothing and baby & kids.
7. Most of the units sold are in the footwear category at around 680, followed by baby care, accessories and ethnic wear.
8. Most of the products sold fall under the innerwear category of about 160 products, followed by shorts and T-shirts.
9. Most products sold fall in the rating range of 4.0, around 1697, followed by 4.1 around 1692, then product rating 4.2 and 4.3.
10. Product ratings range from 1.0 to 5.0 stars.
11. Most products sold have a seller rating of 4.8 around 1565, followed by seller ratings of 4.7 and 4.7.
12. Data includes 21 unique categories of seller ratings.
13. Seller ratings range from 3.0 to 5.0 stars.
14. Most units sold are priced at Rs.299.0 approximately 498 units, followed by products priced at Rs.499.0 and Rs.399.0.
15. Total 1754 products have been sold which are below Rs.50000. And only 62 products were sold above the selling price of Rs.50000.
16. Only one unit is sold for the product whose minimum price is Rs.10.0 and one unit is sold whose price is Rs.300490.
17. There are 1816 unique price amounts for different products in the data.
18. Selling price ranges from Rs.10.0 to Rs.300490.
19. Most of the products sold come under MRP of Rs. 999.0 approximately for 1429 units, followed by Rs. 1999.
20. Total 1332 products are sold which come under MRP of Rs.50000 and only 81 products are sold above MRP of Rs.50000.
21. In MRP column there are only two units of the product which has minimum price of Rs.65.0 have been sold and one unit has been sold which has minimum price of Rs.1174131.0.
22. Data includes 1414 unique MRP amounts for various products.
23. MRP ranges from Rs.65.0 to Rs.1174131.0.
24. The main category of women's apparel has the highest average discount of around 61.57% on most products, followed by discounts on men's apparel and baby and children's products.
25. In the main product category, Average discount ranges from 46.53 to 61.57%.
26. Most of the products which fall under the sub category party dresses have an average discount of around 78.41%, followed by kids sunglasses and kids watches.
27. In the sub category of product, Average discount ranges from 17.39 to 78.41%.
28. Most of the products which fall under product type artificial jewelery have an average discount of around 85.89%, followed by track pants and sarees.
29. In the product type, Average discount ranges from 68.86 to 85.89%.
30. In Main Category, Electronics have the most expensive product of Rs. 300490 followed by Women's wear and Sports, Books and More.
31. In Main Category, Most Expensive Product ranges from Rs. 16495 to Rs. 300490.
32. In Sub Category, The most expensive product is Laptop Rs. 300490 are followed by Camera Accessories and Desktop PCs.
33. In Sub Category, Most expensive products ranging from Rs. 16495 to Rs. 300490.
34. In the top 50 most expensive product, Gaming Laptop priced at Rs. 300490, followed by Lens and Desktop PC. Top 50 most expensive products ranging from Rs. 16495 to Rs. 300490.
35. The most expensive product is Rs.300490 from seller PETILANTE Online, followed by Retailnet and Omnitechretail.
36. The most expensive product ranges from Rs.21599 to Rs.300490 for the top 50 sellers.
37. Seller RetailNet has the highest sales volume of 601, followed by SuperComNet, MythangloryRetail and HSAtlastradeFashion. Sales volume ranges from 22 to 601.
38. Most seller are in the category of product rating of 4.0 stars about 840, followed by 4.1, 3.9 and 4.2 stars. Number of unique seller ranges from 3 to 840.
39. In the main category of product, Women's Wear has the most unique sellers about 822, followed by Home and Furniture and Baby and Kids. Total unique seller ranges from 310 to 822.
40. In the product sub-category, ethnic wear has the most unique sellers around 227, followed by toys and footwear. Total unique sellers range from 2 to 227.

## libraries used
* __mysql.connector__ - to connect mysql database to python for working with jupyter notebook
* __pandas__ - for displaying data in tabular format
* __matplotlib__ and __seaborn__ - for visualizing the data
* __warnings__ - to ignore warnings displayed in Jupyter Notebook

## PowerBi Dashboard
![flipkart_sales_analysis_dashboard_page-0001](https://user-images.githubusercontent.com/105104702/227780805-ddc7404b-0ced-4c33-bd36-27359b3a5be1.jpg)
