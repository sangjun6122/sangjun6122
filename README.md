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

**X-ModalDef: Bridging the Domain Gap Between CAD and Scan Images via Shape-Aware Feature Fusion for Industrial Defect Detection**

Cross-modal defect detection addresses a fundamental challenge in automated optical inspection: reference images (CAD) and inspection targets (scans) originate from heterogeneous imaging modalities with inherent scale, domain, and photometric discrepancies. We propose X-ModalDef, which reformulates this problem as cross-modal feature fusion by exploiting structural shape information as a domain-invariant bridge. The framework introduces edge-based registration using phase congruency for illumination-invariant alignment, a Shape-Aware Siamese Encoder with Transformer backbone for learning structural correspondences through cross-attention, and a Change-Aware Decoder for precise defect localization via feature distance analysis.
*Status: In preparation*

**FAMI: Focus-Aware Metric Height Reconstruction for Ultra-Precision Surface Metrology via Single-Domain Learning**

Ultra-precision manufacturing demands sub-micrometer 3D metrology with stringent repeatability requirements. While Laser Scanning Confocal Microscopy (LSCM) achieves the required ±0.05μm repeatability, its 50-second measurement cycle creates critical production bottlenecks incompatible with 100% inline inspection. We present FAMI, a deep learning framework achieving LSCM-equivalent repeatability through single-domain learning—where diverse cell geometries sharing identical material and optical properties provide sufficient information density for learning microscope-invariant height reconstruction. The architecture introduces boundary-preserving encoding via Swin Transformer V2, multi-level focus attention for cross-scale blur-height learning, and uncertainty-guided reconstruction enabling adaptive fusion between optical measurement and learned geometric priors.
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
