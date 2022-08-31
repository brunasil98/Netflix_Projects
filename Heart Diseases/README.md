# Predicting Heart Diseases In Medical Patients

  The dataset we chose was the Heart Disease dataset provided by UCI Machine Learning Repository. The dataset column to be tested will be the “target” column which will tested against the remaining columns to determine if we will be able to predict which patients will have heart diseases and if we are able to predict these cases. Through our different process methods, we hope to identify which will provide us the best results.
  
  This is how the data set looks. The columns age and sex have the biggest correlation with the target (diseases or no diseases).

![image](https://user-images.githubusercontent.com/75848451/152437074-09b7a1eb-c9cf-49a1-be85-a364a3d4062a.png)


  The data has a bad distribution, while the first half of the rows was positive diseases, the other half was no diseases. 

![image](https://user-images.githubusercontent.com/75848451/152438399-da6810c5-dc60-495a-b4f8-e9220d152f1b.png)

  The data is unbalanced, while the true values represent almost 55% of the data. 
  
![image](https://user-images.githubusercontent.com/75848451/187599722-a0ddc415-41eb-4724-94b8-4e1b30e5cecf.png)

  We chose 5 differents models, Logist Regression, KNeighborsClassifier, Decision tree, Random Forest, and SVM, and tune their hyperparameters, using sklearn modulation. We split our data 80% as train the other 20% as test. To evaluate the model, we calculate the accurancy value, the recall, and AUC values. The accuracy of the best model was 86,96%. The model achived its goal, which was decreasing the false negative from 0.19 to only 0.086 error.

![image](https://user-images.githubusercontent.com/75848451/152655021-12069f71-9784-418e-b09a-dcacd0c0d4fc.png)

 In this project, we created models to predict if the person has a heart diseases or not. We used two different approaches, one a linear regression, and second random forest classifier with balanced data. The second model has a better prediction and smaller error in false negative, which is crucial in biomedical field. The next steps would be the analysis of the false negative and try to find any relation between them. 
