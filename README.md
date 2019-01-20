# Boston Housing Data 
## Quick Summary 
Within the Exploratory Data Analysis notebook, we first conducted some descriptive analysis and produced summary statistics to get a feel of the data set. Additionaal graphical methods such as histograms, scatterplots, and correlation matrices, were plotted to better illustrate the relationship (if any) between various predictive variables and boston housing prices. 

In the Cluster Analysis notebook, we implement the basic nearest neighbor and K-nearest neighbor (KNN) algorithms from scratch, and use them to predict Boston housing prices using available predictive variables. Many important concepts, such as factor normalization, parameter optimization (e.g. optimize K in KNN algorithm using cross-validation), and forward selection were also explored. 

## Conclusion
Using the aforementioned techniques, the lowest root-mean-squared error (RMSE) achieved was 3.42. This was obtained using the KNN clustering technique (K=4) and the features : 'NOX', 'RM', 'DIS', 'PTRATIO', 'LSTAT' (in order: nitric oxides concentration, average number of rooms per dwelling, weighted distances to five Boston employment centres, pupil-teacher ratio by town, % lower status of the population). To put this RMSE value in perspective, the RMSE obtained by naively predicting Boston housing prices using the average house price achieved an RMSE of 9.21. 
