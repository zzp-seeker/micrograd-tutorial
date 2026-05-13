# 深度教学站点

> AI 生成的代码仓库 + 论文深度讲解合集。每篇都包含 Feynman 风格的解释、数学推导、Mermaid 架构图、源码逐行引用，以及作者主观的专业见解。

## 教程目录

### 📦 GitHub 仓库教程

| 项目 | 简介 | 深度 |
|---|---|---|
| **[karpathy/micrograd](micrograd_overview.md)** | 极简自动微分引擎 + 神经网络库（100 行 + 50 行）。理解 PyTorch 底层原理的最佳入门 | 7 章 |

### 📄 论文深度讲解

| 论文 | 会议/年份 | 核心贡献 | 深度 |
|---|---|---|---|
| **[Tree of Thoughts](papers/2305.10601/index.md)** | NeurIPS 2023 | 把 LLM 当成 BFS/DFS 里的生成器 + 评估器，Game of 24 把成功率从 4% 推到 74% | 5 章 |

## 生成工具

这些教程由两个本地 Claude Code skill 自动生成：

- **[`repo-to-tutorial`](https://github.com/zzp-seeker/micrograd-tutorial)** —— GitHub 仓库 → 教学站点
- **[`paper-to-tutorial`](https://github.com/zzp-seeker/micrograd-tutorial)** —— 学术论文 + 其源码 → 教学站点

两个 skill 共享 MkDocs-Material 构建流程，都用 Claude 作为 LLM 后端。详见 [README](https://github.com/zzp-seeker/micrograd-tutorial)。

## 风格说明

每篇教程都遵循：

- **深入浅出**：抽象概念用工厂、汇率、棋类等生活化比喻引入
- **数学严谨**：LaTeX 公式 + 推导，遵守变量记号一致性
- **源码可追**：每个代码引用 pin 到具体 commit SHA + 行号
- **观点鲜明**：💡 个人见解段落必须给出 Level-2+ 的判断 / 取舍 / 洞察，不堆套话
- **zero-loss**：论文里每张图都嵌入站点，每段实验数据都进表格

---

**生成日期**：2026-05-13 · **生成工具仓库**：[zzp-seeker/micrograd-tutorial](https://github.com/zzp-seeker/micrograd-tutorial)
