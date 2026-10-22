# AI MVP Validation / AI 产品 MVP 验证 Skill

[![CI](https://github.com/huaxialucaicaizi/ai-mvp-validation/actions/workflows/ci.yml/badge.svg)](https://github.com/huaxialucaicaizi/ai-mvp-validation/actions/workflows/ci.yml)

**在写代码、写 BP 之前，先用"调研 + Meta 广告测试"验证你的 AI 产品想法有没有人要。**

Validate your AI product idea (AI tools, AI apps, Agents) with desk research, user interviews and small-budget Meta (Facebook / Instagram) ad tests — before you build more or write a business plan.

> 这是「一人公司工具包」的第 1 步（想法验证）。下一步写 BP 可用 [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill)。串联全部步骤的工具包即将推出。
>
> Step 1 of the "One-Person Company Toolkit". Next step: write your BP with [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill). The full toolkit is coming soon.

---

## 痛点 / The Problem

- 做 AI 产品很快，但做完才发现没人用、没人付钱
- 不确定通用大模型（如直接用聊天机器人）会不会让你的产品变得多余
- 模型调用成本算不清，定价心里没底
- 想投广告测需求，但不知道测什么、花多少、看哪些指标、怎样算通过
- 写 BP、申请园区或找投资时，拿不出"市场验证"的证据

- Building an AI product is fast; finding out nobody pays is slow and expensive
- Unsure whether native LLM features make your product redundant
- Unclear inference cost and pricing
- Want to run ad tests but don't know what to test, how much to spend, or what "pass" looks like
- No validation evidence for your BP, incubator application or investors

## 适合谁 / Who It's For

- 一人公司、独立开发者、小团队创始人，正在做 AI 工具、AI 应用或 Agent
- 想出海（Meta 广告）或做国内市场（可换小红书聚光、巨量引擎）
- 需要把验证过程整理成评委、投资人看得懂的证据

Solo founders, indie hackers and small teams building AI products, for overseas (Meta ads) or China (Xiaohongshu / Ocean Engine) markets.

## 使用场景 / Use Cases

| 场景 | 这个 skill 帮你做什么 |
|---|---|
| 有个 AI 产品点子，不知道值不值得做 | 桌面调研 + 用户访谈，判断痛点真伪 |
| 担心被大模型原生功能覆盖 | 对比通用 AI 能否直接完成同样任务，给出风险等级 |
| 不知道模型成本会不会吃掉利润 | 按官方价格页估算单次任务成本 |
| 想用广告测需求 | 落地页 / 等待名单 + 小预算 A/B 测试方案、指标公式、判断标准 |
| 测完不知道怎么下结论 | 组合公式 + "已验证 X，下一步验证 Y" + 继续 / 调整 / 放弃 |
| 要写 BP 或申请园区 | 把证据整理成可直接引用的素材 |

## 工作流 / Workflow

1. **调研**：桌面调研（竞品、搜索热度、社区讨论）+ 用户访谈
2. **痛点 + AI 产品判断**：大模型原生功能覆盖风险、模型 / 推理成本、数据与合规
3. **一人能否做**：时间、钱（含广告费和模型调用费）、技能、AI 工具分工
4. **Meta 广告投放验证**：多卖点 × 多受众 A/B 测试，记录 CTR、CPC、落地页转化率、单线索成本、付费意向、实际预付
5. **结论**：组合公式（给谁 / 解决什么 / 卖点 / 付多少钱）+ 继续 / 调整 / 放弃

辅助方法：小红书笔记测反应、预售、人工模拟交付。

## 原则 / Principles

- **不编数据**：没有的写"待补充"；不提供"行业平均"基准
- **阈值可调**：所有判断标准都标"建议值，可自行调整"
- **如实宣传**：未上线产品只能以"等待名单 / 内测预约"呈现
- **只引用已核实的官方链接**：法规、平台规则以官方原文为准；本 skill 不构成法律意见

## 安装 / Installation

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

其他支持 Agent Skills 的工具（如 Cursor）也可按各自方式安装。Other Agent Skills-compatible tools (e.g. Cursor) can install it in their own way. Skill 规范参考 / Spec: [OpenAI Codex skills](https://learn.chatgpt.com/docs/build-skills).

## 使用示例 / Example Prompt

```text
用 ai-mvp-validation 帮我验证这个想法：一个帮海外独立站卖家自动起草售后邮件的 Agent，预算有限，想先投 Meta 广告测一下。
Use ai-mvp-validation to validate my AI agent idea and plan a Meta ad test.
```

## 目录 / Structure

```text
SKILL.md                         # 主流程 / main workflow
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

## 一人公司工具包 / One-Person Company Toolkit

| 步骤 | 仓库 |
|---|---|
| 1. AI 产品 MVP 验证 / AI MVP Validation | 本仓库 / This repo |
| 2. 商业计划书 / Business Plan | [business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill) |
| 3. 政策与补贴 / Policy & Subsidies | 即将推出 / Coming soon |
| 4. 路演教练 / Roadshow Coach | 即将推出 / Coming soon |
| 5. 增长获客 / Growth | 即将推出 / Coming soon |
| 6. 定价与成交 / Pricing & Closing | 即将推出 / Coming soon |
| 7. 注册与合规 / Registration & Compliance | 即将推出 / Coming soon |
| 串联大仓库 / Full toolkit repo | 即将推出 / Coming soon |

各步骤上线后将陆续补充链接。/ Links will be added as each step launches.

## 许可 / License

[MIT](LICENSE)
