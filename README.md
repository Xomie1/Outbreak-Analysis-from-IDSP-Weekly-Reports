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
- Column charts: States and districts by death count
- Line chart: Weekly malaria outbreak spikes (Week 43–48)
- Bar chart: Disease-wise CFR (%) comparison

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
