# Portfolio
My own projects

1. boosting with no boost

For me as a beginner data scientist it was hard to understand how the gradient boost works. Also I heard that it is often asked in job interview. So I decided to repeat this algorithm without using gradient boost libraries. Looking forward it was useful experience for understanding of boost algorithm.
You can change functions paramters and watch the effect on the model quality.
___

2. gradient_descent_visualisation_

Visualisation of a two-dimensional gradient descent. It shows how the learning rate effects on speed and quality of model learning.
___

3. prediction_medicine_sales

The company is engaged in wholesale supplies of *** drugs to the Russian market. Due to imperfections in the existing forecasting tools, the warehouse regularly experiences overstock and out-of-stock situations. In the first case, the company incurs increased costs for maintaining inventory, while in the second case, it loses sales and, therefore, profit. The logistics pipeline (the time from ordering goods from the manufacturer to their delivery to the local warehouse) takes 6-8 months. To reduce these costs and improve forecasting accuracy, a new, more accurate tool is needed. It is necessary to develop a model that forecasts sales for 1, 3, and 12 months.

Project feature: the code must be optimized for use by inexperienced Python users. In other words, the end-user's intervention in the code should be minimal or completely absent.

To maintain confidentiality, the original data is distorted.
___

4. lung_cancer_os

Using kaggle dataset I created machine learning model which predicts lung cancer probability. Default data set was imbalanced - there were 270 objects with proven disease and only 39 healthy people. With this dataset the model gives excellent metrics but give out illogical conclusions. I assumed that the problem was in the data itself. To solve this problem I created a little survey for healthy people at Google.forms. When I had survey results from 130 people, I added them to the original data. This decision solved problem of imbalanced data, and model trained on new data gave great metrics and logically justified solutions.
