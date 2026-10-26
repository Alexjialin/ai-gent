# 架构及维护文档

仓库采用 Agent、Skill、MCP 服务和工作流程分层管理的目录结构。

- `agents/`：各专业 Agent 的角色与配置。
- `skills/`：专业技能的唯一维护位置。
- `.agents/skills/`：以相对符号链接提供 Codex 技能发现入口。
- `mcp-servers/`：外部能力接入及配置模板。
- `workflows/`：跨专业协作流程。
- `tools/`：后续验证与发布工具。

空目录使用 `.gitkeep` 占位，确保 Git 能保存目录骨架。当前不提供具体实现。
