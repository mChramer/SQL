# SQL
My first assignment for school 2022.10.06

## Here you can read the assignments despriction

- Problem description:
GamersParadise AB is a growing hardware store specialized in gaming equipment.
Popularity and sales are skyrocketing and the traditional way to handle the business is
becoming obsolete. They hired you to modernize the store's system.
From the brands they want to know the name, which is guaranteed to be at most 65
characters long.
From the customers, they want to know, the name, address, email and phone number (max
24 chars long)
From the products, they want to know the name, the brand, a rich html1 description (up to
16MB) and the price (unsigned 10 digits decimal number with 2 decimal positions). One
product is manufactured by one brand and one brand manufactures many products.
Products can be grouped into categories. From categories they want to know the name (up
to 64 characters long). One category contains many products, and one product may belong
to many categories.
From orders, they want to know the customer who issued it and the purchase_date (the
date the order was issued).
One order may contain many order_rows, from which they want to know the product and
the quantity. One order_row belongs to only one order.

- What to do:
1- Create the database schema
2- Every entity (table) has a primary key and must be called id
3- Foreign key constraints are enforced on each relationship
4- Create the following view:
a. orders_with_total which adds a column amount which is the sum of the
amounts of the order_rows in each order.
