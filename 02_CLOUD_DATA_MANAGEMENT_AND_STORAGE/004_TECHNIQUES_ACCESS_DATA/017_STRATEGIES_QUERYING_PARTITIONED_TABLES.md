# Strategies for Querying Partitioned Tables

# Partitioning Pruning

- The process of eliminating unnecessary or irrelevant data from consideration when running a query.
- The data professional runs a query using a qualifying filter on the value of the partitioning column.
- This tells BigQuery to scan the partitions that match the filter and skip the rest

# Query a time-unit column-partitioned table

- To remove unnecessary partitions when querying a table partitioned by a time-unit column, filter based on the partition column

Example of query partitioned table:

```
SELECT * FROM dataset.table 
WHERE transaction_table >= '2016-01-01'
```

- The example query prunes dates by excluding any before January 1, 2016.

# Query a ingestion-time partitioned table

 - This column holds the UTC time when each row was imported, rounded, to the nearest partition boundary, such as hourly or daily, represented as a timestamp value

![[Pasted image 20260924231449.png]]

```
SELECT
	column
FROM
	dataset.table
WHERE
	_PARTITIONTIME BETWEEN TIMESTAMP('2026-01-01') AND TIMESTAMP('2026-01-02')
```

# Query an integer-range partitioned table

- To prune partitions when you query an integer-range partitioned table, included a filter based on the integer partitioning column

```
SELECT * FROM dataset.table 
WHERE customer_id BETWEEN 30 AND 50;
```



























