# LinkedIn Profile Canon

This document is the source of truth for LinkedIn positioning. Keep project names, ordering and quantitative claims synchronized with `BRAND_CANON.md` and repository evidence.

## Headline

**Computer Engineer | Applied AI & Computer Vision | Reliable ML Systems | Edge AI · Industrial AI · XAI**

## About

I build research-driven AI and intelligent systems with an emphasis on measurable performance, robustness, explainability and reproducible engineering evidence.

My work sits at the intersection of **Applied AI, Computer Vision and Reliable ML Systems**. I focus on turning experimental ideas into auditable pipelines: defining the data contract, building a baseline, designing the model/system architecture, evaluating under realistic failure conditions, documenting limitations and exposing a reproducible execution path.

Selected work includes:

- **DeepfakeULTRA** — reliability-aware multi-evidence deepfake forensics with XAI and cross-dataset evaluation. Current machine-readable evaluation artifacts report **0.9820 internal ROC-AUC** and **0.7405 mean external ROC-AUC across 5 external datasets**.
- **SİNAPTİC5G** — real-time Edge AI and 5G road-safety perception built around a **15,487-image governed dataset**, **9 canonical labels**, tracking, BEV reasoning and FTR acceptance evidence.
- **WeaveVision** — one-class industrial visual anomaly detection with PatchCore / EfficientAD, selective decisions, model lifecycle controls and drift monitoring.
- **Halı AI Carpet Design** — controlled SDXL + LoRA design workflow with provenance, retrieval, CIELAB / Delta E analysis and geometry validation.

I also work on embedded and parallel-computing systems through **TinyOLED Desktop** and **MPI Parallel Matrix Multiplication**.

My engineering rule is simple: **evidence before claims**. A model result is not enough by itself; the evaluation protocol, failure modes, reproducibility path and system constraints should be inspectable as well.

## Featured order

Use this order in LinkedIn Featured:

1. **DeepfakeULTRA** — https://github.com/seydivakkas/DeepfakeULTRA
2. **SİNAPTİC5G** — https://github.com/seydivakkas/sinaptic5g
3. **WeaveVision** — https://github.com/seydivakkas/WeaveVision
4. **Halı AI Carpet Design** — https://github.com/seydivakkas/hali-ai-carpet-design

Optional secondary items:

5. **TinyOLED Desktop** — https://github.com/seydivakkas/TinyOLED-Desktop
6. **MPI Parallel Matrix Multiplication** — https://github.com/seydivakkas/mpi-parallel-matrix-multiplication

## Featured descriptions

### DeepfakeULTRA

**Reliability-aware multi-evidence deepfake forensics with XAI and cross-dataset evaluation.** Combines spatial, frequency-domain and facial-geometry evidence while documenting external-domain failures instead of reporting only in-domain performance.

Canonical evidence: **0.9820 internal ROC-AUC · 0.7405 mean external ROC-AUC · 5 external datasets**.

### SİNAPTİC5G

**Real-time Edge AI and 5G road-safety perception.** Integrates driver-action/object detection, tracking, BEV geometry, timestamp-aware motion estimation and FTR-oriented system verification.

Canonical evidence: **15,487 governed images · 9 canonical labels · model-lock / acceptance evidence**.

### WeaveVision

**Reliable visual anomaly detection for textile quality control.** One-class anomaly detection with PatchCore / EfficientAD, selective decision handling, OpenVINO-oriented deployment and drift/lifecycle monitoring.

Canonical evidence: **PASS / REVIEW / FAIL / ABSTAIN decision model · drift lifecycle · live CI**.

### Halı AI Carpet Design

**Controlled generative design for industrial carpet workflows.** Uses SDXL + LoRA with provenance, reference retrieval, CIELAB / Delta E analysis, symmetry/repeat validation and explicit pilot limitations.

Canonical evidence: **provenance · retrieval · analytical validation · live CI**.

## Writing rules

- Never use `merinpsVision`; use **WeaveVision**.
- Do not use the legacy DeepfakeULTRA `0.9839 / 0.7527` metric pair in new public copy.
- Treat static test counts as historical snapshots; use live CI for current repository health.
- Do not describe pilot evidence as production certification.
- Do not imply hardware validation where only simulator/CI evidence exists.
