# GitHub Repository Metadata Canon

Use these values for the six flagship repositories. This file is the source of truth for GitHub `Description`, `Topics`, `Website` and Social Preview direction.

## 1. DeepfakeULTRA

**Description**  
Reliability-aware deepfake forensics with multi-evidence fusion, XAI and cross-dataset evaluation.

**Topics**  
`deepfake-detection` · `computer-vision` · `pytorch` · `explainable-ai` · `domain-generalization`

**Website**  
Leave empty until a stable public demo/documentation URL exists.

**Social Preview — 1280×640**  
Dark forensic/research visual. Left: three evidence streams (RGB face, frequency spectrum, facial-landmark mesh) merging into a central Transformer/fusion node. Right: restrained metric block — `0.9820 Internal ROC-AUC`, `0.7405 External Mean`, `5 External Datasets`. Footer: `Reliability-Aware Deepfake Forensics`. Do not use the legacy `0.9839 / 0.7527` metrics.

---

## 2. SİNAPTİC5G

**Description**  
Real-time Edge AI and 5G road-safety perception for driver behavior, tracking and vehicle intelligence.

**Topics**  
`edge-ai` · `computer-vision` · `yolov8` · `5g` · `real-time-inference`

**Website**  
Leave empty unless a stable public competition/demo page is intentionally published.

**Social Preview — 1280×640**  
Road/cabin perception composition: vehicle/camera view, compact driver-action boxes, tracking trajectories and BEV lane projection connected to a 5G edge node. Evidence block: `15,487 Governed Images` · `9 Canonical Labels` · `FTR Model Lock`. Avoid marketing-style autonomous-driving claims.

---

## 3. WeaveVision

**Description**  
One-class visual anomaly detection for textile quality control with calibrated decisions and drift monitoring.

**Topics**  
`anomaly-detection` · `industrial-ai` · `patchcore` · `anomalib` · `computer-vision`

**Website**  
Leave empty until a deliberately public deployment exists.

**Social Preview — 1280×640**  
Premium industrial textile visual: carpet weave macro texture with localized anomaly heatmap. Right-side reliability pipeline: `PASS · REVIEW · FAIL · ABSTAIN`, plus small labels `PatchCore / EfficientAD` and `Drift Monitoring`. Avoid presenting the heatmap as a guaranteed physical defect label.

---

## 4. Halı AI Carpet Design

**Description**  
SDXL + LoRA design studio with controlled generation, provenance, retrieval and analytical validation.

**Topics**  
`generative-ai` · `stable-diffusion-xl` · `lora` · `diffusers` · `design-automation`

**Website**  
Leave empty while the Streamlit application is local-only. Do not put `localhost` in GitHub metadata.

**Social Preview — 1280×640**  
Split design-workflow visual. Left: structured design brief controls (motif, palette, symmetry, border). Center arrow: `SDXL + LoRA`. Right: elegant generated carpet with small analytical overlays for `CIELAB / ΔE`, `Symmetry`, `Provenance`. Footer: `Controlled Generative Design`.

---

## 5. TinyOLED Desktop

**Description**  
Framebuffer-first micro desktop for Raspberry Pi + SSD1306 with 57+ applications and a browser simulator.

**Topics**  
`raspberry-pi` · `ssd1306` · `embedded-systems` · `framebuffer` · `oled` · `python`

**Website**  
`https://seydivakkas.github.io/TinyOLED-Desktop/`

**Social Preview — 1280×640**  
Minimal hardware/systems visual: Raspberry Pi board connected to a glowing monochrome 128×64 OLED showing the TinyOLED launcher. Side annotation: `Custom Framebuffer` · `57+ Apps` · `3 Buttons` · `Live Browser Simulator`. Keep it technical rather than retro-gaming-only.

---

## 6. MPI Parallel Matrix Multiplication

**Description**  
C + Python MPI benchmark suite for distributed matrix multiplication, scaling and efficiency analysis.

**Topics**  
`mpi` · `parallel-computing` · `distributed-computing` · `benchmarking` · `performance-analysis`

**Website**  
Leave empty.

**Social Preview — 1280×640**  
Clean HPC benchmark visual: matrix tiles distributed across 1/2/4/8/16 worker nodes, with a restrained speedup curve rising on the right. Evidence labels: `P = 1…16` · `N = 512` · `11.33× Python Speedup @ P=16`. Avoid implying this speedup generalizes to other hardware/problem sizes.

---

## Metadata rules

1. Keep descriptions under one concise engineering sentence.
2. Prefer 5–6 strong topics over a wall of generic tags.
3. Only use a Website field for a stable public URL.
4. Social previews should communicate `problem → system → evidence`, not a logo-only banner.
5. Quantitative preview claims must match repository evidence and the brand canon.
