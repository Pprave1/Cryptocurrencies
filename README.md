# Cryptocurrencies
## Overview
 ### Purpose
 The client requested for a report that includes what cryptocurrencies are on trading market and how they could be grouped to create a classification system for their new investment plan.To create this plan we decided to use clustering algorithm to group the cryptocurrencies and use data visualizations to share the findings with the board.
 
 This project consists of four technical analysis:
 
                        1)  Preprocessing the Data for PCA(Principal Component Analysis)
                        2)  Reducing Data Dimensions Using PCA
                        3)  Clustering Cryptocurrencies Using K-means
                        4)  Visualizing Cryptocurrencies Results
                        
 ## Results
 
 ### The dataframe created from imported data,1252 rows of data:
 
   #### ![dataframe_deliv1.png](/Resources/Images/dataframe_deliv1.png)

 
 
### Below image shows the result of tradable cryptocurrenciesafter cleaning the data,532 rows of data.
 
 
   #### ![df_aftercleaning_deliv1.png](/Resources/Images/df_aftercleaning_deliv1.png)
   
### Result of PCA algorithm that reduce the dimensions to three principal components.

  #### ![3_PC_deliverable_2.png](Resources/Images/3_PC_deliverable_2.png)
  
  
###  The K-means algorithm is used to  cluster the cryptocurrencies using PCA(Principal Component Analysis)data.
###  An elbow curve used is created using hvplot to find the best value for K;K=4.
 


  #### ![elbowcurve_deliverable3.png](Resources/Images/elbowcurve_deliverable3.png)


###  Applying the Principal Component Analysis:

 #### ![Clustered_df3.png](Resources//Images/Clustered_df.png)
 
###  Created a 3D-Scatter with the PCA data and the clusters.

 ####  ![3D_Model.png](Resources/Images/3D_Model.png)
 
 
###  Number of Tradable Cryptocurrencies,DataFrame to plot results:

 #### ![Cryptos.png](Resources/Images/Cryptos.png)
 
###  Visualizing Cryptocurrencies Results
###  Create an hvplot scatter plot with x="TotalCoinsMined", y="TotalCoinSupply", and by="Class".

#### ![result_hvplot_scatterplot_deli_4.png](Resources/Images/result_hvplot_scatterplot_deli_4.png)
 
 


  
  



   
   


 
 
 
 
 
 
