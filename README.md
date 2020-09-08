# ML-Project-2-Drug-Sales


#### Project Goal

The goal for this project was to predict future classes of drug sales for the following:
* N02BA - Analgesics and antipyretics, Salicylic acid and derivatives
![](Pictures/BA.JPG)

* N05B - Psycholeptics drugs, Anxiolytic drugs
![](Pictures/B.JPG)

#### Conclusion

I would not rely on the final models built to predict drug sales for the classes of drugs I was interested. I used five different regression models and selected the best three performing models using hte result from cross validation function. The following final models used on the test dataset, N02BA, and their RMSE and R2 respectively are:

* Linear Regression (RMSE: 36.53, R2: 0.076)
![](Pictures/lr.JPG)

* Polynomial Regression (RMSE: 38.13, R2: -0.007)
![](Pictures/po.JPG)

* Gradient boosting (RMSE: 45.73, R2: -0.448)
![](Pictures/gb.JPG)

With Linear regression (54% accuracy), polynomial regression, and gradient boosting (99% accuracy) as the best three performing models.


#### Data Source

This dataset was obtained from [Kaggle!](https://www.kaggle.com/milanzdravkovic/pharma-sales-data?select=salesdaily.csv) Please check out the link if you want to understand what each feature represents in detail.  
 

