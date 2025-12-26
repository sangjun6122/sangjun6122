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
- PyTorch, OpenCV, HALCON, Open eVision, Matrox
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

### X-ModalDef: Cross-Modal Defect Representation Learning for Industrial Inspection

Industrial inspection systems often suffer from severe domain gaps between design references (e.g., CAD) and sensor data acquired from real equipment.  
This research focuses on learning **cross-modal, domain-invariant representations** that enable robust defect detection under variations in optics, illumination, and surface conditions.

- **Problem:** Large appearance discrepancies between reference models and real inspection images cause instability in conventional vision-based inspection.
- **Approach:** Learn defect representations shared across heterogeneous modalities (design references and sensor data).
- **Goal:** Enable reliable defect detection across processes and equipment without exhaustive re-tuning.

**Keywords:** cross-modal learning, industrial inspection, domain shift, defect representation  
**Status:** In preparation

### FAMI: Focus-Aware Metrology Inference for Surface Measurement

Precise surface height and roughness measurement using **Laser Scanning Confocal Microscopy (LSCM)** is highly sensitive to focus conditions and optical constraints.  
This research explores learning-based inference that explicitly accounts for focus-related uncertainty in metrology data.

- **Problem:** Focus variation introduces systematic errors in height reconstruction for confocal-based surface metrology.
- **Approach:** Integrate optical characteristics and focus behavior into deep learning–based inference.
- **Goal:** Improve robustness and accuracy of surface metrology under real measurement conditions.

**Keywords:** surface metrology, confocal microscopy, focus-aware learning, height reconstruction  
**Status:** In preparation

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
