
# Five Reforms That Work: Quantifying the Payoff of Structural Change in Italy

*Draft – for discussion and further work*

## Abstract

Italy combines remarkable strengths – second-largest manufacturer in the euro area, dense networks of family-owned firms, strong design and export capabilities – with persistent weaknesses: low labour productivity, slow justice, under-investment in R&D, fragmented firm size and fragile governance.

This paper builds a small dataset of key indicators and develops five stylised reform scenarios:

1. scaling up SMEs and reducing micro-firm fragmentation;  
2. boosting R&D and SME digitalisation;  
3. increasing public administration and justice efficiency;  
4. opening up closed sectors and lowering entry barriers;  
5. strengthening integrity, transparency and trust in politics.

Using simple back-of-the-envelope calculations, it illustrates how each reform could contribute to higher productivity and a more credible political system. The goal is not to deliver precise forecasts, but to anchor structural reform discussions in numbers rather than slogans.

---

## 1. Introduction: Italy’s structural problem in numbers

Italy’s economic story of the last two decades is one of **stagnation amid potential**.

On one side:

- Italy remains the **second-largest manufacturing economy in the euro area**, with strong clusters in machinery, food, luxury goods and design.
- SMEs form dense networks of suppliers and specialised producers.

On the other side:

- **Labour productivity** (GDP per hour worked, PPP) has barely risen in twenty years and lags behind key peers.
- **Real wages** remain below pre-2008 levels, and a large share of the population remains at risk of poverty or social exclusion.
- **Public debt** is among the highest in advanced economies, limiting fiscal room for manoeuvre.

Using the latest available international data:

- In 2023, Italy’s GDP per hour worked is around **76–77 USD (PPP)** – similar to Spain, but well below France (~91) and Germany (~93). Italy sits close to the OECD average, despite being a high-income EU member.
- Over the long run, Italy’s labour productivity per hour has grown far more slowly than that of France, Germany or Spain.

At the same time, Italy’s **R&D intensity** – gross domestic expenditure on research and development as a share of GDP – is persistently below the EU average:

- Roughly **1.45% of GDP in 2021**, falling to about **1.31% in 2023**.
- The EU average reached **around 2.2%** in 2023, and several innovation leaders are above 3%.

Governance indicators tell a similar story. Italy is a **moderate performer**:

- its corruption perception score is in the middle of the global ranking;
- trust in government and satisfaction with public services are below OECD averages;
- rule of law and media freedom observers regularly flag concerns about institutional backsliding and politicisation.

The objective of this paper is not to provide yet another list of “things that must be fixed”, but to **quantify what could work** by focusing on five levers that are:

- **measurable** – each linked to specific KPIs;
- **recurrent** – repeatedly highlighted by international institutions;
- **mutually reinforcing** – success in one area increases returns in the others.

---

## 2. Data and approach

The analysis is intentionally simple and transparent. The repository includes one main dataset:

- `italy_top5_reforms_dataset.xlsx`  

with four sheets:

1. **`reforms_summary`**  
   - one row per reform;  
   - key KPI; baseline value and year; target scenario and year; rough effect on GDP or productivity in percentage terms where it is meaningful to attempt a quantification.

2. **`sme_detail`**  
   - structure and productivity of Italian SMEs:  
     - number of SMEs, employment and value added shares;  
     - value added per person employed;  
     - comparison with EU, Germany and France;  
     - a very simple scenario where micro firm productivity converges to the EU average for micro enterprises.

3. **`innovation_detail`**  
   - time-points for R&D intensity (% of GDP) in Italy, EU27 and peers (Germany, Spain);  
   - an illustrative convergence scenario for Italy by 2035 (e.g. Italy’s R&D intensity moving towards current EU average levels).

4. **`governance_detail`**  
   - corruption perceptions score;  
   - trust in national government (% with high or moderate trust);  
   - satisfaction with administrative services (% satisfied);  
   - target levels aligned with Western European averages.

