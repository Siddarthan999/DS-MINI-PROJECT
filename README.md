# DS-MINI-PROJECT
* In our project, we analyzed average global climate data by country. We cleaned the dataset, generated features, and detected outliers. We trained a machine learning model called SARIMAX 
* which stands for "Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors". It is a powerful algorithm used for time series analysis and forecasting. 
* It includes three methods: one involving dropping missing values and Imputation followed by detection and removable of outliers, and the other involving standardization. We compared the results of the three methods to find the best approach for predicting global average temperature over the next 25 years.

![READ DATASET (2) COPY](https://github.com/Siddarthan999/DS-MINI-PROJECT/assets/91734840/45bbce0c-150c-43c6-96a6-ac858521de75)

## ACCURACY BASED ON RMSE VALUE
* Root mean square error or root mean square deviation is one of the most commonly used measures for evaluating the quality of predictions.
* The lower the RMSE, the better the model and its predictions. A higher RMSE indicates that there is a large deviation from the residual to the ground truth
![image](https://github.com/Siddarthan999/DS-MINI-PROJECT/assets/91734840/549675d7-87b4-4cce-b6cb-8a08286267e4)
RMSE: 1.3540517085268011
![image](https://github.com/Siddarthan999/DS-MINI-PROJECT/assets/91734840/8db0a1a2-6b38-4e33-8b4f-d6f07492f27c)
RMSE: 1.2054144092168757
![image](https://github.com/Siddarthan999/DS-MINI-PROJECT/assets/91734840/c242d715-e46a-453e-8521-110b630c463e)
RMSE: 0.14366912040368834

## CONCLUSION:
* Our goal aimed to predict the average temperature for the next 25 years using the SARIMAX machine learning model. 
* We employed various data science processes, including dropping missing values, imputation, and Standardization, to improve the accuracy of our predictions. Based on the root mean squared error (RMSE) metric, the Standardization approach yielded the most accurate results for this dataset.
* However, it is important to note that the best-suited process may vary depending on the dataset. Each dataset requires careful analysis and selection of the most appropriate methods to achieve accurate predictions.
