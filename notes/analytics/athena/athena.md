# Athena
Start querying data instantly. Get results in seconds. Pay only for the queries you run.

[Full docs here](https://aws.amazon.com/athena/?c=1&pt=1)

Athena is a serverless service built on Presto to build and execute SQL queries against files stored in Amazon S3. Athena removes the need for ETL (Extract Transforma Load) jobs to prep the data for analysis. Athena is out-of-the-box integrated with AWS Glue Data Catalog, allowing you to create a unified metadata repository across various services, crawl data sources to discover schemas and populate your Catalog with new and modified table and partition definitions, and maintain schema versioning.

## Benefits
* Start Querying instantly
    * Serverless
* Pay Per Query
    * S3 has it's normal pricing
    * $5 Per terrabyte of data queried
    * Save costs and get better performance by:
        * Compressing files
        * Partitioning
        * Converting data into columnar formats
* Open, Powerful, Standard
    * ANSI SQL
    * Data formats:
        * CSV
        * JSON
        * ORC
        * Avro
        * Parquet
    * Highly available
    * Compute resources across multiple facilities and multiple devices.
* Fast, Really fast.
    * Executes queries in parallel, meaning most queries come back in seconds.

