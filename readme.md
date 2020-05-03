# Data Analysis of Yelp Business Data

In this project, I will be analyzing a subset of Yelp's business, reviews and user data. The dataset comes from <a href='https://www.kaggle.com/yelp-dataset/yelp-dataset#yelp_academic_dataset_business.json'>Kaggle</a>. I uploaded the data into a publis s3 bucket: s3://sta9760-project2-yelp-data/\*.json

<h2><a href='/Analysis.ipynb'>Analysis</a></h2>
The whole project was performed on AWS EMR. First, a EMR cluster was configured. Then a PySpark notebook was created using the existing EMR cluster. All the data was analyzed by using PySpark.  This project is consists of 4 parts.

<br>
<br>
<Strong>Part 1: </Strong>
Install and import the necessary dependencies for the analysis. The dataset is also loaded from s3 as PySpark dataframe.
<br>

<Strong>Part 2: </Strong>
I will perform some basic analysis on the business categories.
<br>

<Strong>Part 3: </Strong>
I will use the data to see if the Yelp reviews skew negative or not.
<br>

<Strong>Part 4: </Strong>
I will use the data to see should we trust the Yelp elite user based on the rating to a business.
<br>

<h2>Cluster Configurations</h2>
<img src="./assets/cluster_config.png">

<h2>Notebook Configurations</h2>
<img src="./assets/notebook_config.png">

<h2>S3 Bucket</h2>
Click <a href="https://s3.us-east-2.amazonaws.com/sta9760-project2-yelp-data/yelp_academic_dataset_business.json">here</a> to see the business dataset, which is one of the three datasets in my s3 bucket.
<img src="./assets/notebook_config.png">
