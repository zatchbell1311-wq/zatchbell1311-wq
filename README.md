# Dhruv Dubey
Independent AI Researcher · LLM Memory Architectures · Open Source Contributor

## Research
Building novel memory architectures for LLMs — independently, without lab resources.

### DSPM (Dynamic Semantic Patch Memory)
- 82.4% token reduction
- 94.2% compression-retention ratio across 7 technical dialogue domains
- Statistically validated (Wilcoxon signed-rank, p = 0.0431)
- Zenodo preprint: https://zenodo.org/records/19438636
- Accepted into the Sarvam AI Startup Program

### SSPM (Streaming Sparse Prompt Modeling)
- Real-time evaluation and constraint-preservation methodology
- Validated on the LoCoMo benchmark
- Zenodo preprint: https://zenodo.org/records/19033643

### Vyom OS (ALISA — AI-Integrated OS Architecture)
- Systems-level architecture spanning:
  - Bootloader
  - Paging
  - Priority Scheduling
- Presented, under review, IEEE-affiliated ICSEAI 2026

## Open Source

### Yale `pie` (pie-project/pie)
- 4 merged PRs:
  - #382 — stderr forward-port
  - #383 — sharded GGUF loading
  - #391 — E2E test coverage for raw-completion
  - #407 — async system test coverage
- Open PRs: #460 (CUDA graph key-collision fix), #462 (Vulkan/Windows Context::fork() corruption fix)
- Issue #418
  - Isolated a Vulkan-backend memory-corruption defect via clean baseline comparison
  - Documented workaround

### UW VibeServe (uw-syfi/vibesys)
- 3 merged PRs, supervised by Vic Shihang Li (UW SyFI):
  - #54 — default queue reference, accuracy checker, and benchmark harness
  - #241 — deep-agent graph caching (eliminated full graph rebuild per invocation)
  - #312 — CI gates for format, lint, and coverage in development guide
- Invited into core UI team (August 2026)

### Point Cloud Library (PCL)
- Merged PR #6398
- Fixed non-deterministic azimuth orientation in `ShapeContext3DEstimation`

### Pyserini / Anserini (Castorini Research Group, University of Waterloo)
- Merged PR #2483
- Merged PR #3227
- Reviewed and merged by Prof. Jimmy Lin
- Reproduced and validated baseline metrics:
  - BM25
  - uniCOIL
  - SPLADE
  - Contriever
- Environment:
  - Ubuntu 24.04
  - Java 21

## Stack
- Python
- C/C++
- TypeScript
- PyTorch
- OS Kernels & Memory Management
- LLM Inference Pipelines
- REST APIs
- PostgreSQL
- Supabase
- Groq API
- Gemini API

## Achievements
- Solved 300+ LeetCode problems
  - Arrays, Linked Lists, STL, Dynamic Programming, Graphs, Trees
- 331 combined Zenodo views
- 186 downloads across two published preprints
- NVIDIA GTC 2025 attendee
- Solo participant, Meta PyTorch Hackathon × Scaler

## Links
- Portfolio: https://dhruv-dubey-bento-portfolio.vercel.app/
- LinkedIn: https://linkedin.com/in/dhruvdubey
- LeetCode: https://leetcode.com/u/Dhruv_1311
- ORCID: https://orcid.org/0009-0004-5510-9000
- Email: dhruvdubey1311@gmail.com
