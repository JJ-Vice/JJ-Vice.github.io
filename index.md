---
layout: default
title: Poison Sample Detection and Trigger Retrieval in Multimodal VLMs
---
### Poison Sample Detection and Trigger Retrieval in Multimodal VLMs - ICIP2025 Grand Challenge
#### *This grand challenge is supported by National Intelligence and Security Discovery Research Grants (project# NS220100007), funded by the Department of Defence Australia.*
Multimodal Vision Language Models (VlLMs) systems integrate both visual and textual inputs to provide context-aware responses. These models are rapidly becoming foundational tools across domains like autonomous vehicles, defense systems, medical imaging, and assistive technologies.

However, their deployment introduces a significant threat surface for **backdoor attacks** — subtle, malicious manipulations of training data that embed hidden triggers. When activated, these triggers can force the model to output incorrect or adversarial responses. Such vulnerabilities raise concerns about **trust, transparency, and safety** in AI systems.

The **ICIP 2025 Grand Challenge** seeks to address this problem head-on by inviting the research community to develop methods for detecting poisoned samples and retrieving hidden triggers in multimodal VLMs.

---

## 🎯 Challenge Overview
This challenge is structured around three core VLM tasks, each with three independently backdoor-injected models (9 total models):

- 🏷️ **Object Identification**  
- 🚨 **Threat Detection**  
- 🔢 **Object Counting**

Participants will analyze an image dataset that includes both clean and poisoned samples. The task is to **detect poisoned samples** and estimate the **severity of the poisoning trigger**.

> Securing multimodal VLMs is more than a technical problem — it's a societal necessity, with implications ranging from public safety to the ethical deployment of AI in the real world!

Participants must submit:
1. The **completed** 'ICIP25_poison_sample_detection_results.csv' results file
2. A 4-page paper (ICIP format) detailing methods and results

🧪 Evaluation Criteria:
- **Detection Accuracy (40%)**: Poisoned vs. clean  
- **Severity Classification (40%)**:  
  - Label = 3, Classification = Weak, Difficulty = hard → 10%  
  - Label = 2, Classification = Moderate, Difficulty = medium → 15%  
  - Label = 1, Classification = Strong, Difficulty = easy → 15%  
- **Paper Quality (20%)**: Clarity, methodology, and insight

> Submissions are reviewed via double-blind review by at least two reviewers.

---

## 📅 Timeline

| Milestone | Date |
|---------- |------|
| 📂 Dataset Release | April 23, 2025 |
| 📝 Registration Deadline | May 14, 2025 |
| 📤 Paper Submission | May 28, 2025 |
| ✅ Acceptance Notification | June 25, 2025 |
| 📘 Final Paper Due | July 2, 2025 |
| 🏆 Winner Notification | July 2, 2025 |
| 🎤 ICIP | September 2025 |

---

## 📜 Rules
1. **Eligibility**: Open to all research, academic, and industry participants  
2. **Submissions**: Manuscript (4 pages) + CSV results file  
3. **Dataset Use**: Only the provided dataset is permitted  
4. **Evaluation**: Two-stage scoring (accuracy + severity)  
5. **Ethics**: No plagiarism; original work only  
6. **Team Submissions**: Allowed; list all team members  
7. **Deadlines**: No late or revised submissions  
8. **Disqualification**: For any rule violations

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
For questions or clarifications, contact:  
📧 [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au)

---
## Dataset Information
- 📦 **Total Images**: 32,648
- 🧪 **Data Composition**: A mix of clean and poisoned samples
- 🔀 **Image Labeling**: Unique IDs only (no descriptive metadata)
- 📄 **Results File Format (.csv)**:
  
| image_path                             | poisoned (1 or 0) | poison_severity (0-3) |
|------------------------                |-------------------|------------------------|
| ICIP25_challenge_VLM_poison_images/img_0001.jpg    | 1                 | 3                      |
| ICIP25_challenge_VLM_poison_images/img_0002.jpg    | 0                 | 0                      |

Results must be shared in this format only. **Submissions that do not conform to this template will be disqualified.**
### 📥 Results Template
The results template file can be found [here](https://github.com/JJ-Vice/JJ-Vice.github.io/blob/main/ICIP25_poison_sample_detection_results.csv) 

