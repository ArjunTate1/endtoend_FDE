# Ingesting data

- download the data from "D:\Major_main\data\source\data.txt"   
- create and ec2 instance 
- Spin up the Legacy MSSQL Server
'''
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=FdeEnterprisePass123!" -p 1433:1433 --name legacy-mssql -d mcr.microsoft.com/mssql/server:2022-latest
'''

- install the req > pip install -r requirements.txt