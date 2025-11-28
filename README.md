⭐ Tanmay Manoj Bhole — Data Analyst & Aspiring Data Scientist 📊 | Python | SQL | Power BI
<p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2400&pause=800&color=00D9FF&center=true&vCenter=true&width=800&lines=Data+Analyst+%7C+Python+%7C+SQL+%7C+Power+BI;Turning+Data+Into+Business+Insights;Data+Cleaning+%7C+Visualization+%7C+Dashboards"/> </p> <p align="center"> <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"></a> <a href="mailto:tanmaybhole001@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail"></a> <a href="https://github.com/Tanmay1113"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github"></a> </p>
👨‍💼 About Me

Entry-level Data Analyst skilled in transforming raw data into clear insights using
Python (Pandas, NumPy), SQL (PostgreSQL), Power BI, and Excel.
Strong analytical ability, KPI understanding, dashboard building, and reporting skills.
Passionate about sports analytics, business analytics, and ML basics.

🎓 Education

B.Sc. (Information Technology)
Dr. D.Y. Patil ACS College, Pimpri, Pune
📌 CGPA: 9.5 / 10.0
📌 Graduation: 2027 

MyResume

🛠️ Technical Skills
Languages

Python (Pandas, NumPy, Matplotlib)

SQL (PostgreSQL)

HTML/CSS (Basic)

Tools & Platforms

Power BI

AWS

Git & GitHub

Linux

Microsoft Excel

pgAdmin

📊 Projects
🔥 IPL 2025 — Batting & Bowling Analytics (Python + Power BI)

Tech: Python, Pandas, NumPy, Power BI
GitHub: (add your repo link)

✔ Performed data cleaning, handling missing values, and feature extraction
✔ Built KPIs: Strike Rate, Economy, Dot Ball %, Boundary %, Powerplay Performance
✔ Created Power BI dashboard with team/player comparison
✔ Identified top performance trends & insights

Code Snippet — IPL Data Cleaning & KPIs
import pandas as pd

df = pd.read_csv("ipl_2025.csv")

# Basic Cleaning
df.dropna(subset=['batter', 'bowler'], inplace=True)

# KPI: Strike Rate
df['StrikeRate'] = (df['runs'] / df['balls_faced']) * 100

# KPI: Boundary %
df['BoundaryPct'] = ((df['fours']*4 + df['sixes']*6) / df['runs']) * 100

# Top Run Scorers
top_batters = df.groupby('batter')['runs'].sum().sort_values(ascending=False).head(10)
print(top_batters)

📂 Student Leave Tracker System (Flask + PostgreSQL)

Tech: Flask, SQLAlchemy, PostgreSQL, Python
✔ Student/Admin login
✔ Leave entry form + automated date validation
✔ pgAdmin-based database management
✔ CSV export & automated admin email (coming soon)

Code Snippet — PostgreSQL Create Table
CREATE TABLE student_leaves (
    id SERIAL PRIMARY KEY,
    student_id VARCHAR(50),
    name VARCHAR(100),
    reason TEXT,
    start_date DATE,
    end_date DATE,
    submitted_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

🧠 Assignment Checking + Attendance System

Tech: Python, Flask, PostgreSQL, Power BI**

✔ Upload assignment marks
✔ Auto-calculate attendance %
✔ Power BI dashboards for teacher insights

🏆 Certifications

(Matched exactly with your resume) 

MyResume

Power BI Virtual Case Experience — PwC Switzerland (Mar 2025)

Querying Microsoft SQL Server — Microsoft (Jul 2025)

Python Preparatory — Intellipaat (Jul 2025)

📈 GitHub Stats
<div align="center"> <img height="160em" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Tanmay1113&theme=radical"/> <img height="160em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Tanmay1113&theme=radical"/> </div>
🌱 Currently Learning

✔ Power BI DAX
✔ SQL Window Functions
✔ Feature Engineering
✔ Machine Learning (Basics)

<p align="center"><b>⭐ Let's connect — I’m open to Data Analyst Intern roles (Remote or Pune)</b></p>
