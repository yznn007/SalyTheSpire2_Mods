# SlayTheSpire2_Mods

这是我自用的《杀戮尖塔2》模组集合，下面是当前目录中常用模组的简介（基于各模组在 Nexus 发布信息与本地 manifest 汇总）。

## Mods 简介（按类型）

### 功能

- **Better Mod Menu**：增强模组管理菜单，支持配置分组和配置档管理。
- **BetterSpire2**：综合 QoL 模组，包含受击总量显示、多段攻击标签、快捷重开、跳过开场等功能。
- **BetterSovereignBlade**：可移动 SovereignBlade 的显示位置，便于按个人习惯调整界面布局。
- **Skada: Damage Meter**：战斗统计面板，覆盖伤害、格挡、助攻、卡牌效率等多维数据，便于复盘。
- **Rewind**：公平撤回类模组，支持回合倒带、房间检查点回退、公平模式与种子查看。
- **RouteSuggest**：地图路线建议工具，默认区分稳健路线与激进路线，并支持自定义。
- **SpeedX**：游戏加速模组，最高 20 倍速，支持自动结束回合、自动拾取、自动前进等。
- **Unified Save Path**：统一原版与模组版存档路径，使原版与模组版共享进度。

### 联机

- **QuickLink**：联机快速回退工具，房主可回到历史节点，队友可自动回房并自动准备。
- **RemoveMultiplayerPlayerLimit**：将联机人数上限从 4 人提升到 16 人。
- **Show Player Hand Cards**：联机时实时显示队友手牌，悬停可查看完整卡牌详情。

### 美化

- **RegentCardsAnimeRework**：将 Regent 角色卡图重绘为更偏可爱、彩色的动漫风格。
- **Mesugaki_Regent**：Regent 主题美化模组（非玩法向），提供更个性化的角色视觉风格。

### 框架

- **BaseLib**：通用模组开发基础库，为其他模组提供常见工具能力。
- **ModConfig**：通用模组配置框架，在设置页新增 Mods 标签，支持开关、滑条、下拉、按键绑定等控件。
- **RitsuLib**：共享框架库，为其他模组提供补丁、持久化、生命周期与本地化等 API。

## 备注

- `STS2-ShowPlayerHandCards` 依赖 `STS2-RitsuLib`。
- 目录里的 `slaysp2manager-batch-*` 为批处理安装过程中产生的临时目录，可按需保留或清理

## 使用方法

- 直接将仓库打包成压缩包 [打包链接](https://codeload.github.com/yznn007/SalyTheSpire2_Mods/zip/refs/heads/main) ，在游戏根目录(一般为Steam\steamapps\common\Slay the Spire 2)新建mods文件夹，将解压后的文件放入。
