
数据构成：

<img width="200" height="250" alt="数据构成" src="https://github.com/user-attachments/assets/02c1e98d-ee1a-4991-b700-12c18a3a248b" />

原数据集：1599只眼睛，眼前5649张，眼底2778张

筛选后数据集：1290只眼睛，眼前3253张，眼底2281张 
***
流程：
  
<img width="600" height="250" alt="流程" src="https://github.com/user-attachments/assets/3cf28ada-1afb-4c1a-825f-126c722eac9d" />

***
结果：

原数据集：眼前：AUC: 0.683  ACC: 0.643 

筛选后数据集：眼前：AUC: 0.744  ACC: 0.686

***
Agent：

1.眼底照判别模型(RETFound)

2.眼前节判别模型(知识蒸馏框架)

3.视杯视盘比计算模型

4.病人描述文本信息
