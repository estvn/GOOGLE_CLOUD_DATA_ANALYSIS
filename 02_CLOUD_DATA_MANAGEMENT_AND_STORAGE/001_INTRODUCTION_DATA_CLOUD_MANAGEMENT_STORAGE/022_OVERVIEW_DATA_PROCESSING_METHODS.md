# Overview of Data Processing Methods

- Batch data, where the information is collected, processed, and then delivered in regular, steady intervals
- **Batch processing enables data professionals to collect large volumes of data over a period of time, and the process it all at once**

- The other road represents fast-paced, streaming data.
- **Streaming data is processed right when it's received, like the constant flow of the traffic**

# Batch Processing

- Handling large volumes of data efficiently
- Perform complex analytical calculations 
- Generate insights for long-term planning and decision making

- A method of collecting large volumes of data over a period time, then processing it all at once.
- Batch processing uses various data sources and each has their own characteristics and advantages
- The most common formats include CSV, JSON, and Parquet, a columnar storage format for quick compression and improved query performance

- The frequency of batch data processing varies based on the specific use case, ranging from hourly, to daily, to weekly, and beyond.

# Streaming Data Processing

- Timely insights and continuous monitoring
- Detect anomalies, trends, or critical events in near real time
- Alert systems and triggers actions
- Handling streaming data is more complex and expensive

- A method of processing data as it's received
- It might come from a device in the internet of things, or IoT, a social media feed, and more
- **The frequency of streaming data processing is typically in real-time or near-real-time**
- With streaming data you'll encounter file formats and systems typically designed to handle velocity and agility.

- One format is Avro, which is a format that helps programs understand and share data using schemas and seamless handling of data structure changes.
- Apache Kafka, an open-source distributed event streaming platform that allows you to publish, subscribe, store, and process streams of records. 
	- This is particularly useful for building data pipelines and applications that require handling large amounts of data.
 - And finally, there's an Apache NiFi, an open-source data integration and data flow automation tool which is particularly useful for collecting, transforming, and moving large volumes of data 

- Both batch and streaming data processing have advantages and disadvantages, depending on the use case. 

# Selecting the Appropiate Data Format

- Data requirements
- Data characteristics
- Processing speed
- Latency constraints
- Integration capabilities
- 