# ML-Project-2-Drug-Sales


#### Project Goal

The goal for this project was to predict future classes of drug sales for the following:
* N02BA - Analgesics and Antipyretics, Salicylic Acid and derivatives
![](Pictures/BA.JPG)

* N05B - Psycholeptics drugs, Anxiolytic drugs
![](Pictures/B.JPG)

#### Conclusion

There are less consumptions of N05B & N02BA classes of drugs over time. There I would not rely on the final models built to predict drug sales for the classes of drugs I was interested in. I used five different regression models and selected the best three performing models using the results from the cross validation function. The following final models used on the test dataset, N02BA, and their RMSE and R2 respectively are:

* Linear Regression (MAE: 7.29, RMSE: 8.86)
![](Pictures/lr.JPG)

* Polynomial Regression (MAE: 7.30, RMSE: 8.88)
![](Pictures/po.JPG)

* Random Forest Ression (MAE: 9.47, RMSE: 11.22)
![](Pictures/r.JPG)

* Gradient boosting (MAE: 8.86, RMSE: 10.62) 
![](Pictures/gb.JPG)

#### Data Source

This dataset was obtained from [Kaggle!](https://www.kaggle.com/milanzdravkovic/pharma-sales-data?select=salesdaily.csv) Please visit the link if you would like to understand what each feature represents in detail.  
 

