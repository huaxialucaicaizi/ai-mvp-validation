<a id="top"></a>

# AI MVP Validation / AI 产品 MVP 验证 Skill

[![CI](https://github.com/huaxialucaicaizi/ai-mvp-validation/actions/workflows/ci.yml/badge.svg)](https://github.com/huaxialucaicaizi/ai-mvp-validation/actions/workflows/ci.yml)

[中文](#zh) | [English](#en)

---

<a id="zh"></a>

## 中文

**在写代码、写 BP 之前，先用"调研 + Meta 广告测试"验证你的 AI 产品想法有没有人要。**

验证你的 AI 产品想法（AI 工具、AI 应用、Agent）：用桌面调研、用户访谈和小预算 Meta（Facebook / Instagram）广告测试，在继续开发或写商业计划书之前先确认需求。

> 这是「一人公司工具包」的第 1 步（想法验证）。下一步写 BP 可用 [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill)。串联全部步骤的工具包即将推出。

### 痛点

- 做 AI 产品很快，但做完才发现没人用、没人付钱
- 不确定通用大模型（如直接用聊天机器人）会不会让你的产品变得多余
- 模型调用成本算不清，定价心里没底
- 想投广告测需求，但不知道测什么、花多少、看哪些指标、怎样算通过
- 写 BP、申请园区或找投资时，拿不出"市场验证"的证据

### 适合谁

- 一人公司、独立开发者、小团队创始人，正在做 AI 工具、AI 应用或 Agent
- 想出海（Meta 广告）或做国内市场（可换小红书聚光、巨量引擎）
- 需要把验证过程整理成评委、投资人看得懂的证据

### 使用场景

| 场景 | 这个 skill 帮你做什么 |
|---|---|
| 有个 AI 产品点子，不知道值不值得做 | 桌面调研 + 用户访谈，判断痛点真伪 |
| 担心被大模型原生功能覆盖 | 对比通用 AI 能否直接完成同样任务，给出风险等级 |
| 不知道模型成本会不会吃掉利润 | 按官方价格页估算单次任务成本 |
| 想用广告测需求 | 落地页 / 等待名单 + 小预算 A/B 测试方案、指标公式、判断标准 |
| 测完不知道怎么下结论 | 组合公式 + "已验证 X，下一步验证 Y" + 继续 / 调整 / 放弃 |
| 要写 BP 或申请园区 | 把证据整理成可直接引用的素材 |

### 工作流

1. **调研**：桌面调研（竞品、搜索热度、社区讨论）+ 用户访谈
2. **痛点 + AI 产品判断**：大模型原生功能覆盖风险、模型 / 推理成本、数据与合规
3. **一人能否做**：时间、钱（含广告费和模型调用费）、技能、AI 工具分工
4. **Meta 广告投放验证**：多卖点 × 多受众 A/B 测试，记录 CTR、CPC、落地页转化率、单线索成本、付费意向、实际预付
5. **结论**：组合公式（给谁 / 解决什么 / 卖点 / 付多少钱）+ 继续 / 调整 / 放弃

辅助方法：小红书笔记测反应、预售、人工模拟交付。

### 原则

- **不编数据**：没有的写"待补充"；不提供"行业平均"基准
- **阈值可调**：所有判断标准都标"建议值，可自行调整"
- **如实宣传**：未上线产品只能以"等待名单 / 内测预约"呈现
- **只引用已核实的官方链接**：法规、平台规则以官方原文为准；本 skill 不构成法律意见

### 安装

**Codex 内置安装器：**

```bash
$skill-installer huaxialucaicaizi/ai-mvp-validation
```

**手动克隆到用户技能目录：**

```bash
mkdir -p ~/.agents/skills
cd ~/.agents/skills
git clone https://github.com/huaxialucaicaizi/ai-mvp-validation.git
```

其他支持 Agent Skills 的工具（如 Cursor）也可按各自方式安装。Skill 规范参考：[OpenAI Codex skills](https://learn.chatgpt.com/docs/build-skills)。

### 使用示例

```text
用 ai-mvp-validation 帮我验证这个想法：一个帮海外独立站卖家自动起草售后邮件的 Agent，预算有限，想先投 Meta 广告测一下。
```

### 目录

```text
SKILL.md                         # 主流程
references/
  desk-research.md               # 桌面调研
  interview-guide.md             # 用户访谈指南
  pain-and-feasibility.md        # 痛点、AI 产品判断、一人可行性
  meta-ads-validation.md         # Meta 广告投放验证（核心）
  validation-methods.md          # 辅助方法：小红书、预售、人工交付
  validation-log.md              # 验证记录表
agents/openai.yaml
scripts/validate.py
```

### 一人公司工具包

| 步骤 | 仓库 |
|---|---|
| 1. AI 产品 MVP 验证 | 本仓库 |
| 2. 商业计划书 | [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill) |
| 3. 政策与补贴 | 即将推出 |
| 4. 路演教练 | 即将推出 |
| 5. 增长获客 | 即将推出 |
| 6. 定价与成交 | 即将推出 |
| 7. 注册与合规 | 即将推出 |
| 串联大仓库 | 即将推出 |

各步骤上线后将陆续补充链接。

### 许可

[MIT](LICENSE)

[↑ 返回顶部](#top)

---

<a id="en"></a>

## English

**Before writing code or a business plan, validate whether anyone wants your AI product idea with research + Meta ad tests.**

Validate your AI product idea (AI tools, AI apps, Agents) with desk research, user interviews and small-budget Meta (Facebook / Instagram) ad tests — before you build more or write a business plan.

> Step 1 of the "One-Person Company Toolkit" (idea validation). Next step: write your BP with [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill). The full toolkit is coming soon.

### The Problem

- Building an AI product is fast; finding out nobody uses it or pays for it comes later and costs more
- Unsure whether general-purpose LLMs (e.g. just using a chatbot) make your product redundant
- Unclear model inference cost, so pricing is guesswork
- Want to run ad tests but don't know what to test, how much to spend, which metrics to watch, or what "pass" looks like
- No market validation evidence for your BP, incubator application or investors

### Who It's For

- Solo founders, indie hackers and small-team founders building AI tools, AI apps or Agents
- Targeting overseas markets (Meta ads) or China (swap in Xiaohongshu Juguang or Ocean Engine)
- Need to turn the validation process into evidence that judges and investors can understand

### Use Cases

| Scenario | What this skill does for you |
|---|---|
| You have an AI product idea but don't know if it's worth building | Desk research + user interviews to tell real pain from imagined pain |
| Worried native LLM features will cover your product | Compare whether general-purpose AI can do the same task directly, and rate the risk |
| Unsure whether model costs will eat your margin | Estimate per-task cost from official pricing pages |
| Want to test demand with ads | Landing page / waitlist + small-budget A/B test plan, metric formulas, decision criteria |
| Don't know how to conclude after testing | Combination formula + "Validated X, next validate Y" + continue / adjust / stop |
| Need to write a BP or apply to an incubator | Organize evidence into ready-to-cite material |

### Workflow

1. **Research**: desk research (competitors, search trends, community discussions) + user interviews
2. **Pain + AI product assessment**: risk of native LLM feature coverage, model / inference cost, data and compliance
3. **Can one person do it**: time, money (including ad spend and model API costs), skills, division of work with AI tools
4. **Meta ad validation**: multi-selling-point × multi-audience A/B tests, tracking CTR, CPC, landing page conversion rate, cost per lead, purchase intent, actual prepayments
5. **Conclusion**: combination formula (for whom / solving what / selling point / how much they pay) + continue / adjust / stop

Supplementary methods: Xiaohongshu posts to gauge reactions, pre-sales, manual (concierge) delivery.

### Principles

- **No fabricated data**: write "TBD" for anything missing; no "industry average" benchmarks
- **Adjustable thresholds**: every decision criterion is marked "suggested value, adjust as needed"
- **Honest promotion**: unlaunched products may only be presented as "waitlist / beta sign-up"
- **Only cite verified official links**: regulations and platform rules follow the official source text; this skill is not legal advice

### Installation

**Codex built-in installer:**

```bash
$skill-installer huaxialucaicaizi/ai-mvp-validation
```

**Manually clone into your user skills directory:**

```bash
mkdir -p ~/.agents/skills
cd ~/.agents/skills
git clone https://github.com/huaxialucaicaizi/ai-mvp-validation.git
```

Other Agent Skills-compatible tools (e.g. Cursor) can install it in their own way. Spec: [OpenAI Codex skills](https://learn.chatgpt.com/docs/build-skills).

### Example Prompt

```text
Use ai-mvp-validation to validate this idea: an Agent that automatically drafts after-sales emails for overseas independent e-commerce sellers. Budget is limited, so I want to test it with Meta ads first.
```

### Structure

```text
SKILL.md                         # main workflow
references/
  desk-research.md               # desk research
  interview-guide.md             # user interview guide
  pain-and-feasibility.md        # pain, AI product assessment, solo feasibility
  meta-ads-validation.md         # Meta ad validation (core)
  validation-methods.md          # supplementary methods: Xiaohongshu, pre-sales, manual delivery
  validation-log.md              # validation log template
agents/openai.yaml
scripts/validate.py
```

### One-Person Company Toolkit

| Step | Repository |
|---|---|
| 1. AI MVP Validation | This repo |
| 2. Business Plan | [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill) |
| 3. Policy & Subsidies | Coming soon |
| 4. Roadshow Coach | Coming soon |
| 5. Growth | Coming soon |
| 6. Pricing & Closing | Coming soon |
| 7. Registration & Compliance | Coming soon |
| Full toolkit repo | Coming soon |

Links will be added as each step launches.

### License

[MIT](LICENSE)

[↑ Back to top](#top)
