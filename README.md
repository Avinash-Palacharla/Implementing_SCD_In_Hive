# Implementing_scd_in_hive
The project is to get the file and load the data to RDBMS initially and update the table whenever the changes happend in the data.
Steps for Implementing:
1. Getting the source files and dump in the Edge Node.
2. Load the data from MySQL to HDFS.
3. Import the data to hive managed table from HDFS.
4. Partition and import the data from the managed table to External table and implement the scd logic from the day 2
5. Create an intermediate table to perform data reconciliation
6. Export the filtered data again to the MySQL table.
