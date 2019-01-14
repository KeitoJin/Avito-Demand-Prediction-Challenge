# Avito-Demand-Prediction-Challenge<br>
Avito（ロシアのCtoCオンライン売買プラットフォーム）上の出品広告の売買成約率予測<br>
## 1.使用データ<br>
Avito Demand Prediction Challenge<br>
https://www.kaggle.com/c/avito-demand-prediction<br>
<br>
<img src="Images/2.Avito.jpg"><br>
### 2.分析の流れ
<img src="Images/3.Avito.jpg">
<br>
### 3.データの確認
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1503424 entries, 0 to 1503423
Data columns (total 18 columns):
item_id                 1503424 non-null object
user_id                 1503424 non-null object
region                  1503424 non-null object
city                    1503424 non-null object
parent_category_name    1503424 non-null object
category_name           1503424 non-null object
param_1                 1441848 non-null object
param_2                 848882 non-null object
param_3                 640859 non-null object
title                   1503424 non-null object
description             1387148 non-null object
price                   1418062 non-null float64
item_seq_number         1503424 non-null int64
activation_date         1503424 non-null object
user_type               1503424 non-null object
image                   1390836 non-null object
image_top_1             1390836 non-null float64
deal_probability        1503424 non-null float64
dtypes: float64(3), int64(1), object(14)
memory usage: 206.5+ MB
