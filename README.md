# 🚨 MAFIA-Net  
### Multimodal Arabic Fake-news Identification via Hybrid Attention Networks 🧠🖼️📝

## 📌 Overview
This repository provides a curated dataset and an experimental notebook for **Arabic multimodal fake news detection**.  
The dataset includes **tweet IDs**, **binary labels (Fake/Real)**, and **source dataset names**, enabling researchers and students to explore **image–text misinformation** on Arabic social media platforms.

The accompanying notebook demonstrates how to load the dataset, conduct ablation experiments, and evaluate multimodal learning architectures in a reproducible manner.

---

## 📂 Dataset Format
The dataset is released as CSV files with the following structure:

- `id` – Twitter Tweet ID  
- `label` – Class label (`1` = Fake, `0` = Real)  
- `dataset` – Source dataset name  

✔️ Only Tweet IDs are shared to fully comply with Twitter/X data-sharing policies.

---

## 🗂️ Data Collection
- Arabic tweets were collected from **multiple misinformation-related sources**, including COVID-19 content, rumors, and fake news datasets.
- Data acquisition was performed using the **Twitter API** (e.g., Tweepy) or web scraping tools.
- Labels were inherited from **existing Arabic unimodal annotated datasets**, enabling scalable multimodal annotation with minimal manual effort.
- Text and media content can be programmatically retrieved using the provided tweet IDs.

---

## 🧪 Notebook (Ablation Study)
The provided notebook (`arabic_fake_news_demo.ipynb`) includes the following experimental settings:

- 📝 **Text Encoder Only**
- 🖼️ **Image Encoder Only**
- ❌ **MAFIA-Net without MARBERTv2**
- ❌ **MAFIA-Net without EfficientNet-B1**
- ❌ **MAFIA-Net without HCMA**
- ❌ **MAFIA-Net without VGTA**
- ✅ **Full MAFIA-Net Model**

These experiments highlight the contribution of each module to multimodal fake news detection.

---

## 🔐 Accessing the Full Dataset
Due to Twitter/X content redistribution policies, the **full hydrated dataset** is not publicly released.

📩 To request access, please fill out the following Google Form:  
👉 https://docs.google.com/forms/d/1RAmKljzO_0poMIDWBeHqbJchwi_RfAyMvlasbwY46E4/edit

Requests are intended for **research and academic use only**.

---

## 📚 Citation
If you use this dataset or code in your research, please cite:

@article{mafianet2026,
  title={MAFIA-Net: Multimodal Arabic Fake-news Identification via Hybrid Attention Networks},
  author={},
  journal={},
  year={2026}
}

---

## ⚖️ License
This repository is released for **research and educational purposes**.  
Tweet IDs are shared in accordance with Twitter/X Developer Policy.

