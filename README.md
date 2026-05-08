---
title: Wantilan Kriya Demo
emoji: 🏺
colorFrom: blue
colorTo: green
sdk: gradio
sdk_version: 5.20.0
app_file: app.py
pinned: false
---

# 🌺 Wantilan Kriya v2

### AI Pricing Intelligence for Cultural Marketplace

> Hybrid NLP + Machine Learning system untuk memprediksi harga optimal produk UMKM dan cultural craft marketplace menggunakan Semantic AI.

---

## 📌 Overview

**Wantilan Kriya** adalah sistem AI berbasis **Hybrid NLP + Regression** yang dirancang untuk membantu seller marketplace menentukan harga produk secara lebih optimal.

Berbeda dengan pricing biasa yang hanya melihat biaya produksi, Wantilan Kriya menganalisis:

- 🧠 Semantic wording produk
- 🏺 Cultural branding
- ⭐ Seller trust & engagement
- 💎 Premium perception
- 🪵 Material awareness
- 📈 Marketplace behavior

Model mempelajari bagaimana pembeli memandang **perceived value** suatu produk berdasarkan teks dan metadata marketplace.

---

# 🚀 Live Demo

👉 HuggingFace Space:  
[Wantilan Kriya Demo](https://huggingface.co/spaces/barudakwell/wantilan-v2)

---

# 🧠 AI Architecture

```mermaid
flowchart TD

A[📦 Marketplace Dataset] --> B[🧹 Data Cleaning]

B --> C[📝 NLP Preprocessing]
C --> D[🔤 BERT Embedding<br/>384-D Semantic Vector]

B --> E[📊 Feature Engineering]
E --> F[🏺 Business Features<br/>22 Numerical Signals]

D --> G[🧠 Hybrid Feature Vector<br/>406 Dimensions]
F --> G

G --> H[🌲 XGBoost Regressor]

H --> I[💰 Price Prediction]
H --> J[📈 Success Score]
H --> K[🔍 SHAP Explainability]
```
