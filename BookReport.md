# <center>BookReport</center>  

一些数据分析书籍的读书笔记  

---------------------------

# <center>Head First Data Analysis</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;中文名称为《深入浅出数据分析》，主要介绍数据分析的一些基本方法及思路，用Excel及R进行实践，适合入门。  

**数据分析基础方法及思想：**  
数据分析流程---检验理论---数据图形化  
    
**数据分析前的准备工作：**  
假设检验---信念数字化---数据整理
  
**数据分析方法：**  
最优化---贝叶斯理论---启发式---直方图---回归预测--- 合理误差---关系数据库
## 1.1 数据分析流程
1. 确定问题：  
分析客户，确定客户需求，将客户需求具体化，数字化；  
2. 分解问题：  
将大问题分解为小问题，将数据分解为更小的组块，找到高效比较因子；  
3. 评估：  
利用比较法对数据组块进行评估；  
4. 决策：  
根据分析结果对问题做出决策。

## 1.2 检验理论  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;实验是进行理论检验的好办法。  

1. 利用观察分析法获取数据：被研究者自行决定自己属于哪个群体；    
2. 进行随机分组：避免混杂因素；  
3. 设置控制组与实验组。  

## 1.3 最优化
1. 数据分类：  
将数据分为可控制因素和不可控制因素，得出约束变量及其约束条件；
2. 目标函数：  
目标为最大或最小化结果，目标函数可帮忙找出最优化结果；  
3. 求解：  
可利用相关工具求解最优化结果，如Excel中的Slover等；  
4. 纠正假设。  

## 1.4 数据图形化  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;好的数据图像化具有以下特点：  
 
 1. 展示数据；
 2. 高明比较；
 3. 多元图形；

## 1.5 假设检验
1. 获取信息并判断变量想关性；

2. 构建变量关系网络；

3. 证伪法：  
利用证伪法将不可能的假设剔除，一定不用满意法；  
4. 诊断性证据：  
剔除不具有诊断性的证据；
5. 选取否定证据最少的假设；

## 1.6 贝叶斯统计
**贝叶斯公式**：
$$P(A|B)=\frac{P(B|A)P(A)}{P(B)}=\frac{P(B|A)P(A)}{P(B|A)P(A)+P(B| \sim A)P(\sim A)}$$  

**注意**：  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;贝叶斯公式可以反复多次使用。例如利用贝叶斯公式更新基础概率（见《深入浅出数据分析》P186）。  

## 1.7 信念数字化
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有时数据分析师们的观念貌似出现分歧，通过信念数字化可以更加明确分歧所在，甚至消除分歧。具体流程如下： 

  1. 将概率用词转换为主观概率；
  
  2. 通过散点图等方式将数据图形化，更加直观形象；  

  3. 可以利用标准偏差定量描述分歧大小；

## 1.8 启发法  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当系统中的变量过于复杂难以统计时，可以通过获取一两个变量对整个系统做出分析评估，这一方法就是启发法。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;快省树是描述启发法的一种图形，它的构造方法就是分析者的一种推理过程。该方法耗时不多，且不需要大量认知资源。

## 1.9 直方图  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;直方图是进行数据汇总比较好的方式。具体步骤如下：  

 1. 获取数据并将数据分组；
 2. 画出不同分组间的直方图；
 3. 可利用程序函数如`summary`等总结数据最大最小平均值以及标准差等；  
 3. 观察比较不同直方图间的形状，峰值，横纵坐标；
 4. 得出结论。

## 1.10 回归预测  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;顾名思义，回归预测用来进行数据预测，发现数据的发展变化规律。 具体步骤如下：  
  
  1. 绘制数据散点图并发现它们的相关关系；  
  2. 画拟合数据变化的图形；  
  3. 对绘制出的图形进行相关性评估；  
  4. 利用方程表示图形变化。

## 1.11 合理误差  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据分析当中的误差是无法避免的，针对误差的处理方法及步骤如下：  
  
  1. 分析误差类别；
  2. 如果是使用外插法产生的误差需添加适用范围的说明；  
    `外插法：用回归方程预测数据范围以外的数值`
  3. 如果是机会误差，则要恰当表达误差；
  4. 使用标准差，均方根误差定量描述机会误差；  
  5. 分割数据，管理误差。  
  
## 1.12 关系数据库  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于有多个数据表的情况，应该建立关系数据库将各个表联系起来，具体步骤如下：  
  
  1. 获取数据，建立多个数据表；
  2. 围绕问题，筛选表格；
  3. 找出各数据表间相关联的数据；
  4. 数据公式关联，进行近一步计算。  

## 1.13 整理数据
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;整理数据是数据分析当中最重要且不可或缺的一步，整理数据的一般步骤如下：  
  
  1. 保存原始数据；  
  2. 设想最终数据集的外观；  
  3. 识别数据集中重复出现的模式；
  4. 整理或重新构建数据；  
  `分列， 删除不重要数据，替换数据，排序等`  
  5. 使用整理后的数据集； 