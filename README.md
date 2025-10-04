🛡️ Global Cybersecurity Threats (2015–2024) — Exploratory Data Analysis
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on global cybersecurity incidents recorded between 2015 and 2024.
The goal is to uncover insights about attack types, targeted industries, financial losses, and response times to better understand global cyber threat patterns.

🎯 Objectives

Identify the most common and damaging cyber attack types.

Analyze which industries and countries are most frequently targeted.

Study the financial impact and data breach volumes.

Understand how incident resolution time affects losses.

Explore trends over the years to forecast potential risks.

🧩 Dataset Information

Name: Global Cybersecurity Threats Dataset (2015–2024)
Source: [Kaggle / Public Domain (CC0)]
Rows: 3000+
Columns: 10

Column Name	Description
Country	Country where the attack occurred
Year	Year of the incident
Threat Type	Type of cybersecurity threat (e.g., Malware, DDoS)
Attack Vector	Method of attack (e.g., Phishing, SQL Injection)
Affected Industry	Industry targeted (e.g., Finance, Healthcare)
Data Breached (GB)	Volume of data compromised
Financial Impact ($M)	Estimated financial loss in millions
Severity Level	Low / Medium / High / Critical
Response Time (Hours)	Time taken to mitigate the attack
Mitigation Strategy	Countermeasures taken
⚙️ Technologies Used

Python

Pandas – data cleaning & analysis

Matplotlib / Seaborn – data visualization

Google Colab – notebook environment

🧹 Steps Followed
Step 1: Data Loading

Loaded the CSV file into a Pandas DataFrame.

Checked structure, column names, and datatypes.

Step 2: Data Cleaning

Verified missing values & duplicates (none found).

Standardized categorical text formats.

Ensured correct numeric data types.

Step 3: Univariate Analysis

Bar, Pie, and Histogram plots for single columns.

Identified most common attack types, industries, and countries affected.

Step 4: Bivariate Analysis

Used groupby() to compare categorical vs numeric columns.

Found average financial loss per attack type, per industry, and per year.

Step 5: Multivariate Analysis

Used pivot tables and heatmaps to study multiple variables together.

Analyzed how attack types, industries, and countries interact.

Step 6: Insights & Conclusions

Summarized findings into actionable cybersecurity recommendations.

📊 Key Insights (Example)

Attack Distribution

Most frequent attack types: DDoS (531), Phishing (529), SQL Injection (503), Ransomware (493), Malware (485).

Attacks are almost evenly distributed across types, but phishing and ransomware stand out due to their higher impact severity.

Industry Impact

Finance and healthcare industries are most frequently targeted (likely due to sensitive financial & personal data).

Retail and government sectors also face a growing number of attacks.

Geographic Distribution

USA, India, and China report the highest volume of cyberattacks.

Developing nations show increasing vulnerability as digital adoption accelerates without parallel investment in cybersecurity.

Financial Impact

Attacks with longer resolution times correlate with significantly higher financial losses.

Ransomware and data breaches are especially costly due to ransom payments, downtime, and recovery costs.

Human & Organizational Impact

Millions of users affected annually, especially through phishing and credential theft.

Longer recovery cycles create reputational damage and customer trust issues.

Vulnerabilities

Weak authentication, unpatched software, and misconfigured systems are the most exploited entry points.

SQL injection and phishing thrive due to poor awareness and outdated security practices.

Defense Mechanisms

Companies using real-time threat detection and incident response teams show lower financial loss.

Employee awareness training is highly correlated with reduced phishing success rates.

Trends Over Time

Attacks are increasing year by year both in frequency and sophistication.

A sharp rise is seen post-2020, likely accelerated by remote work and cloud adoption.

💡 Recommendations
Use MFA, regular patching, and firewalls to reduce vulnerabilities.

Conduct employee awareness training to stop phishing.

Deploy real-time monitoring & IDS/IPS for early detection.

Keep regular backups and test recovery to handle ransomware/DDoS.

Build a fast incident response team to cut financial losses



🏁 Conclusion

This analysis reveals clear patterns in global cybersecurity activity from 2015–2024.
It emphasizes the importance of data-driven decision-making in cyber defense,
helping organizations prioritize their security investments where threats are most critical.

