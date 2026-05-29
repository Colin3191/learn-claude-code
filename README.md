# Learn Claude Code

这是一个学习项目，跟随 [learn-claude-code](https://learn.shareai.run) 课程构建一个最小化的 AI Agent。

## 项目简介

使用 Anthropic Claude API 从零实现一个最小化的 coding agent，逐步学习 Agent 的核心概念：

- Agent Loop（循环调用模型 + 工具）
- Tool Use（工具定义与调用）
- 多轮对话管理

> 项目持续开发中，跟随课程进度逐步完善。

## 课程来源

本项目基于 [learn-claude-code](https://learn.shareai.run) 课程内容编写。

## 快速开始

```bash
# 安装依赖
uv sync

# 配置环境变量（参考 .env.example）
cp .env.example .env

# 运行
uv run python s01.py
```

## 环境要求

- Python >= 3.14
- [uv](https://docs.astral.sh/uv/) 包管理器
