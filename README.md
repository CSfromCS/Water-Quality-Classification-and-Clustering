# Water Potability Classification and Quality Clustering
Data analysis experimentation using the dataset from [Kadiwal, A. (2020)](https://www.kaggle.com/datasets/adityakadiwal/water-potability)

![image](https://github.com/user-attachments/assets/836beca1-8cb9-4584-80a8-79041de6b5b2)

## Methodology
- Data Source Collection
- Data Cleaning and Pre-processing
  - Train Test Split of 80/20
  - Creating 3 sets, Origial, MinMax, and Standard scaled
- Modelling
  - Nearest Neighbors
  - Decision Tree
  - K-means Clustering
- Result analysis
  - Best classification model
    - Metrics: Accuracy, Precision, Recall, F1 Score
  - Highest Scoring cluster
    - Silhouette Score

![image](https://github.com/user-attachments/assets/809aed03-564c-42f4-8067-adc977017bff)

Tech stack: Jupyter for the modelling and charting, Canva for the images

## Results
### Classification
![image](https://github.com/user-attachments/assets/3d0da32d-c13c-469e-b526-686041f50d44)
![image](https://github.com/user-attachments/assets/2943f18f-853a-44cf-b93b-2c98a65fb83f)

Best performing model is the Nearest Neighbors (k=10) with the Standard Scaling. This achieved an accuracy of 69.65% and precision of 71.43%.
![image](https://github.com/user-attachments/assets/9c6d58aa-ddf9-4c8e-bf10-3696fd1f8012)

### Clustering
Across the multiple features, only 2 features (solids vs turbidity) are used in the visualisation but all features were used in the model.

K-means clustering with K=2 using the Original dataset performed best with a silhouette score of 0.571.
![image](https://github.com/user-attachments/assets/da6ce2f1-d900-49f6-98b7-34f883a6bc9f)


