# goit-rdb-hw-05 Relationship Databases Topic V Nested requests. Code reuse

-- Task 1. SQL query that displays the `order_details` table and the `customer_id` field from the `orders` table, respectively, for each record field from the `order_details` table

![screenshot](./assets/Screenshot%20rdb-hw-05-test-5.1.jpg)

-- Task 2. SQL query that displays the `order_details` table. The results are filtered so that the corresponding record from the `orders` table fulfils the condition `shipper_id=3`. A nested query in the `WHERE` clause used

![screenshot](./assets/Screenshot%20rdb-hw-05-test-5.2.jpg)

-- Task 3. SQL query nested in the `FROM' statement, which selects rows with the `quantity>10' condition from the `order_details` table.

![screenshot](./assets/Screenshot%20rdb-hw-05-test-5.3.jpg)

-- Task 4: Solution for task 3 using the `WITH` statement to create the temporary table `temp`

![screenshot](./assets/Screenshot%20rdb-hw-05-test-5.4.jpg)

-- Task 5: This function has two parameters that divide the first parameter by the second. Both the parameters and the return value are of `FLOAT` type. The `DROP FUNCTION IF EXISTS` construct applied to the `quantity` attribute of the `order_details` table

![screenshot](./assets/Screenshot%20rdb-hw-05-test-5.5.jpg)

[text](sql_code.txt)