### 2.1 Method

For each reform, the paper:

1. **Describes the problem**, using baseline data.  
2. **Summarises empirical evidence**, mostly from OECD, EU and international reports.  
3. **Builds a stylised scenario**, expressed as:
   - a target level for the key KPI;  
   - a rough long-run productivity or GDP gain (where literature provides a basis).  
4. **Discusses delivery and political economy**, especially where reforms face strong interest group resistance.

Numbers are meant to provide **orders of magnitude**, not precise forecasts. They should be read as *“what direction and scale are plausible?”* not as *“this is exactly +3.2% of GDP”*.

---

## 3. Reform 1 – Overcoming firm size fragmentation

### 3.1 Baseline: SME dominance and productivity gaps

Italy is **extremely SME-intensive** by international standards:

- more than **4 million SMEs**, the highest absolute number among EU Member States;
- they employ around **13 million people** and generate **over 65%** of national value added;
- the share of exports coming from SMEs is also higher than in many peers.

Detailed SME statistics show:

- SMEs (0–249 employees) account for roughly:
  - **~99.8%** of all enterprises;  
  - around **80%** of total employment;  
  - about **70%** of total value added.
- Within SMEs, **micro firms (0–9 employees)** dominate:
  - they make up about **95% of all enterprises**;  
  - employ roughly **45%** of workers;  
  - generate close to **30%** of value added.

Productivity gaps are sizeable:

- Average SME value added per person employed in Italy is around **€42,000** vs an EU average of **€44,600** (≈6% below).  
- Relative to Germany and France, Italian SMEs are roughly **21%** and **29%** less productive, respectively.  
- Micro firms are even further behind: Italian micro-enterprise productivity is estimated at around **€31,000 per worker** compared with approximately **€37,000** for the EU average micro firm.

This structure – **many small firms, relatively low productivity** – is often called “nanismo d’impresa”. It is not a problem in itself to have many small firms; the issue is that too few of them *grow* into medium-sized, innovation-intensive firms.

### 3.2 A simple scenario: micro-firm catch-up

In the sheet `sme_detail`, a very simple calculation is constructed:

- assume micro-enterprise productivity in Italy converges from **€31,000** to the EU average for micro enterprises, around **€37,000** per worker;
- this is about a **+19%** productivity increase for micro firms.

Since micro firms employ approximately **44.9%** of the workforce, the contribution to total value added can be loosely approximated by:

> contribution ≈ employment share × productivity increase  
> ≈ 0.449 × 0.19 ≈ **0.085** → about **+8–9%** of total value added in the very long run.

This is a mechanical calculation and ignores general equilibrium effects, but it provides a sense of scale: **helping micro firms catch up to EU micro peers could move the level of Italian GDP by high single digits**.

External work points in similar directions. International studies on MSMEs suggest that bringing small firms closer to the productivity of large firms can add several percentage points to GDP in advanced economies.

### 3.3 Policy levers

What would it take to unlock such a catch-up?

- **Tax and labour thresholds**  
  - Smooth out the discontinuities around thresholds (e.g. 15 employees) that discourage hiring and scaling.
  - Make social contribution obligations and compliance costs more continuous and predictable across size classes.

- **Consolidation and networks**  
  - Support voluntary mergers, acquisitions and business combinations where sub-scale firms can gain access to capital, technology and managerial skills.  
  - Encourage “networks of enterprises” with shared services (HR, finance, export support) without over-complicating legal frameworks.

- **Management, governance and succession**  
  - Incentivise professionalisation of management in family firms (board structures, external managers, performance-based pay).  
  - Design succession tax and legal rules that make it easier to pass firms on while avoiding fragmentation into multiple micro entities.

These measures should be complemented by **better access to finance** (especially equity and quasi-equity) and by the reforms discussed in the next sections (R&D, justice, competition, governance), which raise the expected payoff of growing rather than remaining sub-scale.

---

## 4. Reform 2 – R&D and SME digitalisation

