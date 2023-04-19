# Dataset Description
The UCI Machine Learning Repository hosts the "Room Occupancy Estimation Data Set," which consists of 20,560 instances and 7 features, including temperature, relative humidity, light intensity, CO2 level, humidity ratio, and binary occupancy labels. This dataset is commonly employed for binary classification tasks aimed at predicting room occupancy based on sensor measurements, making it applicable to research areas such as energy management in buildings and smart homes. It serves as a valuable reference for evaluating and comparing the performance of diverse machine learning algorithms, including Support Vector Machines (SVM), in the context of room occupancy estimation.

# Objective
The main goal of our project was to investigate the effectiveness of Support Vector Machines (SVM) for classification problems and optimize SVM parameters. We used Python's Scikit-learn library to implement SVM models on the room occupancy Data Set, which was randomly divided into 10 samples for training and testing. By experimenting with different SVM parameter combinations, we identified the best settings for each sample. The results were recorded in a table that showcases the accuracy achieved for each sample, along with the corresponding SVM parameters that led to the highest accuracy. This table can serve as a valuable reference for future classification tasks that involve SVM parameter optimization.

## Results 

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.88 | Poly | 5.82 | 4.35 |
| 2 | 0.95 | Linear | 5.13 | 0.30 |
| 3 | 0.96 | Linear | 3.13 | 6.32 |
| 4 | 0.96 | Poly | 1.49 | 3.26 |
| 5 | 0.91 | Linear | 3.52 | 7.34 |
| 6 | 0.83 | RBF | 5.60 | 3.14 |
| 7 | 0.95 | Poly | 0.29 | 7.71 |
| 8 | 0.95 | Poly | 4.87 | 5.57 |
| 9 | 0.97 | Poly | 1.27 | 6.87 |
| 10 | 0.92 | Poly | 0.34 | 5.50 |

## Convergence Graph
![image](https://user-images.githubusercontent.com/79656311/233170296-cbe73e19-9eac-46b8-8152-8f8aa50861f6.png)

##Sample 9 has the best accuracy of 0.97.
