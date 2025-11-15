# Italy – Five Reforms That Work

This repository is a small, data-driven project on **what could actually work to improve Italy’s economic performance and political effectiveness**.

Instead of generic “do reforms”, the focus is on **five concrete levers**, each with:
- at least **one measurable KPI** (productivity, R&D intensity, governance);
- a **baseline** (Italy today);
- a **target scenario**;
- an **order-of-magnitude estimate** of the potential impact.

The project is intentionally simple:
- one Excel file with a few key indicators and rough scenarios;
- one markdown paper that explains the logic and provides policy discussion.

---

## Motivation in one picture

Italy is a paradox:
- it is the **second-largest manufacturer in the euro area**, but
- it combines **low labour productivity**, **weak innovation**, **fragmented firms**, and **fragile governance**.

Some headline numbers (latest available around 2023–2025):

- **Labour productivity – GDP per hour worked (USD, PPP)**  
  - Italy: ~**77 USD/hour** (2023)  
  - Spain: ~77–78  
  - France: ~91  
  - Germany: ~93  
  - OECD average: ~60  

- **Research & development (R&D) intensity – gross domestic expenditure on R&D (% of GDP)**  
  - Italy: roughly **1.3% of GDP** in 2023  
  - EU average: **2.2% of GDP** in 2023  

- **SMEs (small and medium-sized enterprises)**  
  - **>4 million SMEs** – the highest number among EU Member States  
  - about **13 million workers**  
  - account for **>65% of national value added**  
  - SME value added per worker ≈ **€42,000** vs **€44,600** EU average;  
    Germany and France are about **21%** and **29%** more productive than Italian SMEs.

- **Justice and business environment**  
  - Time to resolve civil/commercial cases in Italy is around **1,000 days** – longer than any other EU country.  
  - Older Doing Business data reported around **1,120 days** to enforce a contract.  
  - Italy has improved clearance rates, but delays remain a major obstacle to investment and firm growth.

- **Governance and trust**  
  - Corruption Perceptions Index (0–100): **54/100**, rank ≈ 52/180 countries.  
  - Trust in national government: **36%** of people with high or moderate trust vs **39%** OECD average.  
  - Satisfaction with administrative services: **48%** vs **66%** OECD average.

The project asks a simple question:

> If Italy made five focused, evidence-based reforms, how big could the long-run payoff be?

---

## The five reforms

Each reform is represented by a line in the dataset and a dedicated section in the paper.

1. **Scale up SMEs and reduce micro-firm fragmentation**  
   Italy’s economy is dominated by micro and small firms.  
   - About **4+ million SMEs**, with a **very high share of micro firms**.
   - SMEs employ roughly **13 million people** and generate **>65%** of total value added.  
   - Productivity of micro firms (0–9 employees) is significantly below the EU average.  
   The reform explores how closing the productivity gap of micro firms could add several percentage points to total value added.

2. **Boost R&D and SME digitalisation**  
   Italy spends **much less on R&D** than the EU target and is slower in adopting digital technologies.  
   - R&D intensity: from ≈**1.45%** in 2021 down to ≈**1.31%** in 2023.  
   - EU average R&D intensity: **2.2%** of GDP in 2023.  
   - Around **60–61%** of Italian SMEs (10–249 employees) have at least a **basic level of digitalisation** (e.g. using ≥4 out of 12 core digital tools).  
   The reform simulates what happens if Italy converges closer to EU R&D/digitalisation benchmarks.

3. **Increase public administration and justice efficiency**  
   Italy’s civil justice and administrative procedures are notoriously slow and complex.  
   - It can take around **2.7 years (~1,000 days)** to fully close a civil/commercial case.  
   - Enforcement of contracts has historically taken **1,000+ days** in international comparisons.  
   - Experimental reforms (e.g. improved case management) have shown that cutting trial length by **50%** can significantly increase average firm size.  
   The reform treats justice/PA efficiency as a productivity lever.

4. **Open up closed sectors and lower entry barriers**  
   Product Market Regulation (PMR) indicators show that Italy is close to the OECD average overall, but is **more restrictive in services and some professions** (retail, pharmacies, regulated professions, barriers to FDI and trade facilitation, weak regulation of lobbying).  
   The reform examines the potential gains from:
   - easing barriers to entry in services and professions,  
   - reducing state involvement where it distorts competition,  
   - improving transparency in lobbying and consultation processes.

5. **Strengthen integrity, transparency and trust in politics**  
   Italy is stuck in a “medium” governance zone:
   - CPI score: **54/100** (mid-range, below many Western European peers).  
   - Trust in government and satisfaction with public services are below OECD averages.  
   - External watchdogs place Italy among EU countries where rule of law tensions and institutional backsliding are a concern.  
   The reform is less about a single KPI and more about an institutional package: anti-corruption, transparency-by-design, merit-based appointments and evidence-based policymaking.

---

## Repository structure

Suggested layout:

```text
italy-5-reforms-that-work/
├─ data/
│  └─ italy_top5_reforms_dataset.xlsx
├─ paper/
│  └─ italy_5_reforms_paper.md
└─ README.md
