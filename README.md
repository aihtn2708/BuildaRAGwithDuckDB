# Build a RAG with DuckDB
# What is DuckDB?

DuckDB is a modern, high-performance, in-memory analytical database management system (DBMS) designed to support complex analytical queries. It is a relational (table-oriented) DBMS that supports the Structured Query Language (SQL). DuckDB combines the simplicity and ease of use of SQLite with the high-performance capabilities required for analytical workloads, making it an excellent choice for data scientists and analysts

# Its key advantages include:
- High Performance: DuckDB employs a columnar-vectorized query execution engine, enabling rapid analytical queries by processing data in large batches. This design ensures efficient CPU cache utilization, resulting in performance that often surpasses traditional OLAP databases. 
- Ease of Use: As an embedded database, DuckDB integrates seamlessly into applications without the need for a separate server setup. It has no external dependencies, simplifying installation and deployment across various platforms. 
- SQL Compatibility: DuckDB supports a rich SQL dialect, including complex queries, aggregations, and window functions. This compatibility allows users familiar with SQL to perform advanced data analyses without learning new query languages. 
- Extensibility: The system is designed to be extensible, allowing third-party features such as new data types, functions, file formats, and SQL syntax to be added. This flexibility enables customization to meet specific analytical needs. 
- Cross-Platform Support: DuckDB operates across multiple operating systems, including Linux, macOS, and Windows, and supports various hardware architectures. It offers client APIs for major programming languages, facilitating integration into diverse development environments. 
- Open Source and Free: Licensed under the permissive MIT License, DuckDB is free to use and open-source, encouraging community contributions and rapid development. 

**_Here’s an example of using Duckdb to retrieve data with python:_
**
[duckdb_demo.ipynb](https://github.com/aihtn2708/BuildaRAGwithDuckDB/blob/2a8d75963b5b0e6f75eecb1eba45aac17e9c04ba/duckdb_demo.ipynb)

## Comparing DuckDB, SQLite and Pandas for executing analytical queries on a dataset: 
[comparing_DuckDB_vs_SQLlite_vs_Pandas.ipynb](https://github.com/aihtn2708/BuildaRAGwithDuckDB/blob/8add7dc9ce3a2ea8b2d435375635cc124f7fa390/comparing_DuckDB_vs_SQLlite_vs_Pandas.ipynb)
