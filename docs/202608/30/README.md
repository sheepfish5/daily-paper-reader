# 日报 · 2026-08-30

- 最近生成时间：2026-08-30 23:16:46 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：34
- 精读区：22
- 速读区：12

## 今日简报（AI）
今日共读34篇论文，精读22篇、速读12篇，核心聚焦LLM推理效率与分布式系统优化。

最值得关注的两项高分工作：Minima-KV用混合格式分页注意力实现KV缓存压缩，ResiSpec通过残差分布塑造增强多候选投机采样，二者均达满分10分。

后续可优先深挖KV缓存压缩与投机采样的实际落地效果，再结合分布式推理带宽与通信的速读内容，构建更完整的推理优化视野。

## 精读区
1. [Minima-KV: Retention-Preserving KV Cache Compression with Mixed-Format Paged Attention](/202608/30/2608.23834v1-minima-kv-retention-preserving-kv-cache-compression-with-mixed-format-paged-attention) （10.0/10）
2. [ResiSpec: Enhancing Multi-Candidate Speculative Sampling via Residual Distribution Shaping](/202608/30/2608.24411v1-resispec-enhancing-multi-candidate-speculative-sampling-via-residual-distribution-shaping) （10.0/10）
3. [LLM4LLM: Bridging Kernel Benchmarks and Real Deployment via Closed-Loop Agentic Optimization](/202608/30/2608.21836v1-llm4llm-bridging-kernel-benchmarks-and-real-deployment-via-closed-loop-agentic-optimization) （9.0/10）
4. [NeuroPrefetcher: Storage-Aware Sparse LLM Inference via Delta Prefetching](/202608/30/2608.22643v1-neuroprefetcher-storage-aware-sparse-llm-inference-via-delta-prefetching) （9.0/10）
5. [WnW: Waxing-and-Waning KV Cache for Long-Form Speech LLMs](/202608/30/2608.22704v1-wnw-waxing-and-waning-kv-cache-for-long-form-speech-llms) （9.0/10）
6. [Sigmoid Attention as a Better Substrate for Learned KV Cache Eviction](/202608/30/2608.23296v1-sigmoid-attention-as-a-better-substrate-for-learned-kv-cache-eviction) （9.0/10）
7. [VIPER: Architecture-Aware Performance Modeling for Processing-in-Memory Design-Space Exploration](/202608/30/2608.23404v1-viper-architecture-aware-performance-modeling-for-processing-in-memory-design-space-exploration) （9.0/10）
8. [Elastic KV Cache for LLM Serving:A Working Reclamation Mechanism, and Why Chunked Prefill Already Closes the Gap](/202608/30/2608.23658v1-elastic-kv-cache-for-llm-servinga-working-reclamation-mechanism-and-why-chunked-prefill-already-closes-the-gap) （9.0/10）
9. [PuzzleKV: Page-Wise Low-Rank Decomposition for KV Cache Compression](/202608/30/2608.23843v1-puzzlekv-page-wise-low-rank-decomposition-for-kv-cache-compression) （9.0/10）
10. [More GPUs or a Smaller Cache? Tensor Parallelism versus KV Compression for Memory-Bound LLM Serving](/202608/30/2608.23962v1-more-gpus-or-a-smaller-cache-tensor-parallelism-versus-kv-compression-for-memory-bound-llm-serving) （9.0/10）
11. [AgentSpec: Speculative Decoding for Batch Inference of LLM Agents](/202608/30/2608.24004v1-agentspec-speculative-decoding-for-batch-inference-of-llm-agents) （9.0/10）
12. [VisCache: Visual KV Cache Pruning for Efficient Vision Large Language Model Inference](/202608/30/2608.24063v1-viscache-visual-kv-cache-pruning-for-efficient-vision-large-language-model-inference) （9.0/10）
13. [FAMPWQ: Fisher Information-based Adaptive Mixed Precision Weight Quantization for Effective LLM Inference](/202608/30/2608.24945v1-fampwq-fisher-information-based-adaptive-mixed-precision-weight-quantization-for-effective-llm-inference) （9.0/10）
14. [MacroAgent: Regularity-Aware Macro Legalization with LLM-Agent-Designed Contour Algorithms](/202608/30/2608.24946v1-macroagent-regularity-aware-macro-legalization-with-llm-agent-designed-contour-algorithms) （9.0/10）
15. [DataKernelBench: Can LLMs Optimize Database Queries on GPUs?](/202608/30/2608.25061v2-datakernelbench-can-llms-optimize-database-queries-on-gpus) （9.0/10）
16. [Hierarchical Shared Memory-Aware Optimization for TRSM on GPU Platforms](/202608/30/2608.25469v1-hierarchical-shared-memory-aware-optimization-for-trsm-on-gpu-platforms) （9.0/10）
17. [TOPAS: Workflow-Aware Prefix-State Scheduling for Multi-Agent LLM Serving](/202608/30/2608.25523v1-topas-workflow-aware-prefix-state-scheduling-for-multi-agent-llm-serving) （9.0/10）
18. [Goodput Maximization for Large Language Model Edge Inference: A Two-Phase Maskable PPO Approach](/202608/30/2608.25543v1-goodput-maximization-for-large-language-model-edge-inference-a-two-phase-maskable-ppo-approach) （9.0/10）
19. [Beyond Scaling: Self-Evolving LLM Agents for Hardware Kernel Optimization via an Experience-Driven Workflow and Experience Graph Memory](/202608/30/2608.25570v1-beyond-scaling-self-evolving-llm-agents-for-hardware-kernel-optimization-via-an-experience-driven-workflow-and-experience-graph-memory) （9.0/10）
20. [AsymSpec: Context-Asymmetric Speculative Decoding for Agentic LLMs](/202608/30/2608.26004v1-asymspec-context-asymmetric-speculative-decoding-for-agentic-llms) （9.0/10）
21. [VPP: Virtual Pipeline Parallelism for Efficient Chunked Prefill in Long-Context LLM Inference](/202608/30/2608.26523v1-vpp-virtual-pipeline-parallelism-for-efficient-chunked-prefill-in-long-context-llm-inference) （9.0/10）
22. [TwinKV: A Composable Repair Pass for KV Cache Eviction via Pairwise Key Redundancy](/202608/30/2608.27128v1-twinkv-a-composable-repair-pass-for-kv-cache-eviction-via-pairwise-key-redundancy) （9.0/10）

