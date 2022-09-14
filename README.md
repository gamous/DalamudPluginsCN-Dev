# DalamudPluginsCN-Dev

适用于国服的Dalamud第三方插件仓库 `dalamud-api6 net5.0-windows`

本仓库仅存储非主库插件，若有插件移入国服主库后会进行移除

若插件无法使用，请查看 Dalamud Console（使用`/xllog`打开）中报错并提交 issue

## 使用 Usage

### 测试仓库 Testing plugins

优先仓库，插件下载地址位于插件源码仓或其他发布源，优先更新

`https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/PluginMaster.json`

### 稳定仓库 Stable plugins

备用仓库，插件包备份托管于本仓库内，防止发布源变更导致无法访问或无法适配

**部分闭源插件请酌情考虑风险使用**

`https://raw.githubusercontent.com/gamous/DalamudPluginsCN-Dev/main/dist/PluginMaster.json`



## 内容 Contents

### 测试仓库 

| 插件名称                                                     | 介绍                               | 插件作者                                              | 本地化维护                          |
| ------------------------------------------------------------ | ---------------------------------- | ----------------------------------------------------- | ----------------------------------- |
| [PostMeteion](https://github.com/gamous/PostMeteion)         | 梅蒂恩会执行光呆的指令并汇报成果   | [gamous](https://github.com/gamous)                   | x                                   |
| [FishNotify](https://github.com/carvelli/Fish-Notify)        | 钓鱼咬钩时发出声音以及聊天框提醒   | [carvelli](https://github.com/carvelli)               | [gamous](https://github.com/gamous) |
| [PriceInsight](https://github.com/Kouzukii/ffxiv-priceinsight) | 在物品弹出帮助上显示市场板价格信息 | [Kouzukii](https://github.com/Kouzukii)               | [gamous](https://github.com/gamous) |
| [ItemVendorLocation](https://github.com/electr0sheep/ItemVendorLocation) | 查找购买道具的地点                 | [electr0sheep](https://github.com/electr0sheep)       | [gamous](https://github.com/gamous) |
| [SunderingWorld](https://github.com/LittleNightmare/SunderingWorld) | 处理国区服务器问题                 | [LittleNightmare](https://github.com/LittleNightmare) | x                                   |

### 稳定仓库 

| 插件名称                                              | 介绍                             | 插件作者                                  | 本地化维护                                |
| ----------------------------------------------------- | -------------------------------- | ----------------------------------------- | ----------------------------------------- |
| [Radar](https://github.com/emptyset0/Radar_akira0245) | 显示游戏物体在屏幕和地图上的位置 | [akira0245](https://github.com/akira0245) | [emptyset0](https://github.com/emptyset0) |

## 开发 Contribution

### 提交到测试仓

- 添加插件源码仓到目录 `src` 下的子模块（仅全新添加时）
- 先提交源码子仓模块内的更新
- 编译插件并发布到插件源码仓内的Release内
- 确认源码子仓模块均与远程完成同步（commit id一致）
- 更新 `PluginMaster.json ` 与 `README.md`（仅全新添加时）
- 提交更新

### 提交到稳定仓

- 添加打包好的插件到 `dist` 下的子目录
- 更新 `PluginMaster.json ` 与 `README.md`（仅全新添加时）



### 常见本地化问题 Faq

| 问题                                  | 解决方案                                                     | 兼容化方案                                                   |
| ------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| API 版本或 .Net 版本不匹配            | 重新编译即可                                                 | 无                                                           |
| Opcode不匹配                          | 从[FFXIVOpcode](https://github.com/karashiiro/FFXIVOpcodes)查找并替换相应的Opcode | 联网从Opcode文件中获取对应Opcode                             |
| Signature未找到                       | 使用CE/IDA等逆向工具重新寻找国服客户端的函数签名             | 找更通用的Sig :xD                                            |
| 文本需要汉化                          | 使用[XIV文本检索工具](https://strings.wakingsands.com/)查找或在解包数据中查找对应文本，添加或替换 | 添加Crowdin支持                                              |
| DataCenter为空（国服World表存在错误） | 添加[Utils4CN](https://github.com/AsterOcclu/FFXIV_RpToolboxCN/tree/master/RoleplayersToolbox/Utils4CN)库，初始化时修改World表 | 忽略，绑定使用[SunderingWorld](https://github.com/LittleNightmare/SunderingWorld)插件 |
| 未提供源码                            | 使用[ILSPY](https://github.com/icsharpcode/ILSpy)逆向生成C#源码导出并手动完善修复 | 找插件开发者py源码                                           |
| ...                                   |                                                              |                                                              |



### 待完成任务清单 Todo

- 使用解决方案对整个源码仓进行统一编译
- 从插件仓库列表自动化生成 `PluginMaster.json ` 
