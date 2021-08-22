# Credit Risk Analysis

Overview of the loan prediction risk analysis:
To better understand credit risk with unbalanced classes, I resampled this data set using multiple machine learning methods. 

Example:


Results:

### RandomOverSampler

      *Balanced Accuracy: 52%
  
      *Precision: High Risk 0.01, Low Risk 1.00
  
      *Recall: High Risk 0.57, Low Risk 0.46
      
### SMOTE
      *Balanced Accuracy: 65%
  
      *Precision: High Risk 0.01, Low Risk 1.00
       
       *Recall: High Risk 0.66, Low Risk 0.64
      
### ClusterCentroids

      *Balanced Accuracy: 52%
  
      *Precision: High Risk 0.01, Low Risk 1.00
  
      *Recall: High Risk 0.57, Low Risk 0.46
      
      
 ### SMOTEENN

      *Balanced Accuracy: 63%
  
      *Precision: High Risk 0.01, Low Risk 1.00
  
      *Recall: High Risk 0.69, Low Risk 0.56
      
      
### BalancedRandomForestClassifier

      *Balanced Accuracy: 82%
  
      *Precision: High Risk: 0.04, Low Risk 1.00
  
      *Recall: High Risk: High Risk 0.72, Low Risk 0,91
      
      
 ### EasyEnsembleAdaBoostClassifer

      *Balanced Accuracy: 82%
  
      *Precision: High Risk: 0.04, Low Risk 1.00
  
      *Recall:   High Risk 0.72, Low Risk 0,91  

Summary:

I think more data is needed to make an accurate reccomendation. 
