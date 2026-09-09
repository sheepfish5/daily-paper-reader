# 日报 · 2026-09-09

- 最近生成时间：2026-09-09 22:24:13 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：25
- 精读区：13
- 速读区：12

## 今日简报（AI）
今日精读13篇、速读12篇，重点聚焦端侧多任务大模型内存管理与异构GPU并发推理调度。

最值得关注的是两篇9.0分工作：`mzCache` 面向多任务场景优化设备端LLM内存复用；MeanField代理模型则提升共享GPU上并发AI推理的运行时调度可扩展性。

若想紧跟前沿，可优先浏览这两篇高分论文，并顺带扫读AI代理硬件设计、混合精度量化等8分速读文章以扩展视野。

## 精读区
1. [mzCache: On-Device LLM Memory Management under Multitasking](/202609/09/2609.01338v1-mzcache-on-device-llm-memory-management-under-multitasking) （9.0/10）
2. [MeanField Surrogate Modeling for Scalable Runtime Scheduling of Concurrent Heterogeneous AI Inference on Shared GPUs](/202609/09/2609.02109v1-meanfield-surrogate-modeling-for-scalable-runtime-scheduling-of-concurrent-heterogeneous-ai-inference-on-shared-gpus) （9.0/10）
3. [Latency-Aware Orchestration for Multi-Agent LLM Workflows on Heterogeneous GPUs](/202609/09/2609.03335v1-latency-aware-orchestration-for-multi-agent-llm-workflows-on-heterogeneous-gpus) （9.0/10）
4. [LevelSyn: Physical-Aware Logic Synthesis via Level-Asynchronous Graph Neural Networks](/202609/09/2609.03594v1-levelsyn-physical-aware-logic-synthesis-via-level-asynchronous-graph-neural-networks) （9.0/10）
5. [ACE: Adaptive Calibration-Free Expert Skipping for MoE-based LLMs](/202609/09/2609.05228v1-ace-adaptive-calibration-free-expert-skipping-for-moe-based-llms) （9.0/10）
6. [Interface-Aware KV Cache Quantization for Dense On-Chip NVM in Long-Context LLM Decoding](/202609/09/2609.05764v1-interface-aware-kv-cache-quantization-for-dense-on-chip-nvm-in-long-context-llm-decoding) （9.0/10）
7. [CMD: An Integrated CGRA Framework with Cluster-Based Distributed Memory Design](/202609/09/2609.05982v1-cmd-an-integrated-cgra-framework-with-cluster-based-distributed-memory-design) （9.0/10）
8. [DFlow: Enabling Verifier Information Flow in Block Diffusion Speculative Decoding](/202609/09/2609.06498v1-dflow-enabling-verifier-information-flow-in-block-diffusion-speculative-decoding) （9.0/10）
9. [ECOKV: Geometry-Aware KV Cache Eviction via Complementary Diversity Metrics](/202609/09/2609.06663v1-ecokv-geometry-aware-kv-cache-eviction-via-complementary-diversity-metrics) （9.0/10）
10. [Unified AI Gateway: A Framework for Joint Model Routing and KV Cache Management](/202609/09/2609.06940v1-unified-ai-gateway-a-framework-for-joint-model-routing-and-kv-cache-management) （9.0/10）
11. [Deadline-Aware Adaptive Prefill Chunking for Efficient Large Language Model Serving](/202609/09/2609.07883v1-deadline-aware-adaptive-prefill-chunking-for-efficient-large-language-model-serving) （9.0/10）
12. [MetaKV: Adaptive KV Cache Compression for Constrained LLM Inference](/202609/09/2609.07966v1-metakv-adaptive-kv-cache-compression-for-constrained-llm-inference) （9.0/10）
13. [Jacap: Robust KV Cache Eviction via Jacobian-Based Nonlinear Information Capacity Preservation](/202609/09/2609.08131v1-jacap-robust-kv-cache-eviction-via-jacobian-based-nonlinear-information-capacity-preservation) （9.0/10）

## 速读区
1. [Benchmarking AI Agents for Hardware Design Automation via MCP Tool Calling](/202609/09/2608.26199v1-benchmarking-ai-agents-for-hardware-design-automation-via-mcp-tool-calling) （8.0/10）
2. [DAMP: Decay-Aware Mixed-Precision Recurrent-State Quantization](/202609/09/2608.27513v1-damp-decay-aware-mixed-precision-recurrent-state-quantization) （8.0/10）
3. [From Generation to Discovery: Diffusion Mutation Kernels for Circuit and Physical Design](/202609/09/2608.27649v1-from-generation-to-discovery-diffusion-mutation-kernels-for-circuit-and-physical-design) （8.0/10）
4. [Parser States Already Know: Structure-Conditioned KV Persistence for Structured Generation](/202609/09/2608.28276v1-parser-states-already-know-structure-conditioned-kv-persistence-for-structured-generation) （8.0/10）
5. [Scaling Inference Prefill with High-Radix Photonic Interconnects](/202609/09/2609.01821v1-scaling-inference-prefill-with-high-radix-photonic-interconnects) （7.0/10）
6. [FlowTT: Exploiting Computation Flow Reuse in Irregular Tensor-Train Embedding](/202609/09/2609.03459v1-flowtt-exploiting-computation-flow-reuse-in-irregular-tensor-train-embedding) （7.0/10）
7. [MaxKernel: Agentic Kernel Generation for TPUs](/202609/09/2609.04523v1-maxkernel-agentic-kernel-generation-for-tpus) （7.0/10）
8. [Toward Sustainable Distributed LLM Inference: A Systems Synthesis and Research Agenda for an Energy-, Carbon-, and Cache-Aware llm-d Control Plane](/202609/09/2609.05565v1-toward-sustainable-distributed-llm-inference-a-systems-synthesis-and-research-agenda-for-an-energy--carbon--and-cache-aware-llm-d-control-plane) （7.0/10）
9. [SPD: Single Pass Decoding for Generative Reranking](/202609/09/2609.01807v2-spd-single-pass-decoding-for-generative-reranking) （6.0/10）
10. [Semantics-Guided Automatic Tensorization for Multiobjective Evolutionary Algorithms: A Multi-Agent Framework](/202609/09/2609.02387v1-semantics-guided-automatic-tensorization-for-multiobjective-evolutionary-algorithms-a-multi-agent-framework) （6.0/10）
11. [No-Regret Bayesian Optimization with Finite-Library Input-Warped Kernels](/202609/09/2609.02993v1-no-regret-bayesian-optimization-with-finite-library-input-warped-kernels) （6.0/10）
12. [RAGMark: A Comprehensive Framework for Benchmarking Retrieval-Augmented Generation Systems](/202609/09/2609.05760v1-ragmark-a-comprehensive-framework-for-benchmarking-retrieval-augmented-generation-systems) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
