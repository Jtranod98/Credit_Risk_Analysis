# Credit_Risk_Analysis

# Overview:

The purpose of this excercise is to use different machine learning models to make a loan prediction risk analysis. Evaluate the performance of six different sampling models: RandomOverSampler, SMOTE, clusterCentroids, MOTEENN, BalancedRandomForestClassifier, EasyEnsembleClassifier. Then, recommend whether they should be used to predict credit risk.

# Results: 

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
Use screenshots of your outputs to support your results.


  1. RandomOverSampler:
  2. SMOTE:
  3. clusterCentroids:
  4. MOTEENN:
  5. BalancedRandomForestClassifier:
  6. EasyEnsembleClassifier
  


# Summary: 
There is a summary of the results (2 pt)
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 

  - The summary table shows that the balanced accuracy scores ranges from 0.54 to 0.93.  ClusterCentroids method has the lowest score of 0.54 and EasyEnsembleClassifier has the highest score of 0.93.  Since EasyEnsembleClassifier has highest accuracy score, it also means that it has the higest percentage of predictions that are correct. 
  
  - The precision scores of low risk loans are the same in all all sampling methods(RandomOverSampler, SMOTE,clusterCentroids, MOTEENN),score of 1.  This means all methods are able to predict low risk loans equally.
  
  - The precision scores of high risk loans are equal, 0.01, for all four resampling methods.  However the two ensemble methods (BalancedRandomForestClassifier, EasyEnsembleClassifier) have are higher scores 0.03 and 0.09, respectively.  This means the resampling methods are able to predict high risk loans better than the ensemble methods, 99% correct vs. 97%, and 91%.
  
  - The recall scores are less consistence between methods.  In the high risk loans the scores ranges between 0.63 to 0.92.  SMOTE has the lowest score of 0.63 and EasyEnsembleClassifier has the highest score of 0.92.  Which means 92% were correctly predicted .
  In the low risk loans ranges between 0.59 to 0.94. Again, EasyEnsembleClassifier has the highest score of 0.94.
   
  - Ensemble classifiers methods have lower precision but higher recall at the high risk loans the random methods were better. at 99.09 vs. .03 and .93 for BalancedRandomForestClassifier and EasyEnsembleClassifier respectively.

  - I recommend using the EasyEnsembleClassifier, due to the fact that it has a very high accuracy scores and recall scores; 93% correctly predicted all the loan, 92% at predicting correctly high risk loan and 94% at predicting low risk loans. 
