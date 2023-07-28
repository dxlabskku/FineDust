## Micro-Locational Fine Dust Prediction Utilizing Machine Learning and Deep Learning Models

### Framework
<img src='https://user-images.githubusercontent.com/68065313/204736718-11963c10-cf61-4af8-b750-0928717f1073.png' width='500' height='500'>

### Introduction
Given the increasing number of countries reporting degraded air quality, effective air quality monitoring has become a critical issue in today's world. However, the current air quality observatory systems are often prohibitively expensive, resulting in a lack of observatories in many regions within a country. Consequently, a significant problem arises where not every region receives the same level of air quality information. This disparity occurs because some locations have to rely on information from observatories located far away from their regions, even if they may be the closest available options. To address this challenge, a novel approach that leverages machine learning and deep learning techniques to forecast fine dust concentrations was proposed. Specifically, continuous location features in the form of latitude and longitude values were incorporated into our models. By utilizing a comprehensive dataset comprising weather conditions, air quality measurements, and location properties, various machine learning models, including Random Forest Regression, XGBoost Regression, AdaBoost Regression, and a deep learning model known as Long Short-Term Memory (LSTM) were trained. Our experimental results demonstrated that the LSTM model outperforms the other models, achieving the best score with a root mean squared error of 23.48 in predicting fine dust (PM10) concentrations on an hourly basis. Furthermore, the fact that incorporating location properties, such as longitude and latitude values, enhances the overall quality of the regression models was discovered. Additionally, the implications and contributions of our research were discussed. By implementing our approach, the cost associated with relying solely on existing observatories can be substantially reduced. This reduction in costs can pave the way for economically efficient fine dust observation systems, ensuring more widespread and accurate air quality monitoring across different regions.

### Data
We collected our dataset from the Korean Ministry of Environment and Airkorea and the datasets for experiment could not be uploaded because of the data memory problem. If anyone requires the complete dataset, please feel free to request it.
below figure shows the shifting process of dataset for LSTM
<img src='https://github.com/dxlabskku/FineDust/assets/68065313/e9713dd7-2e01-403e-907c-537b28b431a9' width='700' height='400'>

### Result
The results revealed that LSTM performed better than all other machine learning models. The RMSE and Pearson correlation of LSTM were 23.48 and 0.6176, respectively. 

<img src='https://github.com/dxlabskku/FineDust/assets/68065313/620c3b9e-8d7e-4e6f-aefe-d8b687378e8f' width='800' height='300'>
