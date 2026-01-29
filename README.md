# task_9_star_schema

SQL Data Modeling: Building a Star Schema

📌 Project Overview

This project focuses on SQL Data Modeling by transforming a flat dataset into a Star Schema. The goal is to optimize data organization for Business Intelligence (BI) reporting and warehouse modeling.


🛠️ Tech Stack

Database: PostgreSQL/MySQL (Primary) or SQLite 
Modeling Tools: dbdiagram.io / draw.io 
Language: SQL

🏗️ Data Architecture

Following the project guidelines, I identified the core components of the schema:
Fact Table: Sales (Contains quantitative data and foreign keys) 
Dimension Tables: Customer, Product, Date, and Region (Contains descriptive attributes) 


Schema Implementation Steps:

Normalization: Identified distinct attributes to create dimension tables with primary keys.
Fact Table Construction: Built the Sales table using foreign keys that map to dimension IDs.
Optimization: Created indexes on join keys to improve query performance.
Validation: Verified record counts and checked for missing key matches to ensure data integrity.

📂 Repository Structure

task9_star_schema.sql: Full SQL script including table creation, data insertion, and indexing.
star_schema_diagram.png: Visual representation of the Star Schema.
analysis_outputs.csv: Results from analytics queries run on the schema.

📊 Sample Analytics Queries

The following queries were executed to test the schema efficiency:
Total sales revenue by Region.
Top-performing Products per Quarter.
Customer purchase frequency analysis.

🎓 Key Learnings

Understanding the difference between Fact and Dimension tables.
Benefits of the Star Schema in BI environments for simplified joins and faster aggregation.
Implementation of surrogate keys and indexing for performance tuning
