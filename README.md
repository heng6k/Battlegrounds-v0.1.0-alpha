# Battlegrounds v0.1.0-alpha

这是一个非官方的单人酒馆训练器 alpha 版本，用来测试酒馆决策、卡池版本、随从/法术剔除、战斗模拟和日志反馈。

当前版本还不是完整模拟器，也不是正式发布版。它更适合想构造局面、尝试思路、找 bug 并反馈问题的玩家。

## 下载

推荐从 Release 页面下载：

- Release 页面：[https://github.com/heng6k/Battlegrounds-v0.1.0-alpha/releases/tag/v0.1.0-alpha](https://github.com/heng6k/Battlegrounds-v0.1.0-alpha/releases/tag/v0.1.0-alpha)
- Windows 压缩包：[https://github.com/heng6k/Battlegrounds-v0.1.0-alpha/releases/download/v0.1.0-alpha/BattlegroundsTrainer_v0.1.0-alpha_win.zip](https://github.com/heng6k/Battlegrounds-v0.1.0-alpha/releases/download/v0.1.0-alpha/BattlegroundsTrainer_v0.1.0-alpha_win.zip)

校验值：

```text
SHA256: CAD6CD8C845B301BB939976D6FA28206131E4CD44C55F18017FD19C65F576FDA
```

## 使用方法

1. 下载 `BattlegroundsTrainer_v0.1.0-alpha_win.zip`。
2. 解压到任意文件夹。
3. 运行 `Learn Heartstone.exe`。
4. 第一次试玩建议先阅读压缩包内的 `README_使用说明.md` 和 `KNOWN_ISSUES_已知问题.md`。

## 本版可以测试

- 单人酒馆训练主流程。
- 选择可用种族并进入对局。
- 创建、命名、保存卡池版本。
- 按等级、种族、类型和搜索文本筛选随从/法术。
- 从卡池版本中剔除卡牌，并用该版本进入对局。
- 刷新、购买、出售、冻结、升级、下一回合。
- 运行战斗并查看招募/战斗日志。
- 右下角窗口比例调试工具，可切小窗检查 UI，也可恢复 `1920x1080`。

## Alpha 限制

- 当前只面向单人酒馆训练流程。
- 双打/BGDUO 卡牌不进入当前单人卡池版本。
- 部分英雄、伙伴、复杂法术和战斗细节仍是简化或代理实现。
- 部分图片可能缺失。
- 小窗口 UI、批量撤销、筛选共享等体验仍在改进。

## 反馈格式

```text
版本号：v0.1.0-alpha
你想做什么：
实际发生了什么：
期望结果：
是否能稳定复现：
截图/阵容/日志：
```