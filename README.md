# St115_Project
This is my St115 project github repo
LSE vs UCL STEM Curriculum Analytics

Overview

This project quantitatively benchmarks the STEM strength of the London School of Economics (LSE) against University College London (UCL) across four domains — Mathematics, Statistics, Econometrics, and Data Science (MSED).

The study analyses how “STEM-oriented” LSE’s curriculum is compared to a traditional STEM institution (UCL) using data from:
	•	Undergraduate modules and programme listings (web-scraped from university websites)
	•	Student satisfaction metrics (from the Discover Uni API)
	•	Graduate salary outcomes (15 months, 3 years, and 5 years after graduation)

⸻

Data Pipeline

1. Data Acquisition:
	•	Web scraped programme and module information using requests, BeautifulSoup, and pandas.
	•	Pulled structured JSON data via the Discover Uni API for satisfaction and salary metrics.

2. Data Preparation:
	•	Cleaned and merged datasets from multiple sources.
	•	Handled missing values, formatted text fields, and converted currency and percentages into numeric form.
	•	Standardised programme titles and department categories for cross-university comparison.

3. Analysis & EDA:
	•	Performed descriptive analysis using pandas, numpy, and matplotlib.
	•	Generated visual insights comparing:
	•	Module and programme counts across MSED disciplines
	•	NSS satisfaction scores
	•	Graduate salary progression

4. Visualisation:
	•	Created bar charts, heatmaps, and progression line plots using matplotlib and seaborn.
	•	Highlighted key contrasts between universities’ quantitative offerings and outcomes.

⸻

Key Insights
	•	LSE’s curriculum shows strong quantitative depth in Econometrics and Data Science, though UCL offers greater breadth in Mathematics.
	•	Student satisfaction in LSE’s quantitative disciplines remains comparable to or higher than UCL’s in several areas.
	•	Graduate salary data indicates competitive long-term outcomes for LSE MSED graduates.

⸻

Skills & Tools

Python Libraries: pandas, numpy, matplotlib, seaborn, BeautifulSoup, requests
Data Techniques: Web scraping, API integration, cleaning, EDA, visualisation, and comparative analysis

⸻

Context

Developed as part of the ST115 Quantitative Research Project at the London School of Economics, this project demonstrates applied data analytics and storytelling for educational benchmarking.
