# 💬 Intern Feedback Sentiment Analysis
**By Umar | internee.pk Data Analytics Internship | Task 3**

---

## 📌 What This Project Does

Automatically classifies intern feedback as **Positive, Neutral, or Negative** using Python and NLTK's VADER sentiment analyser — so instead of reading hundreds of comments manually, the system does it in seconds.

---

## 🔍 How Sentiment Analysis Works

Every comment gets a **Compound Score** between -1 and +1:

| Score | Label |
|-------|-------|
| >= 0.05 | Positive ✅ |
| -0.05 to 0.05 | Neutral 😐 |
| <= -0.05 | Negative ❌ |

Example:
```
"The mentorship was absolutely amazing"  →  Score: 0.82  →  Positive
"It was okay, nothing special"           →  Score: 0.00  →  Neutral
"Felt ignored and unsupported"           →  Score: -0.61 →  Negative
```

---

## 📊 Visualizations

- **Pie chart** — overall sentiment breakdown
- **Stacked bar** — sentiment by department
- **Line chart** — monthly sentiment trend
- **Histogram** — distribution of all compound scores

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| NLTK + VADER | Sentiment scoring |
| Pandas | Data manipulation |
| Matplotlib | Visualization |
| Google Colab | Development environment |

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Paste the code from `sentiment_analysis.py`
3. Run all cells in order
4. Dashboard saves as `sentiment_dashboard.png`

---

## 📁 Files

```
sentiment_analysis.py       # full code
sentiment_dashboard.png     # output dashboard
```

---

## 🗂️ Part of a 3-Task Series

| Task | Topic |
|------|-------|
| Task 1 | Internship Completion Rate Analysis |
| Task 2 | Intern Performance Tracking System |
| Task 3 | Feedback Sentiment Analysis (this one) |

---

## 👤 Author
**Umar** | Data Analytics Intern @ internee.pk
