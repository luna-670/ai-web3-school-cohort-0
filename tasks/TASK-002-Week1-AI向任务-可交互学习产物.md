# 任务记录 — TASK-002

## 基本信息

- **任务名称**：Week 1 ｜ AI 向任务 ｜ 完成 AI 可交互学习产物
- **来源**：WCB
- **开始日期**：2026-05-22
- **完成日期**：2026-05-22
- **状态**：✅ 已完成

## 任务描述

用 AI Agent 辅助生成一个可交互学习产物，选择 Week 1 的一个概念（LLM / Prompt / Workflow / Agent / 钱包 / 签名 / 交易 / Gas / 合约），产出形式可以是概念卡片、测验、流程图、网页、CLI 工具或最小 Demo。

## 选择的概念

**智能体（Agent）** — 来自 AI × Web3 School Handbook

选择理由：
- 正在使用 Hermes Agent，学习 Agent 概念与实践结合
- Agent 是 AI × Web3 桥梁中的核心角色
- 内容运营方向可以从概念卡片 + 测验入手，不需要写代码

## 产出

| 产出 | 路径 |
|------|------|
| 交互式概念卡片 + 测验网页 | [experiments/agent-concept-cards/index.html](../experiments/agent-concept-cards/index.html) |
| 实验说明 README | [experiments/agent-concept-cards/README.md](../experiments/agent-concept-cards/README.md) |

### 网页包含

- 🃏 **7 张可翻转概念卡片**：什么是 Agent、Tool Use、Planning、State、Reflection、Multi-Agent、AI × Web3 中的 Agent
- 🧩 **5 道选择题**：带进度指示、正误反馈和答案解析
- 🎨 暗色主题、GitHub 风格配色
- 📱 响应式布局

## Agent 做了什么 vs 人工做了什么

| 项目 | Agent | 人工 |
|------|-------|------|
| 概念卡片内容提取 | ✅ 基于 Handbook 原文 | ✅ 逐条确认准确性 |
| HTML/CSS/JS 代码 | ✅ 全部生成 | — |
| 测验题目措辞 | ✅ 自动生成 | ✅ 逐题审核，确认解释准确 |
| README 文档 | ✅ 自动生成 | ✅ 补充风险点和改进计划 |
| 整体审阅 | — | ✅ 通读确认 |

## 复盘

### 学到了什么

- Agent 可以从 Handbook 原文中提取知识节点，生成结构化的交互内容
- 概念卡片 + 测验这种形式很适合「无代码 + 内容运营」方向
- Agent 生成的内容需要人工审阅——尤其是测验题目的措辞和答案准确性
- 一次性生成的 HTML 质量不错，但多轮迭代会让卡片更深入

### 可以改进

- 测验仅 5 题，覆盖度不够——下一步增加 Planning 和 Multi-Agent 相关题目
- 可以尝试让 Agent 生成对比版（Claude Code vs Hermes），体验不同工具在相同任务上的差异
- 部署到 GitHub Pages 让作品可以公开访问和分享
