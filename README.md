# Stock_timeseries
项目意义：金融时间序列是复杂金融市场的综合外在表现形式，
通过对金融时间序列的分析和预测，可以发掘金融市场潜在的内在关系和规律，为金融市场中投资者和决策者提供重要参考依据。
## 本仓库用于股票时序序列处理代码版本控制和管理
>  股票数据来自tushare网站提供的沪深股票日行情API
## 1 当前版本使用线性插值来处理时序序列存在的异常值
> tushare_pre.py为数据预处理代码
### 预处理流程
图片
## 2 预测模型
当前版本暂时使用LSTM结合TCN对序列进行预测，使用夏普损失函数对模型进行训练
> 损失函数参考链接 &emsp; https://arxiv.org/abs/2310.10500
 
