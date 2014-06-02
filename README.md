Ali_Data_Mining
===============

 阿里巴巴大数据竞赛
 
 [官网](http://102.alibaba.com/competition/addDiscovery/index.htm)
 

 
 ##简介
 
 在天猫，每天都会有数千万的用户通过品牌发现自己喜欢的商品，品牌是联接消费者与商品最重要的纽带。本届赛题的任务就是根据用户4个月在天猫的行为日志，建立用户的品牌偏好，并预测他们在将来一个月内对品牌下商品的购买行为。

 
 ##数据类型
 
 - 字 段	字段说明	提取说明
 
 - user_id	用户标记	抽样&字段加密
 
 - Time	行为时间	精度到天级别&隐藏年份
 
 - action_type	用户对品牌的行为类型	包括点击、购买、加入购物车、收藏4种行为 (点击：0 购买：1 收藏：2 购物车：3）
 
 - brand_id	品牌数字ID	抽样&字段加密

 用户对任意商品的行为都会映射为一行数据。其中所有商品ID都已汇总为商品对应的品牌ID。用户和品牌都分别做了一定程度的数据抽样，且数字ID都做了加密。所有行为的时间都精确到天级别(隐藏年份)。

 
 ##评估指标

最后我们用F1-Score 来拟合准确率与召回率，并且大赛最终的比赛成绩排名以F1得分为准。 

 
 
 ##实现算法

 - 逻辑回归
 
 - 随机森林
 
 - 贝叶斯
 
 
