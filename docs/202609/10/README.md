# 日报 · 2026-09-10

- 最近生成时间：2026-09-10 21:38:01 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：19
- 精读区：7
- 速读区：12

## 今日简报（AI）
今天筛完19篇论文，精读7篇、速读12篇，重点落在LLM推理系统、多轮对话调度与MoE优化三条线上。  
最值得看的是两篇9.0分：一篇用平均场渐近和命中率近似分析LRU策略下的多轮LLM对话，另一篇AMEND用审计边距在GPU-PIM解码中实现非阻塞丢弃；速读中DynaNDE、PCoMoE等8.0分工作也集中在MoE专家调度、路径组合与计算通信重叠。  
普通读者可先读两篇9.0分抓核心结论，再顺着MoE推理优化扫一遍8.0分速读，建立“调度+资源重叠”的系统视角。

## 精读区
1. [Multi-Turn LLM Conversations under the Least-Recently-Used Policy: Mean-Field Asymptotics and Hit Ratio Approximation](/202609/10/2609.02027v1-multi-turn-llm-conversations-under-the-least-recently-used-policy-mean-field-asymptotics-and-hit-ratio-approximation) （9.0/10）
2. [AMEND: Audited Margins Enable Nonblocking Drops in GPU-PIM LLM Decoding](/202609/10/2609.09823v1-amend-audited-margins-enable-nonblocking-drops-in-gpu-pim-llm-decoding) （9.0/10）
3. [DASC: Decay-Aware State Compression for Hybrid Linear-Attention Serving](/202609/10/2608.30386v1-dasc-decay-aware-state-compression-for-hybrid-linear-attention-serving) （8.0/10）
4. [LLM-based Hardware Development with Hierarchical IRs and End-to-End Multi-Agent Workflow](/202609/10/2608.30659v1-llm-based-hardware-development-with-hierarchical-irs-and-end-to-end-multi-agent-workflow) （8.0/10）
5. [Unlocking Lossless Speedups in LLMs via Discrete Diffusion](/202609/10/2609.04010v1-unlocking-lossless-speedups-in-llms-via-discrete-diffusion) （8.0/10）
6. [Characterizing Contention-Induced Reliability Collapse in KV-Cache Timing Side Channels for Multi-Tenant LLM Serving](/202609/10/2609.06853v1-characterizing-contention-induced-reliability-collapse-in-kv-cache-timing-side-channels-for-multi-tenant-llm-serving) （8.0/10）
7. [Benchmarking Agentic HLS Design Tasks With HLS-Eval](/202609/10/2609.09526v1-benchmarking-agentic-hls-design-tasks-with-hls-eval) （8.0/10）

## 速读区
1. [DynaNDE: Dynamic Near-Data Expert Scheduling for Batched MoE Inference](/202609/10/2609.00407v1-dynande-dynamic-near-data-expert-scheduling-for-batched-moe-inference) （8.0/10）
2. [PCoMoE: Shifting MoE Inference from Monolithic Expert Selection to Fine-Grained Path Composition](/202609/10/2609.01024v1-pcomoe-shifting-moe-inference-from-monolithic-expert-selection-to-fine-grained-path-composition) （8.0/10）
3. [Analytical Resource Management for Fine-grained MoE Computation-Communication Overlap](/202609/10/2609.07536v1-analytical-resource-management-for-fine-grained-moe-computation-communication-overlap) （8.0/10）
4. [Do Dynamic Routers Need Memory? HeRo: History-Aware Routing for Efficient LLM Inference](/202609/10/2609.08189v1-do-dynamic-routers-need-memory-hero-history-aware-routing-for-efficient-llm-inference) （8.0/10）
5. [LeanStream: A Speculate-and-Refine Streaming Framework for Efficient on-Device LLM Inference](/202609/10/2609.03079v1-leanstream-a-speculate-and-refine-streaming-framework-for-efficient-on-device-llm-inference) （7.0/10）
6. [All for 1-Bit: Towards Genuine 1-Bit Post-Training Quantization for LLMs](/202609/10/2609.06161v1-all-for-1-bit-towards-genuine-1-bit-post-training-quantization-for-llms) （7.0/10）
7. [AutoUVM: Automated Prefetching Framework for LLMs under UVM Oversubscription](/202609/10/2609.06172v1-autouvm-automated-prefetching-framework-for-llms-under-uvm-oversubscription) （7.0/10）
8. [EStream: Fast and Memory-Efficient MoE Prefill through Expert Virtualization on Mobile NPUs](/202609/10/2609.06551v1-estream-fast-and-memory-efficient-moe-prefill-through-expert-virtualization-on-mobile-npus) （7.0/10）
9. [Cache-Aware Joint Router Adaptation for Memory-Efficient MoE Inference](/202609/10/2609.04895v1-cache-aware-joint-router-adaptation-for-memory-efficient-moe-inference) （6.0/10）
10. [Robustness of LLM-Generated SystemVerilog Assertions to Semantics-Preserving RTL Transformations](/202609/10/2609.05658v1-robustness-of-llm-generated-systemverilog-assertions-to-semantics-preserving-rtl-transformations) （6.0/10）
11. [A Measurement Study of LLM Inference Trade-offs Across Edge Continuum Hardware](/202609/10/2609.08307v1-a-measurement-study-of-llm-inference-trade-offs-across-edge-continuum-hardware) （6.0/10）
12. [Tools-CC-Bench: a Benchmark Suite for Collective Communication with Compression in HPC and AI Workloads](/202609/10/2609.08739v1-tools-cc-bench-a-benchmark-suite-for-collective-communication-with-compression-in-hpc-and-ai-workloads) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
