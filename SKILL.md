---
name: high-match-remote-application-loop
description: |
  用母版简历与证据库筛选远程岗位、定制真实经历、小批投递并按回复数据迭代。适用于远程求职、AI 定制投递和平台比较；不用于无差别海投、伪造经历或迷信固定投递时段。Triggers: remote job, tailored application, 远程工作, 定制投递, ATS。
metadata:
  source: "24 条 Bilibili AI 搞钱视频证据包：视频 02、13、17；用户方向 1、3、7"
  tags: "job-search, remote-work, application"
---
# 高匹配度远程求职闭环

## R — 原文（Reading）
> 不同远程平台要分别统计申请数、回复率和面试率，不能迷信固定投递时段。
>
> — 视频 17 验证摘要，BV1uukWBXEav

## I — 方法论骨架（Interpretation）
AI 求职的价值不是把海投速度推到极限，而是降低逐岗研究和真实材料重排的成本。流程从母版简历与项目证据库开始，先核查地区、时区、语言、合同与硬资格，再比较技能匹配和缺口。AI 可解释 JD、提取关键词、重排真实经历与做一致性检查，但不得补造经历。每次只投一个可核验的小批次，并把平台、岗位新鲜度、材料版本、回复和面试结果连接起来，靠数据更新渠道与材料。

## A1 — 资料中的应用（Past Application）
- **AI 求职流水线**：覆盖岗位匹配、材料定制、二次审校、ATS 检查、申请状态和面试复盘。
- **远程平台清单**：真正有用的不是网站数量，而是记录国家限制、时区、合同、语言、薪资和平台转化。

## A2 — 触发场景（Future Trigger）
1. 用户要找远程工作或海外岗位，并希望用 AI 提高效率。
2. 用户要针对某个 JD 定制简历、求职信或项目顺序。
3. 用户想验证“晚上 8 点到 2 点投递”或某个平台是否更有效。

语言信号："远程工作怎么投"、"AI 海投"、"按 JD 改简历"、"remote application"、"tailor my resume"。

与相邻 Skill 的区分：本 Skill 执行求职闭环；`evidence-backed-capability-portfolio` 负责建立真实证据；`minimum-batch-evidence-gate` 提供通用小批实验原则。

## E — 可执行步骤（Execution）
1. **建母版与筛选表**：收集真实项目证据；为岗位记录发布日期、地区、时区、合同、语言、薪资、硬资格和来源。
   - 完成标准：不符合硬资格的岗位被明确淘汰，不因匹配分高而跳过资格核查。
2. **逐岗定制并核验**：AI 提取任务与关键词，只重排或改写已有事实；人工核对数字、时间、角色和链接。
   - 完成标准：每句关键声明能回指证据库，材料与 JD 的主要任务对齐。
3. **小批投递与复盘**：先投 5 个高匹配岗位，记录平台、时间、版本、回复、面试和拒因；再决定扩大或修改。
   - 判停条件：连续批次无回复时，先检查资格、证据和渠道，不继续加速海投。

## B — 边界（Boundary）
- 禁止自动提交、伪造经历、冒充候选人沟通或绕过平台规则。
- 固定时段只是待验证变量，不是普遍规律。
- 失败模式：只追申请数量；忽略地区/时区资格；同一简历投所有岗位；把面试当收入。
- 盲点：回复率受行业、资历、季节和签证影响，样本需分层解释。

## 相关 Skills
- depends-on: `evidence-backed-capability-portfolio`
- contrasts-with: `income-evidence-triage`
- composes-with: `minimum-batch-evidence-gate`, `evidence-based-conversion-funnel`

## 审计信息
- 验证通过：V1 ✓ / V2 ✓ / V3 ✓
- 测试通过率：100%（6/6，独立盲测）
- 来源单元：v05
- 蒸馏时间：2026-08-24
