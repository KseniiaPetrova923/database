# Working with databases
As part of a course project, I worked with the relational database of the web application "Demo-Shopping" using MySQL.

## SELECT requests
Filtering: by category, manufacturer, name, price range.
Sorting goods: by value.
Aggregation: calculation of the sum of Samsung products, average price, number of products (#HAVING).
Using #IN (search for products), #UNION (merging data), #CASE (dynamic display of messages).
[SELECT requests](https://docs.google.com/spreadsheets/d/1UxXgwOYt5-R08q3HtyH7fjq9MSvJYXuBR-fUDGMtMnY/edit?usp=sharing)

## JOIN requests (joining data from multiple tables)
User orders: logins, order numbers, total cost (users × orders).
Order details: order numbers, product names, quantity (order_items × products).
All users (including without orders): LEFT JOIN (users × orders).
Paid orders: search for order numbers with paid products (products × order_items_paid).
Nested queries: comparison of product prices, selection of products more expensive than Samsung Active 5 (products).
[JOIN requests](https://docs.google.com/spreadsheets/d/1VE4dcVRH5QYoSK-_9e2f3vdcP7XVQ0ofTAXVfOeWcFM/edit?usp=sharing)

## Working with a non-relational database (MongoDB)
Creation of a database, collections, documents.
Requests for data analysis: find, $match, $gt, $lt.
Text search $regex, aggregation $match + $count.
[MongoDB](https://docs.google.com/spreadsheets/d/1jQ5goNZFf0DTZubtQwXbp-oKJHsrhX5AT-rruhuVztw/edit?usp=sharing)
