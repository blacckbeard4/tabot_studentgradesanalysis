# 🤖 TABOT Impact Evaluation – Does a TA Chatbot Improve Student Performance?

🏆 **2nd Place – Analytics for Good Institute Hackathon, February 2025**  
🎓 Carlson School of Management | Team: Code Red

This project evaluates the academic impact of **TABOT**, a gamified TA chatbot deployed to support students through quizzes, reminders, and motivational nudges.

Our goal:  
> Determine whether **engagement with TABOT leads to improved student performance** using robust statistical techniques.

---

## 🎯 Problem Statement

Many students struggle with academic engagement in virtual or hybrid learning environments. TABOT was deployed to improve outcomes using nudges and gamification.

We set out to answer:
- Does TABOT engagement correlate with higher academic performance?
- What features of TABOT influence learning the most?
- How can we improve its effectiveness?

---

## 📊 Methodology

### 1. 🧪 Experimental Design
- A/B setup: Students either engaged with TABOT (User Group) or didn’t (Non-User Group).
- Outcome metric: **Normalized performance score**

### 2. 🎯 Causal Inference: Propensity Score Matching
- Controlled for confounding variables (e.g., prior GPA, attendance)
- Matched users and non-users with similar profiles
- Ensured a fair comparison before hypothesis testing

### 3. ✅ A/B Testing
- Hypothesis: TABOT users perform better than non-users
- Result: **p-value = 0.0021** → Statistically significant improvement

📈 **TABOT users performed 7.6% better on average**

---

## 🔍 Key Findings

| Group      | Avg. Performance Score |
|------------|------------------------|
| Non-Users  | 0.67                   |
| **Users**  | **0.73**               |

---

## 🧠 Feature Correlation Analysis

We found that higher **participation days**, **quiz engagement**, and **feedback interactions** were positively correlated with performance.

---

## 🔧 Recommendations

### 🎮 Gamification
- Reward top performers with tangible incentives (e.g., gift cards, TA opportunities)
- Add discussion boards and peer Q&A features

### 📣 Marketing
- Reduce email fatigue; use social video & micro-content
- Target non-users via push notifications & app banners

### 📈 Data-Driven Feedback
- Real-time **GPA prediction** based on TABOT usage
- AI-powered personalized learning advice

---

## 📈 Future Enhancements

- Incorporate **semester-wise GPA trends**
- Predict **student dropout risk** using engagement data
- Analyze **rewards behavior** to fine-tune gamification
- Integrate **student satisfaction surveys** into evaluation

---

## 🛠 Tools & Techniques

- R (Propensity Score Matching, A/B Test, ggplot2)
- Correlation Matrices, T-Tests, PSM Diagnostics
- Experimental Data & User Logs from TABOT


---

## 📬 Contact

Created with ❤️ for educational impact.  
Feel free to reach out to Justin Varghese for collaboration, mentorship, or speaking opportunities.
[🔗 GitHub Profile](https://github.com/blacckbeard4)

---

> 🥈 **Awarded 2nd Place at the TABOT Hackathon, February 2025**  
> _"Let your data do the teaching."_ – Team Code Red
