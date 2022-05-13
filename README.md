# E-commerce-challenge
Challenge in collaboration with LUISS University and NTT Data. The goal is to increase the profitability of a real e-commerce 
There were three main tasks:
1. Customer analysis that aims at identifying groups of users with similar purchasing behaviors in order to create a marketing strategy towards each target (Clustering)
![immagine](https://user-images.githubusercontent.com/93279084/168276947-07424fa4-c548-4dbc-80ef-da7f32e60fd4.png)
2. Recommendation System able to provide to each user a set of products related to their interests, in order to maximize the probability of purchase (Product Recommendation)
![immagine](https://user-images.githubusercontent.com/93279084/168276984-b815e4d2-ec41-4e21-bf9b-9184d5020583.png)
3. Shipping time analysis to predict an accurate date of delivery and to reduce delays, in order to improve the quality of the shipping service (Delivery Time Prediction)
![immagine](https://user-images.githubusercontent.com/93279084/168277006-0e5a8c8a-c139-416b-949c-c55900fb089d.png)



# 1. RFM Analysis 
RFM analysis is a marketing technique used to quantitatively rank and group customers based on the recency, frequency and monetary total of their recent transactions to identify the best customers and perform targeted marketing campaigns.

 We calculated the recency (days), the frequency and the amount spent on the store.
Divide the scores into Quintiles (1,2,3,4).
Attribute each customer a score by a combination of the quantiles
![immagine](https://user-images.githubusercontent.com/93279084/168280219-c1501206-e62b-4459-9bd6-d0e61952f936.png)


# 2. Recommendation Systems
Collaborative filtering is commonly used for recommendation system. These techniques aim to fill in the missing entries of a user-item association matrix.
It is based on the idea that the best recommendations come from people who have similar tastes. 
We computed two different approach:
- Model based 
- Item based;
Afterwards, we evaluated each model and performed the predictions
![immagine](![immagine](https://user-images.githubusercontent.com/93279084/168280059-28dcc174-64ee-4961-92f2-a3cc017eb33d.png)


# 3. Time Delivery Predictions
We have done three steps:
- Time Delivery Prediction (with XGBoost and Random Forest)
- Delivery Performance (with neural network)
- How to improve delivery performance? (hypotesis testing)
![immagine](https://user-images.githubusercontent.com/93279084/168280347-8c3740e1-727a-4790-9c83-959dd05913b1.png)


In the repository, you can find all the codes and also a report with all the tasks explained at a high level.

## Authors
- Enrico Romano
- Simone Lu
- Lorenzo Antolini
- Luca Schisano
