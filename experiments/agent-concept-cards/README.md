# 🤖 Agent 概念卡片 + 小测验

> Week 1 Task 3 — 可交互学习产物 | AI × Web3 School

🔗 **在线预览**：[index.html](./index.html)（下载后在浏览器打开，或通过 GitHub Pages 访问）

---

## 🎯 我让 Agent 做了什么

向 Hermes Agent 发出以下指令：

> "基于 AI × Web3 School Handbook 的 Agent 章节内容，生成一个交互式概念卡片 + 小测验网页。包含 7 张可翻转的概念卡片和 5 道选择题。使用暗色主题、现代风格。"

Agent 反馈了以下内容：

1. **7 张概念卡片**：覆盖 Handbook 中 Agent 章节的 7 个核心知识节点
   - 什么是 Agent？、Tool Use（工具调用）、Planning（规划）、State（状态）、Reflection（反思）、Multi-Agent（多智能体）、AI × Web3 中的 Agent
2. **5 道交互式测验题**：每道题有 4 个选项、正确答案解释和进度指示
3. **完成后的得分反馈**

---

## 🖊️ 我手动改了什么

| 项目 | Agent 原始输出 | 人工调整 |
|------|---------------|----------|
| 概念卡片的详细描述 | 基于 Handbook 原文自动提取 | ✅ 确认与 [Handbook](https://aiweb3.school/zh/handbook/ai/agent/) 一致 |
| 测验题目的措辞 | Agent 自动生成 | ✅ 逐题检查，确保选项有区分度、解释准确 |
| 配色方案 | Agent 建议的暗色主题 | ✅ 保持原样，未做修改 |
| 页面结构 | Agent 自动布局 | ✅ 保持原样 |
| 整体审阅 | — | ✅ 通读全文确认无概念错误 |

---

## ⚠️ 哪些输出不可靠（或需要注意）

| 风险点 | 说明 |
|--------|------|
| 概念准确性 | Agent 提取的内容经过人工对比 Handbook 原文确认。但概念卡片是精简版，建议对照 [Handbook 原文](https://aiweb3.school/zh/handbook/ai/agent/) 深入阅读 |
| 测验覆盖度 | 5 道题远不能覆盖 Agent 全部知识点，仅作为入门自测 |
| 生成过程 | 整个 HTML 由 Agent 一次性生成，未做多轮迭代优化 |

---

## 📈 下一步改进

- [ ] 增加更多测验题（覆盖 Planning、Multi-Agent 等高级概念）
- [ ] 添加「AI × Web3 Agent 最小实践」交互演示（DAO 提案研究 Agent 模拟）
- [ ] 尝试用 Claude Code 或 Codex 对同一任务生成对比版本
- [ ] 部署到 GitHub Pages 供公开访问

---

## 📚 参考来源

- [AI × Web3 School Handbook — 智能体（Agent）](https://aiweb3.school/zh/handbook/ai/agent/)
- [WCB Week 1 学习任务](https://web3career.build/zh/programs/AI-Web3-School?tab=learning)

---

*生成时间：2026-05-22 | 工具：Hermes Agent (deepseek-v4-pro)*
