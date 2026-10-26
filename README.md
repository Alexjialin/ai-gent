# AI-Agent

专业 AI Agent、技能和跨专业工作流程的统一管理仓库。

本仓库当前仅包含目录骨架和说明文档，不包含具体业务代码、MCP 服务实现或可执行工作流程。

## 目录导航

| 路径 | 用途 |
| --- | --- |
| `AGENTS.md` | Codex 全局工作规范 |
| `.agents/skills/` | Codex 自动发现技能的入口 |
| `agents/engineering-agent/` | 工程 Agent 配置预留 |
| `agents/research-agent/` | 研究 Agent 配置预留 |
| `agents/financial-agent/` | 金融 Agent 配置预留 |
| `skills/analog-cmos-design-expert/` | 模拟 CMOS 设计专业技能预留 |
| `mcp-servers/` | MCP 服务实现及配置模板预留 |
| `workflows/` | 跨专业工作流程预留 |
| `docs/` | 架构及维护文档 |
| `tools/` | 验证及发布工具预留 |

## 技能发现

专业技能统一维护在 `skills/` 下，`.agents/skills/` 通过相对符号链接引用对应目录。
当前技能目录仅为占位；添加正式 `SKILL.md` 后才能提供具体技能指令。
