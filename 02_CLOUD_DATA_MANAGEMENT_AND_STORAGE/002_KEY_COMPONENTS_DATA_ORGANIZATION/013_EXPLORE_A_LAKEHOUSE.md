# Creating an external table who consumes data from an external origin

![[Pasted image 20260916103222.png]]

![[Pasted image 20260916103444.png]]

![[Pasted image 20260916103618.png]]

- Cuando creas una tabla externa, los datos se almacenan en la ubicación de origen en Cloud Storage, pero se pueden realizar consultas allí como en cualquier tabla de BigQuery estándar.
- El prefijo gs:// en la columna URI de origen indica que los datos se almacenan en Cloud Storage.

![[Pasted image 20260916103841.png]]

# Joining data stored in BigQuery and Cloud Storage

![[Pasted image 20260916104211.png]]

![[Pasted image 20260916104301.png]]

# Importing data via BigQuery console

- Importing a csv file data into a native table in BigQuery
- Where a CSV file stored in Cloud Storage

![[Pasted image 20260916104729.png]]

# Conclusion

- We had practiced two ways to querying external data with local data
- Creating a table linked to a parquet file stored in another service (Cloud Storage), and creating and loading a table with an external csv file stored in another service.

- The external table stores the data in the Cloud Storage service, but treat the data like is in the local table in the BigQuery service.
