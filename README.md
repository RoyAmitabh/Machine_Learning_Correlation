# Machine_Learning_Correlation
This repository has been made to showcase how to obtain correlation between feature pairs of iris dataset
This is the url from where i have obtained the iris dataset - https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data

POC steps - I have uploaded the dataset on ADLS(Azure Datalake Storage). I have used notebook in databricks for all the python codes. I have used sparkML using pyspark interface.
This is the correlation on whole dataset :
<img width="436" alt="image" src="https://github.com/RoyAmitabh/Machine_Learning_Correlation/assets/104931628/9f824be4-11ff-4371-87a3-796faa1fd1b5">

Many times, it can happen that the dataset is very large. In such situation bringing whole data on master node for calculating correlation is not a good idea. So, bootstrap sampling can be used. 

This is the correlation obtained on bootstrap sample. The result using sample is very near to the results using whole dataset.

<img width="428" alt="image" src="https://github.com/RoyAmitabh/Machine_Learning_Correlation/assets/104931628/5f8cd71d-9ae8-4f0d-8c10-cb6d8d9ab4ba">
