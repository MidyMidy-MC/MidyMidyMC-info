MidyMidy 第三周目
=====

我的子民们，欢迎回来！ -- King Casper

服务器基本信息
-----

###1. 访问地址
* 121.42.30.62
* 114.215.156.251
* mc.hijack.moe （Jack Zhang 提供）
* mc-bak.hijack.moe （Jack Zhang 提供）
* midymidy-mc.hijack.moe （Jack Zhang 提供）
* mc.wetofu.top（TonyChyi 提供，有负载均衡）

###2. 插件
* CrazyLogin：登录管理器
* AdvancedBankAccounts：银行帐号和商店
* iConomy：金钱插件
* SignShop：木牌商店
* Lockette：木牌锁箱插件
* WorldEdit：地图编辑器
* WorldGuard：防爆插件
* AntiCropTrample：农田保护
* GameModeInventories：不同游戏模式的独立物品栏
* HomeSpawnPlus：设置家和出生点
* MoneyMobs：杀怪赚钱
* MotdManager：服务器提示（Motd）插件
* MultiWorld：多世界插件，提供一个创造界
* PerfectBackup：备份
* PermissionsEx：权限管理
* PurpleIRC：IRC对接
* ServerWelcome：服务器登录欢迎
* ModifyWorld

###3. IRC
\#MidyMidymc@freenode.net

各插件使用方法
-----

### 登录和权限

登录后属于default组，不能做什么事情。

用`/register <你的密码>`命令注册，然后我就可以手动把你们放到player组里面去。
（注册完了最好水一封邮件到邮件列表）

### 锁箱插件

放一个箱子，直接在上面放一块牌子，什么也不输入直接退出，然后就锁住了。

### 经济系统

现在改用iConomy插件 + SignShop插件。

使用`/money`命令查看余额，每个人最初有300元钱。

通过MoneyMobs插件来增发货币。
* 僵尸7元
* 蜘蛛10元
* 骷髅12元
* 爬行者10元
* 僵尸猪人10元。

###SignShop用法：

1. 放一个箱子，锁不锁随意。在里面放上一次性要卖掉的东西（每次卖这么多）。
2. 放一个牌子，格式如下：
> line1: [Buy]  
> line2: 东西名字（随意填写）  
> line3: 描述（随意）  
> line4: 价格  

3. 手持红石粉，左键单击箱子，然后在左键单击牌子，即可关联。
4. 左键单击牌子可查看商店内容（可以精准的看到所出售的物品），右键单击牌
子可以购买东西。

###穿越到创造界

在出生点附近可以找到传送点，即可穿越到创造界。

如果在创造界迷路，可以使用`/spawn`回到传送点。
