# Juris & Edu Intelligence — 文档库 / Documentation

> 教育 AI SaaS 平台的**工程文档规范目录**。中文为主，术语保留英文。
> 品牌统一为 **Juris & Edu Intelligence**；对外域名 `jurisedu.com`。

## 目录规范 / Canonical taxonomy

工程级文档按下述编号目录**目标布局**组织（借鉴成熟仓库的编号+双语命名规范，单一事实来源 SSOT = 本仓库 Markdown）。当前首推提交把 **SSOT 工程文档 + 本索引**先落在 `docs/` 根，随原件补齐再分入编号子目录：

| 目标目录 | 用途 | 现状 |
|---|---|---|
| `docs/`（根） | 索引 + **总工程文档 SSOT** | ✅ `README.md`（本文件）+ `项目工程文档_v2.md` |
| `docs/20_PRODUCT_产品/` | 产品定位、Deck（中/英）、角色与撮合、Demo | 待补（见"外部制品"） |
| `docs/30_AI_TEACHING_AI教学/` | AI 互动教学（自适应辅导·决策理论框架）规格与论文 | 见工程文档 §4 + 论文 SSRN **7313338**（重投·审核中）/ Zenodo DOI |
| `docs/40_TIDAR_KAG/` | 可问责生成 TIDAR-KAG（域中立）规格与论文 | 见工程文档 §5 + 论文 SSRN **7311378** |
| `docs/50_COMPLIANCE_合规/` | PDPA / 未成年人 / 审计 / 隐私 | 见工程文档 §8 |
| `docs/90_ARCHIVE_存档/` | 历史版本（只读） | — |

## 单一事实来源 / SSOT

**`docs/项目工程文档_v2.md` 是全平台工程 SSOT**——它已把"所有需求与设计"整合为一份全量工程文档，并对 **AI 互动教学（§4）** 与 **TIDAR-KAG（§5）** 做工程级深挖，全文用 ✅已实现 / 🟡已设计 / 🎯目标值 三态严格标注（防幻觉）。其它文档不得与其冲突；如有更新，先改此文件。

## 关键工程约束（摘自工程文档 §0.2）

- 品牌只用 **Juris & Edu Intelligence**；不出现任何内部代号。
- **TIDAR-KAG 域中立**：不含任何特定行业专属内容；教育为主要落地实例。
- **机构教师无撮合**；仅**独立补习老师**有撮合 / 找学生。
- 学习者**单角色 + 三接入方式**（机构 / 独立自学 / 家长订购）。
- 一切业务/性能/财务数字标注 **🎯 目标值 / 演示口径**，不冒充实测。
- 专利仅表述为 **6 项候选发明（patent-pending）**。

## 外部制品 / External artifacts（不在本仓库或另有归属）

| 制品 | 位置 / 标识 |
|---|---|
| 交互 Demo（本平台演示） | 本仓库 `index.html`（部署于 `jurisedu.com`） |
| 论文：AI 教学形式化底座 —— *A Decision-Theoretic Framework for Adaptive Tutoring: Grounded Content Generation, Risk-Controlled Delivery, and Formal Guarantees* | SSRN Abstract ID **7313338**（重投·审核中）· 永久 DOI（Zenodo, concept）**10.5281/zenodo.22012570** |
| 论文：TIDAR-KAG（可问责生成形式化底座） | SSRN Abstract ID **7311378** |
| AI 教学论文 Zenodo 记录（Preprint · CC BY-NC-ND · Open） | https://zenodo.org/records/22012571 （本版本 DOI **10.5281/zenodo.22012571**） |
| AI 教学合成仿真复现代码 | GitHub `cndingbo2030/affect-adaptive-tutoring` |
| 产品 Deck（中/英）、v1 工程方案、SSRN 元数据等原件 | 见 §"补齐说明" |

> **AI 教学论文 ID 变更说明**：该论文原 SSRN Abstract ID **7311778** 因"投稿类型 / 平台范围"的**编辑筛查**被 SSRN 下架（明确说明*非*对论文质量的评判）。现已把标题/摘要**重定位**为决策理论 / 教育经济学定位（正文不变），并重新归类到 **Education Research Network**（教育技术 + 教育心理与认知）与 **Decision Science Research Network**（决策模型与工具 + 决策经济学）——**刻意避开上次很可能触发范围筛查的 AI / Information Systems 网络**——作为**全新提交** **7313338** 重投。同时已在 **Zenodo** 取得永久可引用 DOI，作为不受任何审查影响的引用底座。长期引用建议用 concept DOI `10.5281/zenodo.22012570`。

## 补齐说明 / To be added

产品 Deck（中/英）、v1 工程方案、两篇论文 PDF、SSRN 元数据等**二进制/长文原件**将陆续归入对应目录（`20_PRODUCT` / `30_AI_TEACHING` / `40_TIDAR_KAG`）。工程 SSOT（v2）已包含其**设计要点与形式化对齐**。
