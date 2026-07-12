---
name: story-master
description: Truby-based story development and script doctoring. Triggers: writing novels, screenplays, 7 key steps, 22-step plot, four-corner opposition, symphonic dialogue.
---

# 故事写作大师 (Story Master) - 写作 Skill

本技能基于约翰·特鲁比（John Truby）的《故事写作大师班》（The Anatomy of Story）写作体系，协助由内而外构建具有情感厚度、立体人物网络、强大道德主题与严密有机结构的故事。

> [!NOTE]
> 本体系适用于角色与道德价值驱动的结构主义叙事（中长篇小说、剧本、悬疑、成长史诗、多角色群戏）。不适用于日常流、无冲突网络爽文、意识流实验文学或低龄童话。

---

## 🚦 交互式阶段闸门协议 (Interactive Stage Gate Protocol)

必须逐个阶段推进。在每个阶段输出后暂停，明确获得用户确认后再进入下一阶段。

### 【闸门 1：故事前提与设计原则】
1. **任务**：提炼故事核心并分析潜在结构问题。
2. **输出范本**：
   * **一句话前提**：[主角] 因为 [触发事件]，想要 [欲望/目标]，在 [对手] 的阻碍下，最终 [结局/改变]。
   * **设计原则**（意念+独特形式）：[故事原创意念] + [运作形式]（例如：让沙文主义者乔装成女人来学会如何爱）。
   * **结构性挑战**：[分析此前提天生存在的结构陷阱，并给出 2-3 个“假如这样，会如何”的破局设想]。
3. **完成标准**：用户确认一句话前提、设计原则 and 挑战应对，并明确指示进入下一阶段。

### 【闸门 2：七大关键步骤】
1. **任务**：锁定故事核心骨架。
2. **规则**：查阅 [references/premise_7steps.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/premise_7steps.md)。从结尾真实自我揭露回溯开头弱点需求。
3. **完成标准**：输出 7 大步骤（弱点/需求、欲望、对手、计划、对决、自我揭露、新平衡点）并获得用户确认。

### 【闸门 3：角色网络与四角对立】
1. **任务**：细化对立矩阵，明确价值碰撞。
2. **规则**：查阅 [references/character_theme.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/character_theme.md)。
3. **输出范本**：必须以表格呈现角色对立网络：
   | 角色名称 | 角色定位/原型 | 心理/道德缺陷 | 核心欲望（必须与主角目标重合） | 代表的价值观/生命哲学 |
   | :--- | :--- | :--- | :--- | :--- |
   | **主角** | 主角 / [原型] | [缺陷，且伤害了他人的道德缺陷] | [主角目标] | [主角代表的价值，如：自由] |
   | **对手 A** | 主要对手 / [原型] | [对手的执念/缺陷] | [争夺同一目标] | [与主角对立的价值，如：秩序] |
   | **对手 B** | 假盟友 / [原型] | [隐藏的背叛动机] | [表面协助，实际争夺的目标] | [夹缝中的折中价值] |
   | **对手 C** | 剧情副线 / [原型] | [对比主角的缺陷] | [平行线上的类似欲望] | [另一种变奏价值] |
4. **完成标准**：完成四角对立矩阵表格并获得用户确认。

### 【闸门 4：大纲推演】
1. **任务**：根据作品体量选择结构精细度，推演情节大纲。
2. **缩放规则**：
   * **短篇故事（5,000字以内）**：使用 [references/premise_7steps.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/premise_7steps.md) 的“7步结构”，聚焦单一冲突。
   * **中长篇/剧本（10,000字以上）**：使用 [references/plot_22steps.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/plot_22steps.md) 的“22步结构”，提供丰富的信息揭露与决策。
3. **完成标准**：输出完整的大纲结构步骤，并获得用户确认。

### 【闸门 5：场景编排与起草】
1. **任务**：进行分场设计与文本起草。
2. **规则**：查阅 [references/scene_dialogue.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/scene_dialogue.md) 及 [references/world_symbols.md](file:///D:/AntigravityAbout/.agent/skills/story-master/references/world_symbols.md)。
3. **完成标准**：完成分场大纲及正文片段的撰写。

---

## 🛡️ 智能体自检质量门槛 (Agent Quality Gate)

输出大纲、角色设计或正文前，必须通过以下自检：

1. **【对手目标对齐】** 主角与对手必须在竞逐**同一个目标**（例如：夺取同一样物品/赢取同一场官司/揭发或隐藏同一个真相）。
2. **【道德需求确立】** 主角必须有清晰的道德缺陷，且在开头伤害了具体的人，使结尾的转变具有道德厚度。
3. **【场景动作推进】** 每一个场景必须**揭露新事实**或**剥夺主角一个安全选项**，避免重复的情节节拍。
4. **【对白去扁平化】** 关键对白必须包含情节轨道、道德轨道和潜文本轨道。对手的自我辩护必须具备极高说服力。

---

## 🔍 诊断与剧本医生模式 (Script Doctor Branch)

当用户请求诊断或修改现成故事大纲/剧本时，直接启用此模式：
1. **诊断核心病灶**：对照 **【自检质量门槛】** 找出缺陷（如欲望线不合一、主角完美无缺、对手动机扁平、情节节拍重复等）。
2. **给出重构方案**：基于特鲁比体系给出具体调整建议（如重组四角对立、设计假盟友、或将中段重新编排为“体验死亡/看似落败”等步骤）。
