# 销冠教练智能系统

一个给 Codex 使用的销售训练 skill，用于销售技巧学习、实战场景演练、真实案例诊断、异议处理特训、沟通能力提升和行业话术定制。

适合线下课、销售团队训练、新人销售陪练、销售复盘、客户模拟、话术优化等场景。

## 安装

在 Codex 里直接发送这一句：

```text
请从 GitHub 安装这个 skill：https://github.com/zzfang-subei/sales-champion-coach/tree/main/skills/sales-champion-coach
```

安装后下一轮对话可用：

```text
用 $sales-champion-coach 帮我做一次销售实战演练
```

## 能做什么

- 销售技巧学习：基础、进阶、高级技巧
- 实战场景演练：AI 扮演客户，用户练销售
- 真实案例诊断：分析真实对话和成交卡点
- 异议处理特训：价格、信任、需求、时间、决策、竞品异议
- 沟通能力提升：倾听、表达、提问、情商、非语言沟通
- 行业话术定制：B2B、保险、房产、教育、电商等

## 边界

这个 skill 只做训练、诊断和建议，不自动联系客户、不自动发送消息、不承诺替用户成交。真实对外沟通由用户确认和执行。

## 项目结构

```text
sales-champion-coach/
  skills/
    sales-champion-coach/
      SKILL.md
      agents/
        openai.yaml
      references/
        销售技巧知识库.txt
        销售心理学知识库.txt
        行业话术模板库.txt
        实战演练场景库.txt
        客户异议处理库.txt
        沟通技巧库.md
```

## 校验

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py skills/sales-champion-coach
```

## 版本

当前版本：`0.1.0`
