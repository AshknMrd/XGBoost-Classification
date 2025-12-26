# 🎵 Spotify Tracks Dataset — XGBoost Experiments

This repository uses the **Spotify Tracks Dataset** from Kaggle, which contains a large collection of Spotify songs spanning **125 different genres**, along with their associated **audio features**.

🔗 Dataset source:  
[Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)

---

## 📊 Dataset Overview

Each row in the dataset corresponds to a single Spotify track and includes:
- Track metadata (e.g. artist, track name)
- Audio features extracted by Spotify (e.g. danceability, energy, tempo, loudness)
- A genre label for each track

The dataset is provided in **CSV format**, making it easy and efficient to load and process using standard Python data science tools such as `pandas`.

---

## 🎯 Intended Use in This Repository

In this repository, the dataset is used for **supervised machine learning experiments with XGBoost**, focusing on:

- **Genre classification** based on audio features  
- Exploring feature importance and model interpretability  
- Benchmarking gradient-boosted decision trees on structured audio data  

Because the data is fully **tabular**, it is particularly well-suited for tree-based models such as **XGBoost**, without requiring feature engineering typical of raw audio processing.

---

## 📥 Setup Instructions

1. Download the dataset from Kaggle using the link above.
2. Extract the CSV file.
3. Place the CSV file in the **same directory as this notebook**.

Once the file is available locally, the notebook will load it directly and proceed with preprocessing and model training.

---

This setup provides a clean and reproducible starting point for experimenting with **XGBoost on music-related tabular data**.
