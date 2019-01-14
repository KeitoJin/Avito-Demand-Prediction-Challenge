# Avito-Demand-Prediction-Challenge<br>
Avito（ロシアのCtoCオンライン売買プラットフォーム）上の出品広告の売買成約率予測<br>
## 1.使用データ <br>
Avito Demand Prediction Challenge<br>
https://www.kaggle.com/c/avito-demand-prediction<br>
<br>
<img src="Images/2.Avito.jpg"><br>
## 2.分析の流れ <br>
<img src="Images/3.Avito.jpg"><br>

## 3.データの確認 <br>

`.info()`でデータ内容確認
<br>

```<class 'pandas.core.frame.DataFrame'><br>
RangeIndex: 1503424 entries, 0 to 1503423<br>
Data columns (total 18 columns):<br>
item_id                 1503424 non-null object<br>
user_id                 1503424 non-null object<br>
region                  1503424 non-null object<br>
city                    1503424 non-null object<br>
parent_category_name    1503424 non-null object<br>
category_name           1503424 non-null object<br>
param_1                 1441848 non-null object<br>
param_2                 848882 non-null object<br>
param_3                 640859 non-null object<br>
title                   1503424 non-null object<br>
description             1387148 non-null object<br>
price                   1418062 non-null float64<br>
item_seq_number         1503424 non-null int64<br>
activation_date         1503424 non-null object<br>
user_type               1503424 non-null object<br>
image                   1390836 non-null object<br>
image_top_1             1390836 non-null float64<br>
deal_probability        1503424 non-null float64<br>
dtypes: float64(3), int64(1), object(14)<br>
memory usage: 206.5+ MB

```
<br>
欠損値の多い`param_2`、`param_3`は使わない
他の欠損値の埋めていく<br>

## 4.