## 速读区
1. [When Does Distributed AI Inference Need More Wide-Area Bandwidth? A Co-Design Evaluation of Optical, Packet, and Software Levers](/202608/30/2608.14967v1-when-does-distributed-ai-inference-need-more-wide-area-bandwidth-a-co-design-evaluation-of-optical-packet-and-software-levers) （8.0/10）
2. [Collective Communication for Distributed LLM Systems: Planning, Runtime Adaptation, and Computation Coordination](/202608/30/2608.15118v1-collective-communication-for-distributed-llm-systems-planning-runtime-adaptation-and-computation-coordination) （8.0/10）
3. [LOCAL: Enabling Learning On-device Contiguously for Agent LLMs](/202608/30/2608.15241v1-local-enabling-learning-on-device-contiguously-for-agent-llms) （8.0/10）
4. [DeltaLog: Deferred Materialization of Recurrent States for Linear Attention Decoding](/202608/30/2608.15533v1-deltalog-deferred-materialization-of-recurrent-states-for-linear-attention-decoding) （8.0/10）
5. [Benchmarking Composable Compression Techniques in Mixture-of-Experts LLMs](/202608/30/2608.21693v1-benchmarking-composable-compression-techniques-in-mixture-of-experts-llms) （7.0/10）
6. [Architecting the Next Generation of Asynchronous, Distributed GPUs for the AI Era](/202608/30/2608.22602v1-architecting-the-next-generation-of-asynchronous-distributed-gpus-for-the-ai-era) （7.0/10）
7. [CAI-DLLM: Convergence Aware Inference for Diffusion Language Models](/202608/30/2608.22646v1-cai-dllm-convergence-aware-inference-for-diffusion-language-models) （7.0/10）
8. [Execution-Anchored Hallucination Calibration Reranking for Verilog Code Generation](/202608/30/2608.22938v1-execution-anchored-hallucination-calibration-reranking-for-verilog-code-generation) （7.0/10）
9. [NoTB: Oracle-Free Triage of LLM-Generated RTL via Cross-Model Formal Consensus](/202608/30/2608.21962v1-notb-oracle-free-triage-of-llm-generated-rtl-via-cross-model-formal-consensus) （6.0/10）
10. [SYNTLOG: FSM Benchmarks Evaluation for FPGA](/202608/30/2608.23288v1-syntlog-fsm-benchmarks-evaluation-for-fpga) （6.0/10）
11. [Selective Regenerative Decoding: Trajectory-Level Intervention for Inference-Time Reasoning](/202608/30/2608.24338v1-selective-regenerative-decoding-trajectory-level-intervention-for-inference-time-reasoning) （6.0/10）
12. [Maia 200: A Software Defined Dataflow System for Large-scale AI Acceleration](/202608/30/2608.24664v1-maia-200-a-software-defined-dataflow-system-for-large-scale-ai-acceleration) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
