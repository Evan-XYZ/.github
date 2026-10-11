<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Evan-XYZ/.github/main/profile/banner-dark.png">
  <img alt="用 AI 做投资：方法《AI 投资指南》、动作 ymskill、打样 YMOS" src="https://raw.githubusercontent.com/Evan-XYZ/.github/main/profile/banner-light.png">
</picture>

# 勇麦 · Evan-XYZ

十一年 A 股 + 美股实盘，一年多重度用 AI 做投研、决策和复盘。这里放的是我自己在用的东西，拆出来公开，拿去改成你自己的。

*Yongmai — an individual investor using AI to watch markets, cut the noise and keep the discipline. Method, skills and a working system, all open.*

## 方法 · 动作 · 打样

**指南给方法，ymskill 给动作，YMOS 是照着方法搭好的一份样板。** 三样可以单独用，也能叠着用。

| | 是什么 | 从这里开始 |
|:---|:---|:---|
| **方法**<br>[《AI 投资指南》](https://github.com/Evan-XYZ/ai-invest-guide) | 8 篇。核心一句：AI 替你降噪、梳理，判断你自己来。投研、策略、操盘、复盘、Agent 每一层为什么这么搭、怎么做 | 先想弄懂思路 → [仓库](https://github.com/Evan-XYZ/ai-invest-guide) · [网页版](https://yongmai.xyz/ai-invest-guide/) |
| **动作**<br>[ymskill](https://github.com/Evan-XYZ/ymskill) | 指南的可运行版本：1 个总入口、7 个模块、28 个投资流程动作。装进 Claude Code、Codex、Cursor、OpenClaw、Hermes 这类 Agent，用中文说要做的事就行 | 已经有自己的笔记库，只想要动作 → [仓库](https://github.com/Evan-XYZ/ymskill) · [介绍页](https://yongmai.xyz/ymskill/) |
| **打样**<br>[YMOS](https://github.com/Evan-XYZ/YMOS) | 照着方法搭好的一整套 AI 结构化投资系统：投研层、策略内核层、操盘层，加一条用真实结果改进规则的反馈闭环。本地 Markdown 文件夹，可配桌面客户端 | 想要一套现成的系统，照着用或魔改 → [仓库](https://github.com/Evan-XYZ/YMOS) · [文档](https://yongmai.xyz/ymos-docs/) |

### 三样怎么接上

- **指南 → ymskill**：每一篇末尾都有一张卡，写着这一篇的做法对应 ymskill 的哪几个动作。
- **ymskill → YMOS**：在 YMOS 的文件夹里装上 ymskill，它按根目录的 `YMSKILL_ADAPTER.md` 接上 YMOS 的目录，不用搬家。YMOS 已有的流程（市场洞察、投资雷达、我想买、头脑风暴……）照旧用 YMOS 的；开原件核实、两把尺子、持有期复盘、回看台账这些 YMOS 没有的动作，由 ymskill 来补，产物写回 YMOS 的目录。
- **YMOS ↔ 指南**：YMOS 文档讲在 YMOS 里怎么做，讲「为什么」的地方链回指南对应的那一篇；指南每一篇也链到 YMOS 文档对应的那一页。

我的建议是先读懂方法，再用 YMOS 和 ymskill。那时你更能看懂它们为什么这么设计、哪里不适合你，然后按自己的需求改，而不是整套照搬。

### 不做什么

不荐股，不预测涨跌，不给目标价，**不接任何交易接口**。真实买卖由你自己在券商 App 上手动完成。

不接下单不是信不过 AI：链上交易里 Agent 早就能直接下单。原因是频率：个人投资者大多是低频交易，一个月下不了几次单，交给 AI 省不下多少时间，接口和权限却要一直维护。AI 的力气花在下单之前的降噪、梳理和门禁上，回报大得多。

## 其他开源

- [ymos-diagnosis](https://github.com/Evan-XYZ/ymos-diagnosis)：投资策略诊断 Skill，问诊和体检两种模式，YMOS 的子模块之一
- [tib-rss-list](https://github.com/Evan-XYZ/tib-rss-list)：我在用的 28 个 RSS 订阅源
- [obsidian-templelate](https://github.com/Evan-XYZ/obsidian-templelate)：个股知识库模板
- [tib-os-3.0](https://github.com/Evan-XYZ/tib-os-3.0)：早期版本，15 个投资提示词加一个前端界面

## 联系

- 博客：[yongmai.xyz](https://yongmai.xyz)
- 邮箱：evan@yongmai.xyz
- 公众号：勇麦
- 抖音：勇麦
