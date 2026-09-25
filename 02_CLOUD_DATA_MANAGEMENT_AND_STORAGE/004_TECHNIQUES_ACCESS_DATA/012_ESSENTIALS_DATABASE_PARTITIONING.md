# Essentials of Data Base Partitioning

# Database Partitioning

- Is the process of dividing data into separate data segments, or partitions, that can be managed and accessed separately
- The most important benefits of the data partitioning is the improved scalability, availability and performance. 

Database partitioning helps improve:

- Scalability
- Data availability
- Performance

# Three types of partitioning

### Horizontal Partitioning 

- A process of dividing data into separated segments in which each partition, or shard, is its own data storage, but all shards follow the same organizational layout.
- Each shard keeps a unique piece of all the data 

### Vertical Partitioning

- A process of dividing data into separate segments in which each partition maintains a unique piece of the fields for items in the data store.
- These fields are divided based on how often they are used
- Fields that are used often might be put into the vertical partition, and fields that aren't accessed as frequently might be placed in another.

### Functional Partitioning

- A process for dividing data into separate segments in which data is grouped based on how it's used in different parts of the database system

# Considerations when incorporating partitioning in an active system

- Change how data is accessed in the system
- Require migration of large amounts of existing data 
- Keep using the system during data migration

# Considerations when partitioning data

- Parallel processing
- Application requirements
- Users must rebalance partitions to address uneven distribution of traffic when there's a surge

























