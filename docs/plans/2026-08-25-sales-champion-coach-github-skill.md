# 销冠教练智能系统 GitHub Skill 实施计划

- [x] 检查 zip、目标目录和远端仓库占用
- [x] 整理 `skills/sales-champion-coach/` 标准 skill 结构
- [x] 迁移知识库文件到 `references/`
- [x] 编写 `agents/openai.yaml`
- [x] 补齐 README、版本、许可和忽略规则
- [x] 运行 skill 校验并检查可安装路径
- [x] 初始化本地 Git 仓库并提交
- [x] 创建公开 GitHub 仓库并推送

验证记录：

- 官方 `quick_validate.py` 在当前 Python 环境中因缺少 `PyYAML` 无法启动。
- 已按 `quick_validate.py` 的检查逻辑用 Ruby 完成等价校验：frontmatter、name、description、允许字段、TODO 占位均通过。
- `agents/openai.yaml` 已通过 YAML 解析。
- 已创建公开仓库并推送：`https://github.com/zzfang-subei/sales-champion-coach`
