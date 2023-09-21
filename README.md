# sms-spam
<br>Make project reference by paper [journal](https://arxiv.org/pdf/2110.15718v3.pdf)   <br>
 
 This model has scenario train split test data
 * train data 80% total data
 * test data 20% total data


  **Result** <br>
  `Evaluate metrics`
  ![8eaefedee3ea1ffc1fccb3a25ea4c5e2.png](:/c5de7364f3a24924b548f3e15672ac82)
  
  `Model total prediction`
  ![image](https://github.com/ackermanjayjay/sms-spam/assets/64537170/e89d4b36-08e7-44c2-b73d-38e8bb451e78) <br>
  
**Observation Model from image   Evaluate metrics and   Model total prediction**<br>

* K nearest neighbor
We can see evaluate metrics
accuracy 95%
recall 0.96
f1 score 0.96
Wrong prediction 53 total
correct prediciction 1062

* Naives bayes
We can see evaluate metrics
accuracy 96.95 %
recall 0.96
f1 score 0.96
Wrong prediction 34 total
correct prediciction 1081

* SVM
We can see evaluate metrics
accuracy 98%
recall 0.96
f1 score 0.96
Wrong prediction 18 total
correct prediciction 1097 

![f6d9df9d9a78fa513821e78eb3d42b54.png](:/dacbf4098c4142be841f33ca2cffde93)

![50648d35d7b3c89b99764a7c9679f326.png](:/cd53c05074ac4f2ba687c36668fc1ac1)

**Summary pie chart**
* Pie chart Wrong prediction
SVM 17.1 %
Naives bayes 32.4 %
KNN 50.5 %

* Pie chart Correct prediction
SVM 33.9 %
Naives bayes 33.4 %
KNN 32.8 %

* **KNN has most wrong prediction instead SVM and Naives bayes**
* **SVM has most correct prediction instead KNN and Naives bayes**