# Issue Tracker

## 仓库

- **所有者/仓库**: `JHUN-CMD/ZestComesXtra`
- **平台**: GitHub Issues

## 操作规则

### 创建 Issue

1. 使用 `gh issue create` 命令
2. 必须包含以下字段：
   - `--title` — 简洁的问题描述（中文）
   - `--body` — 详细描述（包括复现步骤、期望行为、实际行为）
   - `--label` — 从 `triage-labels.md` 中选择一个合适的标签

### 查看 Issue

- 使用 `gh issue list` 查看全部未关闭 Issue
- 使用 `gh issue view <number>` 查看单个 Issue 详情

### 关闭 Issue

- 确认问题已解决后使用 `gh issue close <number>`
- 关闭时建议附带一条备注说明原因

## 注意事项

- Issue 标题和描述使用**中文**编写
- 每个 Issue 必须至少有一个标签
- 不创建重复 Issue — 搜索已有 Issue 后再操作
