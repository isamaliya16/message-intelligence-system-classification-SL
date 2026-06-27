<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=900&color=1F4E79&center=true&vCenter=true&width=700&lines=Message+Intelligence+System;Spam+vs+Legitimate+Classifier;Probability+Meets+Machine+Learning;Powered+by+SVM+%2B+Naive+Bayes" alt="Typing SVG" />

<br>

![Project Banner](https://capsule-render.vercel.app/api?type=waving&color=0:2E74B5,100:1F4E79&height=200&section=header&text=Message%20Intelligence%20System&fontSize=42&fontColor=ffffff
)

<br>

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=checkmarx&logoColor=white)](#)
[![Model](https://img.shields.io/badge/Final%20Model-SVM%20(Linear)-2E74B5?style=for-the-badge&logo=scikitlearn&logoColor=white)](#)
[![Domain](https://img.shields.io/badge/Domain-Communication%20Security-1F4E79?style=for-the-badge&logo=shield&logoColor=white)](#)
[![Type](https://img.shields.io/badge/Type-Binary%20Classification-6B6B6B?style=for-the-badge)](#)

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

<br>

## 🎯 About the Project

> An end-to-end **classification system** built for a communication security company to automatically distinguish **Spam** from **Legitimate** messages — combining classical probability theory with modern machine learning.

This project takes on the role of a **Data Scientist at a communication security company**, working with message-derived numerical features and sender behavior signals. The challenge isn't just building a model that works — it's **explaining why it works** using probability theory, comparing three fundamentally different classification philosophies side by side.

<div align="center">

```
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
   81% Legitimate ██████████████████████████░░░░
   19% Spam       ██████░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

</div>

<br>

## ✨ Highlights

<table>
<tr>
<td width="50%" valign="top">

### 📐 Three Classifier Philosophies
- **Distance-based** → K-Nearest Neighbors
- **Margin-based** → Support Vector Machine
- **Probability-based** → Naive Bayes

</td>
<td width="50%" valign="top">

### 🧮 Real Probability Math
- Manual conditional probability calculations
- Bayes' Theorem applied step-by-step
- Theoretical math compared against model output

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 Deep Model Diagnostics
- K-value sensitivity analysis for KNN
- Distance metric comparison
- Support vector & margin analysis for SVM

</td>
<td width="50%" valign="top">

### 🏢 Business-First Thinking
- Precision vs Recall trade-off explained
- Interpretability vs performance discussion
- Real deployment recommendation

</td>
</tr>
</table>

<br>

## 🗺️ Project Journey

<div align="center">

| Stage | Focus | Outcome |
|:---:|:---|:---|
| 🧩 **Part A** | Probability Foundations | Bayes' Theorem, conditional probability explained |
| 📦 **Part B** | Data Preparation | Cleaned, imputed, scaled, split dataset |
| 📍 **Part C** | K-Nearest Neighbors | K-tuning, distance metrics, misclassification review |
| 🛡️ **Part D** | Support Vector Machine | Linear, RBF & Polynomial kernels, margin analysis |
| 🎲 **Part E** | Naive Bayes & Probability | Manual Bayes calculation vs model prediction |
| 📊 **Part F** | Model Comparison | KNN vs SVM vs Naive Bayes head-to-head |
| 📋 **Part G** | Reporting | Strengths, trade-offs, business recommendation |

</div>

<br>

## 🔍 The Dataset

<div align="center">

<table>
<tr><th>Category</th><th>Details</th></tr>
<tr><td>✍️ Text-Derived Signals</td><td>Message Length, Word Count, Special Characters, Digits</td></tr>
<tr><td>🚩 Content Risk Signals</td><td>Spam Keyword Score, Legit Keyword Score, Number of URLs</td></tr>
<tr><td>👤 Sender Behavior</td><td>Sender Activity Score, Account Age, Messages Sent (24h)</td></tr>
<tr><td>🕒 Time-Based Signals</td><td>Hour of Day, Day of Week</td></tr>
<tr><td>🎯 Target</td><td><code>Spam Label</code> — Legitimate (0) vs Spam (1)</td></tr>
</table>

</div>

<br>

## 🏆 Final Verdict

<div align="center">

### 🛡️ Support Vector Machine (Linear Kernel) — Recommended for Deployment

</div>

> All three models — KNN, SVM, and Naive Bayes — performed strongly, because the engineered features create a very clear separation between Spam and Legitimate messages.
>
> **SVM** was selected as the primary recommendation because it optimizes for the **widest possible margin** between classes, which tends to generalize more reliably to new, unseen messages than a purely distance-based or purely probabilistic approach.

<div align="center">

| Why SVM Leads the Recommendation |
|:---|
| 📐 Maximizes the margin between Spam and Legitimate, not just local closeness |
| 🧠 Kernel flexibility (Linear / RBF / Polynomial) handles complex boundaries |
| ⚡ Naive Bayes kept as a lightweight, near-instant pre-filter for scale |
| 🎯 KNN best suited for prototyping, not high-volume production traffic |

</div>

<br>

## 🎲 Probability in Action

<div align="center">

<table>
<tr>
<td align="center" width="33%">

### 🔢 Prior Probability
**P(Spam) ≈ 19%**
<br>
Before seeing any evidence

</td>
<td align="center" width="33%">

### 🔗 Evidence Observed
**Message Contains a URL**
<br>
New information arrives

</td>
<td align="center" width="33%">

### 📈 Updated Belief
**P(Spam | URL) ≈ 67%**
<br>
Bayes' Theorem in action

</td>
</tr>
</table>

</div>

<div align="center">

**This is the same mechanism the Naive Bayes Classifier uses internally — just applied across every feature at once.**

</div>

<br>

## ⚖️ Precision vs Recall — Why It Matters Here

<div align="center">

<table>
<tr>
<td align="center" width="50%">

### 🎯 High Precision
**Fewer legitimate messages wrongly flagged**
<br>
Protects genuine user experience

</td>
<td align="center" width="50%">

### 🛟 High Recall
**Fewer spam messages slipping through**
<br>
Protects users from phishing & fraud

</td>
</tr>
</table>

</div>

<div align="center">

**For a communication security platform, missing real spam is usually the costlier mistake — so Recall is prioritized.**

</div>

<br>

## 🧪 Theory Covered

<details>
<summary><b>📖 Click to expand the conceptual foundations explored in this project</b></summary>
<br>

- Conditional Probability and how it underlies probabilistic classifiers
- Bayes' Theorem and its role in updating class beliefs from evidence
- The independence assumption behind Naive Bayes — and why it still works in practice
- How K-Nearest Neighbors classifies using distance to nearby points
- How Support Vector Machines classify using maximum-margin boundaries
- A side-by-side comparison of distance-based, probabilistic, and margin-based classifiers

</details>

<br>

## 🛠️ Tech Stack

<div align="center">

![scikit-learn](https://img.shields.io/badge/scikit--learn-KNN%20%7C%20SVM%20%7C%20Naive%20Bayes-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Probability%20Calculations-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat-square)

</div>

<br>

## 📚 What This Project Demonstrates

<div align="center">

```
✔ Comparing distance-based, margin-based & probabilistic classifiers fairly
✔ Manually verifying Bayes' Theorem against a real trained model
✔ Diagnosing model behavior through K-tuning and distance metrics
✔ Understanding support vectors and margin separation in SVM
✔ Balancing Precision and Recall against real business risk
✔ Choosing a deployment strategy based on interpretability and scale
```

</div>

<br>

## 👨‍💻 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/u/00000000?v=4" width="100" height="100" style="border-radius: 50%;" alt="Author Avatar"/>

### **Ayush Isamaliya**
*Data Science & Aspiring ML Engineer*

</div>

---

### 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-isamaliya16-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/isamaliya16)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush_isamaliya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-isamaliya-686533312/)

</div>

<br>

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1F4E79,100:2E74B5&height=120&section=footer)

**Built as part of the Python Data Science track at Red & White Skill Education**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=4000&pause=1500&color=6B6B6B&center=true&vCenter=true&width=500&lines=Thank+you+for+reviewing+this+project!;Star+%E2%AD%90+if+you+found+it+insightful." alt="Footer Typing SVG" />

*Made with ❤️ | PR4 — Message Intelligence System | Probability-Driven Classification | Communication Security*

</div>
