# 翼龙面板-WHMCS模块
翼龙面板WHMCS自动售卖模块(仅适用于1.0+版本) 汉化-[官方翼龙](https://github.com/pterodactyl/panel) 或翼龙中国的汉化版本 [稳定版](https://github.com/pterodactyl-china/pterodactyl-chinese-stable) [开发版](https://github.com/pterodactyl-china/panel)
# 安装步骤
1. 下载或Clone该仓库
2. 移动pterodactyl文件夹到```/path/to/whmcs/modules/server/```
3. 在管理页面创建API并设置为下图
   ![API配置](https://download.imxbt.cn/upload/1657942358QQ图片20220716113227.png)
4. 前往WHMCS的管理员页面选择(WHMCS已经设置为中文)```系统设置->产品/服务->服务器设置```
   ![WHMCS](https://download.imxbt.cn/upload/1657942516QQ图片20220716113501.png)
5. 添加新的服务器->主机名(hostname)输入您的翼龙面板地址(不要带http(s)://),IP地址请勿填写,到最下面的 ```Server Type/服务器类型``` 中选择```pterodactyl``` API密钥填写到密码框即可(如果您的面板使用SSL请勾选下面的复选框)
6. 现在你可以为添加产品了!请到```产品/服务->产品```界面添加服务
7. 添加产品->类型选择其他产品(务必把模块选择为Pterodactyl)->配置好最基础的内容之后来到模块配置页面进行配置即可(我们在配置的内容上已经写有提示)
# 注意!
**客户购买服务之后将会在邮箱那里收到他的账户和密码,如果没有收到默认账户是他的电子邮箱地址,密码可以在whmcs的用户产品处进行修改密码**
