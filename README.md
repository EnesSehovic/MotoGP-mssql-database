# MotoGP-mssql-database

Data is derived from https://observablehq.com/@piratus/motogp-results-database

Script for installing the database in SQL server is generated using https://sqlitebrowser.org/

However that script doesn't work in my version of SQL Server (2012):

- DB is not created by running the script
- no character limits on column datatypes
- composite primary key without the UNIQUE constraint (table 'countries')
- missing data (table 'stage_names' short name 'DOH' and 'ALG')

I used:
  Microsoft SQL Server 2012 - 11.0.5058.0 (X64) 
	May 14 2014 18:34:29 
	Copyright (c) Microsoft Corporation
	Express Edition (64-bit) on Windows NT 6.1 <X64> (Build 7601: Service Pack 1)

