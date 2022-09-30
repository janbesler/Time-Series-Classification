# Advances-Topics

This work is part of the module 'Advanced Topics for Data Science' at the University of Tuebingen.

### Abstract
--------


   Real quarter data is used to investigate how comparable the standard load profiles (SLP)  
   (provided by BDEW) are with buildings in the observed area to improve the accuracy of  
   the SLP. The quarter includes households, office buildings, and a factory, to ensure that  
   the SLP H0, G1 and G5 can be investigated and evaluate how well they match real cases.  
   Various time series clustering methods are used for the evaluation, including k-means and  
   fuzzy c-means as well as dynamic warping distance measures. The results demonstrate  
   that BDEW’s rigid models do not stand up to real-world data, such as the insignificance  
   of distinguishing weekends for different seasons and the need for a further breakdown of  
   weekdays across all seasons.

### Graphs
--------

Some graphs have been selected to show results from the paper.

* comparing the real world data to the BDEW clusters

![alt text](https://github.com/janbesler/Advances-Topics/blob/090508bf58f4d1126406516e78e633bc92093e00/graphs/BDEW_KIT_comparison.png "comparison of BDEW and acquired data")

* results of fuzzy c-means clustering for an office building

![alt text](https://github.com/janbesler/Advances-Topics/blob/090508bf58f4d1126406516e78e633bc92093e00/graphs/TeFak_cluster_profiles.png "clustered profiles for an Office building")
