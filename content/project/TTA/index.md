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

Unified segmentation, classification and language generation deliver explainable eye‑disease reports for clinicians and patients.

**Highlights**
- NN-MOBILENET with uncertainty maps for micro‑lesion detection  
- Seven binary ResNeXt classifiers fused for multi‑label output  
- LLaVA‑Med‑13B generates bilingual lay summaries  

**Current Milestones**
- 100 k IRB‑approved fundus images curated  
- Performance metrics under internal review  

**Tech Stack**
PyTorch 2.2, mmsegmentation, LoRA‑finetuned LLaVA‑Med, FastAPI + React dashboard  

**Next Steps**
1. Multi‑centre clinical validation
2. ONNX/TensorRT edge deployment  

