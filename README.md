# MotoGP-mssql-database

Data is derived from https://observablehq.com/@piratus/motogp-results-database

Script for installing the database in SQL server is generated using https://sqlitebrowser.org/

However that script doesn't work in my version of SQL Server (2012):

- DB is not created by running the script
- no character limits on column datatypes
- composite primary key without the UNIQUE constraint (table 'countries')
- missing data (table 'stage_names' short name 'DOH' and 'ALG')
