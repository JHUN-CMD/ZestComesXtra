# 语言

- **全站中文**：整个页面默认以**简体中文**显示，所有界面文案、提示信息、错误消息均使用中文。
- **对话语言**：与 AI Agent 的所有通信默认使用**简体中文**，除非用户主动切换语言。
- **内容语言**：Issue 标题、描述、评论以及代码注释均使用中文编写。

---

# Agent skills

该仓库配置了以下 AI Agent 操作指南，位于 `docs/agents/` 目录中：

- **问题追踪（Issue Tracker）** — `docs/agents/issue-tracker.md`  
  定义 GitHub Issue 的创建、查看与关闭流程，绑定到 `JHUN-CMD/ZestComesXtra` 仓库。

- **分类标签（Triage Labels）** — `docs/agents/triage-labels.md`  
  定义五个中文标签及其含义，用于对 Issue 进行标准化分类。

- **领域文档（Domain Documentation）** — `docs/agents/domain.md`  
  定义单上下文领域文档的编写规则，确保 AI Agent 在同一会话中维护一致的知识边界。
