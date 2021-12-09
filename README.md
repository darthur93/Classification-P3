# Classification-P3
Overview \
Business and Data Understanding\
  I am speaking to Wells of Life charity. We are proposing a model help predict the functionality of wells in Tanzania. As climate change decreases the stability of atmospheric systems, water has become increasingly important. Wells of Life is uniquely well suited to address the problem of water instability in Tanzania. Their primary locus of operation is located just to the north in Uganda.  The geographic proximity will make the deployment of resources comparitively cheap. We obtained a data set of wells in Tanzania to build a model.\
  I took 

Modeling\
I tried a variety of models to attempt to predict the functionality of the wells/
 The Dummy Model was just used as a baseline to evalute the other models.\ 
  Log Regression was remarably bad at predicting given this data set.\ 
  KNeighborsClassifier was an improvement over the log regression model, but its performance was underwhelming.\
  Decision Trees were very prone to overfitting. I compensated for this by using random forest classifiers.\ 
  Random Forests gave me my best model with an accuracy score of 80%\ 
  
  Bagged Trees were another attempt to use decision trees, but they were less effective at the task i desired.\ 
  
  Ensemble models also failed to improve upon the performance of the random forest classifier.
  Gradient Boosting wwas another method I used to improve the decision trees, but it also fell short of the random forest classifer.\ 
  
 Evaluation\
 ![image](https://user-images.githubusercontent.com/92397941/145320278-41fa3026-2bbb-4ff8-bb81-803823831ee4.png)

 Our random forest model can be used to predict the functionality of wells. This will become increasingly valueable as climate change increases water insecuty.  Our model performs well with an accuracy rate of 80%. I selected accuracy as the relavent metric, because well condition will be confirmed with human inspection before resource investment. As such, errors are not overly costly. This model had the best accuracy score on the test data. By predicting which wells will be functional, Wells of Life will be able to more effiently plan and distribute resources to address the problem of water insecurity./
Conclusion\
  We advise that Wells for Life addopt our model to predict where their resources will be best used in Tanzania. To start, we recomend that you address already identified targets (non functional wells) in the northern side of Tanzania. This is the closest point to your existing operations.\
README.md includes concise summary of project with all data science steps\
README.md links to presentation and sources\
README.md includes instructions for navigating the repository\

```
├── README.md                           <- The top-level README for reviewers of this project
├── notebook.ipynb                         <- Concise summary of the project with all data science steps
├── Project 3.pdf                       <- PDF version of project presentation
├── Data                                <- Both sourced externally and generated from code, includes exploratory notebooks
└── Images                              <- Both sourced externally and generated from code
```  

