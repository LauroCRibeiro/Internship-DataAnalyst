# Summary:

- Total number of Rows: 42,448,764
- Total number of Columns: 9
- File Size: 5GB

# Dataset Download Link:
https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store?fbclid=IwAR3Rji50q1WtaHD8By7X-_E6WO52Ksj7SQmulpV7-flbmhQKerdWR1M2cdc&select=2019-Oct.csv

# Task:

Take any csv/text file of 2+ GB of your choice. --- (You can do this assignment on Google colab)

Read the file ( Present approach of reading the file )

Try different methods of file reading eg: Dask, Modin, Ray, pandas and present your findings in term of computational efficiency

Perform basic validation on data columns : eg: remove special character , white spaces from the col name

As you already know the schema hence create a YAML file and write the column name in YAML file. --define separator of
read and write file, column name in YAML

Validate number of columns and column name of ingested file with YAML.

Write the file in pipe separated text file (|) in gz format.
