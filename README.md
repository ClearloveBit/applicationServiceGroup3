# 软件工程需求技术博客
## CSDN博客地址：https://blog.csdn.net/weixin_43480708
* 5-7 第一次更新 *“今天吃什么”项目计划*
* 5-16 第二次更新 *“今天吃什么” 项目前景和范围文档*
* 5-24 第三次更新 *“今天吃什么” 结构化需求分析*  
* 6-2 第四次更新 *“今天吃什么” 项目原型进展*  
* 6-3 第五次更新 *“今天吃什么” UML建模*  

## 本组选题：今天吃什么  

### 一、项目需求（5-7更新）  
* 项目用途：纠结症患者中午不知道吃什么时，帮助他们随机选择或者自定义菜单；  
* 项目前景：本项目适用人群广，适用范围大，适用频率高。可以大大解决人们在吃饭时纠结的心态。本项目开发过程旨在能够提出更加丰富和多元的对于“今天吃什么”的建议，能够更贴近同学们的生活，能够满足更广大受众的需求；  
* 项目用户：学生，上班族；  
* 项目需求：  
	（1）用户可通过多次点击，系统随机产生不同菜单，也可以在自定义菜单中按类别挑选。  
	（2）自定义菜单中的菜式可分为不同国家不同菜系进行分类选择，  
	*e.g. 中餐西餐日料韩餐或者不同口味风格等*  
	（3）用户可以定制自己的菜单，例如早餐，午餐，晚餐，外卖，聚会等各类用户自己喜欢的特色菜单。  
	（4）加入减肥模式， 为用户提供健康菜品的选择，并且在各菜品中添加卡路里数据。  
	（5）在菜品中添加此菜的来历，做法，吃法，或者适宜使用环境等高阶数据，让用户使用的同时能获得更多的知识和乐趣。  
	（6）我的食堂功能，添加自己学校或单位食堂已有的菜品到我的食堂，可只在这几种之间随机选择，同理可以添加我的外卖功能，并跳转到外卖软件。 
	
### 二、项目前景（5-16更新）  
#### 2.1 前景概述
对学校的学生来说，该平台是一个提供每日三餐推荐的系统，来
解决他们对于三餐的纠结。同时在对三餐的选择中，可以自定义范围，
例如外卖或者食堂模式。另外对于每一种菜品，都有其分类，方便同学们
更好的选择。有了这个平台，可以很好的解决同学们对于每餐吃什么的问
题，同时也能为其进行三餐的搭配。

#### 2.2 受众分析
本产品主要面向在校师生
* 学生：
*特征：熟练使用手机，喜欢简洁的操作，对界面美观有一定要求，喜好的口味风格多。*

* 老师：
*特征：与学生基本类似，要求操作简单和界面简洁大方，口味各异。*

#### 2.3 主要特性
软件主要是面向在校师生，根据用户特性，软件需要有以下特征：  
* 面向学生团体，界面美观友好，无专业术语
* 系统支持学生自定义菜单范围
* 对每一种菜品有真实的展示
* 用户可以将喜欢的菜品加入收藏
* 操作简洁不繁琐

### 三、项目范围（5-16更新）  
* FE-1:面向学生团体，界面美观友好，无专业术语  
* FE-2:系统支持学生自定义菜单范围  
* FE-3:对每一种菜品有真实的展示  
* FE-4:用户可以将喜欢的菜品加入收藏  
* FE-5:操作简洁不繁琐
#### 3.1 范围列表
**版本一：** 对菜品进行收集，以及实现简单的界面框架。对应FE-1,FE-5  
**版本二：** 将菜品数据输入程序。实现简单的菜品推荐功能。对应FE-3  
**版本三：** 实现偏好设置，用户可以自定义推荐的范围。对应FE-2  
**版本四：** 实现用户收藏的功能，以及其他一些功能的完善。对应FE-4   
#### 3.2 限制与排除
* LI-1:一些不是很常见的外卖商家不会列入名单。
* LI-2:对于某些食堂菜品的推荐，对自行选择原材料的例如火锅等不会给出具体的材料推荐。
  
### 四、结构化需求概述（5-24更新）  
#### （1）功能分解图  

