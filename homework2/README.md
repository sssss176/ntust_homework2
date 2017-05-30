## 第二次作業

####Gradient Boosting
>(1)設定固定參數
>>min_samples_split = 500?
>>min_samples_leaf = 50 
>>max_depth = 8 
>>max_features = ‘sqrt’ 
>>subsample = 0.8
####
>(2)[使用教學網址](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)
>調整後參數如下:
>>{'n_estimators': 80}
>>{'max_depth': 9, 'min_samples_split': 200}
>>{'min_samples_leaf': 60, 'min_samples_split': 1200}
>>{'max_features': 4}
>>{'n_estimators': 80}
####
>(3)最後使用cross_val_score計算



