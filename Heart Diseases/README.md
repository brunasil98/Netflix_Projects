# Predicting Heart Diseases In Medical Patients

  The dataset we chose was the Heart Disease dataset provided by UCI Machine Learning Repository. The dataset column to be tested will be the “target” column which will tested against the remaining columns to determine if we will be able to predict which patients will have heart diseases and if we are able to predict these cases. Through our different process methods, we hope to identify which will provide us the best results.
  
  This is how the data set looks. The columns age and sex have the biggest correlation with the target (diseases or no diseases).

![image](https://user-images.githubusercontent.com/75848451/152437074-09b7a1eb-c9cf-49a1-be85-a364a3d4062a.png)


  The data has a bad distribution, while the first half of the rows was positive diseases, the other half was no diseases. 

![image](https://user-images.githubusercontent.com/75848451/152438399-da6810c5-dc60-495a-b4f8-e9220d152f1b.png)

  The data is unbalanced, while the true values represent almost 55% of the data. 
  
![image](https://user-images.githubusercontent.com/75848451/187599722-a0ddc415-41eb-4724-94b8-4e1b30e5cecf.png)

  We chose 5 differents models (Logist Regression, K-Neighbors, Decision tree, Random Forest, and SVM) and tuned their hyperparameters using sklearn modulation. We split our data 80% as train the other 20% as test. To evaluate the model, we calculate the accurancy, the recall, and AUC values. The K-Neighbors has the best accuracy with 84,9%, but the SVC has the best recall value, as 97%. 

!![image](https://user-images.githubusercontent.com/75848451/187725106-6e8aebda-99ae-4e2f-8d78-8bfe04e8bd3a.png)

 In this project, we created models to predict if the person has a heart diseases or not. We used five different approaches, one a linear regression,  second a K-Neighbors, third a  random forest classifier,  fourth decision tree and fifth a SVM. The K-Neighbords has a better prediction and SVC smaller type 2-error \e, which is crucial in biomedical field. 
