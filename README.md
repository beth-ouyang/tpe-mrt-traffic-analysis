# Taipei MRT Hourly Traffic Analysis

## About
This project is based on the [Taipei MRT Hourly Traffic Data](https://www.kaggle.com/datasets/bethouyang/taipei-mrt-hourly-traffic-data), conducting a dive into Taipei's MRT traffic patterns. The approaches that have been tried can be found in the `analysis/analysis.ipynb`.

## Finished Approaches 
The approaches that have been done and wrapped up:
- `pca_kmeans.ipynb`: Utilizing PCA and K-means clustering: simplify the complex traffic data to reveal insightful patterns among MRT stations. 
This part is also documented in the Medium article as a tutorial: [PCA & K-Means for Traffic Data in Python](https://towardsdatascience.com/pca-k-means-for-traffic-data-in-python-a0ec66ab4789). 

## Installation instructions - Running the Code Locally

To run the codes locally, clone the repository, navigate to the project directory, and execute:
```bash
conda env create -f environment.yml
```
```bash
conda activate tpe_mrt 
```
The above two commands install and activate the necessary environment to run the notebooks locally. After activation, you will be able to run the notebooks.

## Data Source
Original data is from Taipei Government: [臺北捷運各站分時進出量統計](https://data.gov.tw/dataset/128506)
> English version of this data on [kaggle](https://www.kaggle.com/datasets/bethouyang/taipei-mrt-hourly-traffic-data)
 
## Author
[Beth Ou Yang](https://github.com/beth-ouyang)
