# 🛢️ PetroPulse India — Oil & Gas Business Intelligence Dashboard

> **An interactive Power BI dashboard analyzing India's Oil & Gas value chain — from crude production and imports to refining, petroleum product production, gas consumption, and exports.**


<p align="center">
  <b>Power BI</b> • <b>Power Query</b> • <b>DAX</b> • <b>Data Modeling</b> • <b>Energy Analytics</b>
</p>

---

## 📌 Overview

**PetroPulse India** is an end-to-end Oil & Gas Business Intelligence project built using **Microsoft Power BI**.

The project transforms monthly and cumulative petroleum and natural gas statistics into an interactive analytical dashboard covering the complete energy value chain:

**Supply → Sourcing → Processing → Production → Consumption → Import → Export**

Instead of looking at individual datasets separately, the dashboard connects them to answer broader business questions around India's:

- Crude oil production
- Crude oil imports
- Refinery crude processing
- Petroleum product production
- Petroleum product imports
- Petroleum product exports
- Natural gas production
- Natural gas availability
- Sector-wise gas consumption

The objective was not just to build visualizations, but to understand **what is happening, why it is happening, and what it means from a business perspective.**

---

# 🎯 Project Objectives

The dashboard was designed to answer key Oil & Gas business questions:

### 🛢️ Crude Oil
- How much crude oil is produced domestically?
- Which production regime contributes the most?
- How dependent are Indian refineries on imported crude?
- Where does India's imported crude come from?

### 🏭 Refining & Petroleum Products
- How much crude is processed by different refinery categories?
- What is the imported vs indigenous crude processing mix?
- Which petroleum products dominate refinery output?
- How does monthly production compare with cumulative FY performance?

### 🌍 Imports & Exports
- Which petroleum products are imported?
- Which products dominate exports?
- How does India's crude import dependence compare with finished-product trade?

### 🔥 Natural Gas
- How much natural gas is produced domestically?
- How much LNG is imported?
- Which sectors consume the most natural gas?
- What do YoY and MoM trends indicate about gas production?

---

# 📊 Dashboard Architecture

The dashboard contains **10 analytical pages**, structured around the Oil & Gas value chain.

| # | Dashboard Page | Key Analysis |
|---|---|---|
| 01 | 🛢️ Oil Products Export | Product-wise petroleum exports |
| 02 | 📦 Oil Products Import | Product-wise petroleum imports |
| 03 | 🌍 Crude Import & Region Share | Crude import trend and source regions |
| 04 | 🏭 Products Production — FY | Financial-year cumulative production |
| 05 | 📅 Products Production — July 2026 | Monthly product production |
| 06 | ⚙️ Crude Processing Share | Imported vs indigenous crude |
| 07 | 🛢️ Crude Production by Regime | Production by licensing regime |
| 08 | 🔥 Gas Sectoral Consumption | Consumption by sector |
| 09 | 📈 Gas Sectoral Monthly Trend | Growth and sector trends |
| 10 | 🔥 Gas Production Summary | Production, sales & LNG imports |

---

# 🔍 Dashboard Pages

## 01 — Oil Products Export

Analyzes petroleum product exports by volume and product category.

**Key observation:**
- HSD contributes approximately **16%**
- MS contributes approximately **9%**
- Naphtha, ATF and other products make up the remaining export mix
- Cumulative FY performance is compared with the latest monthly position

<img width="6150" height="3525" alt="p_page-0010" src="https://github.com/user-attachments/assets/ab7f0ea8-0252-47da-b0ce-48f4fcd3512d" />


---

## 02 — Oil Products Import

Analyzes India's petroleum product imports by product.

**Key observation:**
- LPG and Petcoke are among the major imported products
- HSD, ATF, MS and SKO imports are comparatively low in the analyzed period

<img width="6150" height="3525" alt="p_page-0009" src="https://github.com/user-attachments/assets/703d2ebf-4d2b-4702-a01d-fe6d579a0f9d" />


---

## 03 — Crude Oil Import & Region Share

Analyzes crude oil imports along with the geographical sourcing mix.

### Crude Import Source Mix

| Region | Share |
|---|---:|
| 🌏 Eurasia | **47.3%** |
| 🕌 Middle East | **30.7%** |
| 🌎 South America | **12.7%** |
| 🌍 Africa | **6.1%** |
| 🇺🇸 North America | **3.2%** |

**Key observation:**

> **Eurasia + Middle East account for nearly 78% of India's crude oil imports in the analyzed dataset.**

<img width="6150" height="3525" alt="p_page-0008" src="https://github.com/user-attachments/assets/04a1e05b-bec4-4e7c-acf1-fad626367989" />


---

## 04 — Oil Products Production — FY Cumulative

Analyzes cumulative petroleum product production during the financial year.

The dashboard provides both:

- Absolute production in **MMT**
- Product-wise contribution percentage

**Key observation:**

> **HSD (Diesel) contributes approximately 43% of total petroleum product production.**

<img width="6150" height="3525" alt="p_page-0007" src="https://github.com/user-attachments/assets/f8cf2d3d-a18c-44bc-91ca-c48ef1336ec0" />


---

## 05 — Oil Products Production — July 2026

Analyzes monthly petroleum product production for **July 2026**.

**Total production: ~24.8K thousand MT**

**HSD leads production at approximately 10.4K thousand MT.**

The ranked visualization makes it easier to compare production volumes across major petroleum products.

<img width="6150" height="3525" alt="p_page-0006" src="https://github.com/user-attachments/assets/0f26a38d-3695-4545-acf9-38c9edecad0f" />


---

## 06 — Crude Oil Processing Share

Compares crude sourcing patterns across:

- Private refineries
- PSU/JV refineries

