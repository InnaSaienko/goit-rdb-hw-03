# GoIT RDB HW-03 - SQL Queries

This project contains SQL queries and their execution results for homework assignment 03. The project demonstrates various SQL operations on the `products` and `shippers` tables.

## Project Structure

- `homework_queries.txt` - Contains all SQL queries for the 5 tasks
- `images/` - Contains screenshots of query results from MySQL Workbench

## Tasks and Results

### Task 1: Select Data from Tables
- **Query**: Select all columns from `products` table and `name`, `phone` from `shippers` table
- **Files**:
  - `p1_select_all_products.png` - Result of `SELECT * FROM products`
  - `p1_select_name_phone_shippers.png` - Result of `SELECT name, phone FROM shippers`

### Task 2: Aggregate Functions
- **Query**: Find average, maximum, and minimum price values from `products` table
- **File**: `p2_avg_min_max_prices_products.png` - Result of aggregate functions

### Task 3: Unique Values with Sorting and Limiting
- **Query**: Select unique `category_id` and `price` from `products`, ordered by price descending, limited to 10 rows
- **File**: `p3_find_unique.png` - Result of distinct selection with sorting and limit

### Task 4: Count with Condition
- **Query**: Count products with price between 20 and 100
- **File**: `p4_count_products_in_range.png` - Result of conditional count

### Task 5: Grouping and Aggregation
- **Query**: Count products and calculate average price grouped by `supplier_id`
- **File**: `p5_calculate_avg_price_by_supplier.png` - Result of grouped aggregation

## SQL Operations Demonstrated

- Basic SELECT queries
- Aggregate functions (AVG, MAX, MIN, COUNT)
- DISTINCT for unique values
- ORDER BY for sorting
- LIMIT for result restriction
- WHERE for conditional filtering
- GROUP BY for data grouping
