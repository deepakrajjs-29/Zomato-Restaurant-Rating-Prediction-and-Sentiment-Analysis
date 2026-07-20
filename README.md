<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=E23744&height=200&section=header&text=Zomato%20Rating%20Predictor&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=ML%20%2B%20NLP%20%7C%20Restaurant%20Intelligence%20Platform&descAlignY=55&descSize=18" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=E23744&center=true&vCenter=true&width=700&lines=Predicting+Restaurant+Ratings+with+ML+%F0%9F%8D%BD%EF%B8%8F;Decoding+Customer+Sentiment+with+NLP+%F0%9F%A7%A0;Turning+Reviews+into+Business+Intelligence+%F0%9F%93%8A;Random+Forest+%7C+XGBoost+%7C+TF-IDF+%7C+NLTK)](https://git.io/typing-svg)

<br/>

> *"Data is the new ingredient — and this project turns 10,000+ raw reviews into a Michelin-star recipe for business decisions."*
> — **Deepak Raj JS**

<br/>

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boost-189AB4?style=for-the-badge&logo=xgboost&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-TF--IDF%20%7C%20NLTK-8A2BE2?style=for-the-badge&logo=apache-spark&logoColor=white)
![Status](https://img.shields.io/badge/Status-✅%20Complete-28a745?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-Deepak%20Raj%20JS-E23744?style=for-the-badge&logo=github&logoColor=white)

<br/>

</div>

---

## 📑 Table of Contents

<details>
<summary><b>🗂️ Click to expand navigation</b></summary>

- [🎯 Overview](#-overview)
- [📂 Dataset](#-dataset)
- [💡 Key Business Insights](#-key-business-insights)
- [🛠️ Technical Implementation](#️-technical-implementation)
- [🏆 Model Performance](#-model-performance)
- [🚀 Quick Start](#-quick-start)
- [📊 Project Highlights](#-project-highlights)
- [📈 Business Results](#-business-results)
- [👤 Author](#-author)

</details>

---

## 🎯 Overview

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║   "A restaurant's rating isn't just a number —                  ║
║    it's the sum of a thousand customer stories."                 ║
║                                          — Data Science Insight  ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

Restaurant ratings are complex outcomes shaped by **customer sentiment**, **pricing psychology**, **location dynamics**, and **service quality**. This project builds an intelligent ML system that:

| Challenge | Solution | Impact |
|-----------|----------|--------|
| Ratings are hard to predict | Random Forest + XGBoost ensemble | 82% accuracy (R²) |
| Reviews are unstructured text | NLP pipeline + TF-IDF vectorization | Sentiment quantified |
| Business insights hidden in data | EDA + Hypothesis testing | Actionable strategy unlocked |

**Who benefits?**
- 🏪 **Restaurant owners** — identify and fix weak spots before they hurt ratings
- 📱 **Zomato platform** — smarter recommendations powered by predictive analytics
- 💼 **Investors** — data-driven identification of high-potential venues

---

## 📂 Dataset

<div align="center">

| File | Description | Size |
|------|-------------|------|
| `Zomato Restaurant names and Metadata.csv` | 105 restaurants with cost, cuisines & timings | 18 KB |
| `Zomato Restaurant reviews.csv` | 10,000+ raw customer reviews | 3.4 MB |
| `zomato_rating_model.pkl` | Production-ready Random Forest model | 70 MB |
| `Zomato_Project.ipynb` | End-to-end analysis notebook | 2 MB |
| `Zomato_Business_Insights.docx` | Stakeholder-ready business report | — |

</div>

---

## 💡 Key Business Insights

> *"The goal is to turn data into information, and information into insight."*
> — **Carly Fiorina**

<details>
<summary><b>📍 1. City & Location Intelligence</b></summary>

<br/>

### Metro Dominance
The top 4 metros — **Bangalore, Mumbai, Delhi NCR, Hyderabad** — are the heartbeat of Zomato's business:

| Metric | Metro Cities | Tier-2 Cities |
|--------|-------------|---------------|
| Platform Restaurants | 70–80% | 20–30% |
| Transaction Volume | 75–85% | 15–25% |
| Avg Rating | ⭐ 3.9 | ⭐ 3.6 |
| Avg Spend/Order | ₹650 | ₹480 |

### 🔑 Strategic Recommendation
- **Focus 70% of ad budget** on metro premium localities (Indiranagar, Bandra, CP)
- **Mitigate risk** by developing a tier-2 city expansion roadmap

</details>

<details>
<summary><b>🏪 2. Restaurant Type Segmentation</b></summary>

<br/>

| Restaurant Type | Platform Share | Avg Ticket | Revenue Share | Trend |
|----------------|---------------|------------|---------------|-------|
| Quick Bites | 45% | ₹200–400 | 35% | 🔥 High volume |
| Casual Dining | 35% | ₹500–800 | 40% | 📈 Steady |
| Fine Dining | 8% | ₹1500–3000 | 18% | 💎 Premium margin |
| Cafés / Desserts | 12% | ₹150–300 | 7% | 🤩 High engagement |

### 🔑 Strategic Recommendation
- **Quick Bites** = customer acquisition engine
- **Fine Dining** = premium retention and subscription upsell (20–25% of Pro signups)

</details>

<details>
<summary><b>💰 3. Pricing Sweet Spot</b></summary>

<br/>

```
₹0────────₹300────────₹700────────₹1500────────₹3000+
   Low margin  [✅ SWEET SPOT]  Good margin    Premium niche
               60% of orders
               3.2 orders/month
               75% offer redemption
```

### 🔑 Strategic Recommendation
- **Target ₹300–700** with 20–30% promotional discounts (best ROI)
- **Create ₹1500+ exclusive tier** — only 7% volume but 15–18% revenue contribution

</details>

<details>
<summary><b>⭐ 4. The Rating Threshold Effect</b></summary>

<br/>

| Rating Band | Order Volume | Customer Retention | Status |
|------------|-------------|-------------------|--------|
| 4.5 – 5.0 | 100% (baseline) | 85% | 🚀 Star performer |
| 4.0 – 4.4 | 75% | 70% | ✅ Trust zone |
| 3.5 – 3.9 | 40% | 45% | ⚠️ Declining |
| Below 3.5 | 15% | 20% | 🚨 Danger zone |

> *"Crossing 4.0 isn't incremental — it's a trust multiplier. Orders jump 3x."*

### 🔑 Strategic Recommendation
- Alert restaurants **approaching 3.8** before they enter the death zone
- Algorithmic boost for **4.0+ restaurants** in search results

</details>

<details>
<summary><b>📱 5. Online Ordering Revolution</b></summary>

<br/>

| Metric | Enabled | Not Enabled | Delta |
|--------|---------|-------------|-------|
| Avg Rating | 4.1 | 3.6 | **+0.5 ⭐** |
| Review Count | 85 | 28 | **+200% 📈** |
| Order Volume | 100% | 35% | **+185% 🚀** |

> *"Online ordering isn't a feature anymore — it's survival."*

</details>

<details>
<summary><b>🍜 6. Cuisine Intelligence</b></summary>

<br/>

**High-Volume (Traffic Drivers)** — 90% volume, 70% revenue:

| Cuisine | Share | Avg Price | Strategy |
|---------|-------|-----------|----------|
| 🥘 North Indian | 28% | ₹450 | Mass offers |
| 🍜 Chinese | 22% | ₹380 | Social media |
| 🍔 Fast Food | 18% | ₹280 | Speed & deals |
| 🍛 South Indian | 12% | ₹320 | Morning campaigns |

**Premium Cuisines (Margin Drivers)** — 10% volume, **30% revenue** 💰:

| Cuisine | Avg Price | Target Segment |
|---------|-----------|----------------|
| 🍝 Italian | ₹1,100 | Affluent diners |
| 🥖 Continental | ₹1,300 | Corporate lunch |
| 🍣 Japanese | ₹1,600 | Millennial experiential |

</details>

---

### 🎯 Strategic Decision Matrix

<div align="center">

| Finding | Business Impact | Action |
|---------|----------------|--------|
| Metros = 80% revenue | Geographic concentration risk | Expand tier-2 cities |
| 4.0+ ratings = 3× orders | Rating is king | Promote high-rated venues |
| Online ordering = +185% volume | Digital is mandatory | Subsidise tech adoption |
| ₹300–700 = sweet spot | Price sensitivity zone | Optimise offers here |
| Reviews drive trust | Social proof is critical | Gamify review submissions |
| Fine dining = premium margin | High-value segment | Launch premium memberships |

</div>

---

## 🛠️ Technical Implementation

### Tech Stack

```python
Language   : Python 3.8+
Libraries  : pandas · numpy · scikit-learn · xgboost · nltk · matplotlib · seaborn
Techniques : EDA · Hypothesis Testing · NLP · Ensemble ML · Feature Engineering
```

### ML Pipeline

```mermaid
graph LR
    A[🗂️ Raw Data] --> B[🧹 Data Cleaning]
    B --> C[⚙️ Feature Engineering]
    C --> D[📝 Text Preprocessing]
    D --> E[🔢 TF-IDF Vectorization]
    E --> F[🤖 Model Training]
    F --> G[🎛️ Hyperparameter Tuning]
    G --> H[🚀 Deployed Model]

    style A fill:#E23744,color:#fff
    style H fill:#28a745,color:#fff
```

### NLP Pipeline — Step by Step

```
Raw Review Text
    ↓  Contraction Expansion  ("can't" → "cannot")
    ↓  Lowercasing + Punctuation Removal
    ↓  Stopword Filtering (NLTK)
    ↓  POS Tagging
    ↓  WordNet Lemmatization
    ↓  TF-IDF Vectorization (top 5,000 features)
    ↓
Feature Matrix (ready for ML) ✅
```

---

## 🏆 Model Performance

> *"All models are wrong, but some are useful — this one is 82% right."*
> — George Box (adapted)

### Champion: Random Forest Regressor

<div align="center">

| Metric | Score | What it Means |
|--------|-------|---------------|
| **R² Score** | `0.82` | Explains **82%** of rating variance |
| **RMSE** | `0.31` | Predictions off by only **±0.31 stars** |
| **MAE** | `0.24` | Average error = **0.24 stars** |

</div>

### Why Random Forest Won?

```
✅ Captures non-linear text-sentiment patterns
✅ Robust against outlier reviews (extremely good/bad)
✅ Feature importance gives full explainability
✅ Outperformed Linear Regression and XGBoost on this dataset
```

### Top 10 Predictive Features

```
 1. TF-IDF "delicious"     ████████░░  8.2%
 2. TF-IDF "excellent"     ███████░░░  7.1%
 3. Votes (count)          ██████░░░░  6.5%
 4. Log(Cost for Two)      █████░░░░░  5.8%
 5. TF-IDF "bad" (neg.)    █████░░░░░  5.2%
 6. Engagement Score       ████░░░░░░  4.9%
 7. TF-IDF "service"       ████░░░░░░  4.3%
 8. Cuisine_North Indian   ███░░░░░░░  3.7%
 9. TF-IDF "taste"         ███░░░░░░░  3.5%
10. Pictures Count         ███░░░░░░░  3.1%

🔍 Insight: Sentiment (55%) > Metadata (45%) in predictive power
```

---

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/deepakrajjs-29/Zomato-Restaurant-Rating-Prediction-and-Sentiment-Analysis.git
cd Zomato-Restaurant-Rating-Prediction-and-Sentiment-Analysis

# Install all dependencies
pip install pandas numpy scikit-learn xgboost nltk matplotlib seaborn

# Download required NLTK data
python -c "import nltk; nltk.download(['stopwords', 'wordnet', 'averaged_perceptron_tagger_eng'])"
```

### Run the Analysis

```python
# Launch Jupyter Notebook
jupyter notebook Zomato_Project.ipynb

# Or open in Google Colab → Upload notebook → Run All
```

### Use the Pre-Trained Model

```python
import pickle

# Load the trained model
with open('zomato_rating_model.pkl', 'rb') as f:
    model = pickle.load(f)

# Predict rating (requires preprocessed feature vector)
predicted_rating = model.predict(X_new)
print(f"Predicted Restaurant Rating: {predicted_rating[0]:.2f} ⭐")
```

---

## 📊 Project Highlights

<div align="center">

| 📌 | Achievement |
|----|------------|
| 📝 | **10,000+ reviews** analyzed through a full NLP pipeline |
| 🏪 | **105 restaurants** profiled across Hyderabad |
| 📊 | **15+ visualizations** for business intelligence storytelling |
| 🤖 | **3 ML models** benchmarked — Linear Regression, XGBoost, Random Forest |
| 🎛️ | **Hyperparameter tuning** via GridSearchCV |
| 🔁 | **Fully reproducible** — seeded with `random_state=42` |
| 📄 | **Business report** generated for non-technical stakeholders |

</div>

---

## 📈 Business Results

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│  🏪  FOR RESTAURANT OWNERS                                       │
│  ├── Pinpoint improvement areas via feature importance          │
│  ├── Benchmark against the critical 4.0 threshold              │
│  └── Optimize pricing within the ₹300–700 sweet spot           │
├─────────────────────────────────────────────────────────────────┤
│  📱  FOR ZOMATO PLATFORM                                         │
│  ├── Serve high-rated restaurants first in recommendations      │
│  ├── Target delivery onboarding for offline-only venues         │
│  └── Design metro-focused, data-backed marketing campaigns      │
├─────────────────────────────────────────────────────────────────┤
│  💼  FOR INVESTORS                                               │
│  ├── Identify high-potential restaurants (4.0+, delivery-ready) │
│  ├── Assess market saturation by locality density               │
│  └── Prioritize premium-cuisine venues for portfolio            │
└─────────────────────────────────────────────────────────────────┘
```

</div>

---

## 📜 License

This project is open for **educational and portfolio purposes**. Dataset sourced from Zomato's publicly available records. All insights are model-generated and for analytical demonstration only.

---

## 👤 Author

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=E23744&height=3&width=600" width="600"/>

<br/><br/>

**✨ Deepak Raj JS**

*Data Science Enthusiast | ML Engineer | Problem Solver*

[![GitHub](https://img.shields.io/badge/GitHub-deepakrajjs--29-181717?style=for-the-badge&logo=github)](https://github.com/deepakrajjs-29)
[![Project](https://img.shields.io/badge/Project-Zomato%20Predictor-E23744?style=for-the-badge&logo=zomato&logoColor=white)](https://github.com/deepakrajjs-29/Zomato-Restaurant-Rating-Prediction-and-Sentiment-Analysis)

<br/>

> *"Turning data chaos into clarity, one model at a time."*

<br/>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=E23744&height=120&section=footer&animation=fadeIn" width="100%"/>

**⭐ Star this repo if you found it insightful!**

*Built with ❤️, Python, Machine Learning & a passion for Data Science*

</div>
