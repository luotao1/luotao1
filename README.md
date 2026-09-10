# 骆涛

### AI Infrastructure & Developer Technology Leader

**AI Systems · HPC · CPU/GPU Performance Optimization · AI Framework · Open Source · Developer Ecosystem · Technical Program**

> 我长期工作在 AI 基础设施、系统性能与开发者生态的交叉领域。  
> 从并行计算、CPU/GPU 性能优化，到 AI 推理引擎、AI Framework、CI/CD、开源治理与开发者生态，我的经历覆盖了从底层系统到开发者生态的完整技术链路。

**Open to opportunities across AI Infrastructure, Developer Technology, and Developer Ecosystem.**

---

# 个人简介

拥有**计算机博士背景和 10+ 年 AI Systems / Infrastructure 研发经验**，长期专注于：

**Parallel Computing、CPU/GPU Performance Optimization、AI Inference Engine、AI Framework、Developer Ecosystem 与 Technical Program。**

职业经历横跨从底层系统到开发者生态的完整技术链路：

**HPC / Parallel Computing → AI Performance → Inference Infrastructure → AI Framework → Open Source → Developer Ecosystem → Technical Program**

早期长期负责 CPU/GPU 算子、推理引擎和异构计算性能优化，主导或参与多个核心基础设施项目；后期逐步从纯技术 IC 延伸至**跨团队技术项目、开源治理、开发者增长、模型迁移、数据集与工具链建设**。

擅长在没有直接汇报关系的情况下推动跨组织技术协作，将复杂的底层技术问题转化为**可落地的工程方案、开发者能力和生态价值**。

希望探索 **AI Infrastructure、Developer Technology、Developer Ecosystem 与 AI-native Products** 的交叉领域，连接底层系统能力、开发者体验与技术生态，推动技术能力形成可规模化的产品与生态价值。

---

# 核心能力

**AI Infrastructure & Systems**  
CPU/GPU Performance Optimization · AI Operator / Kernel · AI Inference Engine · Graph Optimization · Heterogeneous Computing · Model Migration · Runtime / Toolchain · CI/CD & Engineering Infrastructure

**Developer Technology & Ecosystem**  
AI Framework Developer Experience · Open Source Governance · Developer Community · Developer Growth · Technical Enablement · Developer Tools & Benchmark · Open Dataset / Model Ecosystem · Cross-functional Technical Program · Influence Without Authority

**Languages & Technologies**  
C++ · Python · CUDA · CPU/GPU Architecture · AI Framework · CI/CD

---

# 工作经历

**百度资深研发工程师 / 技术项目负责人 · 2015–2026**

## 01 · 从底层性能优化到 AI Infrastructure

长期负责 AI Framework、Inference Engine 与底层计算性能优化，覆盖 CPU/GPU、Operator、Runtime、Graph 与多硬件适配。

- ERNIE 核心 GEMM 优化：**60ms → 34ms，性能提升 42.5%**
- Graph Conversion 优化：**15 min → 13 sec，约 70×**
- 深度参与 MKL / MKL-DNN 集成及指令级性能优化
- 建设 Runtime Cache、CPU/GPU Heterogeneous Computing 优化与核心 Operator 调优

## 02 · 跨组织技术协作：Intel × Paddle

负责 Intel × Paddle 跨组织技术合作，在无直接汇报关系的情况下推动中美多个技术团队协同。

- 推动 **50+ Core Operators** 的开发与优化
- 完成 **900+ 次 Code Review / Technical Collaboration**
- 协作团队规模从 **2 → 20+**
- 协同 **4 个全球技术团队、6 个 Paddle 版本**的资源、技术、版本与质量管理
- 建立跨团队 Technical Collaboration 机制，推动项目从技术方案走向实际落地

> 理解不同团队的目标 → 找到技术共同点 → 建立协作机制 → 推动项目真正落地。

## 03 · AI Engineering Infrastructure / CI/CD

负责 AI Framework Engineering Infrastructure、CI/CD、Benchmark 与质量体系建设，通过工程化手段提升研发效率与资源利用率。

