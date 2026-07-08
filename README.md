# LLM Paper List

Reading checklist for LLM papers.

## Foundations and Transformers

- [ ] [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [ ] [Transformers Are RNNs: Fast Autoregressive Transformers with Linear Attention](https://arxiv.org/abs/2006.16236)

## Linear Attention and Long Context

- [ ] [A Survey of Linear Attention: Algorithm, Theory, Application, and Infrastructure](https://openreview.net/forum?id=ilkVX8aGmQ)
- [ ] [Kimi Linear: An Expressive, Efficient Attention Architecture](https://doi.org/10.48550/arXiv.2510.26692)
- [ ] [Gated Linear Attention Transformers with Hardware-Efficient Training](https://arxiv.org/abs/2312.06635)
- [ ] [Parallelizing Linear Transformers with the Delta Rule over Sequence Length](https://doi.org/10.48550/arXiv.2406.06484)
- [ ] [Erase-then-Delta Attention: Decoupling Erase and Write Addresses in Delta-Rule Linear Attention](https://doi.org/10.48550/arXiv.2606.26560)
- [ ] [Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models](https://doi.org/10.48550/arXiv.2401.04658)
- [ ] [Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention](https://doi.org/10.48550/arXiv.2405.17381)
- [ ] [IndexCache: Accelerating Sparse Attention via Cross-Layer Index Reuse](https://ar5iv.labs.arxiv.org/html/2603.12201)

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

## MoE, MLA, and Efficient Model Architecture

- [ ] [DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models](https://doi.org/10.48550/arXiv.2401.06066)
- [ ] [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://doi.org/10.48550/arXiv.2405.04434)
- [ ] [DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models](https://doi.org/10.48550/arXiv.2512.02556)
- [ ] [TransMLA: Multi-head Latent Attention Is All You Need](https://doi.org/10.48550/arXiv.2502.07864)

## LLM Serving / Inference Systems

- [ ] [SGLang: Efficient Execution of Structured Language Model Programs](https://doi.org/10.48550/arXiv.2312.07104)
- [ ] [Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve](https://doi.org/10.48550/arXiv.2403.02310)
- [ ] [Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving](https://arxiv.org/abs/2407.00079)
- [ ] [KVBuffer: IO-aware Serving for Linear Attention](https://doi.org/10.48550/arXiv.2605.19049)

## Training and Parallel Systems

- [ ] [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://doi.org/10.48550/arXiv.1909.08053)
- [ ] [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://doi.org/10.48550/arXiv.1910.02054)
