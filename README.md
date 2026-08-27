# LLM Paper List

Reading checklist for LLM papers.

## Foundations and Transformers

- [ ] [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## Normalization and Training Stability

- [ ] [Layer Normalization](https://arxiv.org/abs/1607.06450)
- [ ] [Root Mean Square Layer Normalization](https://arxiv.org/abs/1910.07467)
- [ ] [On Layer Normalization in the Transformer Architecture](https://arxiv.org/abs/2002.04745)
- [ ] [Understanding the Difficulty of Training Transformers](https://arxiv.org/abs/2004.08249)

## Optimization and Pretraining

- [ ] [Muon: An optimizer for hidden layers in neural networks](https://kellerjordan.github.io/posts/muon/)
- [ ] [Deriving Muon](https://jeremybernste.in/writing/deriving-muon)
- [ ] [Old Optimizer, New Norm: An Anthology](https://arxiv.org/abs/2409.20325)
- [ ] [Muon is Scalable for LLM Training](https://arxiv.org/abs/2502.16982)
- [ ] [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534)
- [ ] [SOAP, Muon, and Beyond: Pushing LLM Pretraining Scales](https://arxiv.org/abs/2607.20548)

## State Space Models

- [ ] [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752)

## Efficient Attention Architectures

- [ ] [Transformers Are RNNs: Fast Autoregressive Transformers with Linear Attention](https://arxiv.org/abs/2006.16236)
- [ ] [A Survey of Linear Attention: Algorithm, Theory, Application, and Infrastructure](https://openreview.net/forum?id=ilkVX8aGmQ)
- [ ] [Kimi Linear: An Expressive, Efficient Attention Architecture](https://doi.org/10.48550/arXiv.2510.26692)
- [ ] [Gated Linear Attention Transformers with Hardware-Efficient Training](https://arxiv.org/abs/2312.06635)
- [ ] [Parallelizing Linear Transformers with the Delta Rule over Sequence Length](https://doi.org/10.48550/arXiv.2406.06484)
- [ ] [Erase-then-Delta Attention: Decoupling Erase and Write Addresses in Delta-Rule Linear Attention](https://doi.org/10.48550/arXiv.2606.26560)
- [ ] [Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models](https://doi.org/10.48550/arXiv.2401.04658)
- [ ] [Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention](https://doi.org/10.48550/arXiv.2405.17381)

## Long Context Attention and Retrieval

- [ ] [IndexCache: Accelerating Sparse Attention via Cross-Layer Index Reuse](https://ar5iv.labs.arxiv.org/html/2603.12201)
- [ ] [Ring Attention with Blockwise Transformers for Near-Infinite Context](https://arxiv.org/abs/2310.01889)

## Long Context Training Recipes

- [ ] [LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models](https://arxiv.org/abs/2309.12307)
- [ ] [LongAlign: A Recipe for Long Context Alignment of Large Language Models](https://arxiv.org/abs/2401.18058)

## Position Encoding and Context Extension

- [ ] [Extending Context Window of Large Language Models via Positional Interpolation](https://arxiv.org/abs/2306.15595)
- [ ] [YaRN: Efficient Context Window Extension of Large Language Models](https://arxiv.org/abs/2309.00071)

## AI Compiler and Kernel Programming

- [ ] [TileLang: A Composable Tiled Programming Model for AI Systems](https://arxiv.org/abs/2504.17577)

## Automatic Parallelization

- [ ] [GSPMD: General and Scalable Parallelization for ML Computation Graphs](https://arxiv.org/abs/2105.04663)
- [ ] [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://arxiv.org/abs/2201.12023)
- [ ] [nnScaler: Constraint-Guided Parallelization Plan Generation for Deep Learning Training](https://www.usenix.org/system/files/osdi24-lin-zhiqi.pdf)

## FlashAttention / Attention Kernel

- [ ] [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://doi.org/10.48550/arXiv.2205.14135)
- [ ] [FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning](https://doi.org/10.48550/arXiv.2307.08691)
- [ ] [FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision](https://doi.org/10.48550/arXiv.2407.08608)
- [ ] [FlashAttention-4: Algorithm and Kernel Pipelining Co-Design for Asymmetric Hardware Scaling](https://doi.org/10.48550/arXiv.2603.05451)

## Speculative Decoding

- [ ] [EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty](https://doi.org/10.48550/arXiv.2401.15077)
- [ ] [EAGLE-2: Faster Inference of Language Models with Dynamic Draft Trees](https://doi.org/10.48550/arXiv.2406.16858)
- [ ] [EAGLE-3: Scaling up Inference Acceleration of Large Language Models via Training-Time Test](https://doi.org/10.48550/arXiv.2503.01840)
- [ ] [DFlash: Block Diffusion for Flash Speculative Decoding](https://doi.org/10.48550/arXiv.2602.06036)
- [ ] [When Hidden States Drift: Can KV Caches Rescue Long-Range Speculative Decoding?](https://doi.org/10.48550/arXiv.2604.26412)

## Model Architecture

- [ ] [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://doi.org/10.48550/arXiv.2405.04434)
- [ ] [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437)
- [ ] [DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models](https://doi.org/10.48550/arXiv.2512.02556)
- [ ] [DeepSeek-V4: Towards Highly Efficient Million-Token Context Intelligence](https://arxiv.org/html/2606.19348v1)
- [ ] [GLM-5: from Vibe Coding to Agentic Engineering](https://arxiv.org/abs/2602.15763)
- [ ] [TransMLA: Multi-head Latent Attention Is All You Need](https://doi.org/10.48550/arXiv.2502.07864)
- [ ] [Attention Residuals](https://arxiv.org/abs/2603.15031)
- [ ] [mHC: Manifold-Constrained Hyper-Connections](https://arxiv.org/abs/2512.24880)
- [ ] [GLU Variants Improve Transformer](https://arxiv.org/abs/2002.05202)
- [ ] [Looped Transformers are Better at Learning Learning Algorithms](https://arxiv.org/abs/2311.12424)

## MoE and Sparse Models

- [ ] [A Survey on Mixture of Experts in Large Language Models](https://arxiv.org/abs/2407.06204)
- [ ] [GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding](https://arxiv.org/abs/2006.16668)
- [ ] [Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/abs/2101.03961)
- [ ] [DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models](https://doi.org/10.48550/arXiv.2401.06066)
- [ ] [LatentMoE: Toward Optimal Accuracy per FLOP and Parameter in Mixture of Experts](https://arxiv.org/abs/2601.18089)
- [ ] [MegaBlocks: Efficient Sparse Training with Mixture-of-Experts](https://arxiv.org/abs/2211.15841)
- [ ] [MegaScale-MoE: Large-Scale Communication-Efficient Training of Mixture-of-Experts Models in Production](https://arxiv.org/abs/2505.11432)

## LLM Serving / Inference Systems

- [ ] [SGLang: Efficient Execution of Structured Language Model Programs](https://doi.org/10.48550/arXiv.2312.07104)
- [ ] [Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve](https://doi.org/10.48550/arXiv.2403.02310)
- [ ] [Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving](https://arxiv.org/abs/2407.00079)
- [ ] [KVBuffer: IO-aware Serving for Linear Attention](https://doi.org/10.48550/arXiv.2605.19049)

## Training and Parallel Systems

- [ ] [GPipe: Efficient Training of Giant Neural Networks Using Pipeline Parallelism](https://arxiv.org/abs/1811.06965)
- [ ] [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://doi.org/10.48550/arXiv.1909.08053)
- [ ] [Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM](https://arxiv.org/abs/2104.04473)
- [ ] [Reducing Activation Recomputation in Large Transformer Models](https://arxiv.org/abs/2205.05198)
- [ ] [Scalable Training of Mixture-of-Experts Models with Megatron Core](https://arxiv.org/abs/2603.07685)
- [ ] [DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models](https://arxiv.org/abs/2309.14509)
- [ ] [USP: A Unified Sequence Parallelism Approach for Long Context Generative AI](https://arxiv.org/abs/2405.07719)
- [ ] [MTraining: Distributed Dynamic Sparse Attention for Efficient Ultra-Long Context Training](https://arxiv.org/abs/2510.18830)
- [ ] [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://doi.org/10.48550/arXiv.1910.02054)
- [ ] [WLB-LLM: Workload-Balanced 4D Parallelism for Large Language Model Training](https://arxiv.org/abs/2503.17924)
- [ ] [ByteScale: Communication-Efficient Scaling of LLM Training with a 2048K Context Length on 16384 GPUs](https://doi.org/10.1145/3718958.3754352)

## Distributed Training Systems

- [ ] [Efficient Training of Large Language Models on Distributed Infrastructures: A Survey](https://arxiv.org/abs/2407.20018)
- [ ] [MegaScale: Scaling Large Language Model Training to More Than 10,000 GPUs](https://arxiv.org/abs/2402.15627)
- [ ] [Characterization of Large Language Model Development in the Datacenter](https://arxiv.org/abs/2403.07648)
- [ ] [Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning](https://arxiv.org/abs/2008.12260)
- [ ] [MegaScale-Data: Scaling DataLoader for Multisource Large Foundation Model Training](https://doi.org/10.1145/3767295.3803568)

## Collective Communication and Network Systems

- [ ] [TACCL: Guiding Collective Algorithm Synthesis using Communication Sketches](https://arxiv.org/abs/2111.04867)
- [ ] [TopoOpt: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs](https://arxiv.org/abs/2202.00433)
- [ ] [ForestColl: Throughput-Optimal Collective Communications on Heterogeneous Network Fabrics](https://arxiv.org/abs/2402.06787)
- [ ] [HeteCCL: Synthesizing Near-Optimal Collective Communication Schedules for Heterogeneous GPU Clusters](https://www.usenix.org/conference/nsdi26/presentation/hei)

## Training Reliability and Checkpointing

- [ ] [Understanding Stragglers in Large Model Training Using What-if Analysis](https://arxiv.org/abs/2505.05713)
- [ ] [Robust LLM Training Infrastructure at ByteDance](https://arxiv.org/abs/2509.16293)
- [ ] [AdaCheck: An Adaptive Checkpointing System for Efficient LLM Training with Redundancy Utilization](https://www.usenix.org/conference/fast26/presentation/liu-weijie)
