# task4 Bike-sharing rental prediction
## 题目描述
#### 根据日期时间、天气、温度等特征，预测自行车的租借量（predict bike rental count hourly or daily based on the environmental and seasonal settings）
## 数据
#### Bike-Sharing-Dataset.zip 
解压包中 day.csv 和 hour.csv 选其一，本项目选择的是hour.csv
## 数据分析
#### data_analysis.ipynb
## 特征工程与模型训练
#### model.ipynb
## 评价指标
![rmsle](https://github.com/jsheng2017/MachineLearningCourse/blob/master/task4/rmsle.png)
## 结果
 模型 | RMSLE值 
 ---- | ----- 
 LinearRegression   | 1.1042911495627106 
 Ridge  | 1.0714880917741527 
 Lasso  | 1.543475667153089
 RandomForestRegressor  | 1.697711134316645
 XGBRegressor  | 1.856336990888132
