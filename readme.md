# XGBoost-Learning-Notes

## 第一讲: 初识XGBoost

一、XGBoost简介
- Gradient Boosting简介  
- XGBoost的特别之处  

二、XGBoost的优势  
- 速度  
- 性能  

三、与XGBoost的第一次亲密接触  
- 数据科学任务的一般处理流程
- XGBoost独立使用
- 与scikit-learn一起使用（学习率、交叉验证）

四、案例：XGBoost安装包自带数据集（蘑菇分类）



## 第二讲：暂别XGBoost

一、监督学习
- 模型
- 参数
- 目标函数（损失、正则、过拟合／欠拟合）
- 优化：梯度下降、常用损失函数的梯度推导

二、分类回归树
- 模型／参数／目标函数／优化（分裂与剪枝）

​三、随机森林
- Bagging／行、列随机采样

四、案例：Kaggle蘑菇分类任务


## 第三讲：重回XGBoost

一、Boosting
- 基本思想
- AdaBoost

二、Gradient Boosting
- 基本框架
- L2Boosting／AdaBoost

三、XGBoost
- 性能改进：规范的正则、损失函数二阶近似、建树&剪枝、缺失值处理
- 速度改进：稀疏特征、并行、Cache、分布式

四、案例：Kaggle的Allstate Instance Claim任务

 

## 第四讲：XGBoost实战

一、特征工程

常规数据检查流程
特征类型变换编码
特征工程一般原则

二、XGBoost参数调优

评估准则
复习交叉验证
三、XGBoost其他高级应用
多线程，并行  
四、案例：Kaggle的Two Sigma Connect：Rental Listing Inquiries任务