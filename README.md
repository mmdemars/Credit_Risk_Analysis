# Credit_Risk_Analysis

## Overview of the analysis: 
Explain the purpose of this analysis.
Using credit card credit dataset from LendingClub, different techniques have been utilized to emplot different techniques to train and evaluate models to assess credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 


## Results: 
Credit Risck Resampling
- Oversampling - In the Oversampling test the Precision was 99%, the Recall was 59% and the f1 score was 73%.
- SMOTE Oversampling - In the SMOTE Oversampling test the Precision was 99%, the Recall was 69%, and the f1 score was 81%.
- Undersampling - In the Undersampling test, the Precision was 99%, the Recall was 40% and the f1 score was 56%.
- Combination Sampling - In the Combination Sampling test, the Precision was 99%, the Recall was 57%, and the f1 score was 72%.
- Balanced Random Forest Classifier - In the BRFC test, the Precision was 99%, the Recall was 87%, and the f1 score was 93%.
-Easy Ensemble AdaBoost Classifier - if the AdaBoost Classifier, the Precision was 99%, the Recall was 94%, and the f1 score was 97%.


## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
All six models had a Precision score of 99%,. The Recall scores varied from 40% on the Undersampling to 94% on the Easy Ensemble AdaBoost Classifier. The f1 scores varied from 56% on the Undersampling, to 97 on the Easy Ensemble AdaBoost Classifier. Overall the Easy Ensemble AdaBoost Classifier preformed much better overall than any of the other models. Given the idea that "good loans easily outnumber risky loans" this would be the recommended model for a Lender who wanted to ensure that no good loans were missed. A more cautious Lender might prefer to default to the Undersample test, and individually review any loan applicantss rejected by it.