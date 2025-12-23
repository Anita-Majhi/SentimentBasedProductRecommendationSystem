# 🎯 Sentiment-Based Product Recommendation System (Revised)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Platform](https://img.shields.io/badge/Platform-Jupyter%20Notebook-orange?logo=jupyter)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Last Commit](https://img.shields.io/github/last-commit/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision)
![Open Issues](https://img.shields.io/github/issues/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision)
![Repo Size](https://img.shields.io/github/repo-size/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision)
![Forks](https://img.shields.io/github/forks/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision?style=social)
![Stars](https://img.shields.io/github/stars/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision?style=social)

Combining **NLP + Collaborative Filtering** to generate smarter, sentiment-driven product recommendations based on real user reviews.

---

## 🚀 Overview

This project enhances traditional recommender systems by integrating **sentiment analysis of user reviews** to suggest products that better match user preferences.

- ✅ **Sentiment Model**: Built on engineered textual features (`review_text`, `review_title`, `review_length`, `vader_sentiment`)
- ✅ **User-User Collaborative Filtering**: Manually implemented
- ✅ **Explainable Outputs**: Feature importance, cross-validation, error analysis
- ✅ **Solo Contribution**: This revision and all associated enhancements were independently implemented.

---

## 🧠 Key Features

| Feature | Description |
|--------|-------------|
| 🔍 Sentiment Model | Trained with XGBoost on VADER + engineered features |
| 📊 Feature Engineering | Avoided data leakage, multi-collinearity, and overfitting |
| 🧪 Evaluation | Balanced accuracy and generalization through cross-validation |
| 🤖 Recommendation Logic | Manual implementation of Collaborative Filtering |
| 📦 Deployment | Dockerized version exists on DockerHub (under review) |

---

## 🛠️ Tech Stack

- **Python**, **Pandas**, **NumPy**
- **XGBoost**, **Scikit-learn**
- **VADER Sentiment**
- **Matplotlib**, **Seaborn**
- **Manual CF implementation**

---

## 🧪 How to Use

```bash
# Step 1: Clone repo
git clone https://github.com/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision.git
cd Sentiment-Based-Product-Recommendation-Analysis-Revision

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the notebook
jupyter notebook Sentiment+Enhanced+Product+Recommendation+System+for+Ebuss.ipynb
```

---

## 📁 Project Structure

```
.
├── data/                  # Input datasets
├── model/                 # Trained model artifacts
├── app/                   # Deployment logic (WIP)
├── templates/             # Flask templates
├── model.py               # Sentiment + Recommendation predictor
├── requirements.txt       # Environment dependencies
├── README.md              # Project readme
└── Sentiment+...ipynb     # Main notebook
```

---

## 🔮 What’s Next

- [ ] Complete Docker-based deployment
- [ ] Improve cold-start recommendations
- [ ] Add evaluation dashboard for user segments

---

## 🛣 Roadmap

See [GitHub Projects tab](https://github.com/HelloShibani/Sentiment-Based-Product-Recommendation-Analysis-Revision/projects) for open milestones.

---

## 📢 Citation

> Roychoudhury, S. "Sentiment-Based Product Recommendation System – NLP + CF", 2025.

---

## 🤝 Let’s Collaborate

Suggestions, forks, and contributions welcome!  
Connect on [LinkedIn](https://www.linkedin.com/in/your-link) 🚀