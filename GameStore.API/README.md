# Game Store API

## Starting SQL Server
```powershell
$sa_password="[yourPassword(!)Here123]"

docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=$sa_password" -p 1433:1433 -v mssql-volume:/var/opt/mssql -d --rm --name mssql mcr.microsoft.com/mssql/server:2022-latest
```