- 建设 **20+ CI/CD Pipelines**
- CI Queue 等待时间：**24h → 2.5h**
- Hardware Cost 降低至原来的约 **20%**
- Compile Time 降低 **50%**
- Unit Test Time 降低 **40%**
- GPU CI 利用率：**~1% → 30%+**
- 建设 Benchmark、Quality Monitoring、Performance Gate 与 Automated Release 体系

> 关注的不只是“把代码跑起来”，而是通过 Engineering Infrastructure 持续衡量和优化研发效率、质量与性能。

## 04 · Paddle Developer Ecosystem 从 0 到 1

负责 Paddle Developer Ecosystem 建设，覆盖 Framework、Distributed Training、Inference、OCR、LLM Application、AI for Science 等方向。

- External PR 占比：**~1% → 44%**
- 累计 **674 位 Contributors**
- 培养约 **290 位 Core Developers**
- 建立 **5 级 Developer Growth Path**
- 组织 Hackathon、Developer Activities 及高校 / Open Source Community 合作
- 推动 **50+ 开发者**进入推荐及 Core Contributor 培养体系
- 创造年度 **1300+ 万元研发成本节省价值**

> 将 Framework 能力进一步转化为开发者能够**理解、使用、贡献和参与**的生态能力。

## 05 · Operator 开发标准化与生态治理

围绕 Operator 开发与维护建立系统化治理机制，从**规范设计 → 标准化 → 规模化推广**推动工程质量提升。

- **制定 Paddle Operator 开发与维护规范**，建立 **10+ 项开发及错误信息规范**
- 建设 Contributor Collaboration 机制，降低社区参与门槛
- 推动社区开发者完成 Paddle 2.5 → 3.0 大规模 Operator 开发及多硬件适配
- 推动社区开发者完成 Speculative Decoding、KV Cache 等 LLM Inference 能力建设
- 降低 Operator Adaptation 与长期 Maintenance Cost

## 06 · AI 数据、Benchmark 与模型工具链

建设面向 AI Coding、模型迁移与多语言场景的 Data、Benchmark 与 Toolchain。

- **GraphNet**：构建 **82K+ 真实模型 Graph**，用于 Coding Agent AI-assisted Kernel Generation；支持 Agent 自动提取，性能提升 **2–3×**，Token 消耗降低约 **90%**
- **Multilingual OCR Benchmark**：覆盖 **7 种少数民族语言、2.5K+ 图片、4K+ 标注**
- **X2Paddle**：支持 TensorFlow / ONNX / PyTorch / Caffe 等模型迁移，**125 个模型一键迁移，精度损失 ≤0.1%**

---

# 代表性开源项目

**[PaddlePaddle/Paddle](https://github.com/PaddlePaddle/Paddle)**  
核心 AI Framework。参与 Inference Performance Optimization、Operator Development & Standardization、CPU/GPU 及多硬件适配、CI/CD、Developer Experience 与 Open Source Collaboration。

**[PaddlePaddle/X2Paddle](https://github.com/PaddlePaddle/X2Paddle)**  
Model Migration 与 Developer Toolchain，支持 TensorFlow / ONNX / PyTorch / Caffe 等模型向 Paddle 迁移。

**[PaddlePaddle/GraphNet](https://github.com/PaddlePaddle/GraphNet)**  
面向 AI Coding 与 Kernel Generation 的真实模型 Graph 数据集与工具链，支持大规模模型结构分析与 AI-assisted Kernel Development。

**[PaddlePaddle/community](https://github.com/PaddlePaddle/community)**  
Paddle Open Source Governance、Contributor Collaboration、Developer Growth 与 Ecosystem 建设相关项目。

---

# 教育背景

**中国科学技术大学｜计算机科学与技术｜博士**  
2010–2015 · 并行计算模型与性能优化 · 导师：陈国良院士

**中国科学技术大学｜计算机科学与技术｜工学学士**  
2006–2010

---

# 荣誉与成果

- **百度杰出 Committer · 2025** — 第一届，全公司仅 16 人
- **百度 C++ Code Master · 2019** — 第一届，全公司不超过 20 人
- **开放原子基金会活力开源贡献者奖 · 2023**
- 第一作者专利 **4 项**，累计专利 **36 项**
- 博士学位论文：CNKI 引用 **50+**，下载 **7500+**

---
