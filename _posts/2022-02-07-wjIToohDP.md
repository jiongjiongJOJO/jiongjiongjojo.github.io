---
title: 《天池龙珠 - 机器学习训练营》02.机器学习算法： 基于XGBoost的分类预测 学习笔记
author: 囧囧JOJO
top: false
cover: false
mathjax: false
tags: [机器学习, 天池龙珠, 笔记, 入门]
date: 2022-02-07 11:52:03
img:
coverImg:
password:
summary:

---
# 一、学习知识点概要
简单介绍一下XGBoost，并对比XGBoost的优缺点和历史发展及应用。
借助天气数据集进行XGBoost模型的训练测试预测的分类实战。
最后介绍XGBoost模型的重要参数含义和XGBoost模型的原理。


# 二、学习内容
了解到了XGBoost的历史背景及使用XGBoost的应用成果。
复习了XGBoost的优缺点，对XGBoost认识更加清晰。
复习了数据可视化的操作。
了解了seaborn绘图函数库的简单使用。
复习了XGBoost的训练与预测。
学习了利用 XGBoost 进行特征选择。
复习了XGBoost的一些重要参数。
学习了XGBoost的一些基本原理。

# 三、学习问题与解答
【问题描述】
这是我自己剔除的一个疑问，个人觉得有点矛盾，**希望有大佬在学习过程中，能帮助我解答一下。**大致描述如下：
摘抄天池实验室的教学文本中的两句话：

> XGBoost的主要优点：
> 2.高效可扩展。在处理大规模数据集时速度快效果好，对内存等硬件资源要求不高。

> XGBoost的主要缺点：
> 2.在拥有海量训练数据，并能找到合适的深度学习模型时，深度学习的精度可以遥遥领先XGBoost。

优点中说了处理大规模数据的速度比较好。缺点中说的是大量数据下，深度学习比XGBoost有优势。
那么，既然大量数据下深度学习优势更大，为什么不用深度学习框架呢，XGBoost的处理速度再快，正确率不高，也不能起到很好的作用啊。

# 四、学习思考与总结
通过本节的学习，让我回顾了集成学习中XGBoost的使用，并且了解了一些XGBoost的简单原理。
同时学习了一个从未接触过的函数库 —— seaborn绘图函数库。
并且对XGBoost有了一些自己的思考。

~希望大佬们能够对上面提出的问题进行指点~