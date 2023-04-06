# Windfarm Data Lake

## Steps:

1. Creating a data stream flow on Kinesis Data Streams.
2. Developing Python applications (ipynb files) to perform data streaming.
3. Creating a delivery stream through Kinesis Data Firehose and creating a destination bucket in S3.
4. Running applications to populate the S3 bucket with generated data.
5. Creating an access function in IAM.
6. Creating a database in AWS Glue.
7. Configuring the Crawler to transform JSON file data generated by applications into tables.
8. Creating a new bucket to receive the tables.
9. Creating a job in Glue Job.
10. Configuring the Job. Selecting AWS Glue Data Catalog, selecting the database and table. Transforming data and schema.
11. Creating the target to be the bucket created in S3, selecting the Parquet format and Snappy compression.
12. Running the Job.
13. Configuring Athena to send queries to a new S3 bucket and select the database in the editor.
14. Querying data with Athena.

### Architecture

![image](https://user-images.githubusercontent.com/124625776/229630394-cbdd66bd-4e18-41ee-819d-cb050298c780.png)


