# Learn Claude Code

这是一个学习项目，跟随 [learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) 课程构建一个最小化的 AI Agent。

## 项目简介

使用 Anthropic Claude API 从零实现一个最小化的 coding agent，逐步学习 Agent 的核心概念：

- Agent Loop（循环调用模型 + 工具）
- Tool Use（工具定义与调用）
- 多轮对话管理

> 项目持续开发中，跟随课程进度逐步完善。

## 课程进度

| 文件 | 内容 |
|------|------|
| `s01.py` | 基础 Agent Loop — 最小化的多轮对话循环 |
| `s02.py` | Tool Use — 在 s01 基础上增加 5 个工具（bash、read_file、write_file、edit_file、glob） |
| `s03.py` | Todo 管理 — 在 s02 基础上增加 todo_write 工具，支持任务规划与进度追踪 |
| `s04.py` | Subagent — 在 s03 基础上增加 task 工具，支持派生子代理处理复杂子任务 |
| `s05.py` | Skills — 在 s04 基础上增加技能系统，支持从 skills/ 目录加载可扩展技能 |

## 快速开始

```bash
# 安装依赖
uv sync

# 配置环境变量（参考 .env.example）
cp .env.example .env

# 运行基础版
uv run python s01.py

# 运行工具版
uv run python s02.py
```

## 环境要求

- Python >= 3.14
- [uv](https://docs.astral.sh/uv/) 包管理器
