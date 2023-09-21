# sms-spam
<br>Make project reference by paper [journal](https://arxiv.org/pdf/2110.15718v3.pdf)   <br>
 
 This model has scenario train split test data
 * train data 80% total data
 * test data 20% total data


  **Result** <br>
  * Evaluate metrics <br>
  ![Evaluate metrics](/assets/metrics_models.PNG)
  
  * Model total prediction <br>
  ![Model total prediction](https://github.com/ackermanjayjay/sms-spam/assets/64537170/e89d4b36-08e7-44c2-b73d-38e8bb451e78) <br>
  
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
correct prediciction 1097 <br>

**Pie chart prediction**
![summary_wrong_predict](/assets/pie%20chart%20wrong%20predict.PNG)
![summary_right_predict](/assets/pie%20chart%20correct%20predict.PNG)


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