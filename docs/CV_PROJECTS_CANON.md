# CV Selected Projects Canon

Use these entries as the canonical project layer for CV/resume material. Keep names and metrics synchronized with `BRAND_CANON.md` and repository evidence.

## Professional summary

**Computer Engineer focused on Applied AI, Computer Vision and Reliable ML Systems, with hands-on work spanning deepfake forensics, Edge AI, industrial anomaly detection, controlled generative systems, embedded computing and MPI-based parallel computing. Emphasis on reproducibility, failure analysis, CI, deployment and evidence-backed technical claims.**

## Selected Projects

### DeepfakeULTRA — Reliability-Aware Multi-Evidence Deepfake Forensics

**Python · PyTorch · OpenCV · Transformers · XAI · CUDA**

- Built a multi-evidence deepfake detection pipeline combining spatial appearance, frequency-domain evidence and facial geometry with reliability-oriented evaluation.
- Established artifact-backed evaluation and failure disclosure across **5 external datasets**; current canonical metrics are **0.9820 internal ROC-AUC** and **0.7405 mean external ROC-AUC**.
- Added cross-dataset benchmarking, explainability tooling, calibration-oriented analysis, CI, reproducibility documentation, limitations and academic citation metadata.

Repository: https://github.com/seydivakkas/DeepfakeULTRA

### SİNAPTİC5G — Real-Time Edge AI & 5G Road-Safety Perception

**Python · YOLOv8 · OpenCV · Tracking · BEV · Kalman Filtering · Docker**

- Developed a road-safety perception architecture spanning driver-action/object detection, temporal tracking, BEV projection and timestamp-aware motion estimation.
- Built a governed **15,487-image** dataset pipeline with **9 canonical labels**, group-aware splitting, augmentation and class-balancing controls.
- Added FTR-oriented model-lock, schema, Docker and pre-submission acceptance checks while preserving explicit blocker/evidence documentation.

Repository: https://github.com/seydivakkas/sinaptic5g

### WeaveVision — Reliable Textile Visual Anomaly Detection

**Python · Anomalib · PatchCore · EfficientAD · OpenVINO · Streamlit · SQLite**

- Built a one-class visual anomaly detection system for textile quality inspection using normal-reference learning rather than requiring a large labeled defect corpus.
- Designed selective decision handling with **PASS / REVIEW / FAIL / ABSTAIN**, validation-only thresholding, audit trails and model lifecycle controls.
- Added live CI, drift monitoring, dataset/license governance, evidence indexing, portability cleanup and explicit limitations for industrial pilot use.

Repository: https://github.com/seydivakkas/WeaveVision

### Halı AI Carpet Design — Controlled Generative Design System

**Python · SDXL · LoRA · Diffusers · Streamlit · CIELAB / Delta E**

- Developed a controlled carpet-design workflow using SDXL + LoRA with structured prompts, provenance tracking and reference-aware generation.
- Integrated retrieval, CIELAB / Delta E color analysis, symmetry/repeat checks and SHA-based evidence artifacts to make generated outputs inspectable.
- Added live CI, reproducible execution, evidence/architecture indexes and pilot limitations to separate technical capability from manufacturing/legal guarantees.

Repository: https://github.com/seydivakkas/hali-ai-carpet-design

### TinyOLED Desktop — Framebuffer-First Embedded Micro Desktop

**Python · Raspberry Pi · SSD1306 · I2C · JavaScript**

- Built a custom framebuffer-first desktop environment for a **128×64 SSD1306 OLED** controlled through a three-button interaction model.
- Implemented bitmap rendering, cooperative scheduling and **57+ documented applications**, plus a browser simulator for hardware-independent inspection.
- Added GitHub Pages deployment, release-readiness CI, known-limitations documentation and a gated `v1.0.0` release process.

Repository: https://github.com/seydivakkas/TinyOLED-Desktop

### MPI Parallel Matrix Multiplication — Distributed Computing Benchmark

**C · Python · MPI · mpi4py · MS-MPI · Benchmarking**

- Implemented distributed N×N matrix multiplication in both C and Python using MPI Scatter/Broadcast/Gather-style decomposition.
- Benchmarked scaling at **P = 1, 2, 4, 8, 16** and documented speedup/efficiency behavior under a controlled **N = 512** workload.
- Recorded a **11.33× Python speedup at P=16** in the documented benchmark while explicitly scoping the claim to the measured hardware/workload.

Repository: https://github.com/seydivakkas/mpi-parallel-matrix-multiplication

## CV selection rules

For a one-page CV, prefer the first four projects and add TinyOLED or MPI only when the role values embedded/systems/HPC breadth.

Recommended order:

1. DeepfakeULTRA
2. SİNAPTİC5G
3. WeaveVision
4. Halı AI Carpet Design
5. TinyOLED Desktop
6. MPI Parallel Matrix Multiplication

## Claim rules

- Use only canonical DeepfakeULTRA metrics: `0.9820 internal ROC-AUC` and `0.7405 mean external ROC-AUC`.
- Keep SİNAPTİC5G dataset evidence scoped to `15,487 governed images` and `9 canonical labels`.
- Treat historical test counts as snapshots rather than current-state guarantees.
- Never call a pilot a production deployment unless independent production evidence exists.
- Scope hardware/performance metrics to the tested configuration.
