# Chocolate-Ratings-Prediction
Made by: Juan Camilo Paz and Juan José Pinilla

In this project you will find a Chocolate Rating Predictor based on a dataset obtained in Kaggle.
The dataset used can be found in the following link: https://www.kaggle.com/datasets/andrewmvd/chocolate-ratings
![image](https://user-images.githubusercontent.com/98425571/169709868-941126cb-ae21-4aba-9488-5613c5964369.png)

The project was made using Python and Colab. The code contains multiple tests on the data in order to obtain the best method for analysis. 
1. The code made in Colab has the steps listed in order to run the analysis properly.
2. Dataset was cleaned during the first steps. The following is the clean dataset:
[Datos procesados.csv](https://github.com/pazju/Chocolate-Ratings-Prediction/files/8750000/Datos.procesados.csv)
3. A classification and supervised method was selected based on the data, after this data was normalized.
4. The realization of PCA is discarded. The following image explains the reason: ![image](https://user-images.githubusercontent.com/98425571/169710216-60804549-8b84-468f-b3fb-67b21dd4dffc.png)
5. After doing a grid search and cross-validation using GridSearchCV to optimize the hiperparameters of different models, the model that best fits the data is a Linear Discriminant Analysis (LDA). The following shows the optimized model: ![image](https://user-images.githubusercontent.com/98425571/169710334-a3ea2846-94cc-4531-ae76-dc00ec39f508.png)
6. Finally the model is retrained with all the data and these are the results: ![image](https://user-images.githubusercontent.com/98425571/169710369-d054fa12-e67a-4e82-88ec-2d24f603ee19.png)

CONCLUSION:
The data given in the dataset is quite decorrelated to each other, demonstrating why the existence of chocolate tasters (people) and that the dataset can be improved if you want to analyze it using a machine learning model.

Link:
https://youtu.be/alCgHVV9Okg
