# 日报 · 2026-08-23

- 最近生成时间：2026-08-23 20:10:29 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：32
- 精读区：20
- 速读区：12

## 今日简报（AI）
今日精读20篇、速读12篇，共处理32篇论文，重点关注GPU内核优化与边缘端MoE解码。  
最值得看的是满分论文《KernelArc》的多智能体GPU内核优化框架，以及9分的《S2-MoE》边缘设备自推测解码方案。  
下一步建议优先深入KernelArc，同时留意LLM在硬件设计（Verilog/DRC）中的自动化应用趋势。

## 精读区
1. [KernelArc: A Multi-Agent Framework for GPU Kernel Optimization](/202608/23/2608.17071v1-kernelarc-a-multi-agent-framework-for-gpu-kernel-optimization) （10.0/10）
2. [S2-MoE: Enabling Efficient Self-Speculative Decoding for Mixture-of-Experts on Edge Devices](/202608/23/2608.15018v2-s2-moe-enabling-efficient-self-speculative-decoding-for-mixture-of-experts-on-edge-devices) （9.0/10）
3. [P-PAS: Prefill-Pressure Adaptive Scheduling for Long-Context LLM Serving](/202608/23/2608.15171v1-p-pas-prefill-pressure-adaptive-scheduling-for-long-context-llm-serving) （9.0/10）
4. [Every Expert Counts: ExactMoE for Memory-Efficient W4A16 Inference](/202608/23/2608.15383v1-every-expert-counts-exactmoe-for-memory-efficient-w4a16-inference) （9.0/10）
5. [Q-First: Most of Attention Needs Only the Query in Disaggregated LLM Decoding](/202608/23/2608.15473v2-q-first-most-of-attention-needs-only-the-query-in-disaggregated-llm-decoding) （9.0/10）
6. [SchurQuant: Groupwise Discrete Optimization for Layer-Wise LLM Quantization](/202608/23/2608.15567v1-schurquant-groupwise-discrete-optimization-for-layer-wise-llm-quantization) （9.0/10）
7. [GraniKV: Asymmetric Granularity KV-Cache Paging for Multi-Agent Systems with Long Shared Prefix](/202608/23/2608.15584v1-granikv-asymmetric-granularity-kv-cache-paging-for-multi-agent-systems-with-long-shared-prefix) （9.0/10）
8. [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](/202608/23/2608.16157v1-freetoken-efficient-edge-native-moe-serving-with-bandwidth-adaptive-execution) （9.0/10）
9. [Beyond Binary Priorities: Multi-Tier SLA Scheduling for Large Language Model Serving](/202608/23/2608.16336v1-beyond-binary-priorities-multi-tier-sla-scheduling-for-large-language-model-serving) （9.0/10）
10. [Pallas: A Proactive KV Cache Migration Framework for LLM Inference in AI-RAN](/202608/23/2608.16477v1-pallas-a-proactive-kv-cache-migration-framework-for-llm-inference-in-ai-ran) （9.0/10）
11. [GoalEvolve: From Handcrafted Algorithm Priors to Goal-Driven Evolution of Physical Design Algorithms](/202608/23/2608.16733v1-goalevolve-from-handcrafted-algorithm-priors-to-goal-driven-evolution-of-physical-design-algorithms) （9.0/10）
12. [TileMix: Tile-Centric Mixed-Precision Attention for LLM Inference Acceleration](/202608/23/2608.17336v1-tilemix-tile-centric-mixed-precision-attention-for-llm-inference-acceleration) （9.0/10）
13. [PTXBench: Benchmark and Adapt LLMs for GPU Kernel Optimization with Architecture-specific PTX](/202608/23/2608.17379v2-ptxbench-benchmark-and-adapt-llms-for-gpu-kernel-optimization-with-architecture-specific-ptx) （9.0/10）
14. [MoNe: Modular Neural Memory for Efficient Long Context Inference](/202608/23/2608.17616v1-mone-modular-neural-memory-for-efficient-long-context-inference) （9.0/10）
15. [Bounded-State Restoration: Decoupling Local Restore Capacity from External LLM State](/202608/23/2608.17826v1-bounded-state-restoration-decoupling-local-restore-capacity-from-external-llm-state) （9.0/10）
16. [HYDRA: A Heterogeneous Chiplet DSE Framework for Serving Dynamic Hybrid LLM Workloads](/202608/23/2608.19395v1-hydra-a-heterogeneous-chiplet-dse-framework-for-serving-dynamic-hybrid-llm-workloads) （9.0/10）
17. [ReCache: Efficient KV Cache Reuse and Compression for Tool-Augmented LLM Agents](/202608/23/2608.19662v1-recache-efficient-kv-cache-reuse-and-compression-for-tool-augmented-llm-agents) （9.0/10）
18. [CacheRoute: Planned Prefix-Affinity Routing for Large-Scale LLM Serving](/202608/23/2608.19677v1-cacheroute-planned-prefix-affinity-routing-for-large-scale-llm-serving) （9.0/10）
19. [LLMs as Acquisition Policies for Finite-Pool Materials Optimization: A Controlled Study](/202608/23/2608.19790v1-llms-as-acquisition-policies-for-finite-pool-materials-optimization-a-controlled-study) （9.0/10）
20. [Learning how to Forget: Fine-tuning for Long-Context Sparse Attention](/202608/23/2608.19920v1-learning-how-to-forget-fine-tuning-for-long-context-sparse-attention) （9.0/10）

