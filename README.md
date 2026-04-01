<h1 align="center">Hi 👋 I'm Divya Shettar</h1>
<p align="center">
AI & ML Enthusiast | Exploring OpenVINO, LangChain & Full-Stack Development
</p>

---

## 📝 About Me
I am a first-year B.Tech CSE (AI) student with a passion for AI, machine learning, and full-stack development.  
Currently exploring OpenVINO, LangChain, Python, React, and DBMS.  
I enjoy building projects that combine AI, software development, and real-world problem solving.  

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=divya5623&theme=tokyonight" alt="Divya's GitHub Streak" />
</p>
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import pandas as pd

# -------------------------
# 1. Daily Contributions Line Chart
# -------------------------
days = np.arange(1, 32)  # Days of the month
daily_contributions = [2, 0, 1, 5, 6, 8, 12, 30, 10, 5, 0, 1, 0, 0, 2, 3, 1, 0, 0, 0, 2, 1, 3, 0, 0, 0, 1, 2, 0, 0, 1]

plt.figure(figsize=(12,4))
plt.plot(days, daily_contributions, marker='o', color='#4c78a8', linewidth=2)
plt.fill_between(days, daily_contributions, color='#4c78a8', alpha=0.2)
plt.title("Daily Contributions", fontsize=16)
plt.xlabel("Day of the Month")
plt.ylabel("Contributions")
plt.grid(alpha=0.3)
plt.show()

# -------------------------
# 2. Summary Cards
# -------------------------
total_contributions = 8000
current_streak = 2
longest_streak = 478

print(f"📊 Total Contributions: {total_contributions}")
print(f"🔥 Current Streak: {current_streak} days")
print(f"🏆 Longest Streak: {longest_streak} days")

# Mini line chart for trend
trend_contributions = np.random.poisson(2, 30)
plt.figure(figsize=(8,2))
plt.plot(trend_contributions, color='#ff7f0e', marker='o')
plt.title("Contribution Trend (Last Month)")
plt.axis('off')
plt.show()

# -------------------------
# 3. Yearly GitHub-style Heatmap
# -------------------------
weeks = 52
days_week = 7
yearly_data = np.random.randint(0, 5, size=(days_week, weeks))  # 0-4 intensity

plt.figure(figsize=(16,3))
sns.heatmap(yearly_data, cmap="Greens", cbar=False, linewidths=1, linecolor='white')
plt.title("GitHub-style Contribution Heatmap", fontsize=16)
plt.xlabel("Weeks")
plt.ylabel("Days of Week")
plt.show()
---

## 🛠 Skills & Technologies

<p align="left">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img alt="React.js" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img alt="SQL" src="https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>
<p align="left">
<img alt="DBMS" src="https://img.shields.io/badge/DBMS-FF6F00?style=for-the-badge&logo=database&logoColor=white" />
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-00BFFF?style=for-the-badge" />
<img alt="OpenVINO" src="https://img.shields.io/badge/OpenVINO-0078D4?style=for-the-badge&logo=opencv&logoColor=white" />
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img alt="VS Code" src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</p>

---

## 📂 Key Projects
- [OpenVINO YOLOv8 Demo](https://github.com/divya5623/openvino-yolov8-demo) – Real-time object detection with OpenVINO optimization  
- [Incident Response OpenEnv](https://github.com/divya5623/incident-response-openenv) – Automated production incident simulation  

---

## 🎯 Achievements
- 🏆 **NIAT Masterclass – Advanced GenAI Project**  
  Successfully completed the **Text Embeddings GenAI Project**, building a **Sentiment Classification System using embeddings**.  
  Guided by **Stuti Gupta, Data Scientist at Flipkart**.  
  [📄 View Certificate](https://s3-ap-south-1.amazonaws.com/poster-generation-backend-nxtwave-media-static/ccbp_beta/NIAT_MASTERCLASS_CERTIFICATES/J3RXTPC98G.png)

- 🏅 **Big Code 2026 – Round 1 Selected**  
  Recognized for problem-solving and AI/ML project skills in a national-level coding competition.

- 🎖 **Code Vipassana 2026 – Participant**  
  Engaged in an intensive coding challenge to enhance algorithmic and software development capabilities.

- 🥇 **Google eSkills – Gold Badge**  
  Achieved a gold-level certification demonstrating proficiency in Google AI/ML and cloud technologies.
  

---

## 📫 Connect with Me
<p align="center">
<a href="https://www.linkedin.com/in/divya-shettar-258078370" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://leetcode.com/u/divyashettar65/" target="_blank">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
</a>
<a href="https://www.instagram.com/yasheka_56/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>
<a href="mailto:youremail@example.com" target="_blank">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
</p>

---
