# SQLiteCloneGo

## Project Abstract

### This project is a from-scratch implementation of a minimal SQLite-compatible database engine. It explores the internals of the SQLite file format and SQL query execution, focusing on reading raw database files and evaluating basic SELECT statements — with and without indexes.

### Throughout the project, the engine evolves from simply parsing database headers to executing SQL queries using full table scans and index lookups.

- Key Features & Learning Milestones
- Read database page size from the SQLite file header
- Identify number of tables in the database
- List all table names from the schema
- Count rows in a specific table
- Read data from one or multiple columns
- Support filtering results using WHERE clauses
- Perform full-table scans to retrieve data
- Use indexes to optimize data retrieval

### I'm building this to deepen my understanding of how real-world relational databases work — including file formats, indexing, SQL parsing, and query execution mechanics.
