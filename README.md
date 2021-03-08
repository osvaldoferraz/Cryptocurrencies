# Cryptocurrencies
## Unsupervised Machine Learning

This is an analysis of several cryptocurrencies, aiming to find some clusters of data using unsupervised machine leraning in order to give advice on how to better invest on Cryptocurrencies.

- Data was cleaned and processed 
- Data was reduced with PCA
- Data was clusterd with K-means
- Visualizations were created to present the results.

### Code
Python on JupyterNotebooks was used to clean the dataset and apply the transformations.

- Original Dataset

![Screen Shot 2021-03-07 at 10 06 11 PM](https://user-images.githubusercontent.com/72593264/110273054-551ecf00-7f91-11eb-939e-a11467755c71.png)

- Cleaning Process

![Screen Shot 2021-03-07 at 10 07 14 PM](https://user-images.githubusercontent.com/72593264/110273115-7aabd880-7f91-11eb-91f3-bb16a8c5ba3f.png)
![Screen Shot 2021-03-07 at 10 07 30 PM](https://user-images.githubusercontent.com/72593264/110273142-839caa00-7f91-11eb-9ce0-993a8b017167.png)
![Screen Shot 2021-03-07 at 10 07 39 PM](https://user-images.githubusercontent.com/72593264/110273150-88f9f480-7f91-11eb-8998-9757bdfc6db2.png)
![Screen Shot 2021-03-07 at 10 07 48 PM](https://user-images.githubusercontent.com/72593264/110273161-8eefd580-7f91-11eb-8a85-a6ffceb9431e.png)
![Screen Shot 2021-03-07 at 10 07 57 PM](https://user-images.githubusercontent.com/72593264/110273167-944d2000-7f91-11eb-99d6-eb2f5466c93b.png)
![Screen Shot 2021-03-07 at 10 08 17 PM](https://user-images.githubusercontent.com/72593264/110273185-a038e200-7f91-11eb-96d7-02a60585f4c3.png)
- Final Data cleaned Data Set with 533 Rows and 4 Features.

![Screen Shot 2021-03-07 at 10 08 29 PM](https://user-images.githubusercontent.com/72593264/110273200-a75ff000-7f91-11eb-96a8-8932909e4c0b.png)

 - PCA w/ Standard Scaler and K-means for clustering

![Screen Shot 2021-03-07 at 10 13 36 PM](https://user-images.githubusercontent.com/72593264/110273516-5f8d9880-7f92-11eb-8133-86cb13eaf06a.png)
- Elbow Curve

![Screen Shot 2021-03-07 at 10 13 54 PM](https://user-images.githubusercontent.com/72593264/110273536-69170080-7f92-11eb-9ed3-7a448ae0ca5a.png)
- K-means

![Screen Shot 2021-03-07 at 10 14 12 PM](https://user-images.githubusercontent.com/72593264/110273553-7338ff00-7f92-11eb-8eea-04819e1f1143.png)

- Final Table with PCA components and Clusters (Class) found.

![Screen Shot 2021-03-07 at 10 14 51 PM](https://user-images.githubusercontent.com/72593264/110273593-8a77ec80-7f92-11eb-8f42-9084be50260c.png)

## Visualizations

- 3D Scatter Plot - PCA Components and Classes

![Screen Shot 2021-03-07 at 10 19 43 PM](https://user-images.githubusercontent.com/72593264/110273902-391c2d00-7f93-11eb-9485-5125ae9c87e5.png)

- Scatter Plot - Total Coins Supply vs Total Coins Mined and Class (color).

![Screen Shot 2021-03-07 at 10 20 02 PM](https://user-images.githubusercontent.com/72593264/110273924-4507ef00-7f93-11eb-87d1-3ac18ac6950a.png)

