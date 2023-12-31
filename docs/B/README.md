## 指令

### 经济

`/pay <金额> <玩家列表...>` 向一名或多名玩家发送游戏币（ P点）。多名玩家用空格分开。例如 `/pay 100 player1 player2`。注意，汇款功能收取 5% 手续费，实际到达收款玩家的账户金额会少于实际发送金额。

`/ah` 打开全球市场，左键点击购买 1 件物品，潜行+左键点击购买一组物品。市场的交易消费税为 5%。

`/ah sell <单价>` 上架物品到全球市场。上架费为 10 P点/次。玩家可上架使用最多 5 个物品栏位。

> 木牌商店：手持牌子右键箱子，可用的商店种类有：**sell、buy、slot**。第二第三行可自定义。最后一行输入“$价格”，再手持红石粉，先左键单击一个箱子，再左键点击写好的牌子完成商店的绑定。每个商店最多绑定2个箱子，每人最多可以创建15个商店。

### 职业

`/mcstats` - 查询你的MCMMO信息

`/mcmmoview OPEN` 查询你的MCMMO信息（图形化界面）

`/<skill>`- 查看技能的详细信息

`/mctop <skill> <page>` - 排行榜

`/inspect <player>` - 查看玩家详细信息

### 队伍

`/party create <名称>` - 创建一个新队伍

`/party join <玩家>` - 加入一个玩家的队伍

`/party quit` - 离开你现有的队伍

`/party chat` - 切换队伍聊天

`/party invite <玩家>` - 发送组队邀请

`/party accept` - 接受队伍邀请

`/party teleport <玩家>` - 传送到队伍成员

### 粘液科技

`/sf guild` 获得一本粘液科技指南书

`/sf stats` 查看自己的粘液科技进度统计

### 辅助

- `/u show` 展示手中物品。
- `/u sit` 切换座椅功能，开启后右键特定类型的方块可以坐在上面。
- `/u chat prefix set <前缀>` 设置前缀。允许使用 `&#RRGGBB` 格式的 RGB 颜色代码。每次设置消耗 250 P点。注意：可能需要重新登入服务器才会生效。
- `/u chat suffix set <后缀>` 设置后缀。允许使用 `&#RRGGBB` 格式的 RGB 颜色代码。每次设置消耗 250 P点。注意：可能需要重新登入服务器才会生效。
- `/u chat prefix remove` 清除前缀
- `/u chat suffix remove` 清除后缀
- `/u item rename <名称>` 为物品更名，允许使用格式代码。每个物品 25 P点
- `/u xp store <数量>` 保存经验到手中的经验瓶中
- `/u xp take <数量>` 从手中的经验瓶取出经验。也可以直接砸开
- `/u lock setup` 锁定展示框，用作保护物品。展示框锁定时会复制并弹出内含物品。展示框在被外力破坏时，不会再掉落物品
- `/u lock property` 编辑锁定展示框的属性，如物品发光与框体透明
- `/u signedit <行数> <内容>` 编辑手中的牌子，编辑后放置该牌子即可显示内容
- `/u redbag create <类型> <金额> <个数> <密码>` 发红包，类型可以为 `fixed` 或 `lucky`，即为固定金额红包或拼手气红包。如果类型为固定金额，金额部分识别为单个金额，如果类型为拼手气，金额部分识别为总金额。密码可选，请遵守一般聊天规则设置密码

### 日志检查(co i)

`/co i` 打开日志查看器，左键点方块、右键点箱子查看变更记录。再输入一次 `/co i` 关闭查看器回到正常生存状态。

### 在线时间统计

`/ptt` 查看自己的游戏时间。

提醒满足在线奖励规则时，使用 `/ptt ac` 领取在线时间奖励。在线时间奖励分为经济活跃、每日、每周、每月奖励。

> 经济活跃奖励，即为全球市场中的各种交易税收所得中抽取 0.01% 作为促进经济活跃的奖励办法。在一定的下限和上限内，交易活跃、税收多时，奖励也就越高。