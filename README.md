# English Learning Plan

A practical learning system for speaking English in Internet and IT workplace meetings.

这个仓库的目标不是系统学习所有英语知识，而是通过互联网和IT领域的虚构场景，训练在工作会议中完成以下任务：

- 汇报进度、问题、风险和下一步
- 听不懂时主动要求重复或解释
- 回答常见追问并表达简单意见
- 确认负责人、截止时间和行动项
- 用简单、准确的英语完成一至两分钟脱稿表达

## Content Focus — Internet and IT

每日短文应围绕通用的互联网或IT工作主题，例如：

- 软件开发、代码评审、API和应用测试
- 云服务、基础设施、网络和数据库
- DevOps、CI/CD、发布、部署和回滚
- 监控、性能、故障排查和事件复盘
- 信息安全、访问控制、风险和变更管理
- 技术项目计划、状态汇报和行动项确认
- 商务沟通、优先级、预算、时间线、决策和跨团队协作

“与工作相关”仅指主题和沟通技能相关。所有场景必须从零虚构，不得使用、改写、脱敏或影射任何真实公司、项目、系统、会议或事件。

## Business English and Abbreviations

除互联网和IT词汇外，每日课程还应自然加入常见商务表达，例如提出建议、确认优先级、讨论截止时间、推动决策、礼貌表达不同意见和总结后续行动。课程也会逐步介绍 `FYI`、`EOD`、`ETA`、`TBD`、`ASAP`、`KPI`、`ROI` 和 `SLA` 等常见缩写。

- 缩写第一次出现时必须同时写出英文全称和中文含义。
- 说明缩写更适合口语、邮件还是即时消息，以及可能的语气问题。
- 对 `POC` 等存在多个含义的缩写，必须结合上下文解释，不能单独死记。
- 不使用任何公司或团队内部自创的简称。

常见表达和缩写见 [`phrasebook/business-communication.md`](phrasebook/business-communication.md)。

## Start Here

1. 阅读 [`goals.md`](goals.md)，了解目标和衡量标准。
2. 按照 [`study-plan.md`](study-plan.md) 每天练习约30分钟。
3. 从 [`lessons/week-01/day-01-weekly-status-update.md`](lessons/week-01/day-01-weekly-status-update.md) 开始第一周课程。
4. 每次练习后更新 [`progress.md`](progress.md)。
5. 真实会议前后使用 [`templates/`](templates/) 中的准备和复盘模板。
6. 第一周之后，使用 [`prompts/generate-daily-lesson.md`](prompts/generate-daily-lesson.md) 生成新的每日课程。

## Daily Learning Loop

每天不要只逐字背诵，而是完成下面的闭环：

1. **Read**：朗读短文三遍，理解内容和停顿。
2. **Memorize**：记住3～5个核心会议句型。
3. **Replace**：替换环境、问题、团队和时间等信息。
4. **Retell**：不看原文，用自己的话复述一分钟。
5. **Review**：在第2、4、7天再次复述。

## Repository Structure

```text
.
├── goals.md                 # 学习目标和衡量标准
├── study-plan.md            # 12周学习计划
├── progress.md              # 每日和每周进度
├── lessons/                 # 每日短文和练习
├── phrasebook/              # 可复用的会议、商务句型和缩写
├── prompts/                 # 安全的每日课程生成提示
└── templates/               # 每日练习、会前准备、会后复盘模板
```

## Public Repository Safety

这个仓库是公开仓库。所有练习必须是从零创作的完全虚构、通用互联网或IT职场场景，不能改写或脱敏真实工作内容：

- 不记录公司内部项目名、域名、IP、集群、Namespace或工单详情。
- 不记录密码、Token、Secret、证书或其他凭据。
- 不上传真实会议录音、逐字稿、日志或内部截图。
- 不从真实工作资料中提取、总结、推断或匿名化练习内容。
- 使用 `the application`、`the test environment`、`the infrastructure team` 等通用名称。
