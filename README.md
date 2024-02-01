# Module 12 Report Template

### Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

### Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    - Precision for Healthy loans is exceptional wihth a score of 1.00, we can have confidence that there are no false positives.
    - Recall for Healthy Loans is .99 and can correctly identify almost all.
    - F1-Score for Healthy Loans is 1.00 which idicates a favorable performance of the model.
    - Precision for High-Risk Loans is good, but not the best with a .85 meaning we will get some false positives.
    - Recall for High-Risk Loans id .91 which is strong and has a good ability to correctly identify.
    - F1-Score for High-Risk Loans is .88 which is favoraable performance even though there is an imbalance.

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    
     **Healthy Loans**
     - Precision has not changed and no false postives.
     - Recall is the same, and can accuratly identify.
     - F1-Score is same and shows good performance.
       
     **High-Risk Loans**
     - Precision has decreased, which may indicate that it will have moe false positves,
     - Recall has increased to .99 where it can correctly identify with accuracy.
     - F1-Score has slightly increased to stronger .91 and providing improved performance even with a lower precision value.

### Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
 - The second model performes best, and despite the resuls of Healthy loans do not change the increased performance and imrroved abliity to acuratley identify for Healthy Loans is a good indication of a better model esepecially for imbalalanced datasets.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
 - The performance is relative to the problem at hand, sometimes we just need something to do the job and sometimes we focus on the performance to compensate for instances of data imbalances. Especially when we a indentifying high_risk loans because the costs of missing high-risks loans are inestimable and can lead to unecessary losses.
