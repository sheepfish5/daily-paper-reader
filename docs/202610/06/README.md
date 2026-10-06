# 日报 · 2026-10-06

- 最近生成时间：2026-10-06 01:25:08 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：23
- 精读区：11
- 速读区：12

## 今日简报（AI）
今日精选 23 篇论文，精读 11 篇、速读 12 篇，重点锁定循环 Transformer 自推测与多 Token 预测推理优化。最值得看的是《Shallow Queries, Mature Values》（9.0）与《Beneath the Tokens》（9.0），前者提出深度异步自推测加速循环 Transformer，后者系统剖析 GPU 上多 Token 预测的性能工程；速读中 MoE 推理、端侧流式与芯片宏布局也值得顺带一读。普通读者可先读这两篇精读文章了解推理加速思路，再按需延伸速读中的系统与硬件方向。

## 精读区
1. [Shallow Queries, Mature Values: Depth-Asynchronous Self-Speculation for Looped Transformers](/202610/06/2609.34538v1-shallow-queries-mature-values-depth-asynchronous-self-speculation-for-looped-transformers) （9.0/10）
2. [Beneath the Tokens: A Performance Engineering Study of Multi-Token Prediction in GPU-Accelerated LLM Inference](/202610/06/2609.35188v1-beneath-the-tokens-a-performance-engineering-study-of-multi-token-prediction-in-gpu-accelerated-llm-inference) （9.0/10）
3. [CORE: COverage CAlibration and Evicted-Mass REdistribution for KV Cache](/202610/06/2610.02235v1-core-coverage-calibration-and-evicted-mass-redistribution-for-kv-cache) （9.0/10）
4. [Design Space Exploration of Backside Clock Meshes for 2 nm GAAFET BSPDN Technology](/202610/06/2610.02401v1-design-space-exploration-of-backside-clock-meshes-for-2-nm-gaafet-bspdn-technology) （9.0/10）
5. [ServeTwin: A Benchmark-Validated Simulator for Distributed LLM Architecture Exploration](/202610/06/2610.02732v1-servetwin-a-benchmark-validated-simulator-for-distributed-llm-architecture-exploration) （9.0/10）
6. [BitNest: Bit-Nested Speculative Decoding for Memory-Efficient LLM Inference Acceleration](/202610/06/2610.02800v1-bitnest-bit-nested-speculative-decoding-for-memory-efficient-llm-inference-acceleration) （9.0/10）
7. [iS-KV: Online Low-Rank KV Cache Compression via Block-Incremental SVD](/202610/06/2610.02815v1-is-kv-online-low-rank-kv-cache-compression-via-block-incremental-svd) （9.0/10）
8. [SlimKV: Joint Token-Feature KV Cache Compression with Reconstruction-Free Beacon Attention](/202610/06/2610.02953v1-slimkv-joint-token-feature-kv-cache-compression-with-reconstruction-free-beacon-attention) （9.0/10）
9. [Tailoring the Quantization Space for 1-Bit KV Cache Compression](/202610/06/2610.03027v1-tailoring-the-quantization-space-for-1-bit-kv-cache-compression) （9.0/10）
10. [Page-EntroKV: Hardware-Aligned, Entropy-Weighted KV-Cache Eviction under Grouped-Query Attention](/202610/06/2610.03135v1-page-entrokv-hardware-aligned-entropy-weighted-kv-cache-eviction-under-grouped-query-attention) （9.0/10）
11. [AFORE: Attention-FFN Disaggregation with Overlapped Reconfiguration of Experts](/202610/06/2610.03203v1-afore-attention-ffn-disaggregation-with-overlapped-reconfiguration-of-experts) （9.0/10）

## 速读区
1. [Coarse-to-Fine Macro Placement via Evolutionary Search and Critical Macro Tuning](/202610/06/2609.34452v1-coarse-to-fine-macro-placement-via-evolutionary-search-and-critical-macro-tuning) （8.0/10）
2. [SPIMOE: Exploiting Hybrid Sparsity for Reasoning MoE Inference on Heterogeneous PIM Architectures](/202610/06/2609.34612v1-spimoe-exploiting-hybrid-sparsity-for-reasoning-moe-inference-on-heterogeneous-pim-architectures) （8.0/10）
3. [OmniTide: Co-Designing Algorithms and Systems for Efficient On-Device Omni-LLM Streaming](/202610/06/2609.34653v2-omnitide-co-designing-algorithms-and-systems-for-efficient-on-device-omni-llm-streaming) （8.0/10）
4. [Tool Waiting and Re-arrival in Compile-Time-Static LLM Serving: Cost Mechanisms and Configuration Selection](/202610/06/2609.34663v1-tool-waiting-and-re-arrival-in-compile-time-static-llm-serving-cost-mechanisms-and-configuration-selection) （8.0/10）
5. [EdgeCraft: Automated Model Crafting for Edge IoT](/202610/06/2609.35167v1-edgecraft-automated-model-crafting-for-edge-iot) （7.0/10）
6. [DisCoMBO: Steering Expert-in-the-Loop Black Box Optimization via Distributional Conformance](/202610/06/2609.36472v1-discombo-steering-expert-in-the-loop-black-box-optimization-via-distributional-conformance) （7.0/10）
7. [Purlin: Separating Orchestration from the Datapath of Collectives](/202610/06/2609.36954v1-purlin-separating-orchestration-from-the-datapath-of-collectives) （7.0/10）
8. [MEDEM: Multi-Engine DL Accelerator Design Methodology](/202610/06/2609.37399v1-medem-multi-engine-dl-accelerator-design-methodology) （7.0/10）
9. [Heddle: Learning Structural Templates for Parallelism Planning on Heterogeneous GPU Clusters](/202610/06/2609.34244v2-heddle-learning-structural-templates-for-parallelism-planning-on-heterogeneous-gpu-clusters) （6.0/10）
10. [WaveAlign: Cache-Aware Query-Row Scheduling for Sparse Attention in Long-Video Generation](/202610/06/2609.34814v1-wavealign-cache-aware-query-row-scheduling-for-sparse-attention-in-long-video-generation) （6.0/10）
11. [GUIDE-FBO: Guidance via Uncertainty Intervention and Distributional Exchange for Federated Bayesian Optimization](/202610/06/2609.35038v1-guide-fbo-guidance-via-uncertainty-intervention-and-distributional-exchange-for-federated-bayesian-optimization) （6.0/10）
12. [OptiCom : A Unified Framework for State-Conditioned Composition in LLM-Driven Optimization](/202610/06/2609.37221v1-opticom--a-unified-framework-for-state-conditioned-composition-in-llm-driven-optimization) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
