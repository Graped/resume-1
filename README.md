# 简历-张哲


## 基本信息
* 男，汉族，1988年2月生，应届生，党员，现居北京市朝阳区
* **英语：** 六级
* **电话：** 18811577546
* **邮箱：** 626729890@qq.com 
* **Git Hub ：** [https://github.com/ZhangzheBJUT](https://github.com/ZhangzheBJUT)
* **个人网站：** [http://zhangzhe.qiniudn.com](http://zhangzhe.qiniudn.com)
* **求职意向：** 后端开发工程师

## 教育背景

* 2012.09 - 至今天，北京工业大学，计算机科学与技术，研究生
* 2008.09-2012.07，河北师范大学，软件工程，本科


## 技能知识

* **主要课程：** 面向对象技术、数字图像处理、模式识别、数据挖掘、高级数据库系统、计算机网络体系结构、UML建模、编译原理、软件工程、项目管理等
* **研究课题：** 基于MongoDB的数据中心分析与设计
* **基本技能：**
    * 熟练使用Hadoop、Storm、Hive进行日志数据处理
    * 熟练使用MongoDB数据库(复制集、分片)
	* 熟练的使用golang语言 (`beego`，`mgo`，`martini`框架) 进行服务器端程序开发
	* 较好的C/C++、数据结构算法功底以及面向对象设计模式思想
	* Linux下多线程编程、网络编程以及数据挖掘的典型算法
	* 熟练使用Xcode进行IOS平台的软件开发
	* 熟练使用MFC进行Windows程序设计
	* 熟练使用`Python`进行Web服务编写(`Flask`框架)
* **编程语言：** `C++`、`Golang`、`Objective-c`、`Java`、`PHP`、`Python`
* **开发工具：** Linux/OS X、VS2008、Sublime Text、Xcode、git


## 实习经历

* 2014.06 - 至今    **北京奇虎（360）科技有限公司**，360手机安全卫士日志数据处理与统计。
* 2013.03-2014.04 **中船电子科技有限公司**，主要负责后端服务开发和数据库运维管理等工作。
* 2010.03-2010.10 **无锡市庞景科技有限公司**，主要负责IOS和Android移动端的开发工作。

## 项目经验
1. **360手机安全卫士短信日志日报系统 ( 2014.06-至今)** 
   * **关键技术：**`hadoop`、`Hive`、`PHP`、`Java`
   * **项目描述：**使用 `Hadoop` 、`Storm`对手机安全卫士上传日志进行分析与统计，将拦截短信的数量、垃圾短信号码源的地域分布、用户举报以及用户恢复短信数等信息使用`High Charts`以日报形式展示。
   * **我的职责:** 在 `Hadoop` 平台上使用Hive进行日志相关信息提取和处理;期间使用`Java`以及`PHP (Hadoop-streaming）`编写MapReduce程序，提取日志中短信相关信息，并使用`High Charts` 做统计日报; 
2. **云端短信分类算法模型的自动更新   (2014.07 - 至今)** 
   * **关键技术:** `C++`、`Makefile`、`CppUnit`、`Valgrind` 
   * **项目描述:** 将新的短信分类算法模型经过运维部门提供的接口自动上线部署，新模型在上线前要经过测试程序检测，使用灰度放量的方式逐量为客户端提供服务。
   * **责任描述:** 负责对将要发布的短信分类模型进行`MD5`检验和短信分类测试。测试程序在`Linu`x上用`C++`语言开发，以动态链接库的方式调用模型中的短信预测接口，通过预先准备好的超级白和超级黑短信来评估分类算法。使用CppUnit来编写单元测试，使用Valgrind来对测试程序进行内存泄露检测。
3.  **机务维修管理系统 ( 2014.02-2014.05 )**
   * **关键技术：** `go`、`Martini`、`Python`、`Flask`
   * **项目描述：** 该系统基于B/S架构，用来跟踪飞机维修信息(飞行记录、维修日志、定期列表等），实现机务维修的信息化管理。该系统使用`Python`的`Flask`框架作为Web服务端，它通过访问**REST API**的方式从数据中心存取数据。
   * **我的职责：** 主要负责Web服务端与数据中心交互API以及部分`Python`功能模块的代码编写工作。  
4.  **通航云数据中心建设（2013.09-2014.05）**       
   * **关键技术：**`MongoDB`、`Hadoop`、`Redis`、`go`          
   * **项目描述：** 该项目是由国家发改委支持的通用航空项目。数据中心为全国各个通航公司提供气象情报、态势告警、飞行计划管理以及运维和机务管理等综合性保障的数据服务。它使用**MongoDB（复制集）**持久化数据，使用**Hadoop**对存储的数据进行分析处理，对高并发的数据(飞机态势)信息使用Redis数据库进行缓存。数据中心为监视系统、运维系统以及机务等业务系统提供数据服务。 
   * **我的职责：** 负责`MongoDB`数据库运行环境的搭建、复制集的配置、`Hadoop`简单数据处理以及数据库日常的维护管理工作。另外，参与负责`MongoDB`数据库与后端服务的数据访问接口开发以及前端REST API编写。期间用到了`Protocol Buffers`在服务端内部不同应用传输数据，使用`ZeroMQ`消息中间件来向客户端推送告警信息。        
5. **iPad 通用航空电子飞行包（2013.03-2013.07)** 
   * **关键技术：** 	`IOS`、`objective-c`、`MapKit`
   * **项目描述：** 电子飞行包是辅助飞行员查阅各种飞行手册、计划、气象、航图等信息。它从数据中心获取数据（主要包括态势、机场、空域、飞行计划以及各种飞行手册和文档），协助飞行员飞行。
   * **我的职责：** 负责iPad软件的架构设计、大部分的代码编写工作，**主要使用MapKit,Core Image,Quarzt 2D,Core Animation,AFNetworking等Framework**。
6. **基于北斗和GPS双模的机载导航系统（2014.02-2014.05）**  
   * **关键技术：**`IOS`、`objective-c`、`百度地图` 
   * **项目描述：**将从北斗终端wifi接口获取位置信息(经度、纬度、高度、航速、航向等），以及iPad GPS自身提供的GPS获取的数据数据，利用百度地图显式在iPad上，并实时更新当前的位置，显示飞行的轨迹等，辅助飞行员进行飞行操作。
   * **我的职责：**项目(iPad和Android两个版本)负责人，负责跟踪协调整个项目的开发，同时负责解析北斗报文。


## 获得奖励

* 大学期间 2008-2009、2009-2010、2010-2011连续三年获得一等奖学金。
* 2008-2009 校级三好学生荣誉称号、道德风尚奖
* 2009-2010、2010-2011院级三好学生荣誉称号
* 河北省2012年优秀毕业生荣誉称号
* 研究生期间积极参加学院组织的一些实训项目，获得老师的肯定和认可。
* [http://www.devstore.cn](http://www.devstore.cn) 的特约评测员

## 自我评价
性格开朗、 乐于助人，具有团队合作精神和强烈的责任感，勤奋踏实、勇于挑战自己。在大学和研究生阶段 参与了多个项目的开发工作，提高了自己的软件开发、逻辑分析能力，同时也培养了自己管理团队的能力。


**座右铭: 脚踏实地，追求卓越！**


## 兴趣爱好
乒乓球、音乐、旅行等









