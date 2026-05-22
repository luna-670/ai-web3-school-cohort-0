# 任务记录 — TASK-001

## 基本信息

- **任务名称**：前置准备｜创建课程 GitHub repo
- **来源**：WCB
- **开始日期**：2026-05-21
- **完成日期**：2026-05-21
- **状态**：✅ 已完成

## 任务描述

为 AI × Web3 School 课程创建个人学习仓库，要求 public 可见，包含完整目录结构、学员画像、学习计划、模板文件，作为 Learning in Public 的 proof-of-work。

## 仓库

- **GitHub**：https://github.com/luna-670/ai-web3-school-cohort-0
- **本地路径**：`~/ai-web3-school-cohort-0`

## 目录结构

```
├── README.md              # 仓库说明 + 隐私提醒 + 目录
├── profile.md             # 学员画像
├── learning-plan.md       # 四阶段学习计划
├── daily/                 # 每日打卡笔记
│   └── 2026-05-21.md
├── tasks/                 # 任务记录
├── experiments/           # 实验与项目
├── handbook-feedback/     # Handbook 反馈
├── hackathon/             # Hackathon 项目
├── submissions/           # 提交记录
└── templates/             # 模板文件
    ├── daily-note.md
    └── task-note.md
```

## 过程记录

### Agent 做了什么

Hermes Agent（Learning Agent 模式）协助完成了：

1. **学员画像收集**：逐步确认 AI 基础（新手）、Web3 基础（新手）、编程能力（无代码）、目标方向（内容运营 + Hackathon）、每日时间（2h）、输出语言（中文）
2. **学习计划制定**：按 Handbook 侧边栏结构规划四阶段路径——AI基础→Web3基础→Bridge→Hackathon
3. **仓库结构初始化**：创建完整目录树和模板文件
4. **README 撰写**：包含课程简介、Handbook/WCB 链接、隐私提醒、目录说明
5. **Git 配置**：处理 WSL 环境下 GitHub git 协议被 GFW 墙的问题，改用 HTTPS + 浏览器认证
6. **首次 commit + push**
7. **每日提醒设置**：早 8:00 / 晚 21:00 学习提醒

### 遇到的环境问题

- **WSL + GFW**：`github.com` git 协议超时，`api.github.com` 可通。解决方式：HTTPS 协议 + 浏览器 OAuth 认证。
- **gh CLI 无法安装**：GFW 导致 release 下载超时。跳过 gh，直接用 git + 手动创建 repo。

### 人工确认了什么

- ✅ 仓库名、可见性、目录结构
- ✅ 学员画像完整性
- ✅ 学习计划是否匹配个人情况
- ✅ README 内容
- ✅ 打卡提醒时间
- ✅ 所有涉及 Git push 的操作

## 产出

| 产出 | 链接 |
|------|------|
| GitHub 仓库 | https://github.com/luna-670/ai-web3-school-cohort-0 |
| 学员画像 | [profile.md](../profile.md) |
| 学习计划 | [learning-plan.md](../learning-plan.md) |
| Day 1 笔记 | [daily/2026-05-21.md](../daily/2026-05-21.md) |

## 复盘

### 学到了什么

- **Learning in Public**：个人学习仓库不是私密笔记，是公开的 proof-of-work
- **GHF 环境适配**：WSL + GFW 下 GitHub 操作需要绕路，但总能找到办法
- **Agent 辅助初始化**：用 Agent 引导初始化比手动建文件高效得多，重点是逐项人工确认

### 可以改进

- 如果后续有同学遇到同样的 GFW 问题，可以整理一份「WSL + GFW 下 GitHub 操作指南」
