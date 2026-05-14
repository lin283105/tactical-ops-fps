# Tactical Ops - 第一人称射击游戏

一个基于 HTML5 Canvas 和 Raycasting 技术的第一人称射击游戏，灵感来源于经典游戏 Wolfenstein 3D。

## 玩法

- **WASD** 移动
- **鼠标** 瞄准视角
- **鼠标左键 / 空格** 射击
- **R** 换弹
- 消灭关卡中所有敌人即可过关

## 技术特性

- 纯 JavaScript 实现的 DDA 光线投射引擎
- 程序化生成的墙壁纹理
- 精灵渲染（敌人 + 道具）
- 敌人 AI（视线检测、追踪、攻击）
- 小地图
- Web Audio API 音效
- 支持桌面端和移动端（触屏操控）

## 运行

直接在浏览器中打开 `index.html` 即可。

```
# 或者使用任意 HTTP 服务器
npx serve .
```
