# Big Data ETL Challenge 
Using AWS create a PostgreSQL database and and S3 bucket to extract, transform, and load (ETL) data.

## Services
* AWS RDS
* AWS S3
* Google Colaboratory

## Jupyter Notebooks
* part_one_us_tools.ipynb
* part_one_us_watches.ipynb

## Results
The total number of records loaded into each table:
* *select count(*) from review_id_table rit;*
    * **2,701,972**
* *select count(*) from products p;*
    * **2,701,972**
* *select count(*) from customers c;*
    * **1,773,429**
* *select count(*) from vine_table vt;*
    * **2,701,972**

## Datasets
* https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz
    * amazon_reviews_us_Watches_v1_00.tsv
* https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz
    * amazon_reviews_us_Tools_v1_00.tsv