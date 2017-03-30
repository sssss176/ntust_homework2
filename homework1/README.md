## 第一次作業
#### 第一次作業

####(1) 哪些屬性對於惡意程式分類有效？
>列舉前五名屬性，
>>1. feature section_names_.tls (0.013089) 
>>2. feature ent_p_4 (0.005496) 
>>3. feature ent_p_6 (0.005352) 
>>4. feature FileSize (0.005232) 
>>5. feature Img13 (0.005084) 
####(2) 哪些屬性對於惡意程式分類無效？
>列舉前五名屬性約有19個特徵importances為0
>>1800. feature WSACleanup (0.000000) 
>>1801. feature GetVersionExW (0.000000) 
>>1802. feature __vbaAryMove (0.000000) 
>>1803. feature GetWindowOrgEx (0.000000) 
>>1804. feature CreateWindowExW (0.000000) 

####(3) 用什麼方法可以幫助你決定上述的結論？
> 使用Feature importances with forests of trees
[使用教學](http://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html)
####(4) 透過Python哪些套件以及方法可以幫助你完成上面的工作？
> import numpy as np
> import pandas as pd
> from sklearn.ensemble import ExtraTreesClassifier
####(5) 課程迄今有無建議？
> 無

