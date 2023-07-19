# Football match prediction
* Developed a robust football prediction model leveraging the Kaggle platform and utilizing the Api-Football-Beta API for data collection.
* Achieved significant improvement in accuracy, with the model achieving an impressive **85.71%** accuracy, a remarkable **40%** enhancement compared to the initial model's accuracy of **61.6%**.

<p float="left">
  <img src="[https://bobbyhadz.com/images/blog/python-print-tab/thumbnail.webp](https://github.com/afnanurrahim/Football_match_prediction/blob/main/Accuracy%20images/Final_model.png)" width="40%" />
  <img src="[https://bobbyhadz.com/images/blog/what-aws-cdk-bootstrap-do/thumbnail.webp](https://github.com/afnanurrahim/Football_match_prediction/blob/main/Accuracy%20images/initial_model.png)" width="40%" />
</p>

Key Features:

* **Data Collection**: Integrated the Api-Football-Beta API to collect an extensive range of football match data, including team statistics, player information, and historical match results. This rich dataset forms the foundation for training and testing the prediction model.
  
* **Model Building** with Random Forest: Employed the Random Forest algorithm for its robustness and ability to handle complex relationships within the data. Leveraging the scikit-learn library, the model was trained on an array of features, including team performance metrics, player attributes, and match-specific details.
  
* **Hyperparameter Tuning**: Utilized Grid Search and Randomized Search techniques to optimize the model's hyperparameters, fine-tuning its performance and enhancing prediction accuracy. This rigorous tuning process ensured optimal configuration for the Random Forest classifier.

* **Feature Engineering**: Applied advanced feature engineering techniques to extract relevant information and create new features that capture intricate patterns and relationships within the data. These engineered features significantly enhanced the model's predictive capabilities.

* **OneVsOneClassifier** for Multiclass Classification: Utilized the OneVsOneClassifier strategy to extend the model's classification capabilities to handle multiclass prediction scenarios. This approach enabled accurate predictions for outcomes involving more than two competing teams.

* **Permutation Importance:** Leveraged permutation importance to assess the significance of each feature in contributing to the model's predictive power. This analysis provided insights into the key factors influencing match outcomes and aided feature selection.

**Links**: 

  Kaggle notebook: https://www.kaggle.com/code/afnanurrahim/pl-table-prediciton
  
  Dataset: https://www.kaggle.com/datasets/afnanurrahim/premier-league-2022-23
  
  API (from which data was extracted): https://rapidapi.com/api-sports/api/api-football-beta/
