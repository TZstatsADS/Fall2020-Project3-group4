# Project: Can you recognize the emotion from an image of a face? 
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2020

+ Team 4
+ Team members
	+ Citina Liang
	+ Xujie Ma
	+ Charles Shin
	+ Rohan Uppuluri
	+ Xinyi Wei

+ Project summary: In this project, we created a classification engine for facial emotion recognition. Using Gradient Boosting Machines as our baseline model, we did the following research and optimization.
	+ Improved feature extraction method and got one with less calculation time and higher test accuracy
	+ Implemented various models including KNN, XGBoost, Random Forest, LDA, Logistic Regression, SVM, Lasso
	+ Used SMOTE(oversampling/undersampling) technique and did hyperparameter tuning to solve imbalanced classification problem in various models
	+ Selected XGBoost with SMOTE as the best model after cross validation with higher AUC and balanced accuracy score and acceptable prediction time
	+ Predicted test accuracy on the new test dataset was about 70%
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. Rohan Uppuluri implemented the GBM, KNN, and SMOTE Bagging models. Rohan also wrote the documentation for the main notebook. Xujie Ma did feature improvement, implemented XGBoost model and organized the slides for presentation. Citina built SVM and Lasso models and did hyperparameter tuning to improve the models. And Citina also did the 10-fold cross-validation on weighted SVM and weighted Lasso. Xinyi Wei implemented the Random Forest Model, LDA and Logistic model. Xinyi also did the 10-fold cross-validation on weighted Logistic. Charles Shin implemented the Naive bayes model, contributed to the presentation slides, and edited the Github repository descriptions.



Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
