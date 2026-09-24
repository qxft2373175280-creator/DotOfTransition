# Dot Of Transition

一款 2D 像素风动作冒险游戏，以「冰火双世界切换」为核心玩法，使用 Unity 开发。

## 游戏内容

- 8 个手工设计关卡 + 主菜单，冰 / 火双主题场景
- 完整战斗系统：普通敌人、精英怪、冰霜 BOSS 多阶段战
- 陷阱、收集、音频、设置等完整游戏流程

## 我的职责：美术 & 地图设计

- **美术**：使用 Aseprite 绘制角色、敌人、弹幕特效、UI 等全部像素美术资源
- **地图设计**：使用 Tilemap 搭建 8 个关卡，规划冰 / 火双世界的场景布局与关卡动线
- **玩法视觉化**：将「冰火双世界切换」机制落地为统一的场景与特效视觉语言

## 致谢

本项目为团队项目，感谢程序与策划同学的协作。

## 技术栈

- Unity 2022.3 LTS + C#
- Aseprite（像素美术）、Tilemap（关卡搭建）

## 运行方式

1. 安装 Unity Hub，并安装 Unity 2022.3 LTS（中国版 2022.3.62f3c1 亦可）
2. 使用 Unity Hub 打开本工程根目录
3. 打开 `Assets/Scenes/game.mainmenu.unity`，点击 Play 运行

## 项目结构

```
Assets/
  Animations/   动画状态机与动画片段
  Audios/       BGM、音效与音频管理
  Prefabs/      预制体（敌人、陷阱、UI 等）
  Scenes/       9 个场景（主菜单 + 8 个关卡）
  Scripts/      C# gameplay 脚本
  Sprites/      像素美术资源（Aseprite 源文件 + 导出图）
  Tiles/        Tilemap 瓦片资源
Packages/       依赖清单
ProjectSettings/ 工程配置
```

## 许可证

美术资源（Sprites、Tiles 下的 Aseprite / PNG 文件）为项目原创，未经允许请勿商用。
代码部分请参考 MIT 许可证（团队项目，如需商用请与作者联系）。
