# BH3-MEOW

《崩坏3》安卓资源包（PI v2），供 [MaaFwApp](https://github.com/Aliothmoon/MaaFwApp) / MAA-Meow 系宿主在 Android 上原生运行。

资源树来自 [MaaXYZ/MAABH3](https://github.com/MaaXYZ/MAABH3)（AGPL-3.0），本仓库为其 Android Pocket 发行版：
interface.json 由 CLI 硬编码任务列表手工转成 PI v2，启动包名改为对象式 StartApp（官服默认，B服/Vivo服走任务选项）。

战斗自定义动作（走位/普攻/闪避/QTE 等 18 个）与 Combating 识别器以 AgentServer 形式内置于 APK（`libmaabh3agent.so`，MaaFramework v5.13 API），不随资源分发。

## 用法

装对应 APK 后直接使用；应用内「检查更新」以本仓库 Release 为源。

- 万象虚境需先手动选好上场女武神
- 材料减负需先三星通关对应关卡

## License

AGPL-3.0（继承上游 MAABH3）
