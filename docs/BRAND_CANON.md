# Engineering Brand Canon

This file is the source of truth for project names, one-line positioning and portfolio metrics used across GitHub, LinkedIn and CV material.

## Positioning

**Applied AI · Computer Vision · Reliable ML Systems · Research → Production**

Recommended LinkedIn/CV headline:

**Computer Engineer | Applied AI & Computer Vision | Reliable ML Systems | Edge AI · Industrial AI · XAI**

## Canonical flagship projects

| Order | Canonical name | One-line positioning | Canonical evidence to quote |
|---|---|---|---|
| 1 | **DeepfakeULTRA** | Reliability-aware multi-evidence deepfake forensics with XAI and cross-dataset evaluation | **0.9820 internal ROC-AUC · 0.7405 mean external ROC-AUC · 5 external datasets** |
| 2 | **SİNAPTİC5G** | Real-time Edge AI and 5G road-safety perception with tracking and physical motion reasoning | **15,487 governed images · 9 canonical labels · FTR model-lock/acceptance evidence** |
| 3 | **WeaveVision** | Reliable one-class visual anomaly detection for textile quality control | **PatchCore / EfficientAD · PASS/REVIEW/FAIL/ABSTAIN · drift lifecycle · live CI** |
| 4 | **Halı AI Carpet Design** | Controlled SDXL + LoRA design studio with provenance and analytical validation | **provenance · retrieval · CIELAB/Delta E · documented 52-test pilot snapshot · live CI** |
| 5 | **TinyOLED Desktop** | Framebuffer-first Raspberry Pi + SSD1306 micro desktop | **57+ apps · custom framebuffer · live browser simulator** |
| 6 | **MPI Parallel Matrix Multiplication** | C + Python MPI benchmark for scaling and efficiency analysis | **P=1,2,4,8,16 · 11.33x Python speedup at P=16 in the documented N=512 benchmark** |

## Naming rules

Use these names everywhere:

- `DeepfakeULTRA`
- `SİNAPTİC5G`
- `WeaveVision` — never `merinpsVision` in public-facing copy
- `Halı AI Carpet Design`
- `TinyOLED Desktop`
- `MPI Parallel Matrix Multiplication`

## Metric rules

1. DeepfakeULTRA portfolio metrics come from the current machine-readable `evaluation/` artifacts, not legacy README values.
2. Do not use the historical `0.9839 / 0.7527` pair in new public-facing material while current artifacts report `0.9820 / 0.7405`.
3. Test counts such as WeaveVision `262/262` and AI Carpet `52` are documented snapshots; use live CI badges for current repository health.
4. Hardware-dependent latency/speed claims must name their evaluation context.
5. Do not convert pilot/engineering evidence into manufacturing, legal or commercial guarantees.

## Featured-project order

Use this order in GitHub pins, LinkedIn Featured and CV selected projects whenever space allows:

1. DeepfakeULTRA
2. SİNAPTİC5G
3. WeaveVision
4. Halı AI Carpet Design
5. TinyOLED Desktop
6. MPI Parallel Matrix Multiplication

This produces a coherent signal sequence:

**AI Research → Edge AI → Industrial AI → Generative AI → Embedded Systems → HPC**
