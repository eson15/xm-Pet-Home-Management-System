# 【原创项目】基于Springboot+Vue的宠物管理系统
基于Springboot+Vue的【宠物管理系统】，系统代码全部原创，并提供带敲视频和笔记  

大家好，我是武哥，最近给大家手撸了一个基于Springboot+Vue的宠物管理系统，宠物领养，宠物寄养，可用于实习项目、毕业设计、课程设计等，系统全部原创，如有遇到网上抄袭站长的，欢迎联系博主~  

#### 项目在线体验地址  
体验地址：**（请电脑端浏览器访问）**：[http://111.229.67.228:82/](http://111.229.67.228:82/)  
管理员账号：**admin 123456**    
用户账号：**zhangsan 123456**    
线上环境，部分基础数据不允许修改 **（例如宠物信息、账号信息、宠物房间等等）**  ，宠物之家核心业务功能全部开放体验，例如：领养、寄养、购买宠物用品、充值、流浪宠物上报等等。  


#### 项目技术栈  
> 前后端分离  
> 后端：Springboot2 + Mybatis  
> 前端：Vue2 + ElementUI  
> 数据库： MySQL  
> 数据库表：十张表  

#### 项目功能描述  

>**管理员**  
>登录、个人信息、修改密码、管理后台管理系统所有数据  
>####   
>01、**宠物信息管理**：管理平台所有的宠物信息（包括上报那边处理后的宠物可以添加到平台）  
>02、**宠物房间管理**：管理员平台所有的宠物房间（用于用户寄养宠物的时候分配使用）  
>03、**宠物领养管理**：宠物领养管理  
>04、**宠物寄养管理**：管理用户在平台寄养的所有宠物，**支持给宠物分配房间，寄养结束自动释放房间**  
>05、**宠物用品管理**：管理平台上所有的宠物用品信息，给用户提供购买入口  
>06、**订单信息管理**：管理平台上用户购买宠物用品所有的订单，可以对订单进行发货处理  
>08、**公告管理**：管理用户向平台上报的所有流浪宠物信息，可以线下安排人去处理，处理好之后可以把上报信息状态更新为已处理，然后将救助回来的宠物信息上传到平台，供用户去领养  
>09、**系统公告管理**：管理平台系统公告  
>10、**管理员信息管理**：管理管理员的信息  
>11、**用户信息管理**：管理平台用户信息  
>#### 
>**用户**  
>注册、登录、个人信息、修改密码、查看系统公告  
>#### 
>1、**宠物信息查看**：可以查看平台所有待领养的宠物信息  
>2、**宠物领养**：对自己喜欢的宠物可以进行领养，在领养中的宠物可以放弃领养（归还平台）  
>3、**宠物寄养**：如果有自己的宠物需要寄养，可以向平台发布寄养，管理员会给宠物分配房间，寄养结束房间释放  
>4、**宠物用品查看**：查看平台所有的宠物用品（包括狗粮猫粮，除虱用品等等）  
>5、**购买宠物用品**：对需要的宠物用品，可以进行购买，填写自己收货信息，等待管理员发货，收到货可以确认收货  
>6、**流浪宠物上报**：用户看到流浪宠物可以拍照，在平台上传上报流浪宠物信息，管理员看到会做处理，处理后的宠物，可以在平台添加信息，等待用户来领养  
>7、**个人中心余额充值**：在购买宠物用品的时候，如果余额不足，需要在个人中心进行充值  

#### 创新点
> 1、真实模拟宠物相关的所有功能操作，非简单的增删改查，包括领养、寄养、流浪宠物上报、宠物用品购买  
> 2、整个过程实现一个完整的闭环，对流浪宠物进行救助，之后再领养，包括宠物用品的购买发货和收货  
> 3、宠物领养页面和宠物用品购买页面进行卡片式设计，改变普通管理系统的死板  
> 4、巧妙的数据关联设计（宠物寄养、领养、订单等操作涉及到两个角色之间的交互）  
#### 页面关键截图  
登陆页面:![请添加图片描述](https://img-blog.csdnimg.cn/direct/926ccfdbf941450892f18a5ea47c4d00.png)
#### 管理系统页面
系统首页:![请添加图片描述](https://img-blog.csdnimg.cn/direct/0d03532ba9aa49d7a31a62ea0236d6c4.png)管理员视角宠物管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/1cf10222b40d4833befa37a1901b1544.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/4d7e512738fd45afbea7843ed678e2aa.png)领养记录：![请添加图片描述](https://img-blog.csdnimg.cn/direct/cfdc3a4aa53e46ebacc53dcd2daf0c11.png)
宠物房间管理：
![请添加图片描述](https://img-blog.csdnimg.cn/direct/0786beb0b5044643a50c94d8038e71ae.png)寄养管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/601e92a9ba7f48e59967423d802887da.png)宠物用品（管理员视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/091c4d7125a24604b959b7a650d2ae73.png)宠物用品（用户视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/bf6a90303301413e9e5ffcf4b1c804a5.png)订单管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/602813f981584fdeab5b9e3a999ea556.png)宠物上报：![请添加图片描述](https://img-blog.csdnimg.cn/direct/15015a1bb5c74edc852b44f237e48287.png)用户管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/64065848e93642228000f84a94dbfc29.png)个人中心充值：![请添加图片描述](https://img-blog.csdnimg.cn/direct/4a344fa55a1545e1ae613f37e093b2cd.png)项目涉及到的十张表：![请添加图片描述](https://img-blog.csdnimg.cn/direct/79656f0d575a4d5993418dd20ec1d82e.png)

资料获取方式：加入知识星球：【项目训练营】即可
<img src="https://img-blog.csdnimg.cn/direct/44f688415c0c47cc81ad08a1f275e6a4.png" width="300px" />

**星球提供**：

1. （**价值**）星球内部的所有实战项目均提供脚手架、详细的笔记和完整的带敲视频，可以跟着完整学习视频敲出来，学习过程中提供一对一答疑。
2. 星球内部的实战项目会一直更新，星球成员可以学习所有项目，具体项目列表如下（长期更新）：[https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf](https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf)
3. 星球内部会提供不同的专栏，其中除了上述实战项目外，还有学习资料，比如经典学习笔记、超全面试题等
4. 星球内部会不定期分享学习经验，开发经验，工作经验，如果你有需要，也可以提供相应文档  
