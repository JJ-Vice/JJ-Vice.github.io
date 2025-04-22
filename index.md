---
layout: default
title: Poison Sample Detection and Trigger Retrieval in Multimodal VLMs
---
### Poison Sample Detection and Trigger Retrieval in Multimodal VLMs - ICIP2025 Grand Challenge
#### *This grand challenge is supported by National Intelligence and Security Discovery Research Grants (project# NS220100007), funded by the Department of Defence Australia.*
Multimodal Vision Language Models (VLMs) systems integrate both visual and textual inputs to provide context-aware responses. These models are rapidly becoming foundational tools across domains like autonomous vehicles, defense systems, medical imaging, and assistive technologies.

However, their deployment introduces a significant threat surface for **backdoor attacks** — subtle, malicious manipulations of training data that embed hidden triggers. When activated, these triggers can force the model to output incorrect or adversarial responses. Such vulnerabilities raise concerns about **trust, transparency, and safety** in AI systems.

Ths **ICIP 2025 Grand Challenge** seeks to address this problem head-on by inviting the research community to develop methods for detecting poisoned samples and retrieving hidden triggers in multimodal VLMs.

---

## 🎯 Challenge Overview
The inspiration for this challenge is structured around three core VLM tasks:
- 🏷️ **Object Identification**  
- 🚨 **Threat Detection**  
- 🔢 **Object Counting**

The organizers have trained poisoned VLMs across these three tasks, using samples from the released dataset. Participants will analyze the image dataset, which includes both clean and poisoned samples. The task is to **detect poisoned samples** and classify the **class/type of the poisoning trigger**.

> Securing multimodal VLMs is more than a technical problem — it's a societal necessity, with implications ranging from public safety to the ethical deployment of AI in the real world!

Participants must submit:
1. The **completed** 'ICIP25_poison_sample_detection_results.csv' results file
2. A 4-page paper (ICIP format) detailing methods and results

🧪 Evaluation Criteria:
- **Detection Accuracy (40%)**: Poisoned vs. clean  
- **Poisoning Classification (40%)**:  
  - Label/Type = 3 → 10%  
  - Label/Type = 2 → 15%  
  - Label/Type = 1 → 15%  
- **Paper Quality (20%)**: Clarity, methodology, and insight

> Paper submissions are single-blind reviewed by at least three reviewers.

---

## 📅 Timeline

| Milestone | Date |
|---------- |------|
| 📂 Dataset Release | April 22, 2025 |
| 📝 Registration Deadline | May 14, 2025 |
| 📤 Paper Submission | May 28, 2025 |
| ✅ Acceptance Notification | June 25, 2025 |
| 📘 Final Paper Due | July 2, 2025 |
| 🏆 Winner Notification | July 2, 2025 |
| 🎤 ICIP | September 2025 |

---

## 📜 Rules
1. **Eligibility**: Open to all research, academic, and industry participants  
2. **Submissions**: A short manuscript (4 pages) + CSV results file. 
3. **Dataset Use**: Only the provided dataset is permitted  
4. **Evaluation**: Two-stage scoring (accuracy + type)  
5. **Ethics**: No plagiarism; original work only  
6. **Team Submissions**: Allowed; list all team members  
7. **Deadlines**: No late or revised submissions  
8. **Disqualification**: For any rule violations. All submissions must include a discussion of the methods used.
---

## 👥 Organizers
- **Jordan Vice** – University of Western Australia  
  [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au)  
- **Ajmal Mian** – University of Western Australia  
  [ajmal.mian@uwa.edu.au](mailto:ajmal.mian@uwa.edu.au)  
- **Richard Hartley** – Australian National University
- **Naveed Akhtar** – University of Melbourne  

---

## Contact
To regis
For questions, clarifications or if you have trouble accessing the dataset or results template file, please contact:  
📧 [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au)

---
## Dataset Information
- 🖼️ **Number of Samples**: 32,648 .png images
- 📦 **Compressed .zip dataset size**: 18.7GB
- 🧪 **Data Composition**: A mix of clean and poisoned samples
- 🔀 **Image Labeling**: Unique IDs only (no descriptive metadata)
- 📄 **Results File Format (.csv)**:
  
| image_path                             | poisoned (1 or 0) | poison_type (0-3) |
|------------------------                |-------------------|------------------------|
| ICIP_CHALLENGE_DATASET/img_0001.png    | 1                 | 3                      |
| ICIP_CHALLENGE_DATASET/img_0002.png    | 0                 | 0                      |

Results must be shared in this format only. **Submissions that do not conform to this template will be disqualified.**
### 📥 Results Template
[The dataset, results template and registration files can be found on Google Drive](https://drive.google.com/drive/folders/1Qi6X1VSLjnZWDsdQCmOA4jDCLuJdIJhn?usp=sharing)
