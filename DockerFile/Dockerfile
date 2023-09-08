# Use the official SQL Server 2019 image as base
FROM mcr.microsoft.com/mssql/server:2019-latest

# Set environment variables for SQL Server
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=Dev@123Sql

# Expose the SQL Server port
EXPOSE 1433

# Start SQL Server
CMD [ "/opt/mssql/bin/sqlservr" ]
