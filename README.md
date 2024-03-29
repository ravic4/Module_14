# Module_14
### The Module 14 homework was completed with the assistance of Shah
* Goal: Create a trading strategy using ML model. 

### Findings: 

            precision    recall  f1-score   support

        -1.0       0.43      0.04      0.07      1804
         1.0       0.56      0.96      0.71      2288

    accuracy                           0.55      4092
   macro avg       0.49      0.50      0.39      4092
weighted avg       0.50      0.55      0.43      4092


              precision    recall  f1-score   support

        -1.0       0.44      0.33      0.38      1804
         1.0       0.56      0.66      0.61      2288

    accuracy                           0.52      4092
   macro avg       0.50      0.50      0.49      4092
weighted avg       0.51      0.52      0.51      4092


Model two is different than model one. With the F-1 score being very low for -1 (at 0.07) for model 1, vs model 2 which is 0.38. The classification report for Model 2 however, is less accurate than model 1. 

Method: 
1. ReadCSV 
2. Obtain the SMA fast and Slow
3. Create classification reports from scaled data (twice)
4. Screenshotted the outputs. 

Findings: 
* Graph_1 strategy outperforms Graph_2 performance, as the Strategy returns fall between mid 2021 to end of 2021 (versus the Graph_1 where performance rises at the end). 
