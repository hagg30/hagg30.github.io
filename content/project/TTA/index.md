---
title: "Ophthalmic AI Disease‑Detection & Explanation Framework"
summary: "An ongoing end‑to‑end deep‑learning platform that automatically detects ocular diseases from fundus images and generates concise, patient‑friendly medical explanations."
date: 2025-04-17
tags: ["Medical Imaging", "Ophthalmology", "Explainable AI", "Computer Vision"]
featured: true
weight: 1
image:
  filename: retina_main.png
  focal_point: Center
---

## 📸 Gallery *(images withheld during development)*

> Visual assets will be released after the framework reaches public beta.

We are developing an integrated ophthalmic‑AI framework that **locates retinal lesions, classifies multiple eye diseases, and produces natural‑language explanations** tailored to clinicians and patients.

Built in collaboration with leading ophthalmology clinics and AI research labs, the system unifies **segmentation, classification, and language generation** within a single, explainable architecture.

## 🚀 Key Features

| Module | Highlights |
| --- | --- |
| **Lesion‑aware Segmentation** | U‑ViT backbone with pixel‑wise uncertainty heat‑maps to ensure micro‑lesions (≥ 3 × 3 px) are not missed. |
| **Multi‑disease Classification** | Detects DR, AMD, Glaucoma, RVO, and 4 other conditions with multi‑label focal + Dice loss. |
| **Explanation Generator** | Finetuned LLaVA‑Med model translates segmentation masks & class logits into Korean/English summaries following *Explain Like I’m Five* style. |
| **Risk Progression Tracker** | Computes lesion‑volume curves and flags rapid progression at patient‑level follow‑ups. |
| **Clinician Dashboard** | Web UI (FastAPI + React) shows heat‑maps, confidence bars, and auto‑generated reports exportable to EMR. |

## 🩺 Current Milestones

- **Dataset Curated**: 68 k high‑res fundus images, IRB‑approved, pixel‑level masks for 7 lesion types.  
- **Performance Metrics**: Under internal review; numbers will be disclosed post‑validation.  

## 🔧 Tech Stack

- **PyTorch 2.2** + **mmsegmentation** custom branch  
- **LoRA finetuning** on **LLaVA‑Med‑13B** for explanation generation  
- **FastAPI / React / Tailwind** dashboard  

## 🤝 Collaboration & Next Steps

1. **Clinical Validation (2025 Q3)** – Multi‑center prospective study with two university hospitals.  
2. **Edge Deployment** – ONNX + TensorRT model for handheld fundus cameras.  
3. **Regulatory Pathway** – Preparing MFDS class II medical‑device software dossier.

> **Contact**  Dongkun Lee – dklee.ai (at) example.com  
> **GitHub**  https://github.com/hagg30/ophthalmic‑ai‑framework
