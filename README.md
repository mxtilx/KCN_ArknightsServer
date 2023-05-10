# KCN_ArknightsServer
![Github](https://socialify.git.ci/JDDKCN/KCN_ArknightsServer/image?description=1&forks=1&issues=1&language=1&logo=https%3A%2F%2Favatars.githubusercontent.com/u/103011451?v=4&name=1&owner=1&pulls=1&stargazers=1&theme=Light)
> 一个Ark服务端 - GUI一键端。
## F&Q

- Q:我该填什么IP?
- A:如果您想要自己玩，填入内网IP即可，一般形式为192.168.x.x。如果您想要开服，请填入您的域名或公网IP。注意：不需要加端口号及http前缀。更改IP的位置在一键端程序左下角-设置-常规设置-IP设置-点击更改IP。如果您不知道您的内网IP地址，请点击IP修改页面的"查看本机IP"查看。
- Q:我该怎么连接客户端？
- A:您先需要在手机中安装代理软件及旧版客户端，新版客户端无法使用。在代理软件中填入您服务端的地址并点击下方的启动即可连接并进入游戏。
- Q:客户端无法连接？
- A:首先，请检查您的IP地址是否正确。接着，请查看服务端是否报错，MySQL数据库是否工作正常。如果上述内容没有问题，请检查待连接的客户端设备是否和服务端在同一网络下。也就是说，服务端和客户端必须连接在同一个WIFI下(此处仅指内网连接的情况)。如果没有问题，请检查客户端代理APP中填写的地址是否正确，标准格式为 http://192.168.x.x:38660 ，检查您是否填入了中文符号。代理地址可在服务端启动的控制台窗口复制。
- Q:连接完成，我该怎么进入游戏？
- A:您需要注册账号并登录。注册账号时的手机号可以瞎填，只要是数字就行。验证码也请随便输一个。请记住自己填写的密码，避免以后忘记密码无法登录此账号。
- Q:我想开服，但是运行在服务器上的服务端无法连接客户端？
- A:当服务端正常运行，客户端却无法连接时，请检查您云服务器的安全组策略，开放所有端口，否则请求会被拦截导致无法连接。
- Q:服务端命令如何使用？
- A:give命令用法：give [玩家UID] [物品ID] [物品数量] ，举例：give 100001 char_325_bison 5 ，给予UID为100001的用户5个拜松。其它命令请自己探索，您可以在控制台输入help获取详细说明。
