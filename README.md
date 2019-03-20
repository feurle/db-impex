# db-impex
The DB Impex application is a tool to import and export database tables into a structured file.


## Prerequisites
The following modules are needed for this application:

### DatabaseSchemaReader (version 2.7.1)
Read database metadata (from SqlServer/Oracle/MySql/SQLite/PostgreSql/DB2 etc) into one simple model
https://github.com/martinjw/dbschemareader

### Csv Package (version 1.0.39)
Simple csv library
https://www.nuget.org/packages/Csv/

### Dapper Package (version 1.60.1)
A high performance Micro-ORM supporting SQL Server, MySQL, Sqlite, SqlCE, Firebird etc..
https://www.nuget.org/packages/Dapper/


### Database Package
We use e.g. MySql.Data package but any other Database SQL package can be used.


## Setup dev Environment 
In a console add the following dependencies:
```
# dotnet add package DatabaseSchemaReader --version 2.7.1
# dotnet add package Csv --version 1.0.39
# dotnet add package Dapper --version 1.60.1
# dotnet add package MySql.Data --version 8.0.15
```