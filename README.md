# 3D Hand-Object Interaction (HOI) — Curated Paper List

A curated list of papers focusing on **3D hand-object interaction** from top-tier venues (CVPR, ECCV, ICCV, NeurIPS, ICLR, ICML, SIGGRAPH, 3DV). Organized by topic and year (2021–2025).

---

## Table of Contents
1. [Joint 3D Hand & Object Reconstruction](#1-joint-3d-hand--object-reconstruction)
2. [3D Hand Pose & Mesh Estimation (under interaction)](#2-3d-hand-pose--mesh-estimation-under-interaction)
3. [Bimanual / Two-Hand Interaction](#3-bimanual--two-hand-interaction)
4. [Grasp Synthesis & Generation](#4-grasp-synthesis--generation)
5. [Diffusion / Generative Models for HOI](#5-diffusion--generative-models-for-hoi)
6. [Contact Modeling & Physics-Aware Methods](#6-contact-modeling--physics-aware-methods)
7. [Egocentric & In-the-Wild HOI](#7-egocentric--in-the-wild-hoi)
8. [Neural Rendering & NeRF/Gaussian Splatting for HOI](#8-neural-rendering--nerfgaussian-splatting-for-hoi)
9. [Datasets & Benchmarks](#9-datasets--benchmarks)

---

## 1. Joint 3D Hand & Object Reconstruction

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **HOLD: Category-agnostic 3D Reconstruction of Interacting Hands and Objects from Video** | CVPR | 2024 | [Project](https://github.com/zc-alexfan/hold) |
| **EasyHOI: Unleashing the Power of Large Models for Reconstructing Hand-Object Interactions in the Wild** | CVPR | 2025 | [GitHub](https://github.com/lym29/EasyHOI) |
| **MagicHOI: Leveraging 3D Priors for Accurate Hand-Object Reconstruction from Short Video** | ICCV | 2025 | - |
| **BIGS: Bimanual Category-agnostic Interaction Reconstruction from Monocular Videos via 3D Gaussian Splatting** | CVPR | 2025 | - |
| **What's in Your Hands? 3D Reconstruction of Generic Objects in Hands** | CVPR | 2022 | [Project](https://judyye.github.io/ihoi/) |
| **Reconstructing Hand-Object Interactions in the Wild** | ICCV | 2021 | [Project](https://jasonyzhang.com/phosa/) |
| **Coarse-to-Fine Implicit Representation Learning for 3D Hand-Object Reconstruction from a Single RGB-D Image** | ECCV | 2024 | - |
| **Joint Reconstruction of 3D Human and Object via Contact-Based Refinement Transformer** | CVPR | 2024 | [GitHub](https://github.com/dqj5182/CONTHO) |
| **Diffusion-Guided Reconstruction of Everyday Hand-Object Interaction Clips** | ICCV | 2023 | [Project](https://judyye.github.io/diffhoi-www/) |
| **Learning to Reconstruct Hand-Held Objects from In-the-Wild Videos** | CVPR | 2023 | - |

---

## 2. 3D Hand Pose & Mesh Estimation (under interaction)

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **HaMeR: Reconstructing Hands in 3D with Transformers** | CVPR | 2024 | [GitHub](https://github.com/geopavlakos/hamer) |
| **WiLoR: End-to-end 3D Hand Localization and Reconstruction in-the-wild** | CVPR | 2025 | [Project](https://rolpotamias.github.io/WiLoR/) |
| **Deformer: Dynamic Fusion Transformer for Robust Hand Pose Estimation** | ICCV | 2023 | - |
| **HandOccNet: Occlusion-Robust 3D Hand Mesh Estimation Network** | CVPR | 2022 | [GitHub](https://github.com/namepllet/HandOccNet) |
| **3D Hand Pose Estimation in Everyday Egocentric Images** | ECCV | 2024 | - |
| **SiMHand: Mining Similar Hands for Large-Scale 3D Hand Pose Pre-training** | ICLR | 2025 | [GitHub](https://github.com/ut-vision/SiMHand) |
| **Overcoming the Trade-off Between Accuracy and Plausibility in 3D Hand Shape Reconstruction** | CVPR | 2023 | - |
| **Analyzing the Synthetic-to-Real Domain Gap in 3D Hand Pose Estimation** | CVPR | 2025 | - |
| **HMP: Hand Motion Priors for Pose and Shape Estimation from Video** | WACV | 2024 | [Project](https://enesduran.github.io/hmp.github.io/) |
| **CPF: Learning a Contact Potential Field to Model the Hand-Object Interaction** | ICCV | 2021 | [GitHub](https://github.com/lixiny/CPF) |

---

## 3. Bimanual / Two-Hand Interaction

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **ARCTIC: A Dataset for Dexterous Bimanual Hand-Object Manipulation** | CVPR | 2023 | [Project](https://arctic.is.tue.mpg.de/) |
| **BimArt: A Unified Approach for the Synthesis of 3D Bimanual Interaction with Articulated Objects** | CVPR | 2025 | [GitHub](https://github.com/eth-ait/BimArt) |
| **Interacting Two-Hand 3D Pose and Shape Reconstruction from Single Color Image** | CVPR | 2021 | - |
| **Keypoint Transformer: Solving Joint Identification in Challenging Hands and Object Interactions for Accurate 3D Pose Estimation** | CVPR | 2022 | [GitHub](https://github.com/shreyashampali/ho3d) |

---

## 4. Grasp Synthesis & Generation

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **GraspXL: Generating Grasping Motions for Diverse Objects at Scale** | ECCV | 2024 | [Project](https://eth-ait.github.io/graspxl/) |
| **G-HOP: Generative Hand-Object Prior for Interaction Reconstruction and Novel Grasps** | CVPR | 2024 | - |
| **ArtiGrasp: Physically Plausible Synthesis of Bi-manual Dexterous Grasping and Articulation** | 3DV | 2024 | - |
| **ContactOpt: Optimizing Contact to Improve Grasps** | CVPR | 2021 | - |
| **GRAB: A Dataset of Whole-Body Human Grasping of Objects** | ECCV | 2020 | [Project](https://grab.is.tue.mpg.de/) |
| **AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose** | ICCV | 2023 | [GitHub](https://github.com/GentlesJan/AffordPose) |

---

## 5. Diffusion / Generative Models for HOI

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Physics-Aware Hand-Object Interaction Denoising** | CVPR | 2024 | - |
| **InterDiff: Generating 3D Human-Object Interactions with Physics-Informed Diffusion** | ICCV | 2023 | [GitHub](https://github.com/Sirui-Xu/InterDiff) |
| **MagicHOI: Leveraging 3D Priors for Accurate Hand-Object Reconstruction** | ICCV | 2025 | - |
| **F-HOI: Toward Fine-grained Semantic-Aligned 3D Human-Object Interactions** | ECCV | 2024 | - |
| **ParaHome: Parameterizing Everyday Home Activities Towards 3D Generative Modeling of HOI** | CVPR | 2025 | - |
| **InterAct: Advancing Large-Scale Versatile 3D Human-Object Interaction Generation** | CVPR | 2025 | [GitHub](https://github.com/wzyabcas/InterAct) |

---

## 6. Contact Modeling & Physics-Aware Methods

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Physics-Aware Hand-Object Interaction Denoising** | CVPR | 2024 | - |
| **CPF: Learning a Contact Potential Field to Model the Hand-Object Interaction** | ICCV | 2021 | [GitHub](https://github.com/lixiny/CPF) |
| **ContactOpt: Optimizing Contact to Improve Grasps** | CVPR | 2021 | - |
| **VPHO: Joint Visual-Physical Cue Learning and Aggregation for Hand-Object Pose Estimation** | AAAI | 2026 | [arXiv](https://arxiv.org/abs/2511.12030) |
| **DeepSimHO: Stable Pose Estimation for Hand-Object Interaction via Physics Simulation** | NeurIPS | 2023 | [GitHub](https://github.com/rongakowang/DeepSimHO) |
| **OakInk: A Large-Scale Knowledge Repository for Understanding Hand-Object Interaction** | CVPR | 2022 | [Project](https://oakink.net/) |
| **Leveraging Photometric Consistency over Time for Sparsely Supervised Hand-Object Reconstruction** | CVPR | 2021 | - |

---

## 7. Egocentric & In-the-Wild HOI

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **HOT3D: Hand and Object Tracking in 3D from Egocentric Multi-View Videos** | CVPR (Highlight) | 2025 | [Project](https://facebookresearch.github.io/hot3d/) |
| **Benchmarks and Challenges in Pose Estimation for Egocentric Hand Interactions with Objects** | ECCV | 2024 | - |
| **3D Hand Pose Estimation in Everyday Egocentric Images** | ECCV | 2024 | - |
| **I'M HOI: Inertia-aware Monocular Capture of 3D Human-Object Interactions** | CVPR | 2024 | [Project](https://afterjourney00.github.io/IM-HOI.github.io/) |
| **AssemblyHands: Towards Egocentric Activity Understanding via 3D Hand Pose Estimation** | CVPR | 2023 | - |
| **Ego4D: Around the World in 3,000 Hours of Egocentric Video** | CVPR | 2022 | [Project](https://ego4d-data.org/) |
| **EasyHOI: Unleashing the Power of Large Models for Reconstructing HOI in the Wild** | CVPR | 2025 | [GitHub](https://github.com/lym29/EasyHOI) |

---

## 8. Neural Rendering & NeRF/Gaussian Splatting for HOI

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **BIGS: Bimanual Category-agnostic Interaction Reconstruction via 3D Gaussian Splatting** | CVPR | 2025 | - |
| **Hand Avatar: Free-Pose Hand Animation and Rendering from Monocular Video** | CVPR | 2023 | [Project](https://seanchenxy.github.io/HandAvatarWeb/) |
| **HOLD: Category-agnostic 3D Reconstruction via Neural Radiance Fields** | CVPR | 2024 | [Project](https://github.com/zc-alexfan/hold) |

---

## 9. Datasets & Benchmarks

| Dataset | Paper / Venue | Year | Description |
|---------|---------------|------|-------------|
| **ARCTIC** | CVPR 2023 | 2023 | Dexterous bimanual hand-object manipulation with articulated objects |
| **HOT3D** | CVPR 2025 | 2025 | Egocentric multi-view 3D hand & object tracking (Meta/FAIR) |
| **HO-3D v3** | CVPR 2020 (updated 2022) | 2022 | RGB-D single-hand object interaction with severe occlusion |
| **OakInk** | CVPR 2022 | 2022 | Large-scale knowledge base for hand-object interaction understanding |
| **AffordPose** | ICCV 2023 | 2023 | Hand-object interaction with affordance-driven hand pose annotations |
| **HIMO** | ECCV 2024 | 2024 | Full-body human interacting with multiple objects |
| **DexYCB** | CVPR 2021 | 2021 | Benchmark for capturing hand grasping of YCB objects |
| **GRAB** | ECCV 2020 | 2020 | Whole-body human grasping with SMPL-X body and MANO hands |
| **InterHand2.6M** | ECCV 2020 | 2020 | 3D interacting hand pose estimation dataset |
| **Ego-Exo4D** | CVPR 2024 | 2024 | Skilled human activity from first- and third-person perspectives |

---

## Key Research Groups / Labs

- **MPI-IS (Black, Tzionas)** — GRAB, ARCTIC, HOLD
- **ETH Zurich (Hilliges group)** — ARCTIC, GraspXL, ArtiGrasp
- **Berkeley (Malik, Kanazawa, Fouhey)** — HaMeR, HOI in the wild
- **UIUC (Gupta)** — IHOI, DiffHOI
- **ShanghaiTech / CMU** — CPF, OakInk, I'M HOI
- **Meta/FAIR** — HOT3D, AssemblyHands
- **NTU / A*STAR** — Various hand-object reconstruction works

---

## Related Surveys & Resources

- **awesome-hand-pose-estimation** — https://github.com/xinghaochen/awesome-hand-pose-estimation
- **Hand3DResearch** — https://github.com/SeanChenxy/Hand3DResearch
- **A Survey on Human Interaction Motion Generation** — arXiv 2025 https://arxiv.org/abs/2503.12763

---

*Last updated: February 2026. Focused on 3D reconstruction, pose estimation, generation, and contact modeling for hand-object interaction.*
