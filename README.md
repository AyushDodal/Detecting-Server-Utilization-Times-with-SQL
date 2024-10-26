# Detecting-Server-Utilization-Times-with-SQL

This project monitors server uptimes & downtimes and can be used to notify administrators if a server exceeds a predetermined downtime.


## Features

1. Calculates downtime between start and stop events.

2. Stores alerts for downtime exceeding a threshold.

3. Uses MySQL stored procedures and event scheduler for automation.


## Usage

1. If you already have a server on MySQL,
     a. Create the table "downtime_alerts"
     b. Create & run the stored procedure
     c. Execute the "Schedule Run" code

2. If you don't have an existing server setup, create a schema and run the code for create and insert into "server_utilization" table. Then follow the sub-steps in 1.
