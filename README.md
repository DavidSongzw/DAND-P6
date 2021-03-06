# DAND-P6

## 概要

此次的数据选取了 IMDB 电影评价的数据。

两张可视化视图，第一张描述按照国家分类，随时间变化，电影投资与收入之间的关系。

第二张，描述评分总体分布概况。

## 设计

第一张，按照国家分类，用动画化的方式，展示了投资与收入，随着时间变化。可以点击按钮暂停，更仔细的观察图形。

设计初衷，动画方式更能有交互感，让用户可以自由探索。

第二张，使用柱状图，展示评分总体分布的关系。

设计初衷，用户方便观察，整个电影数据中，评分的分布情况，预计分布应该接近正态分布。

## 反馈

1.数据量过大，导致动画加载缓慢，甚至崩溃。过滤数据，减少样本量。

2.更改了展示样式，防止坐标轴展示不清晰。

3.添加便签，不同分类清楚辨别。

4.图二中，图形表达模糊，会混淆读者。x轴是电影评分，y轴是表达当前评分电影数量。

## 资源

数据来自：[kaggle](https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset) 在 data 目录下。

d3.js 和 dimple.js 库在 lib 下。

html 中为历史版本文件。

根目录下 index.html 为最终版本。
