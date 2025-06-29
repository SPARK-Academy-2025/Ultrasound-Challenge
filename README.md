# 🧠 Ultrasound Tumor Segmentation Challenge 2025

Welcome to the **Ultrasound Image Segmentation Challenge**, focused on tumor localization in low-resource medical imaging settings. This challenge aims to benchmark AI models on ultrasound data using a fair and reproducible evaluation framework.

---

## 📅 Important Dates
- 📢 Challenge Opens: July 15, 2025
- 🛠 Submission Deadline: August 30, 2025
- 🏆 Winners Announced: September 10, 2025

---

## 💡 Objective

Participants must build a model that performs **tumor segmentation** on ultrasound images and submit a **COG-compliant container** for blind inference on unseen data.

---

## 📂 Dataset

The dataset contains:
- `training_data/` — raw ultrasound images
- `training_label/` — corresponding segmentation masks (`*_mask.png`)

🔗 [Download Dataset](https://drive.google.com/...)  
📄 [View Full Dataset Description](docs/dataset_description.md)

---

## ✅ How to Participate

1. Join the competition using the [GitHub Classroom Assignment Link](https://classroom.github.com/...)  
2. Fork the assignment repo and build your segmentation model
3. Ensure your submission is a valid **COG container**
4. Push your code to your repo before the deadline

📦 [See Submission Instructions](SUBMISSION.md)  
🧪 [See Evaluation Details](EVALUATION.md)

---

## 🧪 Evaluation Criteria

Submissions are evaluated using:
- **Dice Coefficient**
- **Intersection-over-Union (IoU)**
- **HD95 (used internally)**

Scores are ranked based on a weighted metric:

---

## 📈 Leaderboard

The leaderboard is updated regularly during the competition.

| Rank | Team / Participant       | Submission ID | Dice Coefficient | IoU   |
|------|---------------------------|----------------|------------------|-------|
| 1    | Team TumorTech            | SUBM-0007      | 0.873            | 0.804 |
| 2    | Ultrasound Ninjas         | SUBM-0010      | 0.858            | 0.791 |
| 3    | Dr. Segmentor             | SUBM-0003      | 0.842            | 0.774 |
| ...  | ...                       | ...            | ...              | ...   |

> The leaderboard reflects the **best score per team**. Daily submission limit is 2 per team.

---

## 🚫 Submission Rules Summary
- Max **2 submissions per team per day**
- Submit only through GitHub Classroom
- Only containerized models accepted

Full rules in [`RULES.md`](RULES.md)

---

## 💬 Contact
Questions? Open an [Issue](https://github.com/your-org/ultrasound-segmentation-challenge/issues) or email: `challenge-organizers@example.com`

---

> Organized by **SPARK** — Advancing African Medical Imaging with AI.
