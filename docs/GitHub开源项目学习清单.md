# GitHub 开源项目学习清单

这个文件用来记录我在 GitHub 上看到的优秀项目，以及我的学习状态。

## 项目清单

| 项目名称 | 地址 | 类型 | 我为什么关注它 | 当前动作 | 学习状态 |
|---|---|---|---|---|---|
| baoyu-skills | JimLiu/baoyu-skills | AI Agent Skill 库 | 学习别人如何设计 AI Skill 和工作流 | 已 Star / 已 Fork / 已 Clone | 初步学习中 |

## baoyu-skills 学习目标

### 我已经理解的

1. 这是一个 AI Skill 技能仓库
2. `skills/` 是核心技能货架
3. 每个 `baoyu-xxx` 文件夹是一个具体 Skill
4. `SKILL.md` 是技能说明书
5. Fork 是复制到自己账号
6. Clone 是下载到本地

### 我下一步要学习的

1. 拆解 `skills/` 文件夹里有哪些 Skill
2. 选择一个 Skill 深入看，比如 `baoyu-xhs-images`
3. 学习一个 Skill 的结构
4. 尝试设计我自己的 Skill


## baoyu-skills 的 skills 文件夹拆解

### 我的理解

`skills/` 文件夹是这个项目的核心区域，里面每一个 `baoyu-xxx` 文件夹都代表一个具体的 AI Skill。

这些 Skill 本质上不是普通文档，而是给 AI Agent 使用的任务说明书。

### 我观察到的 Skill 类型

1. 内容生成类
2. 图片生成类
3. 图片处理类
4. 发布平台类
5. 翻译类
6. 视频/字幕处理类
7. 文档转换类

### 我现在的理解

这个项目不是一个单一工具，而是把很多 AI 工作场景拆成一个个 Skill。

每个 Skill 解决一个具体任务，比如：

- 生成小红书图文
- 生成 PPT
- 生成信息图
- 发布到公众号
- 翻译内容
- 提取 YouTube 字幕