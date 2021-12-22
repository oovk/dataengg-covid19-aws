# dataengg-covid19-aws
Data Engineering Project on COVID-19 DataLake by AWS

Performing data modeling, data wrangling and extract-load-transform on the COVID-19 Data Lake available on registry of open data AWS using various AWS tools such as boto3, Glue, S3, Athena and Redshift.

**Tools and Usages:**
* Amazon S3 - Storing the data
* Crawler - Used to extract all the schema and information straight from S3
* Amazon Athena - Running adhoc sql queries on the available data in S3
* AWS Glue - data transformation
* Amazon Redshift - storing the tranfromed dimensional model in datawarehouse 
* boto3 - aws python sdk for create, configure, and manage AWS services.

**Architecture**
![image.png](attachment:image.png)

**Data Set:**
[https://registry.opendata.aws/aws-covid19-lake/](https://registry.opendata.aws/aws-covid19-lake/)

**How to get the data?**
* Simply download and upload to S3 bucket
* Using AWS CLI copy command: **aws s3 cp s3://mybucket/test.txt s3://mybucket/test2.txt**

**STEPS:**

* **Running Crawlers on the data uploaded in S3**
* **Analysing data using AWS Athena query editor**
* **Building the ER-Data Model**
* **ETL jobs in python**
* **Saving result in S3**
* **Building the Dimensional Model**
* **Building Dimensional schema in Redshift**
* **Storing the dimensional model into Redshift**

**ER-Data Model**
![image-5.png](attachment:image-5.png)

**Dimension Model**
![image-6.png](attachment:image-6.png)
