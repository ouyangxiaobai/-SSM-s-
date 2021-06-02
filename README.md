# -SSM-s-
基于SSM框架的手机商城设计与实现毕业论文+任务书+项目源码及数据库
下载地址：http://ym.maptoface.com/2021/06/02/%e5%9f%ba%e4%ba%8essm%e6%a1%86%e6%9e%b6%e7%9a%84%e6%89%8b%e6%9c%ba%e5%95%86%e5%9f%8e%e8%ae%be%e8%ae%a1%e4%b8%8e%e5%ae%9e%e7%8e%b0%e6%af%95%e4%b8%9a%e8%ae%ba%e6%96%87%e4%bb%bb%e5%8a%a1%e4%b9%a6/​
摘 要
伴随着Internet的蓬勃发展，网络手机商城中心作为网上手机商城的一种形式正以其高效、低成本的优势，逐步成为新兴的经营模式和理念，人们已经不再满足用途信息的浏览和发布，而是渴望着能够充分享受网络所带来的更加多的便利。网络手机商城正适应了当今社会快节奏地生活，使顾客足不出户便可以方便快捷轻松地选购自己喜欢的商品。
本系统便是尝试用SSM在网络上架构一个动态的网上手机商城，它是在Windows 系统下，以SSM为数据库开发平台，Tomcat网络信息服务作为应用服务器，采用SSM(Java Server Pages)技术开发的网上手机商城系统。他分前台部分和后台部分，前台部分由用户使用，主要包括用户注册，手机购物车管理，订单管理，个人资料管理，留言板管理等功能；后台部分由管理员使用，主要包括商品管理，处理订单，用户信息管理，链接信息管理等功能。
建立后的商城系统是一个动态、交互式、具有商品提供、系统管理、用户留言等功能的网上手机商城。
关键字：手机商城；手机商城系统；交易商城；Java；SSM

Abstract
Along with the vigorous development of Internet，the online shopping center，as a form of online mobile phone mall，is gradually becoming a new business model and concept with its advantages of high efficiency and low cost. People are no longer satisfied with the browsing and publishing of use information，but eager to be able to fully enjoy the more convenience brought by the network. Online shopping is adapting to the fast pace of life in today's society，so that customers can easily，quickly and easily favorite goods without leaving home.
This system is to try to use SSM to construct a dynamic online mobile mall website on the network，it is under the Windows XP，with SSM as the database development platform，the network information service as the application server，uses the SSM (Java Server Pages) technology to develop the online mobile mall system. He is divided into the front part and the background part，the front part is used by the user，mainly including user registration，shopping cart management，order management，personal data management，message board management and other functions；the background part is used by the administrator，mainly including commodity management，processing orders，user information management，link information management and other functions.
After the establishment of the website system is a dynamic，interactive，with commodity supply，system management，user messages and other functions of the online mobile mall website.
Keywords: Mobile Mal；Shopping System；Trading Website；Java；SSM


目  录
摘 要 I

Abstract II

1绪论 1

1.1系统开发背景 1

1,2研究现状 1

1.3研究主要内容 2

2相关技术 4

2.1 SSM的技术原理 4

2.1.1 SSM语言及其特点 4

2.1.2 Java及Java Servlets概述 5

2.1.3 JavaBean简介 5

2.2 服务器配置 6

2.2.1 Tomcat安装及配置 7

2.2.2 数据库配置 7

3系统分析 10

3.1 可行性分析 10

3.1.1 技术可行性 10

3.1.2 操作可行性 10

3.1.3 经济可行性 10

3.1.4 法律可行性 10

3.2 手机商城功能需求分析 10

3.3 数据库需求分析 11

4系统设计 12

4.1 系统功能模块设计 12

4.2系统流程设计 12

4.2.1 系统开发流程 12

4.2.2 用户登录流程 13

4.2.3 系统操作流程 14

4.2.4 添加信息流程 14

4.2.5 修改信息流程 15

4.2.6 删除信息流程 15

4.3系统用例分析 16

4.3.1 管理员用例图 16

4.3.2 用户用例图 17

4.3.3 ER图 18

4.4 数据库设计 21

4.4.1 tb_Ware(商品信息表) 21

4.4.2 tb_manager(管理员信息表) 21

4.4.3 tb_sub(订单生成表) 21

4.4.4 tb_Link(超级链接表) 22

4.4.5 tb_Affiche(公告信息表) 22

4.3 用SSM连接数据库 22

5系统实现 24

5.1 前台部分 24

5.1.1 前台总体框架 24

5.1.2 商城首页 24

5.1.3 产品详情页 25

5.1.4 评价 25

5.2 后台部分 26

5.2.1 后台主页 26

5.2.2 后台评价管理 26

5.2.3 商品管理 27

5.2.4 商品修改 27

5.2.5 分类管理 28

5.2.6 订单管理 28

5.2.7 手机购物车管理 29

6系统测试 30

6.1系统测试的意义 30

6.2性能测试 31

6.3测试分析 31

总  结 32

致  谢 33

参考文献 34

点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动 点击并拖拽以移动

