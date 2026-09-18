# 日报 · 2026-09-18

- 最近生成时间：2026-09-18 22:06:31 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：11
- 精读区：6
- 速读区：5

## 今日简报（AI）
今日扫读 11 篇（精读 6、速读 5），重点落在 LLM 推理加速与 KV Cache、首 token 时延这两条硬骨头上。最值得看的是 MeshKV 用片上网络做 KV Cache 织构（9.0），以及 PrefixBench-H100 对 H100 上前缀复用与首 token 时延的实测刻画（9.0）。普通读者若时间有限，可先读这两篇的结论图，再顺带看 SiliconBench 对比统一内存桌面端的速度与显存取舍。

## 精读区
1. [MeshKV: A Network-on-Chip KV Cache Fabric for Scalable Transformer Decoding Accelerators](/202609/18/2609.19207v1-meshkv-a-network-on-chip-kv-cache-fabric-for-scalable-transformer-decoding-accelerators) （9.0/10）
2. [PrefixBench-H100: Characterizing Prefix Reuse and Time-to-First-Token in H100 LLM Serving](/202609/18/2609.19657v1-prefixbench-h100-characterizing-prefix-reuse-and-time-to-first-token-in-h100-llm-serving) （9.0/10）
3. [D-Quant: Driftable Entropy Coding for KV Cache Quantization](/202609/18/2609.19880v1-d-quant-driftable-entropy-coding-for-kv-cache-quantization) （9.0/10）
4. [SSD-LLaMA: SSD-Native Inference for Trillion-Parameter MoE at 1+ Token/s on a Consumer PC](/202609/18/2609.18110v1-ssd-llama-ssd-native-inference-for-trillion-parameter-moe-at-1-tokens-on-a-consumer-pc) （8.0/10）
5. [Token Latency Fairness: Performance Isolation for Multi-Tenant LLM Serving](/202609/18/2609.18112v1-token-latency-fairness-performance-isolation-for-multi-tenant-llm-serving) （8.0/10）
6. [HBFlex: A Flexible Memory System for Bridging Fine-Grained LLM States and Coarse-Grained HBF Parallel Execution](/202609/18/2609.18675v1-hbflex-a-flexible-memory-system-for-bridging-fine-grained-llm-states-and-coarse-grained-hbf-parallel-execution) （8.0/10）

## 速读区
1. [SiliconBench: Speed, Memory, and Fidelity for LLM Serving on Unified-Memory Desktops](/202609/18/2609.19169v1-siliconbench-speed-memory-and-fidelity-for-llm-serving-on-unified-memory-desktops) （7.0/10）
2. [Understanding and Exploiting Diagonal Attention Sparsity in Autoregressive Image Generation](/202609/18/2609.19702v1-understanding-and-exploiting-diagonal-attention-sparsity-in-autoregressive-image-generation) （7.0/10）
3. [CovR: Coverage-Aware Hardware Verification via Reasoning-Guided Reinforcement Learning](/202609/18/2609.19189v1-covr-coverage-aware-hardware-verification-via-reasoning-guided-reinforcement-learning) （6.0/10）
4. [Rosetta: Automating First-Principles Performance Modeling Using Multi-Agent LLMs](/202609/18/2609.19376v1-rosetta-automating-first-principles-performance-modeling-using-multi-agent-llms) （6.0/10）
5. [Bayesian Optimization with Rich Auxiliary Information via LLMs](/202609/18/2609.19437v1-bayesian-optimization-with-rich-auxiliary-information-via-llms) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
