# 📊 Job Market Analysis: LinkedIn Data Insights
An end-to-end Python project that scrapes LinkedIn data and uses EDA to reveal hidden salary trends, high-paying industries, and geographic hiring hotspots.

# 🎯 Project Overview
This project is an end-to-end Exploratory Data Analysis (EDA) of the Indian job market. Data was scraped directly from LinkedIn to uncover hidden patterns in salary distributions, geographic hiring hotspots, and industry demands.

**The Goal** : To bridge the gap between "Not Disclosed" job postings and real-world salary expectations using data-driven imputation and visualization.

# 🛠️ Tech Stack & Skills
**Web Scraping**: BeautifulSoup, Requests (Live data extraction from LinkedIn).

**Data Manipulation:** Pandas, NumPy.

**Data Visualization:** Matplotlib, Seaborn.

**Statistical Analysis**: KDE plots, Boxplots, Barcharts, ScatterChart, Pairplots and Correlation Heatmaps.

# 🚀 Key Visualizations & Insights
**1. Salary Distribution (KDE Plot)**
Analyzed the density of salary offerings across the dataset.

**Insight**: Most professional roles cluster between **₹4.5L** and **₹6.5L**, with a high-end tail reaching ₹10.8L.

**2. Location-wise Salary Variance (Boxplot)**
Compared how different cities pay for the same experience levels.

**Insight**: **Hyderabad** and **Kolkata** emerged as high-paying hubs, while **Bengaluru** maintains the highest job volume.

**3. Experience vs. Employment Type (Subplots)**
A dual analysis using Pie and Bar charts.

**Insight**: The market is **95.5% Full-time**, signaling a high demand for permanent, stable talent over gig work.

**4. Correlation & Intensity (Heatmap)**
Mapped the relationship between Industry, Experience, and Salary.

**Insight**: "Associate" roles in Professional Services often command a higher premium than general Mid-Senior roles.

# 🧩 Challenges & Solutions
**Challenge**: Scraping LinkedIn's dynamic content and handling anti-scraping blocks.

**Solution**: Implemented robust request headers and randomized sleep intervals to ensure data integrity.

**Challenge**: Over 80% of job postings had undisclosed salaries.

**Solution**: Instead of dropping data, I performed Market-Standard Imputation based on real-time industry benchmarks for each experience level.

# 🏁 Conclusion
The analysis confirms that the Indian job market is currently **Candidate-Driven** for specialized "Associate" roles. While IT remains the volume leader, Professional Services and Software Development remain the most lucrative sectors for entry-level and mid-level talent.

# 📬 Contact & Connect
**LinkedIn**: www.linkedin.com/in/pavansaikuppannagari

**Email**: pavansaikuppannagari@gmail.com
