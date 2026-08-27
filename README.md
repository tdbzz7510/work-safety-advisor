# 安全生产顾问（Work Safety Advisor）

一款面向企业安全管理人员、EHS 工程师与学术研究人员的安全生产与职业健康专业咨询 Skill。

## 能做什么

- **法规合规咨询** — 解读《安全生产法》《职业病防治法》《消防法》《生产安全事故应急条例》及配套规章标准
- **风险辨识评估** — 使用 LEC / LS / JHA / SCL 等方法进行危险源辨识与风险分级管控
- **隐患排查治理** — 生成行业隐患排查清单、隐患分级判定与整改闭环建议
- **应急预案编制** — 综合/专项应急预案框架、演练方案与效果评估
- **职业健康管理** — 职业病危害因素识别、职业健康监护、ISO 45001 体系建设建议
- **事故调查分析** — 事故致因分析、调查报告框架与安全培训课件大纲

## 使用方法

安装本 Skill 后，在 WorkBuddy / SkillHub / ClawHub / Coze 中直接描述你的需求即可触发：

- 「帮我生成一份化工车间的隐患排查清单」
- 「用 JHA 方法分析冲压作业的风险」
- 「制定一份企业生产安全事故应急预案框架」
- 「解读最新版《安全生产法》中企业主要负责人的职责」
- 「分析一起机械伤害事故的原因并给出培训课件大纲」
- 「矿山井下通风系统隐患排查重点是什么？」
- 「冶金高温熔融区域有哪些重大隐患判定要点？」

## 文件结构

```
work-safety-advisor/
├── SKILL.md                              # 技能核心指令与角色设定
├── README.md                             # 本文件
├── references/
│   ├── laws-framework.md                 # 安全生产法规体系速查
│   ├── risk-methods.md                   # 风险辨识与评估方法速查
│   └── output-quality-checklist.md       # 输出质量自检清单
└── assets/
    ├── hazard-check-list-template.md      # 通用隐患排查清单模板
    ├── hazard-check-list-chemical.md    # 化工车间隐患排查专项清单
    ├── hazard-check-list-construction.md # 建筑施工隐患排查专项清单
    ├── hazard-check-list-mining.md       # 矿山井下作业隐患排查专项清单
    ├── hazard-check-list-metallurgy.md   # 冶金/有色高温熔融作业隐患排查清单
    ├── emergency-plan-framework.md       # 应急预案编制框架
    ├── accident-report-framework.md      # 事故调查报告框架
    └── training-outline-template.md      # 安全培训课件大纲模板
```

## 输出规范

- 引用法规条款时注明文件名称、条款号与版本
- 区分「通用管理建议」与「须由专业机构出具的法定文件」（如安全评价、检测检验等）
- 涉及重大安全决策时提示结合属地监管要求与最新法规版本复核

## 能力边界

- 可提供法规解读、风险评估方法、隐患排查清单/报告框架、应急预案框架、培训课件大纲等专业咨询内容。
- 不能替代具备法定资质的第三方机构出具安全评价、检测检验、职业健康检查等法定报告；不能对具体事故进行责任认定或法律定性；不能生成虚假文件。
- 当用户需求模糊、超出边界或涉及敏感数据时，本 Skill 会明确追问、拒绝或提示风险。

## 重要声明

本 Skill 为安全生产专业咨询辅助工具，输出内容基于公开法律法规、国家标准与行业通行实践。所有建议均不构成正式法律意见；法定资质事项（安全评价、检测检验、特种设备检验、职业卫生评价等）须委托具备资质的专业机构执行。

## 作者

台灯不自照先森

## 安装

适用于任何支持 Skills 的 AI 客户端（WorkBuddy / Claude Code / Cursor 等）：

```bash
# WorkBuddy
git clone https://github.com/tdbzz7510/work-safety-advisor ~/.workbuddy/skills/work-safety-advisor

# Claude Code
git clone https://github.com/tdbzz7510/work-safety-advisor ~/.claude/skills/work-safety-advisor

# Cursor
git clone https://github.com/tdbzz7510/work-safety-advisor ~/.cursor/skills/work-safety-advisor
```

安装后无需重启，描述需求即可自动触发。

## 许可证

[MIT](./LICENSE) · 同时上架于 [SkillHub](https://skillhub.cn)
