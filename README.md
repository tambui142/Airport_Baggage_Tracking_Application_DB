# Airport_Baggage_Tracking_Application_DB
>This database will maintain a repository of passenger information to enable passengers to create/modify and login to their account, aslo associates with airport databases. This information will be used to validate against the airline database to ensure that the proper baggage is displayed for the passenger using the application. The collected information from the airline database is used in conjunction with the Google Maps API to display a map that will provide the passenger with a relative position of their baggage to their own location.

**Prerequisites**
- Microsoft SQL Server Management Studio: (https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017)
- Aiport_Baggage_Tracking_Application_backend.sql 
- Airport_Baggage_Tracking_Application_DB_test.sql
- Airport_Baggage_Tracking_Application_Queries.sql

**Running**
- Download all 3 files. 
- In SQL Server Management Studio, Object Explorer folder, right-click on Database -> New Database... 
- Fill in Database name: "Aiport_Baggage_Tracking_Application_backend" -> OK
- Open Aiport_Baggage_Tracking_Application_backend.sql and Execute it to create database in your server.

**Pull the information from database**
```
SELECT *
FROM AIRPLANE;

SELECT *
FROM AIRPORT;

SELECT *
FROM APP_USER;

SELECT *
FROM FLIGHT;

SELECT *
FROM LOST_BAG;

SELECT *
FROM LUGGAGE;

SELECT *
FROM PASSENGER;

SELECT *
FROM RIFD_SENSOR;

SELECT *
FROM USER_FLIGHT;
```
**Authors**
>Tam Bui
