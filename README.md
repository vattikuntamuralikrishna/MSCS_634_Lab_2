                                        Advanced Big Data and Data Mining Lab 2
Purpose of the Lab
The main objective of this lab experiment is to study and compare the performance of K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) classification algorithms. For this purpose, we have used the standard Wine Dataset available in the sklearn library. The practical mainly focuses on understanding how changing the hyperparameter values like the number of neighbors(k) in KNN and the radius size in RNN impacts the final classification accuracy. By training, testing, and plotting the results, we got hands-on experience with these distance-based machine learning algorithms.
**Key Insights and Observations**
  1. KNN Results
    •	We evaluated the KNN classifier by taking different k values: 1, 5, 11, 15, and 21.
    •	The maximum accuracy of 77.78% was obtained when k = 1 and k = 21.
    •	The minimum accuracy of 72.22% was observed at k = 5.
    •	From this, we can conclude that the performance fluctuates depending on the number of neighbors we choose.
  2. RNN Results
    •	The RNN classifier was tested using various radius values: 350, 400, 450, 500, 550, and 600.
    •	The highest accuracy achieved was 75.00% at a radius value of 350.
    •	For all radius values from 400 onwards, the accuracy became constant at 72.22%.
  3. Model Comparison
    •	Comparing both models, KNN performed slightly better than RNN on the given Wine Dataset.
    •	KNN gave a peak accuracy of 77.78%, whereas RNN could only reach up to 75.00%.
    •	The accuracy trend graphs helped us to easily visualize how changing parameters affects the model outputs, proving that proper hyperparameter tuning is highly important.

**Challenges and Design Decisions**
•	Dataset Exploration: Before starting the model training, we thoroughly analyzed the Wine Dataset to understand its features, target labels, and class distribution.
•	Train-Test Split: We performed a standard 80:20 split on the dataset to train the model and then evaluate its performance on unseen test data.
•	Parameter Tuning: Multiple k values and radius limits were explicitly tested to check the sensitivity of both algorithms.
•	Metric Selection: Classification Accuracy was chosen as the main evaluation metric since the dataset is quite balanced and has well-defined classes.
•	Graphs/Visualization: We plotted the accuracy trends for both models, which made it very simple to compare the behavior of KNN and RNN across different settings.

**Tools and Libraries Used**
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Scikit-learn

**Dataset**
•	Wine Dataset from sklearn.datasets

**Author**
Murali Krishna Vattikunta
Advanced Big Data and Data Mining
Lab 2: K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) Classification 

