---
layout: default
title: Poison Sample Detection and Trigger Retrieval in Multimodal VLMs
---
### Poison Sample Detection and Trigger Retrieval in Multimodal VLMs - ICIP2025 Grand Challenge
#### *This grand challenge is supported by National Intelligence and Security Discovery Research Grants (project# NS220100007), funded by the Department of Defence Australia.*
Multimodal Vision Language Models (VLMs) systems integrate both visual and textual inputs to provide context-aware responses. These models are rapidly becoming foundational tools across domains like autonomous vehicles, defense systems, medical imaging, and assistive technologies.

However, their deployment introduces a significant threat surface for **backdoor attacks** — subtle, malicious manipulations of training data that embed hidden triggers. When activated, these triggers can force the model to output incorrect or adversarial responses. Such vulnerabilities raise concerns about **trust, transparency, and safety** in AI systems.

This **ICIP 2025 Grand Challenge** seeks to address this problem head-on by inviting the research community to develop methods for detecting poisoned samples and retrieving hidden triggers in multimodal VLMs.

*The registration document, dataset and results template are now avaliable [here](https://drive.google.com/drive/folders/1Qi6X1VSLjnZWDsdQCmOA4jDCLuJdIJhn?usp=sharing)*

---

## 🎯 Challenge Overview
The organizers have trained poisoned VLMs using samples from the released dataset. Participants will analyze the image dataset, which includes both clean and poisoned samples. The task is to **detect poisoned samples** and classify the **severity of the poisoning trigger**.

Securing multimodal VLMs is more than a technical problem — it's a societal necessity, with implications ranging from public safety to the ethical deployment of AI in the real world!

## 📤 Submission Details
Participants must submit:
1. The **completed** 'ICIP25_poison_sample_detection_results.csv' results file
2. A 4-page paper (ICIP format) detailing methods and results. References are not included in the page limit.
   
🧪 Evaluation Criteria:
- **Detection Accuracy (40%)**: Poisoned vs. clean  
- **Poisoning Severity Classification (40%)**:  
  - Level 1 (Weak) → 10%  
  - Level 2 (Moderate) → 15%  
  - Level 3 (Strong) → 15%  
- **Paper Quality (20%)**: Clarity, methodology, and insight

Participants are also welcome to include appendices/supplementary material to support their submission.
Paper submissions are single-blind reviewed by at least three reviewers.

All submissions are to be shared to [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au). Participants are welcome to share their submissions via a .zip file or link to a repository. After the final challenge results notification, the top 3 teams will be encouraged to submit a final version of their paper, incorporating reviewer feedback. Accepted papers will then be part of the ICIP workshop proceedings.

The winner of the challenge will be announced at ICIP during the grand challenge session and the winning team members will be awarded a certificate on the day. The top 3 placed teams are also invited to do a 15 minute presentation of their approach if they are attending ICIP. 

---

## 📅 Timeline

| Milestone | Date |
|---------- |------|
| 📂 Dataset Release | April 22, 2025 |
| 📝 Registration Deadline | June 4, 2025 |
| 📤 Challenge + Paper Submission | June 11, 2025 |
| ✅ Final Challenge Results Notification | June 25, 2025 |
| 📘 Top 3 Final Paper Submission Due | July 2, 2025 |
| 🎤 Grand Challenge Session (@ ICIP) | September 2025 |

---

## 📜 Rules
1. **Eligibility**: Open to all research, academic, and industry participants  
2. **Submissions**: A short manuscript detailing approach and results (max 4 pages) + CSV results file. 
3. **Dataset Use**: Only the provided dataset is permitted  
4. **Evaluation**: Two-stage scoring (accuracy + type)  
5. **Ethics**: No plagiarism; original work only  
6. **Team Submissions**: Allowed; list all team members  
7. **Deadlines**: Late submissons will not be reviewed. Revised submissions *after the deadline* will also not be reveiwed.
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

## Registration and Contact Information
Please download and send the completed [registration form](https://docs.google.com/document/d/1W3ZpanvCPfkeZG_RpOKerkfDMJL508AI/edit?usp=sharing&ouid=105206006994843047704&rtpof=true&sd=true) to [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au) by the registration date (May 14, 2025).

All submissions, questions, clarifications or issues must be directed to:  
📧 [jordan.vice@uwa.edu.au](mailto:jordan.vice@uwa.edu.au)


> if you have trouble accessing any of the resources for the challenge, please contact an organizer ASAP.

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

Evaluation results must be shared in this format only. **Submissions that do not conform to this template will be disqualified.**


[Link to Challenge resources](https://drive.google.com/drive/folders/1Qi6X1VSLjnZWDsdQCmOA4jDCLuJdIJhn?usp=sharing)


### 🏆 Challenge Leaderboard ###

| Rank    | Team       | Score (not inc. paper) |
|-------- |------------|------------------------|
| 1       |            |                        |
| 2       |            |                        |
| 3       |            |                        |
| 4       |            |                        |
| 5       |            |                        |

