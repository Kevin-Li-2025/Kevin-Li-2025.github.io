# Yin Li Personal Site

Source for [kevin-li-2025.github.io](https://kevin-li-2025.github.io/).

This is a static research engineering portfolio for LLM systems, reproducible evaluation, post-training, retrieval infrastructure, and traceable agent workflows. It intentionally stays dependency-free: one HTML file, one CSS file, and no build step.

## Featured Work

- [Triton PR #10411](https://github.com/triton-lang/triton/pull/10411): merged upstream runtime cache-group integrity fix with full integration CI across NVIDIA, AMD, and macOS runners
- [l20-edu-135m-pretrain](https://github.com/Kevin-Li-2025/l20-edu-135m-pretrain): from-scratch 135M Transformer pretraining on 10B FineWeb-Edu tokens using one NVIDIA L20
- [L20-CodeForge](https://github.com/Kevin-Li-2025/L20-CodeForge): single-L20 post-training and verifier-guided inference stack for executable code benchmarks
- [nl2sql-benchmark](https://github.com/Kevin-Li-2025/nl2sql-benchmark): reproducible text-to-SQL fine-tuning and multi-path inference benchmark
- [goemotions-roberta-large-focal](https://github.com/Kevin-Li-2025/goemotions-roberta-large-focal): RoBERTa-large emotion classifier with focal loss and reported test macro-F1 0.5330
- [finmteb-zh-reranker-sota](https://github.com/Kevin-Li-2025/finmteb-zh-reranker-sota): FinanceMTEB Chinese reranking snapshot with Qwen3-Reranker-8B
- [llm-quant-bench](https://github.com/Kevin-Li-2025/llm-quant-bench): quantized LLM quality-retention, throughput, latency, and availability benchmark toolkit
- [signal-rag](https://github.com/Kevin-Li-2025/signal-rag): retrieval workbench with citation checks and source-trust tiers
- [scitrace-rl](https://github.com/Kevin-Li-2025/scitrace-rl): trace, validation, and reward infrastructure for scientific agents
- [coreb-retrieval-sota](https://github.com/Kevin-Li-2025/coreb-retrieval-sota): reproducible retrieval benchmark snapshot with CI-backed artifacts

## Local Preview

Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
python3 -m http.server 8080
```

## Update Checklist

- Keep project links aligned with renamed GitHub repositories.
- Prefer concrete evidence: benchmark names, hardware, reproducibility notes, artifacts, and explicit claim boundaries.
- Keep the positioning centered on research engineering and systems work.
- Avoid adding a build system unless generated pages or shared components become necessary.
