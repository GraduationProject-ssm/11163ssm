# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11163ssm定西扶贫惠农推介系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


﻿

**定西扶贫惠农推介系统**

**摘要**

######### 扶贫工作是党中央、国务院的一项重要战略部署。党政机关定点扶贫是中国扶贫开发战略部署的重要组成部分，是新阶段扶贫开发的一项重大举措，对推动贫困地区经济社会的发展有着积极的意义。
本论文系统地描绘了整个定西扶贫惠农推介系统的设计与实现，主要实现的主要管理员和用户两个角色，以下是管理员功能有以下几点：管理员；个人中心、用户管理、扶贫计划管理、惠农福利管理、优秀农民管理、志愿者报名管理、在线捐赠管理、管理员管理、系统管理，用户后台有以下几点：个人中心、志愿者报名管理、在线捐赠管理，前台首页：首页、扶贫计划、惠农福利、优秀农民、论坛信息、我的、跳转到后台等功能，本系统其具有简单的接口，方便的应用，强大的互动，完全基于互联网的特点。

对于定西扶贫惠农推介系统层面的特性，规划出符合该领域需求的定西扶贫惠农推介系统软件。本文研究的主要目的是为实现扶贫惠农的信息化、系统化、规范化，为用户的长远发展奠定了基础。基于定西扶贫惠农推介系统，有着较高的现实应用价值。用户不用受时间和地点的约束，进行查询信息。管理员也不用受时间和地点的约束，进行修改信息等操作。大大减少了很多重复繁琐的工作，落实定西扶贫惠农推介系统现代化、科学化和信息化。这是本论文选题的主要目标与研究的价值所在。

本具体在系统设计上，采用了B/S的结构，同时，也使用JSP技术在动态页面上进行了设计，后台上采用Mysql数据库，是一个非常优秀的定西扶贫惠农推介系统。


**关键词：**定西扶贫惠农推介系统，jsp技术，数据库MYSQL



Poverty alleviation is an important strategic deployment of the CPC Central Committee and the State Council. Poverty alleviation designated by the party and government organs is an important part of the strategic deployment of poverty alleviation and development in China, and is a major measure in the new stage of poverty alleviation and development, which has positive significance for promoting the economic and social development of the poor areas.

This paper systematically describes the design and implementation of the whole poverty alleviation and promotion system in Dingxi. The main roles of the administrator and user are as follows: administrator; personal center, user management, poverty alleviation plan management, benefit agriculture welfare management, excellent farmer management, volunteer enrollment management, online donation management, administrator management System management, the user background has the following points: personal center, volunteer registration management, online donation management, front page: home page, poverty alleviation plan, benefits for farmers, excellent farmers, forum information, my, jump to the background and other functions. The system has simple interface, convenient application, strong interaction, and is completely based on the characteristics of the Internet.

For the characteristics of the system level of poverty alleviation and promotion system in Dingxi, the software of poverty alleviation and promotion system in Dingxi is planned to meet the needs of this field. The main purpose of this paper is to realize the informatization, systematization and standardization of poverty alleviation and benefit farmers, and lay a foundation for the long-term development of users. Based on the promotion system of poverty alleviation and benefit agriculture in Dingxi, it has a high practical application value. Users do not need to be constrained by time and place to query information. The administrator also does not need to be constrained by time and place to modify information and other operations. It greatly reduced many repetitive and tedious work, and implemented modernization, scientificalization and informatization of poverty alleviation and agriculture promotion system in Dingxi. This is the main goal of this 

thesis and the value of the research.

This paper uses b/s structure in the system design, and also uses JSP technology to design on dynamic pages. MySQL database is used in the background. It is a very excellent poverty alleviation and agriculture promotion system in Dingxi.

**Key words:** poverty alleviation and farmers promotion system, JSP technology, database mysql

目  录

