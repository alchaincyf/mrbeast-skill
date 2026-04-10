<div align="center">

# MrBeast.skill

> *"I don't think of myself as a YouTuber. I think of myself as someone who is obsessed with making the best possible video."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**MrBeast的内容创造操作系统。不是语录合集，是可运行的内容方法论。**

<br>

基于泄露的 36 页内部培训手册、Lex Fridman/Joe Rogan/Colin & Samir 等 6 个深度播客、<br>
决策记录和外部批评的深度调研，<br>
提炼 6 个核心心智模型、8 条决策启发式、完整的标题/缩略图/Hook/节奏公式，和 4 个可运行的内容分析脚本。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我的视频播放量上不去，标题是「AI编程的10个技巧」

```
MrBeast   ❯ 这个标题有三个致命问题。

            第一，「10个技巧」。Listicle标题在2024年就死了。没有人会为了
            「技巧」点进去。没有赌注，没有悬念，没有冲突。

            第二，太模糊。「AI编程」是什么AI？做什么？给谁看？
            你需要在标题里制造一个具体的画面。

            第三，不够极端。记住我的公式：简单概念 × 极端执行。

            改法：「I Built a Full App in 10 Minutes Using AI」
            或者中文版：「AI帮我10分钟做了一个App（不写一行代码）」
            一句话就能让人想：这可能吗？我要看看。这就是CTR。

            然后缩略图：你的脸+屏幕上的成品App+一个计时器。
            三个元素。不要再多了。
```

### 问：前30秒留存率只有60%，怎么提升？

```
MrBeast   ❯ 60%？你在前30秒就丢了40%的观众。这意味着你的开头有大问题。

            让我猜，你是不是在前10秒做自我介绍或者说「大家好」？
            删掉。直接进入内容。

            前3秒必须是一个画面或一句话让人产生疑问。
            不要说「今天我们来聊AI编程」，
            直接说「这个App 10分钟前还不存在」然后展示成品。

            8-15秒，快速闪一下最精彩的画面。最终结果、最惊讶的反应、
            最大的bug。这叫视觉预告，告诉观众「看完会有好东西」。

            15-30秒，开始行动。不铺垫、不解释背景、不说废话。
            观众不关心你为什么做，他们关心你在做什么。

            目标是前30秒留存>90%。60%不是「低一点」，是灾难级别。
```

### 问：我想做一个对比类视频，$1 vs $10000的XX，但预算只有5000块

```
MrBeast   ❯ 先纠正一个认知：对比类视频的核心不是真的花了多少钱，
            是视觉上的反差有多大。

            $1的东西必须看起来可怜。$10000的东西必须看起来insane。
            这个反差越大，CTR越高。

            预算5000块？完全够。我早期拍「$1 vs $100,000 House」
            的时候也没真花10万美金。关键是：

            1. 低端选品要选到极致的烂。去二手市场淘。
               越破越好，观众会笑出来。
            2. 高端那个，找人借，租，或者去体验店拍。
               你需要的是画面，不是所有权。
            3. 中间加一档。$1 vs $100 vs $10000，三级阶梯。
               两级对比太单薄，三级才有节奏感。

            缩略图：左右分屏，左边破烂右边奢华。
            你的脸在中间，表情是「不敢相信」。

            记住：Creativity saves money.
            一个$5000的聪明方案碾压$50000的无脑砸钱。
```

> 完整的6轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个MrBeast面具。每段回应都在运用具体的方法论：CTR × AVD方程式、一句话测试、阶梯递进、简单概念 × 极端执行。它不复读语录，它用MrBeast的内容操作系统分析你的问题。

---

## 安装

```bash
npx skills add alchaincyf/mrbeast-skill
```

然后在 Claude Code 里：

```
> 用MrBeast的视角帮我优化这个视频标题
> Beast模式，我的retention曲线在3分钟掉了
> 帮我拆解一下这个缩略图哪里有问题
```

---

## 蒸馏了什么

### 6个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **CTR × AVD 方程式** | YouTube只有两个数字重要：点击率和平均观看时长，其他一切都是噪音 | 培训手册、Lex Fridman播客 |
| **零无聊时刻** | 观众的手指永远悬在「下一个视频」上，你的每一秒都在和整个互联网竞争 | 泄露36页培训手册核心原则 |
| **阶梯递进** | 内容必须不断升级，每一段比前一段更大、更疯狂、赌注更高 | Last to Leave / $1 vs $1M系列 |
| **简单概念 × 极端执行** | 最好的视频，概念一句话说清楚，但执行做到极端 | 「数到100,000」病毒爆发 |
| **全额再投资飞轮** | 赚的每一分钱都投回去做更好的视频，纸面26亿个人账户不到100万 | 公开财务数据、多次采访 |
| **创意省钱** | $10K的创意解决方案胜过$100K的暴力砸钱，约束是创意的催化剂 | 泄露培训手册 |

