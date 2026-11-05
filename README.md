<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
    <img src="assets/hero-light.svg" alt="Hardik Gaonkar. I build AI systems, from on-device inference to clinical RAG, and measure them until the numbers hold. A panel cycles through 3.13 TOPS on an Intel AI Boost NPU, 2.4% prefill prediction error, and 0.955 Recall@1." width="100%">
  </picture>

  <p>
    <a href="https://my-portfolio-hrdk2.vercel.app"><b>Portfolio</b></a> &nbsp;&middot;&nbsp;
    <a href="https://www.linkedin.com/in/hardik-gaonkar-b7706a376"><b>LinkedIn</b></a> &nbsp;&middot;&nbsp;
    <a href="mailto:hardikgaonkar2025@gmail.com"><b>Email</b></a> &nbsp;&middot;&nbsp;
    <a href="https://github.com/hrdk6/MyPortfolio/raw/HEAD/assets/Hardik_Gaonkar_Resume.pdf"><b>Résumé</b></a>
  </p>
</div>

AI & ML undergraduate at **BMS Institute of Technology and Management, Bengaluru** (B.E., 2028). I build AI systems end to end and don't call one finished until a measurement says it works. Open to **AI/ML engineering internships**.

## Featured work

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/machlume-dark.svg">
    <img src="assets/machlume-light.svg" alt="MachLume Studio, a hardware-aware AI profiler for Windows. An animated roofline chart shows LLM decode on the memory-bound slope and prefill on the compute roof, with predicted points converging onto measured ones. 3.13 TOPS FP16 on an Intel AI Boost NPU; 2.4% prefill and 3.8% decode prediction error; 54 Rust tests." width="100%">
  </picture>
</div>

A native Windows app that reads live hardware telemetry with no admin rights or drivers: per-core CPU and clocks, package and iGPU power, thermal throttling, GPU engines and NPU load. It profiles local LLM runs in Ollama, benchmarks llama.cpp's 4-bit kernels ported to Rust, and predicts each run with a roofline model. The measurements showed that Llama 3 8B decode is memory-bound: 12.5 tok/s equals 54.5 GB/s, the bandwidth I measured. The source is private.

<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/careflow-dark.svg">
    <img src="assets/careflow-light.svg" alt="CareFlow AI, a clinical AI platform. An animated pipeline shows a question passing an access filter, hybrid search, reranking, PII masking, the LLM and citation validation. Recall@1 0.955 and MRR 0.977 on a 48-question benchmark; context precision rose from 0.62 to 0.84 with reranking." width="100%">
  </picture>
</div>

The LLM only sees records the signed-in user may access (RBAC plus row-level SQL filters), and a three-pass PII gateway masks patient identities before any cloud call. Risk models are trained on 99K patient encounters with patient-grouped splits, and chest X-ray triage is tested on 7.5K patient-disjoint films. Code: **[hrdk6/CareFlow-AI](https://github.com/hrdk6/CareFlow-AI)**.

## Toolbox

| | |
| :-- | :-- |
| **Languages** | Python · TypeScript · Rust · Go · JavaScript · SQL |
| **GenAI** | RAG · hybrid search · reranking · LLM agents · LLM evaluation · on-device inference (llama.cpp, Ollama, OpenVINO) |
| **ML** | scikit-learn · XGBoost · SHAP · ONNX Runtime · transfer learning |
| **Backend & apps** | FastAPI · PostgreSQL · pgvector · Next.js · Tauri 2 |
| **Infra** | Docker · Kubernetes · GitHub Actions |
