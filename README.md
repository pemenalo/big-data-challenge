# big-data-challenge

Perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

## Instructions

### Level 1 Assignment

* Use the furnished schema to create tables in your RDS database.

* Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.
  * Note: It is possible to ETL both data sources in a single notebook, but due to the large data sizes, it will be easier to work with these S3 data sources in two separate Colab notebooks.

* Be sure to handle the header correctly. If you read the file without the header parameter, you may find that the column headers are included in the table rows.

* For each notebook (one dataset per notebook), complete the following:

* Count the number of records (rows) in the dataset.

* Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.

* Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Be sure that everything is correct before uploading.

### Submission

* Important be sure to clean up all your AWS resources. Consult the AWS cleanup guide and AWS check billing guide as reference.

* Download you Google Colab notebooks as .ipynb files and upload those to GitHub.

* Copy your SQL queries into .sql files and upload to GitHub.

* Important: Do not upload notebooks that contain your RDS password and endpoint. Be sure to delete them before making your notebook public!

* Ensure your repository has regular commits and a thorough README.md file
