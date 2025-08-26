# Building-and-Analyzing-Social-Media-Data-in-PostgreSQL
Instagram-style data model built in PostgreSQL with schema design, sample data, and advanced SQL queries. Includes analytics examples using joins, aggregates, window functions, CTEs, case statements, and date handling to explore likes, comments, followers, and posts.

## Repository Contents
- **`instagram_data_model.drawio`** – ER diagram of the schema  
- **`schema.sql`** – Table Creation based on ER diagram
- **`values.sql`** – Table values (Users, Posts, Comments, Likes, Followers)  
- **`queries.sql`** – Example SQL queries for analytics and practice  

---

## Features
- Relational schema design with primary/foreign keys  
- Queries covering:
  - Filtering with `WHERE`, `ORDER BY`  
  - Aggregations with `GROUP BY`, `HAVING`  
  - Functions: `COUNT`, `SUM`, `AVG`  
  - Subqueries and nested queries  
  - Window functions (`RANK`, `SUM OVER`)  
  - Common Table Expressions (CTEs)  
  - `CASE` statements for categorization  
  - Date casting and filtering  

---

## Getting Started
1. Create a PostgreSQL database.  
2. Run the schema file:
   ```bash
   psql -U <user> -d <dbname> -f schema.sql
3. Load or insert sample data.
4. Explore queries:
   ```bash
   psql -U <user> -d <dbname> -f queries.sql

