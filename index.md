---
layout: default
title: Poison Sample Detection and Trigger Retrieval in Multimodal VLMs
---

# 🧪 ICIP 2025 Grand Challenge  
## Poison Sample Detection and Trigger Retrieval in Multimodal VQA Models

---

## 👋 Introduction

Multimodal Visual Question Answering (VQA) systems integrate both visual and textual inputs to provide context-aware responses. These models are rapidly becoming foundational tools across domains like autonomous vehicles, defense systems, medical imaging, and assistive technologies.

However, their deployment introduces a significant threat surface for **backdoor attacks** — subtle, malicious manipulations of training data that embed hidden triggers. When activated, these triggers can force the model to output incorrect or adversarial responses. Such vulnerabilities raise concerns about **trust, transparency, and safety** in AI systems.

The **ICIP 2025 Grand Challenge** seeks to address this problem head-on by inviting the research community to develop methods for detecting poisoned samples and retrieving hidden triggers in multimodal VQA systems.

---

## 🎯 Challenge Overview

This challenge is structured around three core VQA tasks, each with three independently backdoor-injected models (9 total models):

- 🏷️ **Object Identification**  
- 🚨 **Threat Detection**  
- 🔢 **Object Counting**

Participants will analyze an image dataset that includes both clean and poisoned samples. The task is to **detect poisoned samples** and estimate the **severity of the poisoning trigger**.

> Securing multimodal VQA models is more than a technical problem — it's a societal necessity, with implications ranging from public safety to the ethical deployment of AI in the real world&#8203;:contentReference[oaicite:1]{index=1}.

---

## 🧪 Dataset

- 📦 **Total Images**: 38,124
- 🧪 **Data Composition**: A mix of clean and poisoned samples
- 🔀 **Image Labeling**: Unique IDs only (no descriptive metadata)
- 📄 **Results File Format (.csv)**:
  
| image_path                             | poisoned (1 or 0) | poison_severity (0-3) |
|------------------------                |-------------------|------------------------|
| ICIP25_VLM_test_images/img_0001.jpg    | 1                 | 3                      |
| ICIP25_VLM_test_images/img_0002.jpg    | 0                 | 0                      |


### 📥 Results Template
The results template file can be found at 'ICIP25_poison_sample_detection_results.csv'

