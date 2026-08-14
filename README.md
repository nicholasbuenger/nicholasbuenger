# Nicholas Bünger

MSc ETH Mechanical Engineering · Zürich, Switzerland
Applied AI in regulated environments — healthcare and pharmacy. I build systems that
process sensitive patient data, so almost all of my code is **private by design**
(proprietary, covered by trade-secret agreements). This page is the map; the public
work sample is [**rag-eval-harness**](https://github.com/nicholasbuenger/rag-eval-harness).

[LinkedIn](https://linkedin.com/in/nicholas-buenger) · [Google Scholar](https://scholar.google.ch/citations?user=NWQ244UAAAAJ) · nicholas.buenger@gmail.com

---

## What I've built

**FarmaciaOS** — pharmacy management platform *(private)*
Modular ERP for Swiss pharmacies: dispensing, accounting, controlled-substances
registry, audit trails, robotic dispensing (WWKS2), e-prescription, MediData/HCI
e-health integrations. Ships an on-premise AI module: an open-weight LLM served
over a RAG layer on the pharmacy's own data — all patient data stays on-site.
Live in production. *Node.js/Express · React · MySQL · Python · Ollama*

**RicDictate / Medivia** — clinical voice-to-report *(private)*
Radiology dictation pipeline: Whisper-family ASR → LLM structuring → signed PDF
report, fully on-premise with de-identification. Fine-tuned ASR and language
models; systematic evaluation against real cases with a plain-language feedback
loop that corrects the system over time. Built side-by-side with a practising
radiologist. *Python · PyTorch · on-prem NVIDIA*

**farmaciadelparco.ch** — omnichannel pharmacy e-commerce *(private)*
Web shop + native iOS app for my own pharmacy: catalogue, payments, logistics,
multilingual search, and an autonomous LLM agent that monitors and patches the
production system. Designed, built and operated single-handedly.
*Vanilla JS · Node.js · MySQL · Cloudflare · Swift*

**Balgrist University Hospital** — data & AI platform *(institutional)*
Product Owner & Data Engineer of the Biomedical Informatics Platform shared by
four Zürich university hospitals, ETH and UZH (>1M patients). Deep-learning on
medical imaging (DIZH MedTwins, PyTorch), the hospital's LLM environment, and
the only NVIDIA DGX A100 in a Swiss hospital — air-gapped. Co-built the OR-X
national smart-OR platform ([arXiv:2503.14049](https://arxiv.org/abs/2503.14049)).

**HospitHome** — tele-monitoring for home care *(2020–2022)*
Real-time streaming and processing of vital-signs sensor data; 700 patients
monitored over two years as CTO. Co-author of the SUNSHINE-eHealth study.

---

## Public code

- [**rag-eval-harness**](https://github.com/nicholasbuenger/rag-eval-harness) —
  reproducible harness for evaluating RAG pipelines (chunking, retrieval,
  answer quality) on a synthetic corpus. numpy-only, tested, CI. It shows the
  *method* behind my production RAG systems without exposing them.

## Elsewhere

- NVIDIA GTC 2024, San Jose — invited speaker (alongside Microsoft) · HIMSS Europe 2023, Lisbon — speaker
- Second author, "MedSAM2-Anatomy: Training-Free Inference-Time Optimization for Musculoskeletal Segmentation" — [arXiv:2608.00195](https://arxiv.org/abs/2608.00195) (2026)
- Co-author, "Digital Twin Platform Integrated into a Hospital Trusted Research Environment for Hip Preservation Surgical Planning Research" — MICCAI 2026, DT4H Workshop (accepted)
- First author, IEEE/RSJ IROS 2021 (with Prof. Daniela Rus, MIT CSAIL)
- NVIDIA Certificate of Competency — "Deploying and Optimizing AI Inference at Scale" (2026)

*Want to see the private systems? Happy to demo them in person.*
