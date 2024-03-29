# Advanced-Modeling (Machine Learning)

## Theory
We made the decision or predict replying on our own experience. For example, when we see the clear blue sky after it rained we can predict it will be sunny tomorrow. How did we know? Because we've already experienced it and depending on that we can do the prediction. Likewise, by using machine learning algorithm we can make the model for the prediction using the data which is the experience for human prediction. 

Apart from the data, we need some results to make the model and we call this as labels. If our prediction has the binary results then we call this **classification**. <br/>
If the result is continuous value then we call this **regression**.

Depending on the fact if tain data contains labels or not, learning can be divided as **supervised learning** or **unsupervised learning**. <br/>
We assume data shows independent and identical distribution (i.i.d.). <br/>
Machine learning algorithms' bias towards specific hypothesis is called **inductive bias** or **bias**. <br/>

There are three core technology in the big data era that are machine learning, cloud computing, and crowdsourcing. <br/>
Many areas in our reality such as weather forcasting, monitoring the environment, and sales area use machine learning methods. <br/>
For example, in sales area, people can anlyze cutomer's data using machine learning which enable us to do the **target marketing.** <br/>
Machine learning technology is crucial on the search engine companies such as NAVER, Google, and Baidu. <br/>
Search is the input, result is the output and the process for more sophisticated search engine is improved by machine learning method. <br/>
Machine learning method is also used in the political area. It helped a lot for Obama to be elected in the U.S. presidential election.

1. Hold out <br/>
   Divide data set into two subset which are train set and test set. <br/>
   Model which is trained with train set will be measured for the generalization error using test set.

2. Bootstrapping <br/>
   Making the subset of D' by selecting number of m data from the original data set permitting the overlaps. <br/>
   The probability that one data is not selected is **(1-1/m)m** and usually this is about 36.8% of the whole dataset. <br/>
   In this case we can use D/D' as train set and the other as test set (1/3 of m) then we would use all number of m data set.

3. Performance measure <br/>
   1) Mean squared Error
      1/m∑(f(xi)-yi)2
      f(xi): Prediction result
      yi: Answer data

4. Recall and Precision

TP/TP+FP (Number of true positive divided by number of things classified as positive)
TP/TP+FN (Number of true positive divided by number of real posive)

5. ROC (Receiver Operating Characteristic) and AUC (Area Under the ROC Curve)

X-axis: TPR (True Positive Rate) = TP/TP+FN - positive reference row <br/>
Y-axis: FPR (False Positive Rate) = FP/TN+FP - negative reference row

6. Unequal Error: there are two representative types of errors in the reality. For example, doctor can misdiagnose healthy patient as unhealthy one and the other way around. The former error just need one more diagnosis but latter would be a fatal error for the patient. This is the unequal error. 

7-1. Hypothesis Testing <br/>
We can use the test error rate to assume a distribution of normal error rates. This equation represents the probability of obtaining a test error rate ê when testing a learner with a general error rate e on a test set with m samples. 

<img width="385" alt="Screenshot 2024-03-26 at 21 45 07" src="https://github.com/CSSjieun/Advanced-Modeling/assets/152406885/d7de84b6-2a5f-4aff-ab95-ecfba7d799d3"> <br/>
Resource: 단단한 머신러닝, 조우쯔화, 48 page

7-2. Cross validation t-test




   

   
   



(Machine Learning, zhou zhihua)

### Supervised Learning

y = 

### Unsupervised Learning

## Code

### Supervised Learning

### Unsupervised Learning

