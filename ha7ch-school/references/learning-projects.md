# GitHub 学习类项目：来源与融合取舍

调研日期：2026-10-07。已查看以下项目的官方仓库说明或技能定义；没有安装、运行或验证 WorkBuddy 兼容性。以下“适合”是教学设计判断，不是效果测评。借鉴交互机制并自行编写职场练习，没有捆绑第三方源码，也不把项目宣传的学习收益当作事实。

| 项目与原始来源 | 查到的机制 | 本 Skill 中的具体落点 |
| --- | --- | --- |
| [Nar101/learn-anything：SKILL.md](https://github.com/Nar101/learn-anything/blob/main/SKILL.md) | 从学习目标和资料组织课程；区分内容进度与掌握证据 | 材料变短课、先确定题目标准、区分独立与提示下完成 |
| [d-wwei/learn-anything：SKILL.md](https://github.com/d-wwei/learn-anything/blob/main/SKILL.md) | 支持主题、URL、文件输入，简化讲解、错题诊断与复习 | “这份材料带我学”“简单一点”“继续上次”等自然语言入口 |
| [Li-Evan/Bloom](https://github.com/Li-Evan/Bloom) | 根据批注和反馈调整课程；包含类比、原型和反向讲解技能 | 随时指出不懂的句子、用熟悉工作举例、先做小成品、让用户当老师 |
| [deniz-miro/claude-learn-skill](https://github.com/deniz-miro/claude-learn-skill) | 从当前工作切入，逐级提示，记录进展与反向教学 | 从实际交付物教学；按需要给提示或示范，而非固定逼问 |
| [rodbv/socratic-skills](https://github.com/rodbv/socratic-skills) | quiz-me 与 guide-me 围绕实际产物逐步提问和引导 | 对自己的周报或方案做判断题，一次一问，回答后反馈 |
| [SebastianElvis/hammer](https://github.com/SebastianElvis/hammer) | 保存学习状态，安排跨会话复习 | 学习记录与安装包分离；重新进入时用新题复习 |

优先参考前三项了解“一个 Skill 开始学习”的整体体验；后三项主要提供细分交互思路。用户使用本教练即可体验已融合的方法，无需同时安装六个项目。

## Grill me：追问澄清与检验思路

本版参考 [mattpocock/skills 的 grill-me 入口](https://github.com/mattpocock/skills/blob/main/skills/productivity/grill-me/SKILL.md)及其指向的 [grilling 定义](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md)作为可核实参考。

当前入口委派给 grilling；后者围绕方案和决策按依赖关系分轮提问，每轮可有多个问题并给建议。我们借鉴澄清和检验思路，将职场小白版改为一次一个主要问题、先短体验再总结。对应 interactive.md 第 1 节。未安装第三方技能，未验证其 WorkBuddy 兼容性。

## 如何向学员介绍这些资源

用户好奇“还有哪些学习 Skill”时，只推荐与他当前缺口最贴近的一项，说明来源和 WorkBuddy 未实测状态，随后直接演示本教练中的对应方法。不要把仓库列表替代教学，也不要默认让新手运行 GitHub 安装命令。
