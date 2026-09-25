# Methods for Partitioning Tables

# Partitioned Table

- A large table that is divided into smaller segments, or partitions, to improve query performance and control costs by reducing the amount of data query needs to process.
- It improves queries performance, and it control costs.

# When to partition a table

- To improve query performance by only scanning a specific section of a table.
- If a table operation exceeds the expected volume of data, the data professional needs to limit it to specific partition column values. 
- To set a partition expiration time to automatically delete entire partitions after a specific time period.
- To load data to a specific partition without affecting other partitions in the table.
- To delete specific partitions without scanning the entire table

# Three Ways to Partition a Table 

- Inter-range
- Time-unit column
- Ingestion time partitioning

### To create an inter-range partitioned table, provide

- The partitioning column
- The staring value for range partitioning
- The ending value for range partitioning
- Interval of each range within the partition

### Time-unit column

- With the time-unit column partitioning, a data professional can partition a table based on a DATE, TIMESTAMP or DATETIME column

### Ingestion Time Partitioning

- With ingestion time partitioning, BigQuery will automatically assign table rows to partitions based on the time when the data is ingested, or imported, by BigQuery. 

# Clustered Table

- A table which column order is defined by the user using clustered columns. 

# Clustered Column 

- A user-defined table property that arranges storage blocks based on the values within their columns

- The order of the values in a clustered column determines the order in which the rows of the table are stored in memory and on disk. 

# Benefits of Clustering

- Flexible and adaptable 
- Great for columns with tons of unique values
- Keeps sorting criteria in context 
- Improves query performance and costs 
