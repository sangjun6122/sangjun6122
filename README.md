# Sang-Jun Song

**AI Researcher in Industrial Metrology & Inspection**
System Architect with 20+ years of equipment-level experience

---

## Research Focus

I study AI-based precision metrology and inspection systems grounded in real industrial equipment.
My research bridges physical processes, sensing, and deep learning, with a focus on:

- Learning-based surface & thin-film metrology
- Defect detection under severe noise, variation, and domain shift
- Hybrid systems combining physics, rules, and deep neural networks
- Translating research models into deployable, real-time equipment

Currently an M.S. candidate at Sungkyunkwan University, focusing on deep learning for surface metrology.

---

## Core Domains & Capabilities

### 1. Industrial AI & Machine Vision

- Deep learning–based defect detection & measurement
- Hybrid inspection: DL + rule-based + optical heuristics
- PyTorch, OpenCV, HALCON
- Dataset construction from real production equipment

### 2. Precision Metrology & Physical Systems

- Thin-film scratch, stress, tribology measurement
- Residual stress & magnetic field mapping
- Understanding of process-induced measurement uncertainty

### 3. System & Control Architecture

- End-to-end inspection equipment design
- Real-time motion control & synchronization
- C/C++ (MFC), Python, PLC-based systems
- Deployment under strict latency and reliability constraints

---

## What I Research Through Building

Rather than separating research and engineering,
I use production equipment as research platforms.

**Thin-Film Metrology Instruments**
Scratch tester, tribometer, stress analyzer
→ 40+ units deployed globally (ODM with Helmut Fischer, Germany)

**Plasma Surface Treatment Systems**
PECVD, PVD systems for electronics and automotive industries

**Roll-to-Roll Inspection Systems**
Cylindrical roll inspection for printed electronics and optical sheets
→ Deployed in domestic and international production lines

These systems provide real-world data, constraints, and failure modes
that directly inform my research.

---

## Current Research

**X-ModalDef: Cross-Modal Defect Detection for Industrial Inspection**

In automated optical inspection, reference images (CAD drawings) and inspection targets (scanned images) originate from fundamentally different imaging modalities—binary patterns at design-specific scales versus grayscale intensity maps under varying illumination. Conventional pixel-based comparison fails under such cross-modal discrepancies, while existing deep learning methods assume same-domain inputs.

This work addresses the problem of detecting defects when reference and target images cannot be directly compared due to inherent domain gaps in scale, representation, and photometric characteristics.
*Status: In preparation*

**FAMI: Focus-Aware Metric Height Reconstruction for Surface Metrology**

Ultra-precision manufacturing requires sub-micrometer 3D surface measurement with high repeatability. Laser Scanning Confocal Microscopy (LSCM) achieves the required precision but its point-scanning mechanism creates throughput limitations incompatible with production-scale inspection. Conventional deep learning approaches require diverse multi-scene training data, which is impractical when ground truth acquisition is expensive.

This work addresses the problem of achieving high-precision surface metrology at production-compatible throughput, using minimal calibration data from a single manufacturing domain.
*Status: In preparation*

---

## Selected Patents

- **Apparatus for Detecting Defects** – Filed 2024, KR + PCT
- **Vision System for Gravure Roll Inspection** – Patent issued 2017

---

## Research Philosophy

Industrial AI is not about maximizing benchmark accuracy,
but about minimizing uncertainty under real constraints.

I focus on:

- Why models fail in production
- How physical processes shape data distributions
- How AI systems can be trusted on real equipment

---

## Contact

📧 ssj6122@gmail.com

🔗 Please refer to individual repositories for detailed research implementations and experiments.
