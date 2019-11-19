# FIFA-project
### Project by Marc Mejias, Ironhack's Data Analytics Bootcamp student
### November 2019

This project tries to create tools to help football clubs scouts doing their job. Instead of signing well-known 
players at a very expensive price, this project looks for promising young players with low price and high potential.
Besides, a machine learning model try to confirm the potential of the players predicting their evolution
in the next 3 years.



###Aim:

Help the process of a club looking for a young player for a specific position

 - Characterization of all positions in the field: strong features and weak features

 - Search for talented young players

 - Building models to predict players progression for 1, 2 or 3 years (2021, 2022, 2023)


###Data: 

The dataset used for the project is available at Kaggle Datasets 
(https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset)

It contains EA Sports FIFA players data from 2015 to 2020.



###Notebooks:

_FIFA 20 Preprocessing, Cleaning, EDA, Correlations.ipynb_ contains the full preprocessing for FIFA 20 data.

_Players Clustering FIFA 20 4 clusters.ipynb_ contains a model for FIFA 20 player clustering based in K_Means algorithm.

_Visualization Clusters.ipynb_ contains visualization for the 4 clusters obtained.

_FIFA 20 Players attributes Visualization.ipynb_ contains visualization for players positions in FIFA 20.

_Fifa 17 model to predict 2023.ipynb_ contains linear regression model to predict 3 years progression of players.

_Fifa 18 model to predict 2022.ipynb_ contains linear regression model to predict 2 years progression of players.

_Fifa 19 model to predict 2021.ipynb_ contains linear regression model to predict 1 year progression of players.



###Conclusions

- Data analysis could be a useful tool when trying to scout for young and talented football players.

- K-means model for players clustering needs to be improved to be useful.

- Prediction of players progression is quite accurate for 1 year prediction, but is lesser accurate for longer periods.




