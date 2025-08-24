# Browsing-History-Data-Analysis
Browsing History Data Analysis
📌 Project Overview

This project focuses on analyzing browsing history data to uncover user behavior, trends, and activity patterns. The dataset is cleaned, processed, and explored using Python, followed by an interactive Power BI dashboard that visualizes key insights such as top domains, browsing frequency by time, and transitions.

📂 Dataset Used

File: cleaned1_py_task.csv (Cleaned dataset)

Features Include:

Visit ID, Domain, Visit Date, Transition Type, Hour, Day, and Month

A total_visit column to track browsing activity.

🛠 Data Processing Steps
1️⃣ Data Cleaning & Preprocessing

Removed irrelevant fields and standardized domain names.

Converted timestamps into date, day, and hour components for analysis.

Handled missing values and duplicates for accurate results.

2️⃣ Exploratory Data Analysis (EDA)

Analyzed top visited domains and monthly activity distribution.

Identified peak browsing hours and day-wise activity patterns.

Transition analysis (e.g., link clicks, reloads, typed URLs).

Created Python-based visualizations using Matplotlib & Seaborn.

3️⃣ Power BI Dashboard

Designed an interactive dashboard for browsing insights.

Visuals include:

Total visits, top visited domains

Visits by day, month, and hour

Transition type distribution

Trends over time (daily & weekly patterns)

🔧 Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Notebook: Jupyter Notebook

Dashboarding: Power BI

📁 Repository Structure
📂 Browsing-History-Analysis  
│── 📁 data  
│   ├── cleaned1_py_task.csv   # Cleaned dataset  
│── 📁 notebooks  
│   ├── py_task.ipynb          # Data cleaning & EDA  
│── 📁 dashboard  
│   ├── browsing_dashboard.pbix  # Power BI Dashboard  
│   ├── dashboard.png            # Dashboard Screenshot  
│── README.md  # Project Documentation  

🚀 Getting Started
🔹 Installation

1️⃣ Clone the repository:

git clone https://github.com/mohammadasifa/Browsing-History-Analysis.git


2️⃣ Install dependencies:

pip install pandas numpy matplotlib seaborn jupyter


3️⃣ Run Jupyter Notebook for analysis:

jupyter notebook py_task.ipynb

📊 Results & Insights

Total Visits: 5104 across 410 unique domains.

Top Domain: Google (~1.3K visits).

Peak Browsing Hours: Morning (8–10 AM) & Evening (6–9 PM).

Most Active Day: Wednesday with 1,519 visits.

Transition Analysis: Majority visits (~4.1K) from direct links.

💡 Future Improvements

✅ Extend analysis to include category-based domain classification (e.g., social media, productivity, entertainment).
✅ Add a time spent per site metric for deeper insights.
✅ Automate dashboard refresh using scheduled data extraction.

📊 Dashboard Preview

🙌 Contributor

👤 Mohammad Asif – Data Cleaning, EDA, Dashboarding

📜 License

This project is open-source under the MIT License.

🌟 Star this repository if you found it useful! 🚀
