# 学习资源与办公 Skill 推荐

核实日期：2026-10-07。视频仅核实公开页面标题和简介，未逐一观看全片；推荐理由是围绕本课程目标的编辑判断。GitHub 链接核实到仓库或技能定义，不代表在 WorkBuddy 实测通过。不要把这些信息变成“最好”“必装”或长期兼容承诺。

## 选择推荐方向

如果用户要找“用一个 Skill 开始学习”的 GitHub 项目，读取 [学习类项目调研](learning-projects.md)。其中列出 Learn Anything、Bloom 等六个项目及本教练已融合的机制；想直接体验时转到 [交互式学习](interactive.md)。

## B 站学习入口

### 秋芝2046：先理解 Skill，再做一个小练习

- [手把手彻底学会 Agent Skills！【小白教程】](https://www.bilibili.com/list/385670211?bvid=BV1G3FNznEiS&oid=116000439664997)
- 页面简介涉及 Skill 原理和制作，适合已经完成过一次 AI 任务、开始想复用方法的人。
- 看完在 WorkBuddy 做：“把刚才跑通的周报流程整理成一个 Skill 草稿，说明每次要给什么材料、按什么步骤做、最后检查什么。”先检查草稿，再决定安装。
- 视频涉及其他产品时，只迁移做事方法；WorkBuddy 的操作入口按官方说明核实。

### 技术爬爬虾：按需补 GitHub 使用基础

- [爬爬虾：小白玩转 Github/Git，全功能精讲](https://www.bilibili.com/cheese/play/ep1104862)
- 这是付费课程页面，含试看；不是入门必修，也不要求购买。适合明确想学 GitHub 网页与项目操作的用户，第一阶段无需学习整套 Git 命令。
- 当下练习：在一个技能仓库中找到 SKILL.md、辅助文件和许可，能指出“技能文件夹”和“整个仓库”的区别。本教练也可直接带着做，无需先上课。

## 首批 GitHub Skill：先选任务，再选一个

以下五项均来自 [Anthropic 官方技能仓库](https://github.com/anthropics/skills)，其实现面向 Claude。它们是 WorkBuddy 的候选适配来源，不是已验证的 WorkBuddy 原生插件。仅链接原项目，本包没有复制或捆绑第三方技能。文档类技能的使用许可与其他示例不同，分发前查看各自 LICENSE。

| Skill | 适合解决什么 | 在 WorkBuddy 中可以怎样提出任务 | 开始前要核对 | 小样验收 |
| --- | --- | --- | --- | --- |
| [internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms) | 周报、内部进度沟通 | “根据这三条记录，写给主管的简短进度说明，保留待确认项。” | 阅读配套 examples，替换不适用的组织格式；未实测 | 事实、受众、行动请求准确 |
| [doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | 一起写方案、说明材料 | “先和我确定这份方案给谁看、要促成什么决定，再按段落一起写。” | 核对宿主专用工具要求，不可假设拥有相同工具；未实测 | 读者看得懂目标、依据和下一步 |
| [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) | 表格整理、计算与输出 | “汇总这份虚构费用表，缺失金额单列，保留可复算公式。” | 需要相应 Python 库等运行依赖，公式重算还有工具条件；未实测 | 抽查原始行、汇总口径和公式结果 |
| [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) | PDF 提取、合并或转换 | “提取这两页中的事项，并给出对应页码；看不清的标记出来。” | 文本 PDF 与扫描件路径不同，OCR 等工具需实际可用；未实测 | 对照原页抽查，不能只看排版 |
| [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) | 制作或修改汇报文件 | “先把这些记录变成三页汇报大纲，确认后再生成可编辑文件。” | 核对脚本、运行环境、渲染与字体条件；未实测 | 文件可打开、内容准确、没有溢出 |

只需要改一段文字时，先用 WorkBuddy 现有能力。有反复做相同任务的需要时，优先考虑前两项；有明确文件处理缺口时，再考虑后三项。WorkBuddy 已提供等效技能且小样通过，就不重复安装。

## 从 GitHub 到实际使用

1. 打开目标技能目录，阅读 SKILL.md，并查看它引用的脚本、资料、依赖和许可。让 WorkBuddy 先解释其用途与前提，不直接执行来源不明的命令。
2. 下载后保留目标技能文件夹及其必要配套文件，不能只复制 SKILL.md 而丢掉引用文件，也不要把整个大型仓库当作单个技能导入。
3. 对照 [WorkBuddy 官方技能说明](https://www.workbuddy.cn/docs/workbuddy/From-Beginner-to-Expert-Guide/Function-Description/Skills-Market)，使用本地技能包上传入口；打包格式以当前客户端要求为准。不要照抄 Claude 的插件市场命令。
4. 在已安装列表确认启用，用虚构材料明确请求使用该技能；检查是否读到了它的说明和依赖，不能仅凭 AI 口头说“用了”判定调用成功。
5. 小样失败时记录具体报错，区分导入、调用、依赖和产出问题；可以改用现有能力完成任务。没有经过实际运行，兼容性状态保持“未实测”。

资源更新原则：保留稳定原始链接，失效时查官方替代。基于当前岗位和卡点推荐，避免以星数、播放量或“万能”标题代替适配判断。
