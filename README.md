# Retail-Store-Order-Analysis-SQL
\
Database: Orders Database (built as a part of SQL file before executing queries) \
Language Used: SQL \
IDE used: MySQL \
\
Problem Statement: To write SQL queries to fetch the required information stated as below. \
\
Problem Type: Data fetching. \
\
Problems: 
1. Write a query to display customer full name with their title (Mr/Ms), both first name and last name are in upper case, customer email id, customer creation date and display customer’s category after applying below categorization rules: i) IF customer creation date Year <2005 Then Category A ii) IF customer creation date Year >=2005 and <2011 Then Category B iii)IF customer creation date Year>= 2011 Then Category C 
2. Write a query to display the following information for the products, which have not been sold: product_id, product_desc, product_quantity_avail, product_price, inventory values (product_quantity_avail*product_price), New_Price after applying discount as per below criteria. Sort the output with respect to decreasing value of Inventory_Value. i) IF Product Price > 20,000 then apply 20% discount ii) IF Product Price > 10,000 then apply 15% discount iii) IF Product Price =< 10,000 then apply 10% discount 
3. Write a query to display Product_class_code, Product_class_description, Count of Product type in each productclass, Inventory Value (p.product_quantity_avail*p.product_price). Information should be displayed for only those product_class_code which have more than 1,00,000. Inventory Value. Sort the output with respect to decreasing value of Inventory_Value. 
4. Write a query to display customer_id, full name, customer_email, customer_phone and country of customers who have cancelled all the orders placed by them  
5. Write a query to display Shipper name, City to which it is catering, num of customer catered by the shipper in the city and number of consignments delivered to that city for Shipper DHL 
6. Write a query to display product_id, product_desc, product_quantity_avail, quantity sold and show inventory Status of products as below as per below condition: a. For Electronics and Computer categories, if sales till date is Zero then show 'No Sales in past, give discount to reduce inventory', if inventory quantity is less than 10% of quantity sold,show 'Low inventory, need to add inventory', if inventory quantity is less than 50% of quantity sold, show 'Medium inventory, need to add some inventory', if inventory quantity is more or equal to 50% of quantity sold, show 'Sufficient inventory' b. For Mobiles and Watches categories, if sales till date is Zero then show 'No Sales in past, give discount to reduce inventory', if inventory quantity is less than 20% of quantity sold, show 'Low inventory, need to add inventory', if inventory quantity is less than 60% of quantity sold, show 'Medium inventory, need to add some inventory', if inventory quantity is more or equal to 60% of quantity sold, show 'Sufficient inventory' c. Rest of the categories, if sales till date is Zero then show 'No Sales in past, give discount to reduce inventory', if inventory quantity is less than 30% of quantity sold, show 'Low inventory, need to add inventory', if inventory quantity is less than 70% of quantity sold, show 'Medium inventory, need to add some inventory', if inventory quantity is more or equal to 70% of quantity sold, show 'Sufficient inventory' 
7. Write a query to display order_id and volume of the biggest order (in terms of volume) that can fit in carton id 10 
8. Write a query to display customer id, customer full name, total quantity and total value (quantity*price) shipped where mode of payment is Cash and customer last name starts with 'G' 
9. Write a query to display product_id, product_desc and total quantity of products which are sold together with product id 201 and are not shipped to city Bangalore and New Delhi. Display the output in descending order with respect to the tot_qty. 
10. Write a query to display the order_id,customer_id and customer fullname, total quantity of products shipped for order ids which are even and shipped to address where pincode is not starting with "5" 
