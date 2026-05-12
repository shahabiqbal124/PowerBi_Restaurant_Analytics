# Restaurant Business Intelligence Dashboard

**Power BI · Excel · DAX · Data Modeling**

A business intelligence dashboard built to transform raw restaurant data 
into decision-ready insights across customer behavior, cuisine performance, 
and service attributes. Designed for operators and analysts who need to move 
beyond gut-feel into evidence-based strategy.

---

## The Problem

Restaurant managers typically know their revenue figures but lack visibility 
into *why* performance varies — why one cuisine outperforms another, why 
certain customer segments rate lower, or which service attributes are silently 
dragging satisfaction scores down. This dashboard makes those relationships 
visible and actionable.

---

## Business Questions Answered

- Which cuisines consistently earn higher satisfaction scores, and which have 
  a demand gap despite good ratings?
- How does customer budget level affect rating behavior and dining preferences?
- Do service attributes — alcohol availability, smoking policy — meaningfully 
  shift rating distributions?
- Which customer segments are most underserved, and where is the growth 
  opportunity?
- What combination of factors (food, service, environment, price) drives a 
  restaurant's overall rating?

---

## Dashboard Overview

> 📸 Add your dashboard screenshot here

The report is structured around three analytical layers:

**1. Restaurant Performance** — rating distribution, cuisine-level benchmarks, 
and attribute impact analysis

**2. Customer Segmentation** — budget tier breakdown, demographic preferences, 
and behavioral patterns by segment

**3. Service & Environment Analysis** — how operational attributes (alcohol 
availability, smoking policy, ambiance) correlate with satisfaction scores

---

## Key Findings

**Budget level shapes rating behavior, not just spend.**
Higher-budget customers give more consistent ratings. Lower-budget segments 
show wider variance — their satisfaction is more sensitive to perceived value 
for money, meaning small pricing or service missteps hit ratings harder.

**Strong cuisines are hidden by weak demand — not weak quality.**
Several cuisines post above-average satisfaction scores but low volume. The 
bottleneck is visibility and positioning, not product quality. These are the 
clearest low-risk expansion opportunities in the dataset.

**Service attributes matter more than most operators assume.**
Alcohol availability and smoking policy don't just attract or repel certain 
customers — they actively shift the rating distribution of customers who do 
visit. Mismatches between environment and customer expectation erode scores 
even when food quality is high.

**Ratings are a composite signal, not a food quality score.**
Satisfaction is shaped by the interaction of service, environment, price 
expectations, and food. Improvement plans that weight food quality alone 
miss most of the lever.

---

## KPIs Tracked

| Metric | Description |
|---|---|
| Average Restaurant Rating | Overall satisfaction benchmark across the dataset |
| Rating Distribution | Spread of scores by cuisine, budget tier, and service attribute |
| Cuisine Performance Index | Satisfaction score vs. demand volume per cuisine type |
| Budget Segment Split | Customer count and average rating by low / medium / high budget |
| Service Attribute Impact | Rating delta between restaurants with and without key service features |

---

## Data Preparation

The raw dataset required significant work before it was ready for modeling:

- Resolved nulls and standardised inconsistent categorical fields (cuisine 
  labels, budget tiers, rating scales)
- Cleaned free-text entries into groupable categories using Power Query
- Built calculated columns for segmentation logic
- Created DAX measures for all KPIs — averages, segment comparisons, and 
  attribute-filtered ratings
- Structured the data model with clear dimension/fact separation for clean 
  cross-filtering

---

## Business Impact

| Decision Area | How the Dashboard Helps |
|---|---|
| Menu & Pricing | Identify which cuisine-price combinations earn the strongest ratings by segment |
| Expansion Planning | Pinpoint high-satisfaction, low-volume cuisines where demand can be grown |
| Service Improvement | Quantify the rating impact of specific service attributes before committing to changes |
| Marketing | Understand which customer segments are under-engaged and what they respond to |
| Positioning | Diagnose whether a rating problem is food, service, environment, or expectation mismatch |

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Report development, interactive visualisations, cross-filtering |
| Power Query (M) | Data cleaning, transformation, and model preparation |
| DAX | KPI calculations, segmentation logic, comparative measures |
| Microsoft Excel | Source data preparation and validation |

---

## Getting Started

1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop (free download from microsoft.com)
3. If prompted, reconnect the data source to the Excel file in the repo —
   **Home → Transform Data → Data Source Settings**
4. Use the slicers (cuisine type, budget tier, service attributes) to explore 
   the data by segment

---

## What's Next

- **Demand-side analysis** — the current dataset explains *satisfaction* but 
  not *volume*. Adding footfall or order frequency data would reveal whether 
  high-rated cuisines are also high-demand, or just undiscovered.

- **Competitor benchmarking layer** — enriching the dataset with comparable 
  restaurants in the same area would shift this from internal analysis to 
  true competitive intelligence.

- **Segmentation clustering** — replace manual budget tiers with k-means or 
  similar clustering on actual spending patterns to find natural customer 
  groups the current categories may be missing.

---

## 📸 Dashboard Snapshots

### Birmingham Location
<img width="1218" height="681" alt="image" src="https://github.com/user-attachments/assets/87215bd0-3e8c-4e8b-b864-db55f84b6ba3" />

*Revenue: £11.65K | Goal: -23.91% | Avg Transaction: £95.64*

### Liverpool Location
<img width="1228" height="668" alt="image" src="https://github.com/user-attachments/assets/c2730cfb-cecf-4a26-8785-01c4304f6832" />

*Revenue: £21.23K | Goal: +29.57% | Avg Transaction: £112.17*

### London Location
<img width="1200" height="650" alt="image" src="https://github.com/user-attachments/assets/47b9fe1e-636a-4433-8f55-8d1b9281fa44" />

*Revenue: £20.65K | Goal: +7.14% | Avg Transaction: £111.88*

### Manchester Location
<img width="1223" height="646" alt="image" src="https://github.com/user-attachments/assets/66442bec-ecd1-4fbb-8830-f319a8ba9f1e" />

*Revenue: £22.59K | Goal: +59.63% | Avg Transaction: £94.93*

### Consolidated Overview
<img width="1215" height="684" alt="image" src="https://github.com/user-attachments/assets/1ff0952e-8c0f-498f-a130-7927ea5ea6e4" />


