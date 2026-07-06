# Awesome Vision-Tactile Robot Learning Papers

A curated reading list for vision-tactile robot learning, with an emphasis on tactile VLA/VTLA, world models, data collection, open datasets, tactile policy learning, and contact-rich manipulation.

Inspired by the awesome-list style of [ddz16/TSFpaper](https://github.com/ddz16/TSFpaper). Links are external only; local PDFs and generated working files are intentionally ignored by Git.

## Contents

- [VLA / VTLA](#vla--vtla)
- [World Model / Prediction](#world-model--prediction)
- [Data Collection & Hardware](#data-collection--hardware)
- [Open Datasets & Benchmarks](#open-datasets--benchmarks)
- [Policy / Control / Tactile Representation](#policy--control--tactile-representation)
- [Maintenance Notes](#maintenance-notes)

## VLA / VTLA

| Date | Method | Paper | Venue/Status | Links | Notes |
|---|---|---|---|---|---|
| 2025-07-12 | Tactile-VLA | Tactile-VLA: Unlocking Vision-Language-Action Model's Physical Knowledge for Tactile Generalization | arXiv | [Paper](https://arxiv.org/abs/2507.09160) | Connects VLA reasoning to tactile feedback and force-aware action. |
| 2025-08-12 | OmniVTLA | OmniVTLA: Vision-Tactile-Language-Action Model with Semantic-Aligned Tactile Sensing | arXiv | [Paper](https://arxiv.org/abs/2508.08706) | Uses semantic-aligned tactile sensing and ObjTac-style tactile representations. |
| 2026-03-15 | TacFiLM | Tactile Modality Fusion for Vision-Language-Action Models | arXiv | [Paper](https://arxiv.org/abs/2603.14604) | Lightweight FiLM-style fusion of tactile features into VLA visual features. |
| 2026-06-27 | TAP-VLA | TAP-VLA: Tactile Annotation Prompting for Vision Language Action Models | arXiv | [Paper](https://arxiv.org/abs/2606.29089) | Overlays tactile annotations into the visual observation space without changing the VLA architecture. |
| 2026-06-30 | UniTacVLA | UniTacVLA: Unified Tactile Understanding and Prediction in Vision Language Action Models | arXiv | [Paper](https://arxiv.org/abs/2606.31723) | Combines tactile understanding, future tactile prediction, and tactile-action control. |

## World Model / Prediction

| Date | Method | Paper | Venue/Status | Links | Notes |
|---|---|---|---|---|---|
| 2026-03-19 | OmniVTA | OmniVTA: Visuo-Tactile World Modeling for Contact-Rich Robotic Manipulation | arXiv | [Paper](https://arxiv.org/abs/2603.19201), [Project](https://mrsecant.github.io/OmniVTA) | Predictive contact modeling with a large visuo-tactile-action dataset. |
| 2026-03-24 | VTAM | VTAM: Video-Tactile-Action Models for Complex Physical Interaction Beyond VLAs | arXiv | [Paper](https://arxiv.org/abs/2603.23481) | Uses tactile streams to ground video-action world modeling. |
| 2026-06-09 | TacForeSight | TacForeSight: Force-Guided Tactile World Model for Contact-Rich Manipulation | arXiv | [Paper](https://arxiv.org/abs/2606.11184), [Project](https://tacforesight.github.io/ProjectPage) | Predicts tactile latent dynamics conditioned on wrist force/torque. |
| 2026-06-25 | Tactile-WAM | Tactile-WAM: Touch-Aware World Action Model with Tactile Asymmetric Attention | arXiv | [Paper](https://arxiv.org/abs/2606.26663) | Adds tactile asymmetric attention to protect video prediction while improving action generation. |
| 2026-07-02 | VT-WAM | VT-WAM: Visual-Tactile World Action Model for Contact-Rich Manipulation | arXiv | [Paper](https://arxiv.org/abs/2607.02503), [Project](https://vt-wam.github.io/) | Jointly learns future visual prediction, tactile deformation prediction, and action prediction. |

## Data Collection & Hardware

| Date | Method | Paper | Venue/Status | Links | Notes |
|---|---|---|---|---|---|
| 2026-01-31 | LVTG | A Low-Cost Vision-Based Tactile Gripper with Pretraining Learning for Contact-Rich Manipulation | arXiv | [Paper](https://arxiv.org/abs/2602.00514) | Low-cost visuo-tactile gripper with pretraining for contact-rich manipulation. |
| 2026-04-22 | FingerEye | FingerEye: Continuous and Unified Vision-Tactile Sensing for Dexterous Manipulation | arXiv | [Paper](https://arxiv.org/abs/2604.20689), [Project](https://nus-lins-lab.github.io/FingerEyeWeb/) | Continuous pre-contact and post-contact vision-tactile sensing hardware. |

## Open Datasets & Benchmarks

| Date | Method | Paper | Venue/Status | Links | Notes |
|---|---|---|---|---|---|
| 2024-02-20 | TVL | A Touch, Vision, and Language Dataset for Multimodal Alignment | arXiv | [Paper](https://arxiv.org/abs/2402.13232), [Project](https://tactile-vlm.github.io) | Vision-touch-language alignment dataset and benchmark. |
| 2025-05-28 | VTV-LLM | Universal Visuo-Tactile Video Understanding for Embodied Interaction | arXiv | [Paper](https://arxiv.org/abs/2505.22566) | VTV150K dataset and visuo-tactile video-language understanding. |
| 2026-06-03 | HapTile | HapTile: A Haptic-Informed Vision-Tactile-Language-Action Dataset for Contact-Rich Imitation Learning | arXiv | [Paper](https://arxiv.org/abs/2606.04825), [Project](https://haptile-dataset.github.io) | Contact-grounded VTLA demonstrations with haptic-informed teleoperation. |
| 2026-06-21 | Tactile Genesis | Tactile Genesis: Exploring Tactile Sensors at Scale for Learning Dexterous Tasks | arXiv | [Paper](https://arxiv.org/abs/2606.22332), [Project](https://neuroagents-lab.github.io/2026-tactile-genesis/) | GPU-parallel tactile sensor simulation and large-scale tactile ablations. |
| 2026-06-24 | TacVerse | TacVerse: A Multi-Sensor Dataset and Benchmark for Cross-Sensor Vision-Based Tactile Perception | arXiv | [Paper](https://arxiv.org/abs/2606.25877) | Multi-sensor VBTS benchmark for sensor shift and adaptation. |
| 2026-06-30 | RCT | RCT: A Robot-Collected Touch-Vision-Language Dataset for Tactile Generalization | arXiv | [Paper](https://arxiv.org/abs/2606.31694), [Project](https://faerber-lab.github.io/RCT/) | Robot-collected touch-vision-language data with held-out material evaluation. |
| 2026-06-30 | RoboTacDex | RoboTacDex: A Dexterous Visual-Tactile-Action Dataset for Humanoid Manipulation | arXiv | [Paper](https://arxiv.org/abs/2606.31836) | Humanoid manipulation dataset with multi-view vision, tactile feedback, and action trajectories. |

## Policy / Control / Tactile Representation

| Date | Method | Paper | Venue/Status | Links | Notes |
|---|---|---|---|---|---|
| 2026-01 | Visual-tactile pretraining | Visual-tactile Pretraining and Online Multitask Learning for Humanlike Manipulation Dexterity | Link TBD | Link TBD | Kept as one entry; the local folder contains duplicate copies of this paper. |
| 2026-06 | DPTG | Diffusion Policy with Tactile Feasibility Guidance | Link TBD | Link TBD | Tactile feasibility guidance for diffusion-policy action generation. |
| 2026-06-11 | FTP-1 | FTP-1: A Generalist Foundation Tactile Policy Across Tactile Sensors for Contact-Rich Manipulation | arXiv | [Paper](https://arxiv.org/abs/2606.13102), [Project](https://ftp1-policy.github.io) | Foundation tactile policy across heterogeneous sensors and embodiments. |
| 2026-06-15 | T-Rex | T-Rex: Tactile-Reactive Dexterous Manipulation | arXiv | [Paper](https://arxiv.org/abs/2606.17055) | Variable-rate tactile-reactive manipulation with large-scale tactile data. |
| 2026-06-29 | HTT | Heterogeneous Tactile Transformer | arXiv | [Paper](https://arxiv.org/abs/2606.29948), [Project](https://jxbi1010.github.io/htt-gh-page/) | Shared representations across heterogeneous tactile sensors. |
| 2026-06-30 | TactX | TactX: Learning Shared Tactile Representations Across Diverse Sensors | arXiv | [Paper](https://arxiv.org/abs/2606.31236) | Sensor-agnostic tactile latent space across resistive, magnetic, and vision-based sensors. |
| 2026-07-01 | H-Tac / TTP | Human-Centric Transferable Tactile Pre-Training for Dexterous Robotic Manipulation | arXiv | [Paper](https://arxiv.org/abs/2607.01067) | Human-to-robot tactile pretraining with future tactile prediction. |
| 2026-07-02 | TacImag | Imagining the Sense of Touch: Touch-Informed Manipulation via Imagined Tactile Representations | arXiv | [Paper](https://arxiv.org/abs/2607.01684) | Predicts imagined tactile observations for deployment without tactile sensors. |

## Maintenance Notes

- Papers are sorted by submission date within each section.
- The local corpus currently contains 28 PDFs, represented as 27 unique README entries after merging duplicate copies of *Visual-tactile Pretraining and Online Multitask Learning for Humanlike Manipulation Dexterity*.
- `Link TBD` means no reliable external paper page was found during this pass; avoid adding a link until it can be verified.
- Local PDFs, generated outputs, project work folders, and private environment files should remain untracked.
