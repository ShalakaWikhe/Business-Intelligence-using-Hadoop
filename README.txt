Project Title :- Insightful Retail data analytics of a bicycle store data using big data approach. 
----------------
Project Objective :- To generate OLAP cubes using Apache kylin on Hadoop platform. Further creating dashboards using BI tool, Qlikview to help take appropriate decisions.
----------------
Project Requirements :- 
Microsoft SQL Server 
Apache SQOOP
Cloudera Hadoop
Apache hive
Apache Kylin
HBase
JDBC ODBC drivers
Qlikview 
----------------
Dataset :- AdventureWorks DataWarehouse
---------------
1) Load adventureworksDW on SQL, transferring it onto Hive using sqoop by command:-
   sqoop import --connect jdbc:mysql://quickstart.cloudera/database_name --password cloudera --m 1 --hive-import --driver com.mysql.jdbc.Driver
2) Load all tables from hive onto Kylin and create olap cubes according to specific requiremnents.
3) Connect Qlikview and hive using jdbc driver nd create dashboards.

