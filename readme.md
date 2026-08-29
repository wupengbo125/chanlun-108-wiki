# 缠论《教你炒股票108课》LLM Wiki 知识库

> 🚀 **Chanlun 108 Lessons Knowledge Base**  
> 基于**缠中说禅《教你炒股票108课》**原文及配图，融合 **LLM Wiki** 与 **OKF (Open Knowledge Format)** 规范打造的深度结构化知识资产库。

---

## 🌟 核心特色

1. **冷热物理隔离架构**：
   - **冷层 (`raw/`)**：永久存档 108 课完整原始文稿及 43 幅原版图解，保持历史真相一字不改。
   - **热层 (`onewiki/`)**：AI 深度提炼的 19 个核心概念、3 个关键实体、108 课精要摘要及总图谱索引。
2. **Obsidian 原生双链连通**：
   - 完美适配 Obsidian 双向链接 `[[...]]` 与图谱视图（Graph View）。
   - 每篇摘要均包含一键直达原始 Markdown 文件的源文双链（`[[../../raw/...]]`）。
3. **公理化知识体系**：
   - 严格覆盖形态学（K线包含 $	o$ 分型 $	o$ 笔 $	o$ 线段 $	o$ 中枢 $	o$ 走势类型）、动力学（背驰 $	o$ MACD辅助 $	o$ 区间套 $	o$ 小转大）、买卖点完备性定理、资金管理与市场哲学。

---

## 📁 目录结构

```text
chanlun-108-wiki/
├── readme.md                     # 项目主文档与使用指南
├── one-context.md                # 统一上下文与领域术语表
├── AGENTS.md                     # AI 协作与宪法守则
├── CLAUDE.md
├── raw/                          # 🧊【冷层】108课完整原文与原图
│   ├── pic/                      # 原文图解配图 (43幅)
│   ├── 001-教你炒股票1_不会赢钱的经济人_只是废人.md
│   └── ...
│   └── 108-教你炒股票108_何谓底部从月线看中期走势演化.md
└── onewiki/                      # ⚡【热层】知识图谱与概念词条
    ├── index.md                  # 🗺️ 知识库总地图与分类大纲
    ├── log.md                    # 📜 知识库演化与编译日志
    ├── concepts/                 # 📍 核心概念深度解析 (19篇)
    │   ├── k-line-inclusion.md
    │   ├── fractal-patterns.md
    │   ├── stroke-definition.md
    │   ├── line-segment.md
    │   ├── trend-pivot.md
    │   ├── trend-divergence.md
    │   ├── three-classes-of-buy-sell-points.md
    │   ├── nested-interval-locating.md
    │   └── ...
    ├── summaries/                # 📍 108课逐课精编摘要 (108篇)
    │   ├── summary-lesson-001.md
    │   └── ...
    └── entities/                 # 📍 关联实体 (缠中说禅, MACD, 均线系统)
        ├── chanzhongshuozhan.md
        ├── macd-indicator.md
        └── moving-average-system.md
```

---

## 🔍 快速上手与阅读

1. **Obsidian 推荐打开**：直接将本仓库根目录作为 Obsidian 库（Vault）打开，即可享受完整的双链跳转与知识星空图谱。
2. **知识总索引**：打开 `onewiki/index.md`，按五维体系（形态学、动力学、买卖点、风控策略、市场哲学）系统学习。
3. **查阅原文**：在任意概念或摘要页顶部，点击 `[[../../raw/...]]` 即可无缝调出原始博文全文。

---

## 📜 版权与致敬

本知识库原文内容版权归原作者 **缠中说禅** 所有。本项目仅用于个人学习、学术研究与知识工程沉淀。
