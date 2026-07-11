# story-master

<div align="center">

[English](./README.md) · [简体中文](./README.zh-CN.md)

**基于约翰·特鲁比的《故事写作大师班》，用于构建角色驱动的结构、有机情节与主题框架。**

<img src="assets/banner.webp" alt="story-master —— 基于特鲁比体系的故事写作技能" width="100%">

![version](https://img.shields.io/badge/version-0.1.0-blue)
![license](https://img.shields.io/badge/license-MIT-green)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/pappydaddy)

</div>

---

`story-master` 是一个智能体技能与写作工作区，面向小说家、编剧和叙事设计师。它把约翰·特鲁比在《故事写作大师班》中提出的故事系统整理成了一套可交互的步骤。

它不堆砌套路化的情节，而是引导你从角色的内心弱点出发，把人物关系、道德两难、象征空间和分场结构串成一条有机的因果链。

> 情节不是简单堆砌事件，它是主角心理和道德转变的足迹。

---

## 特鲁比叙事法：有机的叙事架构

大多数写作模板产出的是套路化、情节驱动的故事。本技能聚焦于构建有机叙事，核心在于：

- **角色与道德需求对齐**：主角在开篇必须有伤害他人的道德弱点。这使他们之后的心理与道德蜕变显得更真实、合理。
- **四角对立**：在冲突网中设计至少三个对手。他们与主角争夺同一个目标，但各自代表不同的生存哲学，避免简单的非黑即白。
- **双重逆转**：在高潮对决中，让主角与核心对手同时获得对自我真实的发现，从而传递更深刻的道德主题。
- **交响乐式对白**：在对白中同时编织情节进展、道德议题与潜文本，避免平铺直叙。

---

## 你会得到什么

<img src="assets/features.webp" alt="story-master 核心能力与参考指南" width="100%">

智能体会引导你完成以下步骤：
- 梳理故事前提，确定故事的设计原则并诊断结构挑战。
- 规划人物网络，并建立四角对立矩阵。
- 推演情节大纲（短篇用极简 7 步，长篇或剧本用 22 步）。
- 编排场景网络，起草具有潜文本的戏剧对白。

---

## 工作原理：交互式阶段闸门协议

为了防止智能体在创作时出现“大纲塌陷”，或者一次性推演全部内容导致情节粗糙，`story-master` 采用阶段闸门协议。智能体在每个阶段完成后必须暂停，在获得你的确认后才会进入下一步：

<img src="assets/workflow.webp" alt="story-master 阶段闸门工作流" width="100%">

```text
故事前提与设计原则 -> 故事结构七大关键步骤 -> 角色网络与四角对立 -> 阶梯大纲推演 -> 场景编排与正文起草
```

1. **闸门 1：故事前提与设计原则**（提炼一句话故事前提，明确运作形式并诊断挑战）
2. **闸门 2：故事结构七大关键步骤**（锁定核心骨架，从开头弱点一直到结尾的真实自我揭露）
3. **闸门 3：角色网络与四角对立**（设计对手网，理清同一个目标下的价值冲突）
4. **闸门 4：阶梯大纲推演**（依据你的字数体量选择大纲节点：5,000字以内短篇使用 7 步，万字以上长篇或剧本使用 22 步）
5. **闸门 5：场景编排与正文起草**（设计场景编排，起草包含潜文本的对白）

---

## 快速开始

### 1. 安装与配置

**方式 A：通过命令行安装（最简便）**
运行自动化安装指令：
```bash
npx skills add idonafraid-create/story-master -y -g
```

**方式 B：手动克隆安装**
直接克隆仓库至您 Agent 的 skills 目录下：
```powershell
# Windows PowerShell
git clone https://github.com/idonafraid-create/story-master.git D:\path\to\.agent\skills\story-master
```
```bash
# macOS / Linux
git clone https://github.com/idonafraid-create/story-master.git ~/.agent/skills/story-master
```

**方式 C：开发者模式（目录联接/符号链接）**
如果您在本地参与本技能开发，请克隆至工作区，然后通过联接将其链入 Agent 技能目录：
```powershell
# Windows PowerShell (目录联接)
New-Item -ItemType Junction `
  -Path D:\path\to\.agent\skills\story-master `
  -Target D:\path\to\story-master
```
```bash
# macOS / Linux (符号链接)
ln -s ~/path/to/story-master ~/.agent/skills/story-master
```

### 2. 使用示例

直接向 AI 智能体提出写作或诊断需求，例如：

```text
使用 story-master 帮我设计一个关于义体社会不平等的科幻小说前提与设计原则。

我想用 story-master 的 22 步故事结构来推演我的剧本第二幕大纲。

帮我用 story-master 梳理目前主角的角色网络，并规划一个四角对立矩阵。
```

---

## 文档入口

| 文档 | 作用与定位 |
|---|---|
| [SKILL.md](./SKILL.md) | 主控 Agent 引导逻辑、体量缩放规则与自检门槛。 |
| [premise_7steps.md](./references/premise_7steps.md) | 故事前提发展步骤与七个结构步骤。 |
| [character_theme.md](./references/character_theme.md) | 角色原型库、四角对立与双重逆转设计。 |
| [world_symbols.md](./references/world_symbols.md) | 象征网络类型与故事空间、时间设计。 |
| [plot_22steps.md](./references/plot_22steps.md) | 22 个情节步骤的定义与思考清单。 |
| [scene_dialogue.md](./references/scene_dialogue.md) | 场景编排分类与三轨交响乐式对白写法。 |

---

## 许可证

[MIT](./LICENSE)
