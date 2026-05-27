
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



杯盘比(CDR):

总计422张眼底，失败35(检测不到视杯或视盘)

CDR Range: 0.1313 - 0.7426

Average CDR: 0.3192

CDR <0.3: 216 images

CDR 0.3-0.6: 157 images

CDR ≥0.6: 14 images

***
Agent：

1.眼底照判别模型(RETFound)

2.眼前节判别模型(知识蒸馏框架)

3.视杯视盘比计算模型

4.病人描述文本信息

结果：

<img width="640" height="331" alt="image" src="https://github.com/user-attachments/assets/3f019a6e-5250-4e49-9590-329c7e89d5f9" />




***






<img width="607" height="551" alt="image" src="https://github.com/user-attachments/assets/75fd1267-84b6-421f-8fd4-2cac09a930dc" />

<img width="595" height="211" alt="image" src="https://github.com/user-attachments/assets/199808e1-6432-4022-8aff-0f475eb6e317" />

