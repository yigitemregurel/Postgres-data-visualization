# Postgres-data-visualization
Project to visualize contents by connecting with python via postgreSQL
This code snippet involves connecting to a database, executing SQL queries, processing data, and ultimately visualizing it.

Necessary libraries and modules are imported.
Information for the database connection is set, and a connection is established to a PostgreSQL database.
Data is retrieved from specific tables using two separate SQL queries.
The database schema is inspected using SQLAlchemy.
Data is fetched and subjected to certain operations, particularly involving filtering on 'ASSET' and 'SOURCE' columns.
A sample DataFrame is created, the values of a column are counted to calculate frequencies, and these frequencies are visualized using a bar chart.
