# 坦克大战 · Tank Battle

一个用原生 HTML5 Canvas 实现的经典「坦克大战」(Battle City) 小游戏，单文件即可运行，无需任何依赖。

## 在线试玩

克隆仓库后直接用浏览器打开 `index.html` 即可，或部署到 GitHub Pages 后访问。

## 玩法

- **目标**：消灭全部敌人坦克，同时守住基地（屏幕下方的老鹰），一旦基地被毁则游戏结束。
- **移动**：`WASD` 或方向键
- **射击**：`空格` 或 `J`
- **暂停**：`P`
- **静音**：`M`
- **开始 / 重开**：`回车`

## 特性

- 3 个关卡，越往后敌人越强
- 4 种敌人：基础、快速、火力、重装（3 点生命）
- 4 种道具：护盾、加命、全屏炸弹、冰冻
- 可破坏的砖墙、不可破坏的钢铁、水域、草丛等地形
- 像素风画面、音效、屏幕震动、最高分本地记录
- 支持触屏设备的虚拟方向键

## 文件结构

```
tank-battle/
├── index.html   # 游戏本体（单文件）
└── README.md
```

## 技术说明

纯前端实现，使用 Canvas 2D 绘制与 `requestAnimationFrame` 游戏循环，音效基于 Web Audio API，无需安装任何依赖。

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
