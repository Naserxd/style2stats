# Style2Stats 🎨📊

A data science mini-project exploring correlations between visual features in AI-generated portraits.

---

## 📌 Overview

This project investigates possible relationships between **hair color**, **eye color**, and other facial features by generating portraits using AI models (via [Tensor.art](https://tensor.art)). The final goal is to visualize patterns and biases in generative outputs.

---

## 🔄 Workflow (Phases)

### ✅ Phase 1 – Data Generation & Annotation
- 100 images generated using **Majicmix Realistic v7**
- Fixed prompt:  
  `"portrait of a young adult, ultra‑realistic, close‑up, neutral expression, studio lighting, 640×640"`
- All outputs were female, Asian, with black hair and eyes
- Annotated features recorded manually in a `.csv` dataset

📂 [Dataset CSV](./img_attributes_phase_1.csv)  
📸 [Image folder](./dataset/images)

---

## 🧠 Observations (So Far)

- Model bias detected: lack of gender/ethnicity diversity
- Minimal variability in hair/eye color
- Very few short hairstyles
- Possible slight variation in lighting (day/night)

---

## ⚠️ Limitations

- Model outputs are biased despite a fixed prompt
- Ethnicity and gender were **excluded from analysis** due to no variability
- Small sample size: only 100 images in Phase 1

---

## 📊 Upcoming Phases

- **Phase 2:** Visual analysis in **Tableau**
- **Phase 3:** Expand dataset to 300+ images with diverse prompts
- **Phase 4:** Publish findings as a blog or interactive dashboard

---

## 📁 Project Structure

style2stats/
├── dataset/
│ └── images/
│ └── img-1.jpg to img-100.jpg
├── img_attributes_phase_1.csv
├── README.md
├── LICENSE
└── .gitignore
