Project Overview
The Retailer Database Management System aims to centralize and optimize data management for retail businesses by integrating various data sources, such as product catalogs and customer interactions. This system enhances decision-making and operational efficiency through reliable data analysis.

Problem Definition
Retail businesses face significant challenges in managing and utilizing the vast amounts of data generated from various sources such as product catalogs, customer interactions, and sales transactions. The primary problem is the lack of a centralized, efficient, and reliable system to store, integrate, and analyze this data to support informed decision-making and optimize business operations.

Database Description
1.Customers:

Attributes: CNUMBER, CLNAME, CFNAME, ADDRESS, PHONE, STATE, CITY.
Stores details of customers who place orders, including their contact details and location.

2.Vendors:

Attributes: VENDORID, FNAME, LNAME, EMAIL, OFFICECODE.
Manages information about vendors from whom products are sourced, including contact information.

3.Offices:

Attributes: OFFICECODE, CITY, PHONENO, STATE, COUNTRY.
Contains information about different office locations relevant for shipping and vendor management.

4.Orders:

Attributes: ORDERNO, ORDERDATE, DELIVERYDATE, SHIPPINGDATE, STATUS, CNUMBER.
Represents customer orders, tracking date details and status, linking back to the customer.

5.Order Details:

Attributes: ORDERNO, PRODUCTID, QUANTITY, PRICEEACH.
Captures specifics of each product within an order, including product identifier and quantity.

6.Products:

Attributes: PRODUCTID, PRODUCTNAME, BUYPRICE, MSRP, VENDORID, CATEGORY.
Stores information about products available for purchase.

7.Categories:

Attributes: CATEGORY, TEXT DESCRIPTION.
Organizes products into different categories for better management.

8.Payments:

Attributes: PID, AMOUNT, DATE, ORDERNO.
Records payment transactions related to customer orders, including amount and transaction date.

"The project utilizes Informatica PowerCenter, SQL to effectively manage and analyze retail data.
