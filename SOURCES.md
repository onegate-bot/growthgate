# Tracked Growth Intelligence & Research Sources

This document maintains the canonical registry of empirical research databases, agentic growth labs, GEO benchmark publications, and developer distribution repositories scanned by our weekly intelligence pipeline.

---

## 📡 Active Scanned Sources

| Source Name | Organization / Author | Primary URL / Endpoint | Focus Areas | Added Date | Status |
|---|---|---|---|---|---|
| **Enso Agentic Growth Lab** | Enso (`enso.bot`) | [enso.bot/research](https://www.enso.bot/research)<br>[enso.bot/llms-full.txt](https://www.enso.bot/llms-full.txt) | Platform distribution exploits, SDR automation, GEO/answer engine citation experiments, agent supply distribution | 2026-08-19 | 🟢 Active |
| **Hermes Agent Skills Hub** | Agent Capability Registries | [hermes-agent.nousresearch.com/docs/skills](https://hermes-agent.nousresearch.com/docs/skills) | Multi-registry skill distribution & agent runtime capability catalog across 88k+ skills. | 2026-08-24 | 🟢 Active |
| **Princeton & Stanford GEO Benchmarks** | Generative Engine Optimization | [arXiv / Research Benchmark](https://arxiv.org/abs/2311.09735) | Empirical citation mechanics, source authority scoring, and synthetic answer engine visibility benchmarks. | 2026-08-24 | 🟢 Active |

---

## 🔍 Candidate Sources Under Evaluation (Pending Review & Approval)

| Candidate Source | Organization / Authors | URL / Reference | Focus Area | Staged Date |
|---|---|---|---|---|
| **Optimizing Visibility in Generative Engines Survey** | arXiv Research Working Group | [arXiv:2607.14035](https://arxiv.org/abs/2607.14035) | Multi-stage pipeline GEO benchmarks, citation vs absorption dynamics, statistical lifting factors | 2026-09-06 |
| **Similarweb 2026 Generative AI Visibility Index** | Similarweb Research | [similarweb.com/blog/what-is-geo/](https://aisearch.similarweb.com/blog/what-is-geo/) | Consumer search shift tracking, zero-click answer engine market shares | 2026-09-06 |

---

## ⚙️ How New Sources Are Added & Maintained

1. **Discovery:** The weekly intelligence scanner (`scripts/track-growth-sources.py`) monitors established feeds and searches for new empirical growth studies, agent ecosystem distribution playbooks, and GEO benchmarks.
2. **Review & Approval:** Every newly discovered candidate is logged in this registry and submitted for human review and approval.
3. **Activation & Synthesis:** Upon approval, the source is marked 🟢 **Active**, ingested into weekly scans, and its tactical methodologies are synthesized into structured skill specifications (`skills/`) with proper attribution.
