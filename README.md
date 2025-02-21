### Content-Based Recommender System Using KNN and Naive Bayes
### Overview:
In this project, we developed a content-based recommender system using two machine learning techniques: K-Nearest Neighbors (KNN) and Naive Bayes. The system aims to recommend items based on the features of the items and user preferences. Initially, we manually computed the distance (such as Euclidean or cosine similarity) between test and training objects. Afterward, we implemented both KNN and Naive Bayes algorithms to classify the test object based on the computed distances and item features.

### Results:
After applying both KNN and Naive Bayes, the system produced identical results for the test object classification. The KNN algorithm identified the nearest neighbors based on manually computed distances, while Naive Bayes used probabilistic classification. Despite using different approaches, both models predicted the same outcome, showing that the distance metric and feature relationships had the same impact on both algorithms.

### Conclusion:
The project demonstrated that both KNN and Naive Bayes can be effectively applied to a content-based recommendation system and that, under certain conditions, both models can yield identical results. This suggests that the underlying features and distance metrics used in the system were aligned, allowing both algorithms to converge on the same prediction. The findings highlight the versatility of these models in content-based recommendation tasks and their potential to provide consistent results with the right features and calculations.



