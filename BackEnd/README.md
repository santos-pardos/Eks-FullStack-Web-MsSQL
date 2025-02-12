## Links
```
http://public-ip:8080/index.html
https://bravedeveloper.com/2022/04/18/desplegando-una-web-api-hecha-en-net-core-y-sql-server-mediante-docker-compose/

docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=A&VeryComplex123Password" \
   -p 1433:1433 --name sql-server2022 --hostname sql \
   -d \
   mcr.microsoft.com/mssql/server:2022-latest

docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=A&VeryComplex123Password" -p 1433:1433 --name sql-server2022 --hostname sql -d santospardos/sanvalero:mssql-2022

docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Aa123456!" \
   -p 1433:1433 --name sql-server --hostname sql \
   -d \
   mcr.microsoft.com/mssql/server:2019-latest
```
