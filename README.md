# SSISAssignment
SSIS package for importing and exporting data and also creating staging tables

Part1_ExportingData.dtsx - This file is an SSIS package for exporting data from HumanResources.Employee table in Adventure Works database to a flat file source(can be .csv, .txt or an .xls etc. file)

Part2_StagingTableScript - SQL script for creating the Staging table which will be used for importing data from a flat file source.

Part3_Importingdata.dtsx - This is an SSIS package for importing data from a flat file data source to a database table in SQL Server management studio. Importing the data from the data file exported in part 1.

Process Document which has listed all the detailed steps followed for creating the SSIS packages and the staging table.