The dashboard separates:

**Imported Crude vs Indigenous Crude**

### Key Observation

Both refinery categories show a very high dependence on imported crude, with approximately **87–98% of processed crude coming from imports** in the analyzed dataset.

<img width="6150" height="3525" alt="p_page-0005" src="https://github.com/user-attachments/assets/ada02286-0fa8-4825-b00b-f0f643326078" />


---

## 07 — Crude Oil Production by Regime

Analyzes India's domestic crude oil production according to licensing / contractual regimes:

- Nomination
- PRE-NELP
- NELP
- DSF
- OALP

### Key Observation

> The **Nomination regime contributes approximately 79%** of domestic crude production in the analyzed period.

This provides an interesting view of how legacy and newer exploration & production frameworks contribute to India's domestic output.

<img width="6150" height="3525" alt="p_page-0004" src="https://github.com/user-attachments/assets/30fb6b5f-68f4-4814-8cb8-a791395407c2" />


---

## 08 — Gas Sectoral Consumption by Source

Analyzes natural gas consumption across major sectors.

Key sectors include:

- Fertilizer
- City Gas Distribution (CGD)
- Power
- Refinery
- Petrochemical
- Other sectors

### Key Observation

**Fertilizer** and **CGD** are among the largest consumers of natural gas.

In the analyzed cumulative data:

- Fertilizer: **18.2K MMSCM**
- CGD: **7.1K MMSCM**

<img width="6150" height="3525" alt="p_page-0003" src="https://github.com/user-attachments/assets/27d15809-b9bd-44df-9fcf-d23b2f36bd14" />


---

## 09 — Gas Sectoral Consumption — Monthly Trend

A deeper analysis of natural gas consumption combining multiple analytical views.

The page includes:

- FY cumulative funnel
- Waterfall analysis
- Sector contribution %
- MoM growth
- YoY growth
- Monthly sector comparison
- Treemap analysis

This page focuses on understanding not only **how much gas is consumed**, but also **how consumption changes over time and across sectors**.

<img width="6150" height="3525" alt="p_page-0002" src="https://github.com/user-attachments/assets/8bc04f22-6ca1-401c-81ba-31a5ba9e6951" />


---

## 10 — Gas Production Summary

The final page connects:

**Gross Production → Net Production for Sale → LNG Imports**

Production is segmented across:

- OIL
- ONGC
- Private / JV

### Key Observation

> **Gross natural gas production declined by approximately 35% YoY** in the analyzed period.

This acts as an important watch-point because declining domestic production can increase the requirement for imported LNG to maintain overall gas availability.

<img width="6150" height="3525" alt="p_page-0001" src="https://github.com/user-attachments/assets/3bbda695-14b9-4c25-afd8-49e797883544" />


---

# 💡 Key Business Insights

The dashboard helped identify several important patterns in India's Oil & Gas sector.

### 1️⃣ High Crude Import Dependence

Approximately **87–98% of crude processed by the analyzed private and PSU/JV refinery groups is imported crude.**

This highlights the importance of international crude sourcing for India's refining ecosystem.

---

### 2️⃣ Crude Imports Are Regionally Concentrated

**Eurasia + Middle East contribute nearly 78%** of India's crude imports in the analyzed dataset.

This indicates a significant concentration of crude sourcing across a relatively small number of regions.

---

### 3️⃣ Diesel Dominates Petroleum Product Output

**HSD (Diesel) contributes approximately 43%** of total petroleum product production.

This makes diesel one of the most important components of India's refinery output mix.

---

### 4️⃣ Fertilizer & CGD Drive Gas Consumption

The **Fertilizer and CGD sectors** represent major natural gas demand centers.

This demonstrates the importance of natural gas beyond the power sector and its role in industrial and city-gas applications.

---

### 5️⃣ Nomination Regime Remains Significant

Despite the emergence of newer exploration frameworks such as **NELP, DSF and OALP**, the Nomination regime still contributes approximately **79% of domestic crude production** in the analyzed period.

---

### 6️⃣ Gas Production Decline Is a Watch-Point

Gross natural gas production shows an approximate **35% YoY decline**.

If this trend continues, the gap between domestic production and overall gas requirements could increase, potentially increasing reliance on LNG imports.

---

# 🧠 Analytical Story

The most important part of this project was connecting the individual dashboards into one story.

### Upstream

**Domestic Crude + Natural Gas Production**

⬇️

### Sourcing

**Imported Crude + LNG Imports**

⬇️

### Midstream

**Crude Processing / Refining**

⬇️

### Downstream

**Petroleum Product Production**

⬇️

### Domestic Demand

**Gas Consumption Across Major Sectors**

⬇️

### International Trade

**Petroleum Product Imports + Exports**

This approach helped me understand the Oil & Gas sector as a **connected value chain rather than a collection of separate datasets.**

---

# 🧰 Tech Stack

| Category | Tools / Techniques |
|---|---|
| **BI Tool** | Microsoft Power BI Desktop |
| **Data Transformation** | Power Query |
| **Calculations** | DAX |
| **Data Modeling** | Relationships, measures & aggregations |
| **Analysis** | YoY, MoM, cumulative & contribution analysis |
| **KPI** | KPI Cards / Summary Cards |
| **Visualizations** | Bar, Donut, Pie, Treemap, Funnel, Waterfall, Line |
| **Domain** | Oil & Gas / Energy Analytics |

---

# 📅 Data Coverage

The dashboard uses monthly and cumulative energy-sector statistics.

### Current Analysis Period

**July 2026**

### Financial Year

**FY 2026–27**

### Comparisons

- Latest month
- FY cumulative
- Previous financial year
- YoY comparison
- MoM comparison

---
