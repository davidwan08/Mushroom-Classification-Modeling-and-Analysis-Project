# Mushroom-Classification-Modeling-and-Analysis-Project

# Overview

I will perform data exploration, modeling, and analysis on the mushroom dataset in order to make predictions on specific data values based on modeling information to determine what characteristics classify a mushroom as either edible or poisonous.

Link to Coding Project file: https://github.com/davidwan08/Mushroom-Classification-Modeling-and-Analysis-Project/blob/main/Mushroom_Classification_Project_Data_Exploration_and_Modeling.ipynb

# Summary/Conclusion

- Based on the models and hyperparameter tuning, even though all the models, especially the optimized versions, did very well at making mushroom class predictions, if I had to pick a final model that would be the representative model for this project, I would choose the optimized XGBoost model here.
- The reasoning behind my decision is that even though logistic regression performed very well on this dataset, it is because of how distinct the feature differences provided between the edible and poisonous subsets were that really show how sharp the drop-off between the 2 classes were.
- The cross validation scores were slightly better on the optimized XGBoost model than the other models, optimized or default.
- I felt that XGBoost provided much more potential for hyperparameter tuning than logistic regression, since a gradiant booster classification model really provided an effective representation of how the mushroom features help identify the difference between edible and poisonous mushrooms.
- The optimized logistic regression can still be utilized as a backup model in case XGBoost loses its effectiveness on potential and future data generated in addition to the current dataset. Plus, the optimized LightGBM model could also work fairly well as another backup model.
- Despite how well the default KNN model performed, I would not recommend this model for this dataset, as KNN performed very poorly during the optimization process due to the large dataset in general, which slowed down the modeling process significantly.
- Overall, I would highly recommend the XGBoost model for Production, and it can serve as a great indicative tool for identification of any wild mushrooms in the forest and in the wild areas. Morel mushrooms and 'chicken of the forest' mushrooms can be considered culinary delicacies and are high value mushrooms in high demand. On the other hand, we can also use this to identify any toxic Amanita mushroom species that could prove fatal when ingested.

# Contact

If you have any questions or concerns about my project, feel free to reach out to me at davidwan08@gmail.com. Thank you for your consideration!
