# 权限管理

## 功能权限

可以对以下功能及操作进行权限控制：

1. 概览

   查看：控制导航栏中概览的可见性

2. 实时

   查看/新建/编辑：控制导航栏中实时的可见性；添加新的实时指标；删除已存在的实时指标

3. 看板

   查看：控制导航栏中看板的可见性 新建：控制产品中所有新建/另存为看板的操作 分享：控制产品中所有对看板的分享操作

4. 业务场景

   查看：控制导航栏中业务场景的可见性

5. 单图

   查看：控制导航栏中单图的可见性 新建：控制产品中所有新建/另存为单图的操作 分享：控制产品中所有对单图的分享操作 下载数据：控制是否可以下载单图数据

6. 留存魔法师

   查看：控制分析模块下留存魔法师的可见性

7. 智能路径

   查看：控制分析模块下智能路径的可见性

8. 漏斗

   查看：控制分析模块/看板/单图中漏斗入口的可见性 新建：控制产品中所有新建/另存为漏斗的操作 分享：控制产品中所有对漏斗的分享操作

9. 页面流

   查看：控制分析模块下页面流的可见性

10. 留存

    查看：控制分析模块/看板/单图中留存入口的可见性 新建：控制产品中所有新建/另存为留存的操作 分享：控制产品中所有对留存的分享操作

11. 热图

    查看：控制圈选模块下热图Tab的可见性

12. 圈选

    允许圈选：控制圈选模块下浏览/圈选Tab的可见性，以及圈选指标的保存/另存为等操作

13. 用户细查

    查看：控制用户模块下用户细查入口的可见性

14. 用户分群

    查看：控制用户模块下用户分群入口的可见性 新建：控制产品中所有新建分群的操作 分享：控制产品中所有对分群的分享操作 下载数据：控制是否可以下载用户分群数据

15. 指标管理

    查看：控制管理模块下指标管理入口的可见性 编辑/删除：控制是否可以编辑/删除某一个指标 分享：控制产品中所有对指标的分享操作

16. 渠道管理

    配置与管理-日志数据下载：控制用户是否可下载激活日志数据。

    配置与管理-权限管理：控制用户是否可见&可编辑不同用户的渠道资源权限。

    推广活动-查看：控制用户是否可见推广活动。

    推广活动-新建/编辑/删除：控制用户是否可新建&编辑&删除推广活动。

    监测链接-查看：控制用户是否可查看监测链接数据。

    监测链接-新建/编辑/删除：控制用户是否可编辑&新建&删除监测链接。

    基础数据-报表数据下载：控制用户是否可下载数据报表。

    基础数据-移动端-激活概览查看：控制用户是否可见激活概览模块。

    基础数据-移动端-推广详细查看：控制用户是否可见移动端的推广详细报表。

    基础数据-网页端-推广详细查看：控制用户是否可见网页端的推广详细报表。

![](../.gitbook/assets/gongnengquanxian.png)

1. 角色管理

   查看：控制角色管理入口的可见性 新建/编辑/删除：控制是否可以新建/编辑/删除一个角色

2. 项目管理

   查看：控制项目概览/项目配置入口的可见性 新建/编辑/删除：控制是否可以新建/编辑/删除项目配置

3. 用户管理

   查看：控制用户管理入口的可见性 新建/编辑/删除：控制是否可以新建/编辑/删除一个用户

4. 邀请技术支持

   允许邀请：控制是否可以邀请GIO工程师进入项目

5. 应用管理

   查看：控制应用管理入口的可见性 新建/编辑/删除：控制是否可以新建/编辑/删除一个应用

## 资源权限

可以对概览/看板/单图/漏斗/留存/分群/指标/渠道管理的推广活动和链接等资源进行如下控制：

1. 概览：

   可以控制每个用户在概览下每一张图表的可见性

2. 看板/单图/漏斗/留存/分群/指标：

   在自己新建后，准备分享时，可以指定分享的范围为仅自己可见/部分用户可见/部分小组可见/所有人可见，同时可以指定对资源的操作权限，包括：

   **查看：**资源可见、可收藏

   **管理：**资源可编辑、可删除

   **分享：**资源可再次传递，例如A创建的资源分享给B，B可以再次分享给C \(**注：在资源传递过程中，操作权限不可变更，始终由资源的创建人控制**\)

3.渠道管理资源权限说明：

在渠道管理的资源权限管理模块可以对不同角色不同用户进行不同的推广活动权限控制。

![!\[\]\(/assets/权限管理4.png\)](../.gitbook/assets/ziyuanquanxian.png)

## 数据权限

可以对每一个用户设置多个数据访问限制条件，并在全局生效，所有访问数据的节点都会被控制，主要通过设定维度值范围来生效，支持设置的维度包括：

1. 系统默认维度：访问来源、一级访问来源、浏览器、操作系统、城市、地区、国家代码、国家名称、域名、网站/手机应用、设备类型、广告来源
2. 自定义维度：全部

支持的条件组合包括：

1. =
2. ≠
3. In
4. Not in

![](../.gitbook/assets/quan-xian-guan-li-5.png)

## 小组

用户小组功能，帮助您更好的分享项目内部的看板。您可以通过小组快速定义看板的可见性，实现只有特定的人看到特定的看板

### 新建小组

您可以在「用户管理-小组」中找到新建和管理小组的入口。您可以自由的将任意用户加入到小组中，一个用户可以从属于多个小组中。

注意：

* 新建和管理小组必须由管理员用户进行操作
* 删除小组需要谨慎操作，一旦小组被删除，小组成员可能丧失部分看板的权限

## 添加用户&批量添加用户

管理员可以通过添加用户或批量添加用户功能直接在系统中添加用户，通过管理员添加的用户，在添加完成后，该用户邮箱会收到一封初始邮件，包含初始登录密码和系统登录地址，用户在首次登录时，需要修改自己的登录密码。

![](../.gitbook/assets/tian-jia-yong-hu.png)

### 1.添加用户

管理员在直接添加用户时，需要输入该用户的名称、邮箱、部门等信息，同时选择该用户绑定的角色，并点击【确认】。随后，该用户邮箱会收到系统发送的初始邮件，按照邮件引导完成首次登录。

![](../.gitbook/assets/chuang-jian-yong-hu-1.png)

![](../.gitbook/assets/chuang-jian-yong-hu-2.png)

### 2.批量添加用户

管理员通过批量添加用户功能，可以一次性最多批量创建1000名用户。首先通过系统下载用户模板，并在模板中添加好将要创建的用户名称、邮箱等信息，然后将保存后的文件直接拖入系统，系统会自动检测模板内填写的内容是否符合规范，如不符合规范，请修改后重新上传。

注意： 1. 名称、邮箱等信息不要使用空格、特殊字符 2. 请至少将用户的角色在模板中指定为普通成员 3. 已经创建成功的用户无法再次创建，如果重复上传已经创建的用户，该用户会收到登录引导邮件，而不是初始密码邮件

![](../.gitbook/assets/pi-liang-tian-jia-yong-hu.png)

## 使用教程

Step1.点击右上角头像，进入到用户管理界面

![](../.gitbook/assets/quan-xian-guan-li-1.png)

Step2.点击左侧栏下方的新建「自定义角色」

![](../.gitbook/assets/quan-xian-guan-li-2.png)

Step3.选择该用户可以使用的功能模块，以及其他权限

![](../.gitbook/assets/quan-xian-guan-li-3.png)

Step4.邀请新用户/将现有的用户变更为自定义角色

![](../.gitbook/assets/qq20161226-2.png)

