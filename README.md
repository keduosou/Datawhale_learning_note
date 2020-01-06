# 2019未来杯高校AI挑战赛 > 城市-房产租金预测
## Task01：赛题分析（2天）
### 认识数据
#### 1. 了解比赛的背景
* 线上比赛要求参赛选手根据给定的数据集，建立模型，预测房屋租金。

近几年，国内住房租赁市场进入全新的发展阶段，长期公寓市场作为租赁市场的重要部分，越来越受到广泛的关注。但同时中国长期公寓市场也面临着企业市场进入、业务(门店)扩张、资本市场博弈、企业重组并购等多重挑战，其中，如何准确的预测租金便成为该行业发展进程中的一大难题。

本次赛题主要是通过房产市场、租赁市场、市场需求以及房屋配置来做出合理的房租预测，以应对市场变化对运营商和房产机构带来的影响。命题方向为运用机器学习、人工智能等模型算法，结合模型的创新能力，来实现准确预测的目的。

#### 2. 分类问题还是回归问题
其实分类和回归的本质是一样的，都是对输入做出预测，其区别在于输出的类型。
* 分类问题：分类问题的输出是离散型变量(如: +1、-1)，是一种定性输出。(预测明天天气是阴、晴还是雨) 
* 回归问题：回归问题的输出是连续型变量，是一种定量输出。(预测明天的温度是多少度)。

本赛题为预测房产租金预测，所以应该是***回归问题***


#### 3. 熟悉比赛的评分函数

![评分函数](https://github.com/keduosou/Datawhale_learning_note/blob/master/%E8%AF%84%E5%88%86%E5%87%BD%E6%95%B0.jpeg)

拟合优度R方，应该和计量经济学里的R方是类似的。

总离差平方和***TSS=RSS+ESS***

即总离差平方和可分解为回归平方和残差平方和两部分。

拟合优度***R^2=ESS/TSS=1-RSS/TSS***

回归平方和反映了总离差平方和中可由样本回归解释的部分，它越大，残差平方和越小，表明你和程度越好。










