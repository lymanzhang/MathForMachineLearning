## Probability and Statistical Inference 概率与统计推断

### [http://en.wikipedia.org/wiki/Machine_learning](http://en.wikipedia.org/wiki/Machine_learning)

- Machine Learning: "a branch of artificial intelligence, concerns the construction and study of systems that can learn from data."

- 机器学习：机器学习理论主要是设计和分析一些让计算机可以自动“学习”的算法。机器学习算法是一类从数据中自动分析获得规律，并利用规律对未知数据进行预测的算法。

---------------------------------------------------------------------------

## 概率vs. 统计

- 概率：研究随机事件出现的可能性的数学分支
  – 给定以一个数据产生过程，输出的性质?

- 统计推断：处理数据分析和概率理论的数学分支，与数据挖掘和机器学习是近亲
  – 给定输出数据，该数据的产生过程?

## 概率统计基础的重要性
- 研究数据分析必须打好概率和统计基础

  – Using fancy tools like neural nets, boosting and support vector machines without understanding basic statistics **_like doing brain surgery before knowing how to use a band-aid_**.
  

## 概率
- 概率基础
  – 概率公理及推论
- 随机变量及其分布： pmf/pdf、CDF、均值、方差…
- 常用随机变量分布
  – 离散型随机变量、连续性随机变量
- 多元随机向量
  – 联合概率、条件概率
  – 常用多元分布
  – 条件独立及Markov相关模型
- 概率密度估计
  – 参数估计/非参数估计/准参数估计

## 统计推断
- 大数定律
- 中心极限定理
- 蒙特卡洛近似
- 极大似然估计
  – 似然函数
  – 偏差-方差分解、Bootstrap
- 贝叶斯估计
  – 共轭先验、似然、后验、后验预测

## 参考书推荐

![Machine Learning](https://github.com/lymanzhang/MathForMachineLearning/blob/master/01_Probability%20and%20Statistical%20Inference/images/Kevin%20P.%20Murphy_Machine%20Learning_A%20Probabilistic.jpg)

- [Kevin P. Murphy, **Machine Learning: A Probabilistic Perspective**, MIT Press, 2012](https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020/ref=sr_1_2?ie=UTF8&qid=1336857747&sr=8-2)

![All of Statistics](https://github.com/lymanzhang/MathForMachineLearning/blob/master/01_Probability%20and%20Statistical%20Inference/images/Larry%20Wasserman_All%20of%20Statistics_A%20Concise%20Course%20in.jpg)

- [Larry Wasserman, **All of Statistics: A Concise Course in Statistical Inference** (Springer Texts in Statistics)](https://www.amazon.com/All-Statistics-Statistical-Inference-Springer/dp/1441923225/ref=sr_1_1?ie=UTF8&qid=1500723606&sr=8-1&keywords=All+of+Statistics%3A+A+Concise+Course+in+Statistical+Inference)

![统计学完全教程](https://github.com/lymanzhang/MathForMachineLearning/blob/master/01_Probability%20and%20Statistical%20Inference/images/Larry%20Wasserman_All%20of%20Statistics_cn.jpg)

– 中译本：[现代数学译丛5: **统计学完全教程**](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B01CGO67PE/ref=sr_1_1?ie=UTF8&qid=1500723678&sr=8-1&keywords=%E7%BB%9F%E8%AE%A1%E5%AD%A6%E5%AE%8C%E5%85%A8%E6%95%99%E7%A8%8B) L.沃塞曼 (Larry Wasserman) (作者), 张波 (译者), 刘中华 (译者), 魏秋萍 (译者), 代金 (译者) – 2008年6月1日

![概率论与数理统计](https://github.com/lymanzhang/MathForMachineLearning/blob/master/01_Probability%20and%20Statistical%20Inference/images/%E6%A6%82%E7%8E%87%E8%AE%BA%E4%B8%8E%E6%95%B0%E7%90%86%E7%BB%9F%E8%AE%A1(%E7%AC%AC%E5%9B%9B%E7%89%88)%20.jpg)

- 盛骤、谢式千、潘承毅，[**概率论与数理统计**(第四版)](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00Y7UVZHQ/ref=sr_1_1?ie=UTF8&qid=1500723702&sr=8-1&keywords=%E6%A6%82%E7%8E%87%E8%AE%BA%E4%B8%8E%E6%95%B0%E7%90%86%E7%BB%9F%E8%AE%A1) – 2008年6月1日，高等教育出版社.

------------------------------------------

$$\sum_{i=1}^n a_i=0$$
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$
$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$

------------------------------------------

flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end
st->io->op->cond
cond(yes)->e
cond(no)->sub->io
