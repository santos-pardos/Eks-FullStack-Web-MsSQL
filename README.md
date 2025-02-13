## EKS + App + API + MsSQL  (Docker)
### 

SQL Server Management Studio (SSMS)
```
https://learn.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
```
DBeaver Community 24.3.4  (Portable: Zip file)
```
https://dbeaver.io/download/
```

## Tools
```
docker run --name cloudbeaver --rm -ti -d -p 8080:8978 -v /opt/cloudbeaver/workspace dbeaver/cloudbeaver:latest
```
```
docker run -it  nicolaka/netshoot sh
```
```
kubectl run tmp-shell --rm -i --tty --image nicolaka/netshoot
```
