# nhl-prediction-model
See https://alexoh554.github.io/2024/03/14/NHL-Random-Forest-Model.html for more information.

`export_season.ipynb`
This file walks through my process to extract game scores and team statistics for a specified NHL season using the NHL API. The extracted data is saved in a structured format that can be used for training the prediction model.

`random_forest.ipynb`
This file shows my process of training a decision tree and random forest model based on the data exported from `export_season.ipynb`. It also shows my work in optimizing hyperparameters using RandomizedSearchCV to find the best parameters for the random forest. 

## Visuals
### Scatterplots
![goals-vs-wins](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/goals-wins-scatterplot.png)

![plus-minus-vs-wins](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/plusminus-wins-scatterplot.png)

![shots-vs-wins](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/shots-wins-scatterplot.png)

![ppg-vs-wins](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/special_teams_wins_scatterplot.png)

![pims-vs-wins](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/pim-wins-scatterplot.png)

### Decision Tree
![decision-tree](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/0201a4d397a075c9560cbcf7907f8ab47ae27111/visuals/boolean_decision_tree.svg)

### Features
![feature-importance](https://raw.githubusercontent.com/alexoh554/nhl-prediction-model/main/visuals/feature_importance.png)
