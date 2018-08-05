# Integrating IBM Cloud Object Storage and Apache Spark and Creating Visualisations with Pandas and Plotly

## Introduction
This repository contains a jupyter notebook (two versions that differ only in language) that demonstrate how to use the ibmos2spark python package with IBM Cloud Object Storage service and Apache Spark. 
The jupyter notebook is suposed to be executed in Watson Studio (the IBM data science ecossystem), but with little adaptations it can be executed locally, using only the IBM COS and Apache Spark services in the Cloud.

## Required IBM Cloud Services

<a href="https://console.bluemix.net/catalog/services/watson-studio">
    <img src="https://i.imgur.com/PUUM0g8.png" alt="Watson Studio">
</a> 

<a href="https://console.bluemix.net/catalog/services/apache-spark">
    <img src="https://i.imgur.com/so3XxB0.png" alt="Apache Spark">
</a>

<a href="https://console.bluemix.net/catalog/services/cloud-object-storage">
    <img src="https://i.imgur.com/6tnetW6.png" alt="Cloud Object Storage">
</a>

## Other Required APIs

<a href="https://plot.ly/#/">
    <img src="https://i.imgur.com/H2E7R58.png" alt="Plotly">
</a> 

## Setup

1. After creating an IBM Watson Studio service instance, create a new data science project (choose your IBM Cloud Object Storage service instance or create a new one to be integrated);
2. Go to your project settings tab and associate an Apache Spark service instance;
3. Unzip and upload the enem2016.csv file to your project (go to your project assets tab and click in the option to add new files);
4. Go to the assets tab and create a new Jupyter Notebook (copy and paste the .ipynb file from this repository at the "import from URL field", and also choose your Apache Spark runtime created previously);
5. With your new imported notebook open, click at the data button at the top right, choose the previously uploaded .csv file and select "Insert SparkSession DataFrame".
6. Write your Plotly credentials at the designated cell.
7. Now you are ready to execute the jupyter notebook and make visualisations with Pandas and Plotly.
