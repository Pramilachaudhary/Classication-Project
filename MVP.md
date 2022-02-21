## Baseline Classification Model for Determining Poisonous Mushrooms
The goal of this project is to build a classification model which determines whether a mushroom is poisonous or not 
for a Food Science Lab who are interested in studying poisonous mushrooms for medicinal properties. 

I have built a baseline Decision Tree model fit to the numerical features without null values and the target, Class (P:1, E:0) where P = Poisonous and E = Edible

<img width="452" alt="Screen Shot 2022-02-21 at 2 38 24 PM" src="https://user-images.githubusercontent.com/89863226/155034236-d39c3146-72ee-4b99-8ee0-64ce5c1bff9e.png">

the above heat map shows cap-diameter and stem-width are highly correalted with the target. so I used these two features for baseline Decision Tree model

**This model has an accuracy score of 0.77

Confusion matrix:

<img width="468" alt="Screen Shot 2022-02-21 at 2 42 31 PM" src="https://user-images.githubusercontent.com/89863226/155034536-3bf27187-0334-4db1-b734-7ec45afe88b8.png">

I am considering Recall and F1 score to measure the success of a model. 

Recall score for the model is  0.765
F1 score for the model is 0.788