## 速读区
1. [Fast Iterative Dual-Output-Aware LUT Mapping for Fracturable FPGA Architectures](/202608/23/2607.22756v1-fast-iterative-dual-output-aware-lut-mapping-for-fracturable-fpga-architectures) （8.0/10）
2. [Benchmarking LLMs for Verilog Design Flows](/202608/23/2607.22759v1-benchmarking-llms-for-verilog-design-flows) （8.0/10）
3. [DRC-Aid: Design-Rule Correction via Agentic Framework utilizing Inference-Time Large Language Models](/202608/23/2607.22761v1-drc-aid-design-rule-correction-via-agentic-framework-utilizing-inference-time-large-language-models) （8.0/10）
4. [Application-Driven Architecture Exploration for Cross-Layer Heterogeneous Systems](/202608/23/2607.23042v1-application-driven-architecture-exploration-for-cross-layer-heterogeneous-systems) （8.0/10）
5. [BOCoDe: Engineering-Centered Benchmarking for Bayesian Optimization](/202608/23/2608.15073v1-bocode-engineering-centered-benchmarking-for-bayesian-optimization) （7.0/10）
6. [Anatomy of a Quantized Agent: VRAM Stability and Forecasting in Code-Synthesis Agentic Workloads](/202608/23/2608.15117v1-anatomy-of-a-quantized-agent-vram-stability-and-forecasting-in-code-synthesis-agentic-workloads) （7.0/10）
7. [From LLM Inference to Agentic Workloads: Characterization and Implications for Serving Systems](/202608/23/2608.15127v1-from-llm-inference-to-agentic-workloads-characterization-and-implications-for-serving-systems) （7.0/10）
8. [COOL: A Cooling-Aware Point Transformer Framework for Thermal Prediction in Advanced 3D/3.5D IC Packaging](/202608/23/2608.15890v1-cool-a-cooling-aware-point-transformer-framework-for-thermal-prediction-in-advanced-3d35d-ic-packaging) （7.0/10）
9. [KV-Pipe: On the Relation Between KV Sharing and Pipeline Parallel Efficiency in LLMs](/202608/23/2608.15943v1-kv-pipe-on-the-relation-between-kv-sharing-and-pipeline-parallel-efficiency-in-llms) （6.0/10）
10. [DeepOHeat-v2: Self-Improving Operator Learning for Fast and Trustworthy Thermal Optimization in 3D-IC Design](/202608/23/2608.16080v1-deepoheat-v2-self-improving-operator-learning-for-fast-and-trustworthy-thermal-optimization-in-3d-ic-design) （6.0/10）
11. [ExaModels.jl: an Algebraic Modeling System for Nonlinear Programming on GPUs](/202608/23/2608.16265v1-examodelsjl-an-algebraic-modeling-system-for-nonlinear-programming-on-gpus) （6.0/10）
12. [Hybrid ML for Lightweight Pre-Route Delay Estimation in Open-Source IC Design](/202608/23/2608.17914v1-hybrid-ml-for-lightweight-pre-route-delay-estimation-in-open-source-ic-design) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
