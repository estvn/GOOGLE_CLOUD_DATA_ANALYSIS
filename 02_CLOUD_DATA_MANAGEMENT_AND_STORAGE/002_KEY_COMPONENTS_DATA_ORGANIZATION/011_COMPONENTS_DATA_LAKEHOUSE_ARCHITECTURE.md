# Components of a Data Lakehouse Architecture

- Data lakehouse architecture is a comprehensive approach to managing and analyzing data
- Data lakehouse combines data lakes with a data warehouse

**Data lakehouse architecture combines:**

- Data lake: repository of data in its original form
- Data warehouse: organized sets of structured data
- Data lakehouse allows to combines structured and unstructured data

# Architecture

- A framework that defines the design of a technical solution
# Layers 

- There are five layers of a data lakehouse architecture to keep and organize all the data.

**Layers of data lakehouse architecture:**

- Ingestion
- Storage
- Metadata
- API
- Consumption

- **Think on these as the building blocks of an any data lakehouse architecture.**

# Five Layers of a Data Lakehouse Architecture

### Data source layer

- This includes structured, semi-structured and unstructured data.
### Ingestion Layer

- Brings all of these data types into de data lakehouse, either through batch or streaming processes.
### Storage Layer

- Some data goes into the data lake, and other data goes through ETL and into the data warehouse. 
- From here, our data goes to the metadata layer
### Metadata layer

- Where governance rules are applied and indexing occurs.
### API Layer

- Are used to abstract and simplify data and metadata access for the final layer.
### Consumption Layer

- Where business intelligence, visualizations and machine learning occurs.

![[Pasted image 20260916094620.png]]

---

- The primary purpose of the ingestion layer is to pull data from the data source layer, and delivery it to the storage layer.
	- In some cases, this is just using batch or streaming strategies to move data into the data lake.
	- For structured data, you may implement an ETL structure to move data into a data warehouse.
- By leveraging scalable storage, you can efficiently store structured, semi-structured and structured data in the data lakehouse.

- The metadata layer plays a mayor role in ensuring data integrity, privacy and compliance 
	- Data governance
	- Metadata management
	- Data quality
	- Security

- **One of the key strenghts of the data lakehouse is the metadata layer.**
- It catalogs all of your data, both structured and unstructured, and data in your data lake and your data warehouse.

- API Layer. Is designed to integrate APIs that process tasks faster.
	- This is also the step where you might integrate machine learning

- Consumption layer. This layer provides you tools and interfaces to extract valuable insights from the businesses data.
	- Business intelligence tools, including visualizations, dashboards and data querying interfaces, give you self-service analytics capabilities, so you can easily explore data, create reports, and gain near real-time insights.