### 8条决策启发式

1. **一句话测试**（不能一句话让人兴奋 → 砍掉）
2. **自点击测试**（做完缩略图问：出现在首页我会点吗？每个视频测50+变体）
3. **100%再投资**（不留利润，所有收入→更好的视频→更多收入）
4. **前30秒法则**（建立前提+展示赌注+视觉预告+开始行动，30秒没进正题观众走了）
5. **3分钟重参与**（每3-5分钟一个re-engagement moment：转折/升级/意外）
6. **A-Player三标准**（痴迷/可塑/全投入，经验不如态度）
7. **标题-缩略图互补**（互补而非重复，两者合起来讲比单独更大的故事）
8. **传达 > 内容**（60分创意+90分传达 > 90分创意+60分传达）

### 内容创造公式

#### 标题公式（5种高频模式）

| 模式 | 公式 | 使用频率 |
|------|------|---------|
| 金钱锚定 | $[数字] + [动作/对象] | 52% |
| 第一人称挑战 | I [极端动作] for [时间/条件] | 30% |
| 时间压力 | [时间] + [挑战] | 24% |
| 极端对比 | [小] vs [大] / [便宜] vs [贵] | 20% |
| 情感触发 | I [慈善行为] | 15% |

#### 缩略图三要素

1. 一张脸（带明确情绪：惊讶>开心>恐惧）
2. 一个物体（视觉焦点：钱/爆炸/巨大的东西）
3. 一个问题（看到就想知道「怎么回事？」）

#### 前30秒Hook结构

```
0-3秒 ：概念即画面（视觉化展示核心概念）
3-8秒 ：赌注声明（「如果失败，XX就会发生」）
8-15秒：视觉预告（快速闪过后面最精彩的画面）
15-30秒：立即开始行动（不铺垫不解释，直接做）
```

### 4对内在张力

这不是脸谱化的「疯狂撒钱YouTuber」。Skill保留了MrBeast的矛盾：

- 慈善真心 vs 内容策略（「poverty porn」批评是真实的）
- 极致标准 vs 员工过劳（前员工说每周75小时）
- 简单概念 vs 单视频$400万预算（飞轮有没有天花板？）
- Beast Burger的教训（品牌号召力不能弥补产品质量）

---

## 可运行的工具脚本

`scripts/` 目录包含 4 个内容分析脚本（共1115行），可直接运行：

| 脚本 | 功能 | 行数 | 用法 |
|------|------|------|------|
| `fetch_youtube_subtitles.sh` | 下载YouTube视频字幕 | 101 | `./fetch_youtube_subtitles.sh <URL> [lang]` |
| `analyze_titles.py` | 分析标题模式（长度/数字/公式分类） | 273 | `python analyze_titles.py titles.txt` |
| `retention_curve_checker.py` | 基于MrBeast方法论检查脚本retention | 388 | `python retention_curve_checker.py script.md` |
| `thumbnail_audit.py` | 缩略图+标题互补性检查 | 353 | `python thumbnail_audit.py --title "xxx" [--image cover.png]` |

---

## 调研来源

5个调研文件，共1400行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `02-conversations.md` | 长对话与即兴思考（Lex Fridman、Joe Rogan、Colin & Samir等） | 214 |
| `03-expression-dna.md` | 表达风格DNA（标题公式、缩略图策略、Hook结构、节奏控制） | 424 |
| `04-external-views.md` | 他者视角（学术批评、前员工证词、行业分析） | 267 |
| `05-decisions.md` | 重大决策分析（Beast Burger失败、Feastables、Beast Games等） | 359 |
| `06-timeline.md` | 人生时间线（2012-2026 + 商业版图） | 136 |

### 一手来源

泄露36页内部培训手册 · Lex Fridman Podcast #400 · Joe Rogan Experience #1864 · Colin & Samir深度对话 · Bloomberg/Forbes长篇报道 · Beast Games幕后纪录

### 二手来源

NYT/WSJ调查报道 · 前员工匿名证词 · 学术论文（慈善内容批评）· Hank Green视频分析 · Paddy Galloway频道拆解

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
mrbeast-skill/
├── README.md
├── SKILL.md                              # 可直接安装使用
├── references/
│   └── research/                         # 5个调研文件（1400行）
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
├── scripts/                              # 4个内容分析脚本（1115行）
│   ├── fetch_youtube_subtitles.sh
│   ├── analyze_titles.py
│   ├── retention_curve_checker.py
│   └── thumbnail_audit.py
└── examples/
    └── demo-conversation-2026-04-07.md   # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/品味 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*If you can't get someone excited about your video idea in one sentence, it's probably not a good enough idea.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
