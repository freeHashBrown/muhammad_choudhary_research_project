# muhammad_choudhary_research_project
The is the repository for the Artificial Intelligence Research Assignment 

# Abstract

Regression models can be trained to predict the alcohol levels from the many features of red wine. The PyCaret library and its many methods are used to create these regression models. The top 3 best models based on R2 were found to be Light Gradient Boosting Machine (LGBM), Extra Trees Regressor and Random Forest Regressor. The regular non-tuned (regular) LGBM model was found to have a higher R2 of 0.694 compared to the tuned LGBM model. Then a stack and blend model is created with the top three best models. These two models are compared with a LGBM model created with bagging. The best overall method was found to be the stacked model that was made with the top three best models based on R2. The stack was also used to make predictions on the holdout set and unseen data where the alcohol label was dropped. The stacked model performed very well in predicting the alcohol level. Also, the most important features that affect the level of alcohol were found to be density, fixed acidity and residual sugar.

# Video Presentation

https://youtu.be/nlCSu5M9crE

