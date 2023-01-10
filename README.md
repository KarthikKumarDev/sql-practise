# sql-practise
This is a topic-wise collection of Sql Queries in a python notebook format, along with the seed data.


## Getting Started

1. Using Docker, run the following command with your desired password replaced.

    `docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=yourStrong(!)Password" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest`

   else please install Sql Server directly and setup Username and Password

2. Download Azure Datastudio and connect to the Sql Server instance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Download link: https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver16
  - userid = 'sa'
  - password = "above set password"

3. Open the `Init StoreDB.ipynotebook` and execute it completely to setup the Database and tables.
