# Credit_Risk_Analysis

## Overview 

The purpose of this project is to apply different machine learning techniques to calculate credit card risk. 

## Resuilts

- Naive Random Oversampling

  When looking at the balanced accuracy score for the Naive Random Oversampling, the results showed a 64.08% accuracy. The results for the classification report showed the precision for the high_risk was .01 and low_risk was 1.00. This shows that the low_risk was the most precisie for this model. The recall for the high_risk was .65 and the low_risk was .63. When comparing these the different risk groups these are very similar and are both good since they are both over .5. The specificity rates for the high risk is .63 and the low risk is .65. For the f1 score for the high risk is .02 the low risk .77. The geo accuracy for the high and low risk are identical at .64. The iba accuracy are also similar at .41 for the high and low risk. The support for the high risk is 101 and the low risk was 17104. 
  
  [image1]()
  
-  SMOTE Oversampling

   When looking at the SMOTE Oversampling the balanced accuracy score is 66.28%. The results for the classification report show that the precision for the high risk is .01 and the low risk is 1.00. The recall for the high risk ais .63 and the low risk recall was .69 both groups recall are good since they are both over .5. The specificity for the high risk is .69 and the low risk is .63. The f1 accuracy for the high risk is .02 and the low risk is .82. The geo accuracy for the high and low risk is .66. The iba accuracy for tthe high and low risk is also very similar at .44. The support for the high risk is 101 and the low risk is 17104.
  
  [image1]()
  
- Undersampling
 
   The balanbced accuracy score for the undersampling model was 60.03%. The precision for the high risk was .01 and the low risk is 1.00. The recakk for the high risk was .67 and the low risk is .53. Both the recall for the high and low risk are good numbers since they are over .5. The specificity for the high risk was .53 and the low risk was .67. The f1 score for the high risk was .02 and the low risk was .69. The geo accuracy for the high and low risk are both .60. The iba accuracy for the high risk was .36 and the low risk was .35. Both the high and low risk had very similar iba accuracy. The support for the high risk was 101 and the low risk was 17104.
  
  [image1]()
  
 - Combination ( Over and Under) Sampling
 
   The balanced accuracy score for the combination was 60.34%. The precision for the high risk was .01 and the low risk was 1.00. The recall for the high risk was .67 and the low risk was .53. Both groups had a good recall since they are both over .5. The specificty for the high risk was .53 and the low risk was .67. The f1 accuracy for the high risk was .02 and the low risk was .69. The geo accuracy for both high and low risk was .60. The iba accuracy for the high risk was .36 and the low risk was .35. Both groups had a very similar iba accuracy. The support for the high risk was 101 and the low risk was 17104.
   
   [image1]()
   
 -  Balanced Random Forest Classifier
   
    The balanced accuracy score for the balanced random forest classifier was 75.73%. The high risk precision was .02 and the low risk was 1.00. The recall for the high risk was .63 and the low risk was .89. Both recalls for the groups had a good score since they are both over .5. The specificity for the high risk was .89 and the low risk was .63. The f1 accuracy for the high risk was .05 and the low risk was .94. The geo accuracy for both high and low risk was .75. The iba accuracy for the high risk group was .54 and the low risk was .57. The support for the high risk was 78 and the low risk was 17127. The top features with the highest importance ratings when calculating credit risk was total_rec_prncp, total_rect_int, last_pymnt_amnt, total_pymnt, and total_pymnt_inv.
   
   [image1]()
   
   [image1]()
 
 -  Easy Ensemle AdaBoost Classifier
    
    The balanced_accuracy score was 90.89%. THe precision accuracy for the high risk group was .07 and the low risk was 1.00. The recal for the high risk was .87 and the low risk was .95. The recall for both groups are good since they are both over .5. The specificity for the hgih risk group was .95 and the low risk group was .87. The f1 accuracy for the high risk group was .13 and the low risk group was .97. The geo accuracy for both and highb are .91. The iba accuracy for the high risk was .82 and the low risk was .83. The support for the high risk group was 78 and the low risk group was 17127. 
    
    [image1]()
    
## Summary

Overall each model provided good results, meaning that the each models balanced accuracy score was over 50%. The model with the highest balanced accuracy score was the Easy Ensemble AdaBoost Classifier. I would recommend uising the Easy Ensemble AdaBoost since the balanced accuracy score was 90% and the recall accuracy was the highest for both the high risk and low risk groups when comparing them to the other models.
