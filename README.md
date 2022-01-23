# Credit_Risk_Analysis

### Overview
In this analysis, elements of Statistical Reasoning and Machine Learning are used to evaluate the credit risk of individuals seeking loans. 
As this type of risk can be difficult to assess, 6 different machine learning models were used in assessing credit risk. We weighed which model and approach would predict high accuracy based on the classification reports of each.  


### Results
The results of each machine learning model can be found below.

#### Naive Random Oversampling

* Accuracy Score: 63%
* Precision Score: 99%
* Recall Score: 65%

![image](https://user-images.githubusercontent.com/89872154/150699210-e12b5dda-b9d0-494b-9e95-76381319fe60.png)

#### SMOTE Oversampling

* Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 66%

![image](https://user-images.githubusercontent.com/89872154/150699239-b3a7e9f8-2587-49b5-9e07-5845fa853b56.png)

#### Undersampling

* Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 44%

![image](https://user-images.githubusercontent.com/89872154/150699325-1997f674-8604-4d01-bef0-b55ac1eaad24.png)

#### Combination (Over and Under) Sampling

* Accuracy Score: 51%
* Precision Score: 99%
* Recall Score: 57%

![image](https://user-images.githubusercontent.com/89872154/150699341-8e059958-897a-4693-946f-e5580fd59210.png)


#### Balanced Random Forest Classifier 

* Accuracy Score: 77%
* Precision Score: 99%
* Recall Score: 87%

![image](https://user-images.githubusercontent.com/89872154/150699487-d4a3594d-5706-428c-8865-2e0dc8e85967.png)

#### Easy Ensemble AdaBoost Classifier 

* Accuracy Score: 92%
* Precision Score: 99%
* Recall Score: 94%

![image](https://user-images.githubusercontent.com/89872154/150699541-8fcacda3-315f-4ae3-91a4-a3abeed6222b.png)


### Summary

In this particular example, when evaluating credit risk, it is important to have a high level of sensitivity or recall as well as accuracy and precision. The results from the Easy Ensemble AdaBoost Classifer returned the most favorable results with the only Machine Learning Model to score above 90% for all three recorded metrics. Of special importance is the high Recall Score of 94%. Given this high measure of sensitivity, this is the reccomended model to use when evaluating credit risk.
