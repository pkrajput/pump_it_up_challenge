# pump_it_up_challenge
This repository is an attempt at the open classification challange "pump it up" \
Link: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/25/ \
We've come up with three unique solutions in our approach:
1) geo hashing to combine coordinates
2) anomaly detection using knn
3) one vs all classification attempt (not good f1 achieved)

![Dashboard](taarifadashboard.png)

# Label Distribution

![Labels](labeldistribution.png)

In our implementation we achieved the best f1 score of 0.82 using optimal hyperparameters for RandomForest via grid search
