# DalamudPluginsCN-Dev

适用于国服的Dalamud第三方插件仓库 **`dalamud-api6 net5.0-windows`**

本仓库仅存储**非主库插件以及未适配的主库测试插件**，若有插件移入国服主库后会进行移除

若插件无法使用，请查看 Dalamud Console（使用`/xllog`打开）中报错并截图提交 issue

**本仓库所有插件禁止各种形式的倒卖！持续的倒卖行为可能会被挂上本仓库耻辱墙。**

## 使用须知 Warning

根据[《盛趣游戏用户使用许可协议》](https://ff.web.sdo.com/web8/index.html#/newstab/newscont/217463)第四部分 3.1 相关条款，禁止用户使用破坏公平性的外挂软件参与游戏。

本插件仓库以研究性目的而**非盈利**目的开发，**请勿扩散宣传乃至上架售卖**，下载后请在24小时内删除。

根据[《最终幻想14》账号处罚细则明细](https://ff.web.sdo.com/web8/index.html#/newstab/newscont/268832)：

> **5.使用脚本进行游戏包括但不仅限于非盛趣游戏开发、授权的第三方软件、插件等进行采集制作战斗任务等，破坏游戏平衡的行为。**
>
> 一旦查实初次将会处以30天的账号冻结处罚并清空相关游戏所得。屡次违规者**永久冻结**。
>
> **7.制作、宣扬以及使用外挂程序进行游戏包括但不限于加速、瞬移、异常飞天遁地，修改角色数据（攻击、血量）等表现形式。**
>
> 一旦查实将**永久冻结账号**。
>
> **8.利用系统的BUG、漏洞为自己及他人牟利。**
>
> 一旦查实将**永久冻结账号**。

请您知悉使用本插件的相关风险，使用本插件过程中导致的一切**封号风险请自行负责**。

根据[《互联网出版管理暂行规定》](http://www.scio.gov.cn/zhzc/8/5/Document/1014219/1014219.htm)第六条：

> “从事互联网出版活动，必须经过批准，未经批准，任何单位或个人不得开展互联网出版活动。” 

外挂类商品属于**非法出版物**，倒卖将构成**非法经营罪**，望**小店**进货商知悉，**因在中文互联网倒卖宣传**导致的一切**法律风险请自行承担**。

## 使用 Usage

### 测试仓库 Testing plugins

**优先仓库**，插件下载地址位于插件源码仓或其他发布源，**优先更新**

`https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/PluginMaster.json`

### 备份仓库 Stable plugins

**无需订阅**，仅备份闭源插件，防止发布源变更导致无法访问或无法适配

`https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/dist/PluginMaster.json`

### 莫迪翁仓库 Mordion Gaol

**不能保证账号安全**，请酌情考虑风险使用

``https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/MordionGaol.json``



## 内容 Contents

### 测试仓库 

| 插件名称                                                     | 介绍                                         | 插件作者                                              | 本地化维护                                      | 汉化 | 下载量                                                       |
| ------------------------------------------------------------ | -------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------- | ---- | ------------------------------------------------------------ |
| [PostMeteion](https://github.com/gamous/PostMeteion)         | 梅蒂恩会执行光呆的指令并汇报成果             | [gamous](https://github.com/gamous)                   | -                                               | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/PostMeteion/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/PostMeteion/total.svg?label=)]() |
| [ActionTimeline](https://github.com/Tischel/ActionTimeline)  | 更好的实时技能显示与循环记录                 | [Tischel](https://github.com/Tischel)                 | [ArchiDog1998](https://github.com/ArchiDog1998) | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/ActionTimeline/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/ActionTimeline/total.svg?label=)]() |
| [BDTHPlugin](https://github.com/LeonBlade/BDTHPlugin)        | 允许通过坐标轴移动家具并解除摆放限制（汉化） | [LeonBlade](https://github.com/LeonBlade)             | [gamous](https://github.com/gamous)             | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/BDTHPlugin/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/BDTHPlugin/total.svg?label=)]() |
| [FishNotify](https://github.com/carvelli/Fish-Notify)        | 钓鱼咬钩时发出声音以及聊天框提醒             | [carvelli](https://github.com/carvelli)               | [gamous](https://github.com/gamous)             | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/FishNotify/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/FishNotify/total.svg?label=)]() |
| [Browsingway](https://github.com/gamous/Browsingway)         | 游戏内浏览器悬浮窗显示                       | [Styr1x](https://github.com/Styr1x)                   | [gamous](https://github.com/gamous)             | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/Browsingway/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/Browsingway/total.svg?label=)]() |
| [NextUI Plugin](https://gitlab.com/kaminariss/nextui-plugin) | 悬浮窗插件的大喇嘛替代品                     | [Kaminariss](https://gitlab.com/kaminariss)           | [gamous](https://github.com/gamous)             | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/NextUI-Plugin/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/NextUI-Plugin/total.svg?label=)]() |
| [PriceInsight](https://github.com/Kouzukii/ffxiv-priceinsight) | 在物品弹出帮助上显示市场板价格信息           | [Kouzukii](https://github.com/Kouzukii)               | [gamous](https://github.com/gamous)             | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/PriceInsight/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/PriceInsight/total.svg?label=)]() |
| [Marketbuddy](https://github.com/chalkos/Marketbuddy)        | 简化日常的市场出售操作                       | [chalkos](https://github.com/chalkos)                 | [gamous](https://github.com/gamous)             | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/Marketbuddy/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/Marketbuddy/total.svg?label=)]() |
| [MoneyTracker](https://github.com/yschuurmans/FFXIVMoneyTracker) | 记录金币的收入和支出情况                     | [yschuurmans](https://github.com/yschuurmans)         | [gamous](https://github.com/gamous)             | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/FFXIVMoneyTracker/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/FFXIVMoneyTracker/total.svg?label=)]() |
| [LiteralMapLink](https://github.com/Asvel/ffxiv-literal-map-link) | 将地图坐标文本自动转换为地图链接             | [Asvel](https://github.com/Asvel)                     | -                                               | √    | -                                                            |
| [SunderingWorld](https://github.com/LittleNightmare/SunderingWorld) | 处理国区服务器问题                           | [LittleNightmare](https://github.com/LittleNightmare) | -                                               | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/LittleNightmare/SunderingWorld/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/LittleNightmare/SunderingWorld/total.svg?label=)]() |
| [GatherBuddy](https://github.com/Ottermandias/GatherBuddy)   | 采集助手（已移除，请前往主库订阅）           | [Ottermandias](https://github.com/Ottermandias)       | [gamous](https://github.com/gamous)             | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/GatherBuddy/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/GatherBuddy/total.svg?label=)]() |

### 稳定仓库 

| 插件名称                                              | 介绍                             | 插件作者                                  | 本地化维护                                | 汉化 | 下载量 |
| ----------------------------------------------------- | -------------------------------- | ----------------------------------------- | ----------------------------------------- | ---- | ------ |
| [Radar](https://github.com/emptyset0/Radar_akira0245) | 显示游戏物体在屏幕和地图上的位置 | [akira0245](https://github.com/akira0245) | [emptyset0](https://github.com/emptyset0) | √    | -      |

### 莫迪翁仓库

部分插件恕不提供，珍惜账号，远离莫迪翁

| 插件名称                                                     | 介绍                                                         | 插件作者                                        | 本地化维护                            | 汉化 | 下载量                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- | ------------------------------------- | ---- | ------------------------------------------------------------ |
| [AutoHook](https://github.com/InitialDet/AutoHook)           | 自动钓鱼/刺鱼                                                | [InitialDet](https://github.com/InitialDet)     | [gamous](https://github.com/gamous)   | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/AutoHook/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/AutoHook/total.svg?label=)]() |
| [SkipCutscene](https://github.com/a08381/Dalamud.SkipCutscene) | 辍学：跳过主随剧情动画                                       | [a08381](https://github.com/a08381)             | [gamous](https://github.com/gamous)   | -    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/Dalamud.SkipCutscene/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/Dalamud.SkipCutscene/total.svg?label=)]() |
| [SmartVote](https://github.com/gamous/SmartVote)             | 快速点赞（配合主库SimpleTweak食用更佳）                      | [Bluefissure](https://github.com/Bluefissure)   | [gamous](https://github.com/gamous)   | ×    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/SmartVote/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/SmartVote/total.svg?label=)]() |
| [SplatoonX](https://github.com/NightmareXIV/Splatoon)        | 功能丰富的场景绘图（国服绕过限制特供）                       | [Limiana](https://github.com/Limiana)           | [gamous](https://github.com/gamous)   | -    | [![Github Latest Releases](https://img.shields.io/github/downloads/gamous/SplatoonX/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/gamous/SplatoonX/total.svg?label=)]() |
| [XIVAutoAttack](https://github.com/ArchiDog1998/XIVAutoAttack) | 自动攻击（已移除，请前往作者仓库订阅）                       | [ArchiDog1998](https://github.com/ArchiDog1998) | -                                     | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/ArchiDog1998/XIVAutoAttack/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/ArchiDog1998/XIVAutoAttack/total.svg?label=)]() |
| [Lifu](https://github.com/tssailzz8/Lifu)                    | 自动理符（已移除，请前往源码仓库获取）                       | [tssailzz8](https://github.com/tssailzz8)       | -                                     | √    | [![Github Latest Releases](https://img.shields.io/github/downloads/tssailzz8/Lifu/latest/total.svg?label=)]() [![Github All Releases](https://img.shields.io/github/downloads/tssailzz8/Lifu/total.svg?label=)]() |
| [BossMod](https://github.com/awgil/ffxiv_bossmod)            | 战斗模块（暂不提供，请自行[获取源码](https://github.com/Yarukon/ffxiv_bossmod)编译） | [awgil](https://github.com/awgil)               | [Yarukon](https://github.com/Yarukon) | √    | -                                                            |
| AutoMiniGame                                                 | 金碟全能（暂不提供）                                         | [gamous](https://github.com/gamous)             | -                                     | √    | -                                                            |

![kaigua](https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/assets/kaigua.png)



## 开发 Contribution

### 提交到测试仓

- 添加插件源码仓到目录 `src` 下的子模块（仅全新添加时）
- 先提交源码子仓模块内的更新
- 编译插件并发布到插件源码仓内的Release内
- 确认源码子仓模块均与远程完成同步（commit id一致）
- 更新 `PluginMaster.json ` 与 `README.md`
- 提交更新

### 提交到稳定仓

- 添加打包好的插件到 `dist` 下的子目录
- 更新 `PluginMaster.json ` 与 `README.md`

### 常见本地化问题 Faq

| 问题                                  | 解决方案                                                     | 兼容化方案                                                   |
| ------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| API 版本或 .Net 版本不匹配            | 修改Net版本并链接国服Dalamud文件 重新编译即可                | 无                                                           |
| Opcode不匹配                          | 从[FFXIVOpcode](https://github.com/karashiiro/FFXIVOpcodes)查找并替换相应的Opcode | 联网从Opcode文件中获取对应Opcode                             |
| Signature未找到                       | 使用CE/IDA等逆向工具重新寻找国服客户端的函数签名             | 找更通用的Sig :xD                                            |
| 文本需要汉化                          | 使用[XIV文本检索工具](https://strings.wakingsands.com/)查找或在解包数据中查找对应文本，添加或替换 | 添加Crowdin支持                                              |
| DataCenter为空（国服World表存在错误） | 添加[Utils4CN](https://github.com/AsterOcclu/FFXIV_RpToolboxCN/tree/master/RoleplayersToolbox/Utils4CN)库，初始化时修改World表，或自行维护插件World表 | 忽略，绑定使用[SunderingWorld](https://github.com/LittleNightmare/SunderingWorld)插件 |
| 未提供源码                            | 使用[ILSPY](https://github.com/icsharpcode/ILSpy)逆向生成C#源码导出并手动完善修复 | 找插件开发者py源码                                           |
| ...                                   |                                                              |                                                              |

## 耻辱墙 Wall of Shame

出于保护个人隐私，暂做模糊处理，若持续侵权将逐步解密，若有疑惑，欢迎Email或Issue申诉

### XPJ

- 陆行鸟 宇宙和音 芒椰███冻冻
- QQ 745370896
- Phone 157████0334

- 中山大学

- **编译倒卖本仓库一系列插件 在咸鱼使用多个账号上架**

### Hibiki

- 陆行鸟 ?? ??
- QQ 2327635737
- Phone 19953999798
- 山东省 临沂市 兰山区 金雀山街道沂蒙路███号█████
- **二次倒卖XPJ编译倒卖的本仓库一系列插件 在咸鱼上架**
