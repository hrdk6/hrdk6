<div align="center">
  <img src="assets/hero.svg" alt="Hardik Gaonkar. I build AI agents and RAG systems, then benchmark them until the numbers hold. Chart: AegisOps pass rate on 21 injected failures rose from 76% on the first run to 100% on the third." width="100%">
</div>

I'm an AI & ML undergraduate (class of 2028) at BMS Institute of Technology and Management in Bengaluru. I build AI systems end to end, and I don't call one finished until a held-out benchmark says it works. I'm looking for AI/ML engineering internships in India.

## What I've built

**[AegisOps](https://github.com/hrdk6/AegisOps)** is an incident-response agent for Kubernetes. It detects an SLO violation, gathers cited evidence from metrics, logs and traces, diagnoses the cause, applies a fix and checks that the service recovered. A deterministic Go policy engine caps what it may do, and risky fixes run in a sandbox first. On 21 failures injected into a live cluster, the pass rate went from 76% to 100% over three runs with 0 unsafe actions. That benchmark is rules-only, with no LLM involved.
<br>`Go` `Python` `FastAPI` `PostgreSQL` `Kubernetes` `OpenTelemetry`

**[CareFlow AI](https://github.com/hrdk6/CareFlow-AI)** is a clinical AI platform. Its RAG answers only from records the signed-in user may see, and patient identities are masked before any cloud LLM call. Retrieval reaches Recall@1 0.955 on a 48-question benchmark. It also includes explainable readmission and length-of-stay models and a chest X-ray triage model.
<br>`Python` `FastAPI` `pgvector` `XGBoost` `ONNX` `Next.js`

**[PatchPilot](https://github.com/hrdk6/PatchPilot)** takes a repository and a bug report and returns a tested patch. A LangGraph state machine plans, patches, runs the tests in a locked-down Docker sandbox and feeds failures back into a repair loop, with a budget cap. Every code chunk it retrieves is logged with the reason it was chosen.
<br>`Python` `LangGraph` `Docker` `Qdrant` `React`

**[GroundTruth](https://github.com/hrdk6/GroundTruth)** is a RAG system over Kubernetes docs that checks each generated sentence against its cited source, then regenerates or declines to answer. Faithfulness is 0.94 to 0.97. Its evaluation harness reports bootstrap confidence intervals, and a self-audit of that harness found 13 measurement bugs.
<br>`Python` `pgvector` `BM25` `Next.js`

**[FieldNote](https://github.com/hrdk6/FieldNote)** is a market and competitor intelligence assistant. Four agents research, critique, analyze and write, and every claim in a brief carries a source.

**[AI Council](https://github.com/hrdk6/AI-Council)** puts a hard decision to a panel of AI specialists who debate it in parallel. A chairman then writes one directive.

## Toolbox

**Languages** Python, Go, TypeScript, JavaScript, SQL

**GenAI** RAG, hybrid search, reranking, LLM agents, LangGraph, LLM evaluation, guardrails

**ML** scikit-learn, XGBoost, SHAP, Hugging Face, ONNX Runtime, transfer learning

**Backend and infra** FastAPI, PostgreSQL, pgvector, Docker, Kubernetes, GitHub Actions

## Find me

[Portfolio](https://my-portfolio-hrdk2.vercel.app) · [LinkedIn](https://www.linkedin.com/in/hardik-gaonkar-b7706a376) · [Email](mailto:hardikgaonkar2025@gmail.com)
