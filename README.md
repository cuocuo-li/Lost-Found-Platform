# 失物招领平台开发计划
#### 1. 项目概况
- 名称：失物招领平台
- 用途：用于失主发布失物通知，拾到失物者发布通知。
- 目标用户：本校学生
- 形式：网页平台，可由电脑和移动设备访问操作。
- 整体框架：
	网站分为3个主要页面：
&nbsp;&nbsp;&nbsp;&nbsp;1. 失物页面：有捡到他人丢失物品的用户将物品信息发布于此。
&nbsp;&nbsp;&nbsp;&nbsp;2. 寻物页面：丢失物品的用户将物品信息发布于此。
&nbsp;&nbsp;&nbsp;&nbsp;3. 个人中心：用户于此编辑个人信息，管理自己发布的失物、寻物消息（修改、删除等）。
- 主要功能（用户方）<br>
	1. 信息浏览、检索功能：在失物、寻物页面，以时间逆序（消息从新到旧）显示发布的物品信息。用户可以选择不同的分类方式（包括地点、物品类型、图片等）以查询不同种类的消息。物品信息内可查看发布人联系方式。<br>
	2. 注册/登陆功能：只有注册用户才可以使用此条之后的功能。用户需要录入必要的信息（包括真实姓名，手机号，QQ，学号，用户名，密码）以注册，同时也可以录入一些选填信息（包括QQ，邮箱，专业等）。注册后可以登陆并使用以下功能。<br>
	3. 管理物品信息功能：包括发布、修改、删除、认领失物/寻物信息。发布时的必要信息包括物品名称、类型；选填信息包括地点、时间等。只能修改和删除自己发布的信息。通过“认领”可以向消息发布者发送信息。<br>
	4. 个人中心功能：可以在个人中心编辑自己的信息；可以查看、修改和删除自己发布的信息。<br>
#### 2. 项目计划
- 时间安排<br>
5月13日~ 5月19日（第12周）：制作网站基本框架，完成页面基本布局，页间跳转逻辑。<br>
5月20日~ 5月26日（第13周）：完善页面内容，制作注册登录功能和个人信息管理功能。<br>
5月27日~ 6月2日（第14周）：制作消息管理功能（发布，删除，修改，确认）。<br>
6月3日~ 6月9日（第15周）：测试功能，修复bug。<br>
- 开发计划<br>
	- 网页前端使用HTML+CSS+JavaScript，后端使用Django框架。<br>
#### 3. 人员分工
李劭彧：程序员，负责网站后端功能的实现。<br>
郝正亮：程序员，负责前端和部分后端功能的实现。<br>
陈家祺：项目进度管理，负责整个项目进度的协调分工管理。<br>
周正昊：UI设计，负责网站的外观和UI设计。<br>
陶继坤：博客管理，负责项目日志的编写和博客的更新。<br>
徐嘉川：测试，负责在各个平台测试网站寻找BUG。<br>
