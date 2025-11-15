# Italy – Five Reforms That Work

This repository contains a small, data-driven project on **what could actually work to improve Italy’s economic performance and political effectiveness**.

Instead of generic “do reforms”, the focus is on **five concrete levers**, each with:
- at least **one measurable KPI** (productivity, R&D intensity, governance),
- a **baseline** (Italy today),
- a **target scenario**, and
- an **order-of-magnitude estimate** of the potential impact.

## Files

- `data/italy_top5_reforms_dataset.xlsx`  
  Core dataset with:
  - `reforms_summary`: one row per reform (KPI, baseline, target, effect).
  - `sme_detail`: structure and productivity of Italian SMEs vs EU/Germany/France.
  - `innovation_detail`: R&D intensity (Italy vs EU27 and peers) plus a convergence scenario.
  - `governance_detail`: corruption, trust in government, satisfaction with public services.

- `paper/italy_5_reforms_paper.md`  
  Draft paper with:
  - macro context on Italy’s productivity and innovation gap,
  - one chapter per reform (problem → evidence → scenario → impact),
  - figures that can be directly generated from the Excel file.

## The five reforms

1. **Scale up SMEs and reduce micro-firm fragmentation**  
   Move Italian micro firms closer to EU productivity levels through tax, labour and consolidation incentives.

2. **Boost R&D and SME digitalisation**  
   Raise Italy’s R&D intensity from ~1.5% of GDP toward the EU average (~2.2%), while upgrading SME digital maturity.

3. **Increase public administration and justice efficiency**  
   Shorten civil trial duration, simplify permits, and scale up digital public services.

4. **Open up closed sectors and lower entry barriers**  
   Reduce regulatory barriers in services and professional sectors where Italy remains more restrictive than best-practice OECD countries.

5. **Strengthen integrity, transparency and trust in politics**  
   Improve Italy’s corruption and trust indicators through enforcement, transparency-by-design and merit-based appointments.

## How to extend the project

- Add more years of data (e.g. productivity 1995–2024, R&D series, regional breakdowns).
- Replicate simple back-of-the-envelope calculations in Python or R.
- Compare Italy’s “what works” package with other countries stuck in low-productivity equilibria.