[第1章 绪   论	1](#_Toc56688957)

[1.1课题背景	1](#_Toc56688958)

[1.2 课题意义	2](#_Toc56688959)

[1.3 开发工具及技术	2](#_Toc56688960)

[1.4 国内外现状	3](#_Toc56688961)

[第2章 系统分析	5](#_Toc56688962)

[2.1 可行性分析	5](#_Toc56688963)

[2.2总体设计原则	6](#_Toc56688964)

[2.3 系统需求分析	6](#_Toc56688965)

[2.4 业务流程分析	6](#_Toc56688966)

[2.5 数据流图	7](#_Toc56688967)

[第3章 系统设计	9](#_Toc56688968)

[3.1 系统功能设计	9](#_Toc56688969)

[3.2 数据库设计	10](#_Toc56688970)

[第4章 系统实现	15](#_Toc56688971)

[4.1管理员功能模块	15](#_Toc56688972)

[4.2前台功能模块	16](#_Toc56688973)

[4.2用户功能模块	16](#_Toc56688973)

[第5章 软件测试	22](#_Toc56688975)

[5.1软件测试的重要性	22](#_Toc56688976)

[5.2测试实例的研究与选择	22](#_Toc56688977)

[5.3测试环境与测试条件	24](#_Toc56688978)

[5.4系统运行情况	24](#_Toc56688979)

[5.5系统评价	24](#_Toc56688980)

[第6章 总结	25](#_Toc56688981)

[参考文献：	26](#_Toc56688982)

[致谢	27](#_Toc56688983)




1. ` `绪   论

1.1课题背景

2021年处于信息网络高速发展的大背景之下。在今天，缺少手机和电脑几乎已经成为不可能的事情，人们生活中已经难以离开手机和电脑。针对增加的成本管理和操作,国家非常支持各大行业建立自已的网站，这既可以让更多的人体验到网络所带来的方便。

以往的扶贫惠农相关信息管理，都是政府工作人员手工统计。这种方式不但时效性低，而且需要查找和变更的时候很不方便。随着科学的进步，技术的成熟，计算机信息化也日新月异的发展，社会也已经深刻的认识，计算机功能非常的强大，计算机已经进入了人类社会发展的各个领域，并且发挥着十分重要的作用。本系统利用网络沟通、计算机信息存储管理，有着与传统的方式所无法替代的优点。比如计算检索速度特别快、可靠性特别高、存储容量特别大、保密性特别好、可保存时间特别长、成本特别低等。在工作效率上，能够得到极大地提高，延伸至服务水平也会有好的收获，有了网络，定西扶贫惠农推介系统的各方面的管理更加科学和系统，更加规范和简便。

本文所设计的在线定西扶贫惠农推介系统就是在这种客观条件下进行的，是一项利民利国的、非常有价值的扶贫惠农。在定西扶贫惠农推介系统管理方面，传统的管理方式显然无法与在线扶贫惠农相比，在线定西扶贫惠农推介系统正发挥着越来越重要的作用。利用网络速度快、信息量大、安全、简单都是传统模式难以企及的优点，正在发挥着越来越重要的作用。在本文中的在线定西扶贫惠农推介系统是一个基于MySQL数据库和jsp技术的。

1.2 课题意义

社会主义进入新时代，经济实力越来越强。我们也变得越来越忙碌、对生活的要求也变得更加严格，对快速和方便的服务的需求也在逐渐增加。因此，对扶贫惠农的管理、服务的要求也越来越严格。为适应时代的发展，国家开始广泛地使用电脑来进行管理，并查看在线扶贫计划信息、惠农福利等信息，为提高工作人员效率提供了一种新的方式，并且减轻了他们的工作强度，在树立国家形象的同时，为用户提供更加方便、简单而高效的服务，实现双赢。

本系统即为方便管理员和用户而制作的网上定西扶贫惠农推介系统，结合了用户的需求，设计出的一个基于jsp技术、MySQL数据库的网上定西扶贫惠农推介系统。

1.3 开发工具及技术

网上定西扶贫惠农推介系统从本质上讲是一个电子商务模式综合而成的系统。实现了用户管理、扶贫计划管理、惠农福利管理、优秀农民管理、志愿者报名管理、在线捐赠管理等基本功能。

主要用到以下技术：
### **1.3.1  B/S架构** 
在B/S的三层结构当中（Browser/Server，浏览器/服务器结构）系统中，它可以通过浏览对众多的服务器发出信号请求。B/S系统它对用户来说他可以对用户的工作量大大的减少，用户只要在用户端上安装、配置少量的运行软件就可以对用户的工作量大大的减少。对于数据库的访问也是由服务器来简单的完成。B/S的框架不断成熟，它结合多种浏览器和专用的软件不断加强自己的功能，这样一来可以大大的减少了开发的成本，它也是一种新的软件架构。B/S系统主要是通过逻辑层、展现层等，层层相互独立而且又相互联系来进行关联。
### ` `**1.3.2  jsp技术介绍** 
JSP技术本身是一种脚本语言，但它的功能是十分强大的，因为它可以使用所有的JAVA类。当它与JavaBeans 类进行结合时，它可以使显示逻辑和内容分开，这就极大的方便了用户的需求。JavaBeans 可以对JSP技术的程序进行扩展，从而形成新的应用程序，而且JavaBeans的代码可以重复使用，所以就便于对程序进行维护。JavaBean 组件有内部的接口，可以帮助不同的人对系统进行访问。1999年，Sun微系统公司正式推出了JSP技术，这是一种动态技术，是基于整个JAVA体系和JavaServlet提出的，是具有普遍适用性的WEB技术，也是本系统设计的核心技术之一。JSP技术能够极大的提高WEB网页的运行速度。这些内容会与脚本结合，并且由JavaBean和Servlet组件封装。所有的脚本均在服务器端运行，JSP引擎会针对客户端所 提交的申请进行解释，然后生成脚本程序和JSP标识，然后通过HTML/XML页面将结果反馈给浏览器。因此，开发人员亲自设计最终页面的格式和HTML/XML标识时，完全可以使用JSP技术。

所以结合九宫格日志网站的需求及功能模块的实现，使用JSP技术是最合适的，而且JSP的拓展性比较好，对于系统在后期使用过程中可以不断对系统功能进行拓展，是系统更完成，更方便的满足用户需求。

` `**1.3.3 mysql数据库介绍** 

JDBC的驱动程序它是和数据库不同的，在每个数据库的应用它们都是和区分开的，当运行到一定的程序当中，它就会与自己相关的协议与用户端进行通讯。那么这个系统就会对使这些数据进行连接。当我们选择哪个桥的时候，接下来就会简单的叙述这个数据库是如何来创建的。当点击完成按钮的时候就会自动在对话框内弹出数据源的名称，在进行点击下一步即可，直接在输入相对应的身份验证和登录密码。

mysql它可以为用户在数据库上进行应用，它的优点就是让人们学习起来简单易懂，而且它的结构简单并且功能也强大，在信息储存量上也是比较大的，mysql它是一种主要应用于数据库的查询和编程，在很多数据库相互关系上得到了应用，它可以对许多数据进行广泛的查询和应用，对于常规的的数据它可以广泛的查询，不需要对其大量的进行储存和掌握，也不用在这上面进行多层次的组合，纪录相应集合是其主要操作，在使用灵活性强和功能强的mysql数据库的情况下，在实现其他功能时需要进行编写代码，因此，在使用mysql数据库时只需编写一小段就可以对该功能实现。

本系统的开发主要应用了mysql进行对数据的管理。

(1)数据

数据它是在数据库当中储存的对象，在大多数的人们头脑当中是数字。其实简单的来说数字是一种简单的数据，从广义的角度来说一些文字、数据、图形等等都可以认为是一种数据，这样一来可以给数据就做个定义了。

(2)数据库

数据库简单的来说它就是对数据进行储存，只不过它在计算上要以某种格式进行存放。但是数据库经过长期的在计算机内储存，它是比较有组织模型数据在里边，这样对于拥有较高的数据具有独立性和共享性。

(3)数据库管理系统

数据库的管理系统主要功能表现为以下几点：

1.数据上它可以通过数据对象进行定义。

2.数据库的语言它可以提供数据的操纵，用户可以通过语言的操纵进行删除、查询和修改等。

3.通过数据库的建立它可以创建数据库的输入和转换功能，能为数据库的重新组合做出监视等。还可以帮助数据库的恢复功能。

4.数据库的开始转充个初始密码都可以对数据库进行建立和维护功能。
**


1.4 国内外现状

随着计算机网络的不断渗透，人们的生活与工作、学习的方式也在慢慢发生变化。传统的扶贫惠农相关信息管理方式一般都采取人工的方式，信息的获取、整理、修改、存储等工作还停留在人工阶段。这种方式一方面需要花费大量的人力、物力和金钱，交互起来比较困难，而且会浪费时间；另一方面对用户等信息的管理，特别是随着用户数量的递增，查询、修改起来特别困难；最后由于用户等其他信息的不断增加，信息的存储也成为了难题。

一些发达国家，网络发展比较快，已经很大程度上完成了从人工到计算机管理的转变。我国计算机应用起步比较晚，而且发展区域不平衡，还有很多地区或单位使用传统的方式进行管理，但是目前计算机发展较快，包括网络也已经普及，很多单位和用户也开始慢慢接触网络管理系统。

第二章  系统分析

2.1 可行性分析

可行性分析的目的是确定一个系统是否有必要开发、确定系统是否能以最小的代价实现。其工作主要有三个方面，分别是技术、经济和社会三方面的可行性。我会从这三个方面对网上定西扶贫惠农推介系统进行详细的分析。

2.1.1技术可行性

`	`该系统主要使用jsp、Eclipse和MySQL数据库进行开发，jsp易于学习和使用灵活。在校期间也接触过Eclipes和MySQL数据库课程，对此有一定的开发经验，因此开发难度不高，所以从技术上来说是可行的。

2.1.2经济可行性

`	`本系统设计所选择的开发工具和服务器都是免费的开源软件，又或者是适合用户使用的免费版本，并不需要支付费用，而且由作者本人单独完成，也不存在团队费用，几乎没有经济成本，具备经济可行性。

2.1.3社会可行性

`	`社会可行性主要包括法律和用户两个方面，下面将从这两方面进行分析。

(1)法律因素

`	`本系统是学习开发所制作的程序，并不用作商业用途，是在根据实际调研的结果结合现有的网上扶贫惠农推介系统后得出的，而且系统制作的全部过程都是在个人的工作电脑中完成的，使用的都是开源和免费的开发环境、分析软件和数据库，不存在侵权问题。

(2)用户可行性

`	`操作人员或者用户只需要具备一定的windows电脑操作常识，不需要精通计算机技能。此外系统管理人员，只需要在windows常识之上再熟悉下使用Tomcat服务器的操作流程，只要掌握一定的计算机知识即可，在正式上线运营之前，仅需要对操作人员进行简单的熟悉流程培训即可。所以从用户可行性上也是可行的。

2.2总体设计原则

`	`一个系统要在开发和维护的过程中方便使用，必须采取一定的设计原则，其主要设计原则有：

`	`简单性：系统功能简单易懂，只需要掌握基本的计算机操作能力即可使用。

`	`针对性：针对特定的定西扶贫惠农推介系统，没有多余的其他功能，使用户可以专心使用。

`	`实用性：能够满足用户方面的需求。

`	`一致性：设计风格、命名规范一致，整个系统的各个功能模块色彩、摆放位置、功能等都是一致的。

`	`先进性：本系统的代码采用读取数据的方式，方便后续开发、拓展。

2.3 系统需求分析

定西扶贫惠农推介系统需要满足的需求有以下几个：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现用户对信息的控制和管理。

（3）方便查询信息及管理信息等；

（4）通过网络操作，改善处理问题的效率，提高用户利用率；

（5）考虑到用户多样性特点，要求界面简单，操作简便。

`	`（6）管理员功能，管理员可以对用户或者扶贫计划信息进行管理。

`	`（7）系统安全，操作简便，不过于复杂。

（8）系统可以稳定运行，不存在卡顿等问题造成用户反感。

2.4 业务流程分析
### 2.4.1登录流程
登录模块主要满足管理员以及用户的权限登录，用户登录流程图如图2-1所示。

![](/md/blog.001.png)

图2-1 登录流程图
### 2.4.2注册流程
未有账号的用户可进入注册界面进行注册操作，用户注册流程图如图2-2所示。

![](/md/blog.001.png)

图2-2 注册流程图
### 2.4.3添加信息流程
用户在添加信息时，信息编号自动生成，系统会对添加的信息进行验证，验证通过则添加至数据库，添加信息成功，反之添加失败。添加信息流程如图2-3所示。

![](/md/blog.002.png)

图2-3 添加信息流程图
### 2.4.4删除信息流程
用户可选择要删除的信息进行信息删除操作，在删除信息时系统提示是否确定删除信息，是则删除信息成功，系统数据库将信息进行删除。删除信息流程图如图2-4所示。

![](/md/blog.003.png)

图2-4删除信息流程图




1. 系统设计

3.1 系统概要设计

本定西扶贫惠农推介系统选择B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式。适合在互联网上进行操作，只要用户能连网，任何时间、任何地点都可以进行系统的操作使用。系统工作原理图如图3-1所示：

![](/md/blog.004.png)

图3-1 系统工作原理图
## 3.2系统结构设计
整个系统是由多个功能模块组合而成的，要将所有的功能模块都一一列举出来，然后进行逐个的功能设计，使得每一个模块都有相对应的功能设计，然后进行系统整体的设计。

本定西扶贫惠农推介系统结构图如图3-2所示。

![](/md/blog.005.png)

图3-2 定西扶贫惠农推介系统结构图

3.3 数据库设计

数据库可以说是所有软件的根本，如果数据库存在缺陷，那么会导致系统开发的不顺利、维护困难、用户使用不顺畅等一系列问题，严重时将会直接损害利益，同时在开发完成后，数据库缺陷也更加难以解决。所以必须要对数据库设计重点把握，做到认真细致。因此，数据库设计是这个在线定西扶贫惠农推介系统的重点要素。

3.3.1概念结构设计

(1)管理员实体属性图如下图3-3所示

![](/md/blog.006.png)

图3-3管理员实体属性图



(2)用户信息：用户名、用户姓名、头像、性别、联系电话、邮箱实体属性如下图3-4所示

![](/md/blog.007.png)

图3-4用户信息实体属性图

(3)扶贫计划信息：标题、图片、内容、发布日期、国家名称，实体属性如下图3-5所示

![](/md/blog.008.png)

图3-5扶贫计划信息实体属性图

(4)志愿者报名信息：用户名、用户姓名、性别、联系电话、报名意愿、报名日期，实体属性如下图3-6所示

![](/md/blog.009.png)

图3-6志愿者报名信息实体属性图



3.3.2数据库表设计

将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

allusers表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|username||150||255||
|3|pwd||150||255||
|4|cx||150||255||
|5|addtime|DateTime|8||19||

fupinjihua表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|biaoti||150||255||
|4|tupian|DateTime|8||255||
|5|neirong||150||255||
|6|faburiqi|DateTime|8||255||
|7|guojiamingcheng||150||255||

huinongfuli表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|biaoti||150||255||
|4|tupian|DateTime|8||255||
|5|neirong||150||255||
|6|faburiqi|DateTime|8||255||
||fengmian|DateTime|8||255||

yonghu表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|yonghuming|DateTime|8||255||
|5|mima||150||255||
|6|touxiang|DateTime|8||255||
|7|xingbie||150||255||
|8|lianxidianhua|DateTime|8||255||
|9|youxiang||150||255||

youxiunongmin表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|nongminxingming|DateTime|8||255||
|5|touxiang||150||255||
|6|gerenjianjie|DateTime|8||255||
|7|fengguangshiji||150||255||





第四章 系统实现

4.1管理员功能模块

管理员输入个人的用户名、密码、角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的用户名、密码不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的用户名、密码，直到账号密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图4-1所示：

![](/md/blog.010.png)

图4-1管理员登录界面图



`    `管理员进入到界面，通过界面的任务大厅，登录成功后进入到系统可以进行查看个人中心、用户管理、扶贫计划管理、惠农福利管理、优秀农民管理、志愿者报名管理、在线捐赠管理、管理员管理、系统管理等功能模块，进行相对应操作，如图4-2所示。![](/md/blog.011.png)

图4-2 首页界面图


用户管理，管理员在用户信息页面通过查看用户名、用户姓名、头像、性别、联系电话、邮箱等信息 进行添加、修改、删除，如图4-3所示。

管理员在扶贫计划管理页面通查看标题、图片、内容、发布日期、国家名称信息进 进行添加、修改、删除操作，如图4-4所示。

![](/md/blog.012.png)

图4-3用户信息界面图

![](/md/blog.013.png)

图4-5扶贫计划管理界面图

惠农福利管理，管理员在页面通过查看标题、图片、内容、发布日期等信息进行添加、修改、删除 操作，如图4-6所示。

管理员在志愿者报名管理页面进行查看用户名、用户姓名、性别、联系电话、报名意愿、报名日期进行审核回复、查看、修改、删除 操作，如图4-7所示。

![](/md/blog.014.png)

图4-6惠农福利管理界面图

![](/md/blog.015.png)

图4-7志愿者报名管理界面图

管理员通过系统管理页面查看轮播图进行上传图片进行添加、删除、修改以及查看并对整个系统进行维护等操作，如图4-8所示。

![](/md/blog.016.png)

图4-8系统管理界面图


4.2前台功能模块

`   `用户注册、登陆，在用户注册页面可以填写用户名、密码、用户姓名、性别、联系电话、邮箱等信息进行注册，信息无误进行登陆，如图4-9所示。

![](/md/blog.017.png)

![](/md/blog.018.png)

图4-9用户注册、登陆界面图


`     `我的，用户进入个人信息页面可以查看用户名、用户姓名、头像、性别、联系电话、邮箱等可进行添加、修改、删除操作，如图4-10所示。

![](/md/blog.019.png)

图4-10个人信息界面图


前台首页，在前台首页页面中可以查看首页、扶贫计划、惠农福利、优秀农民、论坛信息、我的、跳转到后台等信息，如图4-11所示。

![](/md/blog.020.png)

图4-11前台首页界面图

扶贫计划，用户在扶贫计划页面中可以查看详情，也可根据需要扶贫计划名称进行搜索操作，如图4-12所示。

![](/md/blog.021.png)

图4-12扶贫计划界面图

论坛信息，用户在论坛信息页面中可以添加标题、类型、内容进行提交操作，如图4-13所示。

![](/md/blog.022.png)

图4-13论坛信息面图


4.1用户功能模块

用户登录，通过填写注册时输入的用户名、密码、角色进行登录，如图4-14所示。

![](/md/blog.023.png)

图4-14用户登录界面图



用户进入到首页界面，通过界面的首页，可以进行查看个人中心、志愿者报名管理、在线捐赠管理等功能模块，如图4-15所示。

用户在志愿者报名管理进行用户名、用户姓名、性别、联系电话、报名意愿、报名日期进行添加，管理员审核通过可成为志愿者，程序成效图如下图4-16所示:

![](/md/blog.024.png)

图4-15 首页界面图

![](/md/blog.025.png)

![](/md/blog.026.png)

图4-16 志愿者报名管理界面图

在线捐赠管理，用户在在线捐赠管理页面通过查看可进行物品捐赠、添加、修改、删除操作，如图4-17所示。。

![](/md/blog.027.png)

图4-17在线捐赠管理界面

第五章  软件测试

`	`测试存在于软件开发进程中的最后一个阶段，它可以保证一个软件的开发质量是否符合设计者的初衷，也为程序的正式上线做了最后一道质量检测的工序。软件测试主要是控制各种条件、包括软件输出方式，使用模式和运行环境等，来评估一个系统或应用是否符合设计标准。在软件测试过程中，我们一般刻意的去制造错误和极端条件，不能仅依照正常模式允许，而是多去尝试那些意外的情况。

5.1软件测试的重要性

`	`只有在运行和维护阶段之前经历大量的测试的软件，才能说明它的质量是经得起检验的。最近计算机业界也都一致认为，测试应该存在于软件设计的每个阶段，因为越早发现错误，修复起来就越容易。

`	`实际上，对于一个软件应用，错误是必然存在的，无论使用何种技术或手段，都不可能绝对的排除软件漏洞。测试是随着软件开发一同诞生的，两者是共同发展进步的。实际上，测试可以大幅度的降低维护的成本，如果一个漏洞在开发的早期就被发现，那么修复它的成本远比上线后再修复的成本要低得多。

5.2测试实例的研究与选择

测试有白盒测试和黑盒测试两种方式。

其中，白盒测试是将软件看成一个透明的白盒子，按照程序的内部控制结构和处理技术逻辑来选定测试用例、软件系统测试的逻辑路径及过程需要进行管理测试，又称玻璃盒测试。因此白盒测试需要选择足够多的测试用例，覆盖尽可能多的代码来发现程序中的错误。

黑盒测试，也称为功能测试。它将需软件看作一个黑盒，像一个普通用户一样来模拟软件的使用流程。黑盒测试通过大量的输入边界值或错误数据，来检查是否可产生正确的输出。

本系统测试 主要选择黑盒测试，少量采用白盒测试。通过测试达到以下测试目的：

1.检查各大功能模块的运行，确保其能够正确运行，并检查各页面的完整性，保证页面完整。

2.检查各个接口是否可以正确地输入和输出，保证数据流通稳定可行。

3.检查数据结构，保证其和外部接口没有访问错误，访问顺利。

4.检查原计划的性能需求有没有完成，运行流畅。

本系统的测试用例（部分）：

|**登录部分测试用例**|
| :-: |
|**编号**|**对象**|**项目**|**操作**|**预期结果**|**结果**|
|1|登录|登录提示|使用正确的账号密码登录|成功登录|预期结果|
|2||登录提示|使用正确的账号但错误的密码登录|提示密码错误|预期结果|
|3||登录提示|使用错误的账号登录|提示不存在账户|预期结果|
|4||登录提示|不输入账号，点击登录|提示输入账号|预期结果|
|5||登录提示|输入账号但不输入密码点击登录|提示输入密码|预期结果|
|6||登录入口|已登录账号，查看登录入口|不显示登录入口|预期结果|

5.3测试环境与测试条件

处理器：Inter Core I7-4710MQ四核处理器

内存：4GB

硬盘：1T

操作系统：Windows 10

数据库：MySQL

5.4系统运行情况

`	`全部测试用例都已通过（包括但不限于以上测试用例），且不存在漏洞，实现了论文开始时所作要求。本系统运行稳定，使用流畅，可以满足用户需求。

5.5系统评价

`	`5.5.1系统功能评价

试运行后进行系统评估，可以认为该系统达到预定的目标要求，可以满足用户的需求，也满足了系统开发前所作目标。

`	`5.5.2系统技术评价

系统在经过大量重复测试后运行十分稳定，安全实用，功能模块已经达到预定目标所需。

`	`5.5.3系统经济评价

在规定的时间内实现系统的大部分功能，且满足要求，节省开发成本，有助于提高科学管理水平，符合本人经济情况。

第6章 总结

2021年的今天，计算机技术已经相当成熟。它的发展推动了许多行业改头换面，计算机的出现使人类社会有了进一步降低人力物力和资源的方法，提高了人类社会的生产力，转变了社会生产方式。本文利用jsp技术和MySQL数据库，通过分析现实定西扶贫惠农推介系统的扶贫计划信息的基础上，并完成了在线定西扶贫惠农推介系统。经调试结果显示，本系统基本可以满足一个在线定西扶贫惠农推介系统的需要。系统界面简洁而有美感， 易操作，做出了自己的特点，然而因为时间仓促再加上缺乏系统开发经验和仅依靠少数问卷调查方式，因此本系统还存在不少缺陷、不足，比如：

\1. 数据输入的格式并没有全部检验，所以很难保证数据的准确，可能有一些不符合规则的数据也可以通过检验。

\2. 系统功能还不够完善，无法提供丰富多彩的在线功能，只能实现等一系列功能。

本系统还存在一些漏洞没有解决，在现实应用情境中很难保证完全不出错，但相信通过再次完善，可以调试出真正符合实际的在线定西扶贫惠农推介系统。

`                                `参考文献：

[1] 贝伊利 (Lynn Beighley),莫里森 (Michael Morrison),苏金国, 徐阳. Head First jsp & MySQL(中文版)[M]. 中国电力出版社,2018,03.

[2] 潘凯华,刘中华, 等. jsp开发实战1200例(第1卷)(附DVD-ROM光盘1张)[M].  清华大学出版社,2016,01.

[3] 帕蒂拉(Armando Padilla),霍金斯(Tim Hawkins),盛海艳,刘霞. 高性能jsp应用开发[M]. 人民邮电出版社,2018,11.

[4] 陈益材,等. jsp+MySQL+Dreamweaver动态网站建设从入门到精通(附多媒体语音教学光盘)[M]. 机械工业出版社,2018,06.

[5] 高洛峰,LAMP兄弟连. 细说jsp(精要版)(附DVD光盘1张)[M]. 电子工业出版社,2019,06.

[6] Lorna Mitchell,等. jsp精粹:编写高效jsp代码[M]. 机械工业出版社,2018,10.

[7] 列旭松,陈文. jsp核心技术与最佳实践[M]. 机械工业出版社,2018,07.

[8] Symfon,Cakejsp,Zend Bartosz Porebski,Karol Przystalski,Leszek Nowak, 付勇. jsp框架高级编程:应用[M]. 清华大学出版社,2017,02.

[9] 波诺赛克 (Boroncxyk.T.),Elizabeth Naramore,薛焱. Web开发入门经典:使用jsp6、Apache和MySQL[M]. 清华大学出版社 ,2017,07.

[10] 辛洪郁,张鑫. jsp项目开发全程实录(第3版)[M]. 清华大学出版社,2019,11.

[11] 杨宇,等. jsp典型模块与项目实战大全(附DVD-ROM光盘1张)[M]. 清华大学出版社,2018,01.

[12] 贾素来．常见动态网页技术比较[J]．大众科技，2018,9.

[13] 西尔伯沙茨(Silberschatz.A.) . 计算机科学丛书：数据库系统概念(原书第6版)[M]. 机械工业出版社,2018,03．.                                                      

[14]萨师煊，王珊．数据库系统概论[M]．北京:高等教育出版社，2019：10-180．

[15]陈刚．Eclipse从入门到精通[M]．(第2版)．北京:清华大学出版社，2018：17-380． 

致谢

`	`大学生活在这个时候即将划上一个句号，但是对于我的人生道路来说，这仅仅是一个逗号，我将面对的是又一次征程的开始。

`	`回忆过去，许许多多的事情浮现在脑海：刚上大学时欢乐心情和兴奋的场景还历历在目。一切都是那么新鲜，那么富有吸引力。有快乐也有艰辛，有收获也有失落。衷心感谢学院所有支持帮助过我的同学，谢谢你们多年来的关心和爱护。同窗的友情同样难忘，你们与我共同走过了人生中不平凡的道路，给我留下了值得珍藏的美好记忆。

`	`最后，我要特别感谢指导过我的教师。本论文是在他的悉心指导和热情帮助下完成的，教师认真负责的工作态度，严谨的治学精神和精深的理论水平都使我受益匪浅。教师无论在理论上还是在实践中，都给予我很大的帮助，使我专业技能的应用水平得到很大提高，这对于我以后的工作和学习都有益处。值此论文完成之际，特别向教师表示衷心的感谢和崇高的敬意，谢谢他细心而又耐心地辅导，使得我得以顺利的完成毕业设计开发工作，同时也要感谢其他帮助过我的教师和同学，他们在我成长过程中给予了我很大的帮助，在此一并表示感谢。

`	`由于本人水平有限，加上时间紧促，本文一定有不少缺点和不足，恳请各位教师给予帮助和指正。





31
![](/md/blog.028.png)	











