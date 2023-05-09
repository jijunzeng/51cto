# 51cto下午题大纲  

![0.png](res/0.png)

---
---
---

## 三点估算 执行绩效

某公司拟建设一个门户平台，根据工作内容，该平台项目分为需求调研、系统实施、系统测试、数据准备(培训)、上线试运行、验收六个子任务，各子任务预算和三点估算工期如下表所示。  
到第6周周末时，对项目进行了检查，发现需求调研已经结束，共计花费1.8万元，系统实施的工作完成了一半,已花费17万元。  
![三点估算](res/三点估算.png)

**【问题1】 (5分)**  
(1)请采用三点估算法估算各个子任务的工期：(悲 + 4x中 + 乐) / 6
>需求调研=(0.5+4x1+1.5)/6=1周  
系统实施=(4+4x7+16)/6=8周  
系统测试=(1+4x2+3)/6=2周  
数据准备=(1+4x1+1)/6=1周  
上线试运行=(2+4x3+10)/6=4周  
验收=(1+4x1+1)/6=1周

(2)请分别计算系统实施和系统测试两个任务的标准差。
>(乐 - 悲) / 6  
系统实施标准差=(16-4)/6=2周  
系统测试标准差=(3-1)/6=0.33周

**【问题2】 (9分)**  
该项目开发过程中采用瀑布模型，请评估项目到第六周周末时的执行绩效。
>第6周时，计划完成了需求调研1周，系统实施5周，即PV=1.8+35.2x5/8=23.8万  
实际需求调研结束+系统实施了一半，  
EV=1.8+35.2x50%=19.4万  
AC=1.8+17=18.8万  
SV=EV-PV=19.4-23.8=-4.4万， 进度落后  
CV=EV-AC=19.4-18.8=0.6万，成本节余（计算绩效指数也可）

**【问题3】(4分)**  
如果项目从第7周开始不会再发生类似的偏差，请计算此项目的完工估算EAC和完工偏差 VAC。
>非典型偏差:  
BAC=48.4万  
EAC=AC+(BAC-EV)=18.8+(48.4-19.4)=47.8万  
VAC=BAC-EAC=48.4-47.8=0.6万

**【问题4】(2分)**  
为了提升项目的执行绩效，项目组成员提出采取并行施工的方法加快进度，请指出采取该方式的缺点。
>并行施工可能造成返工等质量问题、风险增加和成本超支

---
---
---

## 定量风险分析工具之决策树分析

![决策树分析](res/决策树分析.png)
**用决策树在若干备选行动方案中选择一个最佳方案， 在决策树分析中，通过计算每条分支的预期货币价值，就可以选出最优的路径（EMV预期货币价值分析）**  
老外是资本主义社会，一切都喜欢用钱来测量，这个EMV也是如此, M是Monetary的意思,这个单词是money的变种。
>第1步，先是要分解备选决策为两个或多个方案（是新建还是扩建呢，哪个更划算，或者说哪个利润多）  
第2步，计算每一个分支结束的价值（叶子结点的利润）  
原谅我这里用了利润一词，是因为我想突出这张图最终关心的并不是收入，也不是费用（投资建厂花出去的钱）  
而是挣的利润，学过会计学基础的同学们都知道有一个公式， 收入-费用=利润  
以建新厂，强需求（2亿美元）为例来计划: 利润=收入（2亿美元）- 费用（1.2亿美元）= 8000万  
类似的，弱需求也可以计算，只不过这种情况下是市场不景气，收入太少了，导致利润是负数，亏钱嘛  
第3步，按百分比加权算出各方案的整体EMV  
例如建设新厂方案的EMV=8000x60%+(-3000)x40%=3600万美元  
在我理解，这就是个典型的利润值，当然随便发明新名词是我的不对  
第4步，决策即比较不同的方案EMV哪个大， 哪个EMV大就选哪个方案。

最后补充，我理解每个机会节点的分支可以不仅有2个，3个或多个也可以的，例如需求可以分为强需求，中等需求，弱需求。

---
---
---

## 项目工作说明书SoW(Statement of Work)

SoW的撰写是在【招标成功后】  
简单理解的话，SoW就类似我们已经拿到了offer，这时候，需要更加明确的规范工作范围、工作的内容以及如何定义工作是保质保量完成的。  
所以，SoW是对项目需交付的产品、服务活成果的叙述性说明。  
对于内部项目，项目启动者或发起人提供工作说明书  
对于外部项目，工作说明书则由客户提供，可以是招标文件的一部分，或合同的一部分

---
---
---

## 组织过程资产

组织过程资产是从过去的项目中积累起来的、最重要的无形资产。  
这里的资产指的是可以在未来带来效益的任何东西，包括：政策、流程、程序、模板、工作指南和知识库。  
其本质就是：从依靠人，变为依靠系统，将人的经验和知识，变成组织的过程资产。

---
---
---

## [2022.05](/2022.5/README.md)  

[题1 质量管理, 新七，质量控制成果](/2022.5/README.md#试题一)  
[题2 进度管理，关键路径，进度压缩](/2022.5/README.md#试题二)  
[题3 风险管理，消极风险，积极风险，应对策略](/2022.5/README.md#试题三)  
[题4 配置管理，配置审计](/2022.5/README.md#试题四)  

## [2021.11](/2021.11/README.md)  

[题1 风险管理，应对策略](/2021.11/README.md#试题一18分)  
[题2 进度管理，三点估算，瀑布模型，执行绩效](/2021.11/README.md#试题二20分)  
[题3 质量管理，帕累托](/2021.11/README.md#试题三17分)  
[题4 干系人管理，沟通管理，权利/利益矩阵](/2021.11/README.md#试题四20-分)  

## [2021.05](/2021.5/README.md)  

[题1 质量管理，老七，质量规划](/2021.5/README.md#试题118分)  
[题2 进度管理，项目绩效](/2021.5/README.md#试题222分)  
[题3 人力资源管理](/2021.5/README.md#试题315分)  
[题4 范围管理](/2021.5/README.md#试题420分)  

## [2020.11](/2020.11/README.md)  

[题1 质量管理，质量管理过程的输入](/2020.11/README.md#试题118分)  
[题2 进度管理](/2020.11/README.md#试题220分)  
[题3 风险管理](/2020.11/README.md#试题320分)  
[题4 立项招标](/2020.11/README.md#试题417分)  