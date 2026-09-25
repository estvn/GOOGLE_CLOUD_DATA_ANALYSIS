# Introduction to BigQuery Sharing

- Analytics hub is build on a publish-and-subscribe model of BigQuery's datasets
- This means data producers, or publishers make their dataset available to data consumers or subscribers.
- The separation of compute and storage enables data producers to share data with many users without having to duplicate it.

## Data Publishers Workflow

- A data publisher first identifies the datasets they want to share in BigQuery
- Creates a listing of datasets in Analytic Hub
- Manages use of shared datasets 

## Data Subscribers Workflow

- Browses Analytics Hub to find a dataset
- Subscribes to a dataset
- Receives a read-only link to dataset in the subscriber's BigQuery project
- Queries the data

# Shared and Linked Datasets

- **Shared dataset** are collections of data, tables and views 
- Data subscribers receive a version of a dataset called a **linked dataset**

## Data listings and exchanges

- Each piece of data is uniquely identified as a listing
- These listings include a link to the dataset, a brief description, and related documentation
- Data exchanges can either be open to every user or restricted to certain users.

# Types of Users

### Publisher

- Generate income with instant data sharing
- Share data without creating duplicates
- Build catalog of data sources ready for analysis
- Create detailed permissions
- Manage subscriptions
### Subscriber

- Merge shared data with existing data
- Use the Built-in tools of BigQuery
### Viewer

- Browse through datasets
### Administrator

- Enable data sharing
- Give access permissions to both data publishers and subscribers

# Analytics Hub Limitations

- For a shared dataset that's encrypted, susbcribers won't have the cloud key needed to access the dataset. 
- Limit of 1000 linked datasets to a shared dataset
- A dataset with unsupported resources can't be shared
