# Clustering-and-PCA

## What need to be done
To categorize the countries using some socio-economic and health factors that 
determine the overall development of the country.

## Analysis Approach
First performed the PCA on data, out of 9 principal components selected only 
5 components as they were explaining the 95% variance in the data. Then 
performed k means and hierarchical clustering, in both the models divided 
the data into three clusters so as to classify countries as under-developed, 
developing and developed.

Hierarchical clustering clustered most of the countries in single cluster so 
results were not much reliable. K means cluster model produced better 
results. Visualized the clusters of k means based on gdpp, child mortality and 
income. Then selected that cluster in which income and gdpp were minimum 
and child mortality was maximum.
