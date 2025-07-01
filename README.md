
## AWS-Based Data Analysis Pipeline using Glue, Athena, and Python






## Description
This project demonstrates a basic data analysis pipeline using AWS services. It involves storing data in S3, cataloging it with Glue Crawlers, querying it using Athena, and performing additional analysis with Python.
## Architecture Overview / Workflow
[CSV Dataset] → [S3 Bucket]
                     ↓
              [Glue Crawler]
                     ↓
              [Glue Data Catalog]
                     ↓
               [Athena Queries]
                     ↓
           [Python (Optional Analysis)]

## Services used
List and briefly describe each AWS service used:

S3 – To store the raw dataset.

Glue Crawler – To infer schema and populate the Glue Data Catalog.

Glue Job – (if used) for transformations or ETL.

Athena – To run SQL queries directly on the S3 data.

IAM – (optional) for managing access roles.
## Steps to Reproduce / Run the Project 
1.Upload dataset to S3.

2.Set up a Glue Crawler.

3.Run the Crawler to create a table.

4.Query data using Athena.

5.Run Python scripts locally or in a Jupyter        notebook.


## Requirments
 Baisc knowledge of AWS (IAM, S3 bucket,Glue,Athena,) and python

### For data analysis
Tools like Pandas or NumPy can be used for data  manipulation(trimming data). 



