# Yin Li Personal Site

Source for [kevin-li-2025.github.io](https://kevin-li-2025.github.io/).

The site is intentionally static: one HTML file, one CSS file, and no build step. It is used as a compact portfolio for LLM systems, retrieval evaluation, post-training, and traceable agent infrastructure work.

## Featured Work

- [L20-CodeForge](https://github.com/Kevin-Li-2025/L20-CodeForge): single-L20 post-training and verifier-guided inference stack for executable code benchmarks
- [nl2sql-benchmark](https://github.com/Kevin-Li-2025/nl2sql-benchmark): reproducible text-to-SQL fine-tuning and multi-path inference benchmark
- [finmteb-zh-reranker-sota](https://github.com/Kevin-Li-2025/finmteb-zh-reranker-sota): FinanceMTEB Chinese reranking snapshot with Qwen3-Reranker-8B
- [signal-rag](https://github.com/Kevin-Li-2025/signal-rag): retrieval workbench with citation checks and source-trust tiers
- [scitrace-rl](https://github.com/Kevin-Li-2025/scitrace-rl): trace, validation, and reward infrastructure for scientific agents

## Local Preview

Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
python3 -m http.server 8080
```

## Update Checklist

- Keep the project list aligned with pinned GitHub repositories.
- Prefer concrete evidence: benchmark names, hardware, reproducibility notes, and explicit claim boundaries.
- Avoid adding a build system unless the site needs generated pages or shared components.
