# 🎮 坦克大战 (Tank Battle)

经典坦克大战网页版 — 基于 HTML5 Canvas 的复古坦克对战游戏。

## 🎯 游戏玩法

- 控制你的坦克，保护下方的基地
- 消灭所有敌方坦克即可过关
- 砖墙可以被子弹摧毁，钢铁墙无法摧毁
- 你的基地被击中则游戏结束

## 🕹️ 操作方式

| 按键 | 功能 |
|------|------|
| `WASD` / `↑↓←→` | 移动坦克 |
| `空格` / `J` | 开火 |
| `P` | 暂停/继续 |
| `R` | 重新开始 |

## ✨ 特性

- 经典俯视角坦克对战
- 多关卡，难度递增
- 可破坏的砖墙 & 不可破坏的钢铁墙
- 敌方坦克 AI（追踪 + 随机移动）
- 爆炸粒子特效
- 简单音效反馈
- 基地保护机制
- 生命系统 & 无敌时间

## 🚀 运行方式

直接用浏览器打开 `index.html` 即可游玩，无需安装任何依赖。

或者使用任意本地服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js (需要安装 http-server)
npx http-server
```

然后访问 `http://localhost:8000`。

## 📁 项目结构

```
tank-battle/
├── index.html    # 游戏主文件（包含全部逻辑）
└── README.md     # 项目说明
```

## 🛠️ 技术栈

- HTML5 Canvas
- 原生 JavaScript (ES6+)
- Web Audio API (音效)

---

🤖 Created with [Claude Code](https://claude.com/claude-code)