![功能分析图](https://img-blog.csdnimg.cn/20190524100929570.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)

#### （2）需求细化  

##### 1、一键生成菜单  

* 源头：核心需求  

* 理由：方便快捷，一步到位  

* 优先级:高优先级  

* 成本：无  

* 可变性：无  

##### 2、偏好设置  

* 源头：核心需求  

* 理由：根据用户需求限定菜品种类  

* 优先级：高优先级  

* 成本：无  

* 风险：无  

* 可变性：无  

##### 2.1 用餐时间选择  

* 源头： 一日三餐不一样  

* 理由：早饭要吃好、午饭要吃饱、晚饭要吃少  

* 优先级：中优先级  

* 成本：无  

* 风险：无  

* 可变性：低  

##### 2.2 菜系选择  

* 源头：不同口味人群  

* 理由：口味偏好  

* 优先级：中优先级  

* 成本：无  

* 风险：无  

* 可变性：增加更多菜系  

##### 2.3 就餐方式  

* 源头：不同的期望就餐地点  

* 理由：可能不想在食堂吃  

* 优先级：低优先级  

* 成本：无  

* 风险：外卖会接入第三方  

* 可变性：也许会舍弃  

##### 2.4 减肥模式  

* 源头：想要减肥的朋友们  

* 理由：减肥当然得健康饮食，低热量  

* 优先级：中优先级  

* 成本：无  

* 风险：无  

* 可变性：也许有一天大家都放弃了减肥  

### 五、过程建模（5-24更新）

#### （1）DFD图

![DFD-1](https://img-blog.csdnimg.cn/20190524003245607.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
![DFD-2](https://img-blog.csdnimg.cn/20190524003257993.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)

#### （2）数据字典

数据项 | 名称 | 描述 | 组成 
:-: | :- | :- | :-
1 | 用户个人信息 | 存储用户基本信息 | 头像，微信号，学校等  
2 | 用户菜品偏好信息 | 存储用户对于菜单的偏好信息 | 餐种，餐时，就餐方式，减肥模式等  

### 六、数据建模（5-24更新）
ERD建模：  
![ERD](https://img-blog.csdnimg.cn/20190524100247108.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)

### 七、UML建模（6-3更新）  

#### （1）用例图  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190603094620638.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)  

#### (2)静态UML图（类图）  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190603094723933.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)  

#### (3)动态UML图  
##### 顺序图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190603094813658.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)   
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190603094823439.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2019060309483744.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
##### 协作图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190604134618252.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
##### 状态图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190604104001897.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
##### 活动图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190604134701848.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190604134710620.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190604134723191.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzQ4MDcwOA==,size_16,color_FFFFFF,t_70)


## 小组分工（5-7更新）：  
* 祁志洋 组长 负责组织组内同学，联系甲方乙方以及助教，协助需求分析和任务开发  
* 刘俊杰 组员 负责博客的编写，需求分析和任务开发，以及展示演讲  
* 刘常思冰 组员 负责展示ppt的制作，各类文档的编写，协助需求分析和任务开发  
* 柏盛元 组员 负责在项目期间对进度进行记录，协助需求分析和任务开发    

## 项目计划（6-1更新）：
* 第11周： 与甲方沟通，获取项目的需求，制定计划和人员分工  
	*分工情况说明：祁志洋 负责与甲方联系；*  
	*刘俊杰 负责撰写博客和做第一次展示；*  
	*刘常思冰 负责制作展示ppt；*  
	*柏盛元 负责组内沟通。*  
	
* 第12周： 与甲方沟通，制定项目软件的具体功能和所需要的具体细节问题，开始项目的框架搭建。  
	*分工情况说明：祁志洋 负责与甲方联系，负责框架搭建；*  
	*刘俊杰 负责撰写博客和展示，协助框架搭建；*  
	*刘常思冰 负责编写项目文稿，负责框架搭建；*  
	*柏盛元 负责组内沟通与记录，协助框架搭建。*  
	
* 第13周： 主要进行项目的框架搭建，尽量实现基本框架的完成。*  
	*组员按情况进行编程工作*  
	
* 第14周： 在框架搭建完成的基础上进行功能的完善，开始进行项目软件界面的设计。  
	*组员按情况进行编程工作*  
	
* 第15周： 完善软件的界面设计，与甲方进行进一步的交接，完善需求，撰写项目日志。  
	*组员按照之前分工情况完成工作*  
	
* 第16周： 对项目进行修改与审核，发布用户使用说明，制作最终的展示材料  
	*组员按照之前分工情况完成工作*  
	
	
## 任务说明（5-24更新）：  

### 5-7周五报告说明  

* 项目背景和范围;  
* 甲方沟通1~2次结果+书面记录;  
* 之后几周的计划， 每个人大致分工;  
* 建立技术博客， 发布以上内容。  

### 5-17周五报告说明  

* 项目前景和范围;  
* 涉及分析和硬数据采样;  
* 面谈;  
* 原型。  

### 5-25周五报告说明
* 结构化需求分析概述（功能分解图、需求细化与优先级划分）（5分）  
* 过程建模（DFD图、微规格说明、数据字典）（5分）  
* 数据建模（简单情况下的ERD建模、硬数据ERD建模）（5分）  
* 现场报告（5分）  
* 技术博客/需求文档（5分）  

## 原型系统进展 （6-1更新,代码在仓库）：

### 5.7 - 5.16
* 决定采用微信小程序  
* 制作了小程序原型的框架  
主页：一键选择按钮和一定程度的简单美化  
功能栏：包含主页，偏好设置和登陆三个功能  
登陆页面：简单的登陆  
* 改进
主页：修改了一部分主页的样式  
功能栏：完善了功能栏的内容  
登陆界面：改进了登陆界面的步骤  
* 分工
刘常思冰：主要负责了框架的制作  
祁志洋：对一部分功能进行修改  
刘俊杰：日志撰写

### 5.16 - 5.24
* 制作了偏好设置页面
* 改进  
功能栏：为菜单栏添加了图标，更加美观  
主页：增加了“减肥模式”切换按钮  
偏好设置页：更新了布局
登陆界面：增加了“联系作者”等功能，完善了界面
* 分工
刘常思冰：主页的修改  
祁志洋：功能栏完善，偏好设置制作  
刘俊杰：日志撰写，图标查找    
柏盛元：图例制作  

### 5.24 - 6.1
* 完善了一部分功能
* 改进  
主页：将“减肥模式”按钮整合到偏好设置中，使得界面更加简洁  
功能栏：更新了图标，使得图标更加美观  
* 分工  
祁志洋：对一部分功能进行修改  
刘常思冰：对一部分功能进行修改  
刘俊杰：日志撰写  
柏盛元：图例制作  

### 5.24 - 6.1 图片更新

![图1](/image2/3.png)
![图1](/image2/5.png)
![图1](/image2/4.png)
![图1](/image2/1.png)
![图1](/image2/2.png)
