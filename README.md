# self-discipline-skill

> 自律成长教练 — 基于《认知觉醒》和《掌控习惯》的科学习惯培养 Skill

[![SKILL.md](https://img.shields.io/badge/standard-SKILL.md-teal)](https://skillsmp.com/zh)
[![Compatible](https://img.shields.io/badge/compatible-Claude%20Code%20%7C%20AirJelly-purple)](https://github.com/jaydenou/self-discipline-skill)

---

## 简介

这是一个基于两本改变无数人的自律书籍而构建的 AI Agent Skill：

- 📘 **《认知觉醒》**（周岭）— 三重大脑模型、元认知、舒适区边缘、清晰力
- 📗 **《掌控习惯》**（James Clear）— 习惯回路、4大定律、身份认同、两分钟法则

当你向 AI 提问习惯养成、自律计划、拖延分析、每日复盘等话题时，这个 skill 会自动触发，给出有理论依据、可立即执行的建议。

---

## 核心能力

| 功能 | 说明 |
|------|------|
| 🧠 习惯诊断 | 用三重大脑模型分析你为什么坚持不下去 |
| 📐 系统设计 | 实施意图公式 + 习惯叠加 + 环境设计 |
| 📊 打卡追踪 | 每日打卡模板 + 周复盘框架 |
| 🔍 拖延分析 | 定位是本能脑/情绪脑/模糊目标导致的拖延 |
| 💬 金句引导 | 两本书精华金句，强化身份认同和行动动力 |

---

## 快速安装

### Claude Code

```bash
# 克隆到 Claude skills 目录
git clone https://github.com/jaydenou/self-discipline-skill.git ~/.claude/skills/self-discipline-skill
```

### AirJelly

直接在 AirJelly 控制台安装 `.skill` 文件即可。

---

## 使用示例

```
帮我制定一个早起习惯计划，目标是每天 6:30 起床
```
```
我总是拖延，帮我用三重大脑模型分析一下原因
```
```
帮我设计一个包含运动、阅读和写作的每日习惯系统
```
```
今天完成了跑步和阅读，但没写作，帮我做今日复盘
```

---

## 理论基础

### 《认知觉醒》核心框架

```
本能脑（求生存）
    ↓ 设计环境绕过它
情绪脑（求奖励）
    ↓ 即时奖励满足它
理智脑（懂道理）
    ↓ 元认知驾驭全局
```

**人生五件套**：早起 · 冥想 · 阅读 · 写作 · 跑步

### 《掌控习惯》4大定律

```
① 让它显而易见  →  提示清晰，习惯叠加
② 让它有吸引力  →  捆绑诱惑，加入群体
③ 让它简便易行  →  两分钟法则，减少阻力
④ 让它令人愉悦  →  即时奖励，不中断 streak
```

---

## 文件结构

```
self-discipline-skill/
└── self-discipline/
    └── SKILL.md    ← 完整 skill 指令文件
```

---

## License

MIT © [jaydenou](https://github.com/jaydenou)
