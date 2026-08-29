# 项目上下文 (Context Map): 缠论 108 课 LLM Wiki 知识库

## 1. 项目定位与目标
- **项目名称**：`chanlun-108-wiki`
- **定位**：基于缠中说禅《教你炒股票108课》构建的公理化量化交易与几何技术分析知识库。
- **架构**：采用 LLM Wiki 冷热物理隔离架构，结合 OKF 规范与 Obsidian 双向链接。

## 2. 核心领域模型与术语定义 (Domain Concepts)
- **K线包含 (K-line Inclusion)**：相邻K线极值重叠时的方向性合并处理。
- **分型 (Fractal)**：三根非包含K线构成的局部极值转折（顶分型 / 底分型）。
- **笔 (Stroke / Bi)**：顶底分型之间至少包含一根独立K线的最小几何连接段（至少5根有效K线）。
- **线段 (Line Segment / Duan)**：至少三笔重叠构成的结构，依据特征序列分型判定线段破坏。
- **走势中枢 (Trend Pivot / Zhongshu)**：某级别中至少三段连续次级别走势的重叠区间 $[ZD, ZG]$。
- **走势终完美 (Completeness Theorem)**：任何级别的任何走势类型终要完成。
- **背驰 (Divergence / Beichi)**：趋势离开段动能相对进入段发生衰竭，构成第一类买卖点的物理基础。
- **三类买卖点 (Three Classes of Buy/Sell Points)**：一买（背驰转折）、二买（回调确认）、三买（中枢破坏突破）。
- **区间套定理 (Nested Interval Theorem)**：跨级别逐级放大背驰段，精确定位买卖点极值。

## 3. 目录与文件布局
- `raw/`：冷层原始文档与图表（严禁日常检索扫描，保持只读纯真性）。
- `onewiki/`：热层提炼知识库（检索与学习的唯一入口）。
- `onewiki/index.md`：总图谱索引。
- `onewiki/concepts/`：核心理论公理与概念。
- `onewiki/summaries/`：108课逐课结构化摘要。
- `onewiki/entities/`：相关人物与指标实体。