### 4.1 Baseline: under-investment in innovation

Italy’s R&D intensity is systematically below the EU average:

- Around **1.45% of GDP** in 2021.  
- Down to about **1.31% of GDP** in 2023.  
- EU27 average: around **2.22% of GDP** in 2023.  

This places Italy significantly below countries such as Germany (around or above 3% of GDP) and other advanced innovation leaders.

On the **innovation output** side:

- The European Innovation Scoreboard 2025 classifies Italy as a **“Moderate Innovator”**, with performance at roughly **93% of the EU average** and ranking around **14th among EU Member States**.

Digitalisation of SMEs is improving but still not where it could be:

- In 2023, about **60–61%** of Italian SMEs (10–249 employees) had at least a **basic level of digitalisation** (e.g. using at least 4 out of 12 core digital technologies – websites, e-commerce, cloud, CRM, ERP, social media, etc.).
- This is progress relative to the past, but still below the desired 90% target of basic digitalisation for EU SMEs by 2030.

### 4.2 Scenario: closing half of the R&D gap

In the sheet `innovation_detail`, a conservative scenario is defined:

- **Baseline (2023)**  
  - Italy R&D intensity: **1.31% of GDP**  
  - EU27 R&D intensity: **2.22% of GDP**

- **Scenario (2035)**  
  - Italy R&D intensity: **2.2% of GDP** (roughly closing the gap with today’s EU average)  
  - EU27: drifting higher to ~2.4%.  

The academic literature finds that higher R&D intensity is associated with higher long-run TFP and GDP levels. Estimates vary, but an additional 0.5–1 percentage point of R&D spending relative to GDP can yield several tenths of a percentage point higher annual productivity growth in the long run.

For the purpose of this project, the sheet `reforms_summary` assigns an illustrative **+3% long-run GDP level gain** to R&D/digitalisation convergence. This number is deliberately conservative and should be read as “in the same order of magnitude as turning Italy into an average EU performer on innovation”.

### 4.3 Policy levers

- **Stable, predictable R&D tax incentives**  
  - Simplify and stabilise tax credits so firms can plan multi-year R&D programmes without policy risk.
  - Focus on incremental R&D and collaboration between firms, universities and public labs.

- **Mission-oriented programmes**  
  - Channel public R&D and innovation funding towards clearly defined missions (energy transition, digitisation of manufacturing, health technologies), where Italian industrial strengths can be leveraged.

- **Scaling up digital support for SMEs**  
  - Expand and streamline voucher schemes and advisory services for SME digitalisation (ERP, CRM, AI-enabled tools, cloud, cybersecurity).  
  - Encourage use of interoperable, open standards to avoid SMEs being locked into monolithic vendors.

---

## 5. Reform 3 – Public administration and justice efficiency

### 5.1 Baseline: long trials and high uncertainty

Justice and bureaucracy are often cited by Italian entrepreneurs as the **single biggest obstacle** to investment.

Recent EU justice scoreboards and media reports highlight:

- It takes around **1,000 days** – roughly **2.7 years** – to resolve civil and commercial cases in Italy, a record within the EU.  
- Historical Doing Business data reported time to enforce a commercial contract at around **1,120 days**, well above the EU and OECD averages.  
- Italy performs reasonably on **clearance rates** (resolving more cases than it receives in some categories), but the **stock of pending cases and length of proceedings remain critical**.

Reforms under the National Recovery and Resilience Plan (NRRP) have begun to show that substantial improvements are possible:

- Pilot projects in some courts, using new case management approaches and “judge’s bureaus”, have reportedly reduced the average length of proceedings from **6.5 years to 2.8 years** in specific contexts.  
- Government documents and academic work suggest that **cutting civil case length by 50%** could increase the **average size of manufacturing firms by around 10%**, by lowering legal uncertainty and enforcing contracts more effectively.

At the macro level, the OECD has analysed Italian firm-level data and found that:

- increasing local public administration efficiency from the 25th to the 75th percentile is associated with around **+1–2 percentage points** higher firm-level labour productivity growth;  
- for more mature firms, the effect can be even larger.

### 5.2 Scenario: from worst-in-class to median EU

In `reforms_summary`, the justice/PA reform is represented by:

- **KPI**: length of civil/commercial proceedings (days) and an index of local public administration efficiency;  
- **Baseline**: around 1,000+ days for full resolution of civil/commercial cases; wide dispersion in PA efficiency across provinces;  
- **Target**: converge towards the **EU median for trial length** and raise lagging provinces to at least the **75th percentile** of PA efficiency.

The stylised effect assigned is a **+2.4% firm-level productivity gain**, taken from OECD estimates on the impact of local public administration efficiency. This is again conservative and does not include potential **indirect gains** via higher investment, more R&D and larger firm size.

### 5.3 Policy levers

- **Process re-engineering and digital justice**  
  - Expand the successful “judge’s bureau” and case management pilots nationwide.  
  - Ensure digital filing, electronic communication and AI-assisted document management are standard, not optional.

- **Performance-based management in the PA**  
  - Introduce clear performance indicators and incentives for courts and administrative offices, including time-to-decision metrics and service quality measures.  
  - Strengthen recruitment, training and career paths for civil servants, with more emphasis on skills and less on seniority.

- **Regulatory simplification and one-stop shops**  
  - Reduce overlapping layers of regulation and create genuine one-stop shops for permits and licenses.  
  - Systematically review and eliminate obsolete procedures.

---

## 6. Reform 4 – Competition and entry barriers

### 6.1 Baseline: mixed PMR profile

OECD Product Market Regulation (PMR) indicators show that:

- Italy’s **economy-wide PMR score** is **close to the OECD average** – so it is not an extreme outlier in terms of overall regulation.
- However, there are **important sectoral problems**:
  - **professional services and retail** are regulated more strictly than in the average OECD country;  
  - there are **high barriers to FDI and to trade facilitation**;  
  - the **scope of public ownership** remains relatively large, although governance of state-owned enterprises is aligned with many OECD standards;  
  - **regulation of lobbying** and transparency of interactions between policymakers and interest groups are weak.

These features combine to create **“insider protection”** in various sectors: established incumbents enjoy protective regulation, while new entrants (including foreign investors and innovative SMEs) face higher costs and uncertainty.

### 6.2 Scenario: moving PMR to top-quartile levels

Quantifying the direct GDP gain from PMR reforms is difficult, but international work suggests that moving from average to top-quartile PMR performance in network and service sectors can:

- raise TFP in regulated sectors;  
- reduce consumer prices;  
- indirectly support investment and innovation.

In `reforms_summary`, this reform is assigned a very cautious **+1% long-run GDP level gain**, corresponding to Italy moving from “close to OECD average” to “top quartile” in terms of product market friendliness, especially in services and entry barriers.

This is probably an underestimate, but it keeps the project on the safe side.

### 6.3 Policy levers

- **Liberalising access to professions and services**  
  - Revisit restrictions on professional activities (e.g. quotas, reserved activities, advertising bans) where they cannot be justified by clear public-interest arguments.  
  - Simplify establishment and licensing for retail distribution and the sale of medicines while protecting core safety standards.

- **Reducing state involvement where it distorts competition**  
  - Review the scope of public ownership and focus state participation on areas with clear market failures.  
  - Ensure neutrality between state-owned and private enterprises via strong, independent regulators.

- **Strengthening competition institutions**  
  - Give the competition authority adequate powers and resources to tackle cartels, abuse of dominance and anti-competitive regulation.  
  - Systematically assess the competitive impact of new laws and regulations.

---

## 7. Reform 5 – Integrity, transparency and trust

### 7.1 Baseline: mid-table governance, fragile trust

On corruption and governance, Italy is **neither a disaster nor a leader**:

- Its Corruption Perceptions Index score is **54/100**, ranking around **52nd out of 180 countries**.  
- This is below many Western European peers, but above some newer EU members and significantly above non-OECD economies.

On citizen perceptions:

- **Trust in national government** in Italy is about **36%**, slightly below the OECD average of 39%.  
- **Satisfaction with administrative services** is around **48%**, compared with **66%** on average in the OECD.

Reports on rule of law and civil liberties have raised concerns about:

- interference with judicial independence;  
- weak anti-corruption enforcement;  
- pressure on media and civil society.

### 7.2 Scenario: closing the governance gap

In `governance_detail`, the governance reform is expressed through targets rather than direct GDP impacts:

- **Corruption Perceptions Index**  
  - Baseline: 54/100  
  - Target: **64/100**, roughly converging towards the Western European average.

- **Trust in government**  
  - Baseline: 36%  
  - Target: **≥50%** of people expressing high or moderate trust.

- **Satisfaction with administrative services**  
  - Baseline: 48%  
  - Target: **66%** (OECD average) or above.

The literature suggests that better governance is associated with higher investment rates, more efficient allocation of capital, less tax evasion and stronger innovation performance. Quantitatively disentangling these channels is difficult, so the dataset does **not** assign a single “+X% GDP” number here. The message is that **governance reform is an amplifier**: it increases the returns to all the other reforms.

### 7.3 Policy levers

- **Anti-corruption and enforcement**  
  - Strengthen investigative capacity and independence of anti-corruption agencies and prosecutors.  
  - Improve asset declaration, conflict-of-interest rules and enforcement for public officials.

- **Transparency-by-design**  
  - Publish detailed, machine-readable data on public procurement, subsidies and lobbying contacts.  
  - Make it easy for citizens, media and researchers to scrutinise public spending and regulation.

- **Merit-based appointments and evaluation**  
  - Reduce political discretion in senior public appointments through transparent, merit-based selection processes.  
  - Introduce rigorous performance evaluation for top civil servants linked to clear service delivery and integrity metrics.

---

## 8. Putting it together: the payoff of a coherent package

The five reforms are best seen as a **package**, not as isolated measures.

If we sum the very conservative, stylised impacts used in `reforms_summary`:

- **SME scaling and micro catch-up**: +5–8% of GDP in the long run (depending on assumptions).  
- **R&D and digitalisation convergence**: around +3%.  
- **PA and justice efficiency**: +2–3% via firm-level productivity, potentially more through higher investment.  
- **Competition and PMR improvements**: +1% or more.  
- **Governance and integrity**: no single number, but an **amplifier** for all the above.

Even using only the lower end of these ranges and assuming overlap between channels, a **coherent reform package** could plausibly deliver:

> **A long-run GDP level that is 7–10% higher than in a no-reform scenario**,  
> with better-quality jobs, more innovative firms and greater institutional credibility.

The political difficulty is enormous: each reform clashes with entrenched interests (status-quo beneficiaries of fragmentation, regulatory rents, slow justice, opaque lobbying, etc.). But the upside is equally large – and measurable.

---

## 9. Conclusion and next steps

This project is deliberately modest: a small dataset and a markdown paper. However, even this simple structure helps to:

- move the discussion from *“Italy needs reforms”* to *“here is what reforms could do in numbers”*;  
- show that **firm size, innovation, justice, competition and governance are deeply interconnected**;  
- provide a foundation for more rigorous work (econometric models, regional analysis, simulations).

Possible extensions include:

- adding **time series** and **regional breakdowns** to distinguish between North, Centre and South;  
- modelling how **specific policy tools** (tax credits, procedural reforms, competition laws) map into the KPIs used here;  
- applying the same methodology to other countries caught in low-productivity equilibria.

Ultimately, the project aims to be a **public, transparent playground** for thinking about what actually works in Italian structural reform – and to make those discussions accessible to students, analysts and policymakers who prefer numbers over slogans.
