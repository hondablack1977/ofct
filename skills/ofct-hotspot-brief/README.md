# OFCT Hotspot Brief Skill

这个 skill 用于把实时热点转化为 OFCT 解读图文：

- 抓取或接收热点事件
- 用 OFCT 的生命接口、关系场、文明接口、时代页码、体验之书、命运节点等视角解读
- 输出适合小红书/短内容平台的中文文案
- 输出 9:16 竖版图片提示词
- 固定使用 OFCT 角色：最近又胖了、四千、草莓

## 目录结构

```text
skills/ofct-hotspot-brief/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── ofct-hotspot-framework.md
```

## 推荐安装方式

在另一台 Codex / Lobster 环境中，如果支持从 GitHub 安装 skill，可使用仓库路径：

```text
hondablack1977/ofct/skills/ofct-hotspot-brief
```

如果当前环境只支持手动安装，把本目录复制到本机 Codex skills 目录下：

```text
%USERPROFILE%\.codex\skills\ofct-hotspot-brief
```

安装后开启新会话，使用类似提示：

```text
用 OFCT 看今天热点，做 3 条图文
```

或：

```text
用 OFCT 分析这个热点，生成小红书文案和 9:16 图片提示词
```

## 固定角色

- 小熊：最近又胖了，永远是主讲人和主角。
- 猫咪：四千、草莓，负责提问、表演、吐槽和情绪连接。
- AI 界面可以作为工具出现，但不是主角。

## 风格要求

整体内容要轻松、清楚、有传播感。不要写成玄学，不要写成论文，也不要写成中年说教。

适合的表达：

```text
冠军不是最亮的个体，而是高压时不散的整体。
```

不适合的表达：

```text
OFCT 为该现象提供了一种结构性讨论路径，仍需科学验证。
```

## 发布位置

GitHub 仓库：

```text
https://github.com/hondablack1977/ofct/tree/main/skills/ofct-hotspot-brief
```
