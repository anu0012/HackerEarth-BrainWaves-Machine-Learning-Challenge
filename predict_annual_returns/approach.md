# Steps: 

1. Filling of null values.

2. I generated some new features from the existing ones i.e. portfolio_duration, profit, rate_diff etc.

3. Then, I did one-hot encoding for categorical features.

4. I chose best features for model training and remove the redundant ones.

5. With the final 15 features, I trained my model using CatBoost. I chose CatBoost because it works very efficiently for categorical features.

6. On public leaderboard I got 97% accuracy.