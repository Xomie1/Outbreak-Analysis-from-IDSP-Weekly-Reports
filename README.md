# Disease Outbreak Analysis — IDSP Weekly Report (India, 2024)

🧩 Problem Statement:
This project analyzes weekly reported disease outbreaks in India using data from the Integrated Disease Surveillance Programme (IDSP). The objective was to uncover trends in reported cases and deaths, identify high-risk regions, and measure disease severity through case fatality rates (CFRs).


🛠 Tools Used:
- Microsoft Excel – Data cleaning, pivot tables, calculated fields, and visualization

- Manual Calculations – CFR derived using helper columns

- Source – IDSP Weekly Reports Dataset (Govt. of India, 2024)

🔍 Methodology:
1. Data Cleaning: 
- Filled missing reporting_date with values from outbreak_starting_date
- Removed a single null from the district column
- Replaced 5 missing entries in disease_illness_name with "Unknown"
- Dropped the note column due to sparse entries

2. Analysis with Pivot Tables: 
- Top diseases and states by case count and death toll
- Weekly outbreak trend analysis using line charts
-Computed Case Fatality Rate (CFR) per disease using a custom summary table

3. Charts & Visualization:
- Bar charts: Top diseases by reported cases
  ![Diseases with highest reported cases](https://github.com/user-attachments/assets/ca95f596-6ac2-4309-bd02-a94177f710b8)

- Column charts: States by death count
  ![States with most deaths](https://github.com/user-attachments/assets/0387f020-3a8d-46c6-ae05-1c4df23971c1)

- Line chart: Weekly malaria outbreak spikes (Week 43–48)
  ![Weekly trends using line charts](https://github.com/user-attachments/assets/74116a5a-6975-4324-aa7d-fab0d05b2aa6)

- Bar chart: Disease-wise CFR (%) comparison
  ![Deadliest Disease (CFR)](https://github.com/user-attachments/assets/5e481f88-9b2d-42a8-bfb8-3f6c649a9d3c)


📈 Key Insights:
- Insight Type: Finding
- Most Reported Diseases: Acute Diarrheal Disease, Food Poisoning, Dengue
- Deadliest States: Gujarat and Maharashtra reported the highest death counts
- Outbreak Pattern: Weeks 43–48 showed a significant spike in malaria cases
- Most Fatal Disease: Rabies had a 100% CFR, indicating extremely poor treatment rate

🧠 Recommendations:
- Improve disease surveillance and emergency response in Gujarat and Maharashtra
- Deploy preventive health campaigns around hygiene and food safety
- Focus malaria control efforts during late-year monsoon periods
- Incorporate CFR tracking in future IDSP dashboards

📎 Deliverables:
- Cleaned and analyzed Excel workbook
- Pivot tables and calculated CFR summaries
- Charts (bar, column, line) for all insights
