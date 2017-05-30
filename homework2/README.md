## 第二次作業

####(1)Gradient Boosting
>設定固定參數
>>min_samples_split = 500?
>>min_samples_leaf = 50 
>>max_depth = 8 
>>max_features = ‘sqrt’? 
>>subsample = 0.8? 
>調整參數[使用教學](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)
>>{'n_estimators': 80}
>>{'max_depth': 9, 'min_samples_split': 200}
>>{'min_samples_leaf': 60, 'min_samples_split': 1200}
>>{'max_features': 4}
>>{'n_estimators': 80}
>>最後使用cross_val_score計算



