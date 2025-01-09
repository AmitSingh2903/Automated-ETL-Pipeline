# ETL Pipeline Project

## Project Description
The goal of the project is to build an ETL pipeline. ETL (Extract, Transform, Load) is a data pipeline used to collect data from various sources, transforms the data according to business requirements, and loads the data into a destination data storage.

This project contains the following files:
- ``src/extract.py`` - a python script that contains instructions to connect to Amazon Redshift data warehouse and to extract online transactions data with transformation tasks performed using SQL<br>
- ``src/transform.py`` - a python script that contains instructions to identify and remove duplicated records<br>
- ``src/load_data_to_s3.py`` - a python script that contains instructions to connect to Amazon S3 cloud object storage and to write the cleaned data as a CSV file into an S3 bucket<br>
- ``main.py`` - a python script that contains all instructions to execute all the steps to extract, transform, and load the transformed data using the functions from extract.py, transform.py, and load_data_to_s3.py<br>
- ``requirements.txt`` - a text document that contains all the libraries required to execute the code<br>
- ``Dockerfile`` - a text document that contains all the instructions a user could call on the command line to assemble an image<br>

