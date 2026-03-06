# 🎵 Spotify Data Analysis Dashboard — Power BI Report 2025


---

## 📋 Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Dashboard Overview](#dashboard-overview)
- [Results & Key Findings](#results--key-findings)
- [Recommendations](#recommendations)
- [Tools & Technologies](#tools--technologies)
- [Dashboard Pages](#dashboard-pages)

---

## Introduction

This project presents a comprehensive **Power BI dashboard** built on a Spotify track-level dataset. The goal is to transform raw streaming data into actionable insights that can inform decisions around **content strategy, artist promotion, genre investment, and release planning**.

The dataset includes thousands of Spotify records capturing:

- Track popularity and duration
- Artist popularity and follower counts
- Album type and total tracks per album
- Explicit content flags
- Artist genres
- Release dates (day, month, year)

> **Target Audience:** Music label executives, A&R teams, digital streaming strategists, and data analytics professionals seeking to understand Spotify content performance.

---

## Problem Statement

The music streaming industry generates vast amounts of data daily, yet many artists, labels, and content teams struggle to extract meaningful patterns from this data. Specifically, key questions remain unanswered:

| # | Business Question |
|---|---|
| 1 | How popular is Spotify content overall, and what are the key performance benchmarks? |
| 2 | Which artists command the highest follower counts and popularity scores? |
| 3 | Which genres dominate the platform, and which are most popular? |
| 4 | Do albums, singles, or compilations perform better in terms of popularity? |
| 5 | Does release timing (month/day) impact track popularity? |
| 6 | Do explicit tracks outperform non-explicit tracks? |

Without a structured analytical framework, these questions remain anecdotal. This dashboard was designed to answer each question with **data-driven evidence**.

---

## Dashboard Overview

The report is structured across **5 interactive dashboard pages**, each targeting a specific analytical objective.

```
📊 Dashboard Structure
├── Page 1 — Artist Performance & Influence
├── Page 2 — Overall Spotify Content Performance
├── Page 3 — Genre-Based Insights
├── Page 4 — Album & Release Strategy Analysis
└── Page 5 — Time-Based Release Trends
```

---

## Results & Key Findings

### 📌 Page 1 — Artist Performance & Influence

![Artist Performance Dashboard](./screenshots/page1.png)

**Key Metrics:**

| Artist | Avg. Followers |
|---|---|
| Taylor Swift | 145,439,063 |
| Ed Sheeran | 122,784,741 |
| Billie Eilish | 118,711,884 |
| The Weeknd | 112,955,670 |
| Ariana Grande | 107,389,695 |
| Eminem | 104,536,546 |
| Drake | 103,061,539 |
| Bad Bunny | 102,533,350 |

**Findings:**

- 🥇 **Taylor Swift** leads all artists with over **145 million average followers**, confirming her dominance as the most-followed artist in the dataset.
- The **scatter plot** of track popularity vs. artist followers reveals a **moderate positive correlation** — artists with more followers tend to produce more consistently popular tracks, though outliers exist.
- **Drake and The Weeknd** have the highest volume of explicit tracks among top artists, suggesting explicit content is prevalent in high-follower profiles.
- Top artists by **track popularity** include Taylor Swift, Drake, The Weeknd, Ariana Grande, Lady Gaga, Eminem, Lana Del Rey, Post Malone, The Neighbourhood, and Nirvana.

---

### 📌 Page 2 — Overall Spotify Content Performance

![Overall Content Performance](./screenshots/page2.png)

**KPI Summary:**

| Metric | Value |
|---|---|
| Total Artists | **3,000+** |
| Total Records (Tracks) | **9,000+** |
| Avg. Track Popularity | **52.36** |
| Avg. Artist Popularity | **69.73** |
| Avg. Track Duration | **3.49 min** |

**Findings:**

- The platform hosts a **diverse catalogue** of over 9,000 tracks across 3,000+ artists.
- **Opalite** ranks as the track with the **highest average popularity score** (close to 100), followed by *Elizabeth T.*, *Man I Need*, and *Father Figure*.
- **Taylor Swift** leads track count with **324 tracks** in the dataset, followed by The Weeknd (141), Lana Del Rey (99), Ariana Grande (94), and Nirvana (91).
- The **popularity bin distribution** shows the majority of tracks fall in the **61–70 popularity range**, indicating a platform skewed toward moderately popular content.
- Tracks like *Runaway*, *Numb*, *Breathe*, *Moonlight*, and *Paradise* record the **highest total popularity sums**, reflecting both popularity scores and frequency of appearance.

---

### 📌 Page 3 — Genre-Based Insights

![Genre-Based Insights](./screenshots/page3.png)

**Findings:**

- **Country** and **Pop** are the **most represented genres** by track count, each with over 500 entries, followed by Soundtrack, Rap, and Soft Pop.
- In terms of **average artist popularity**, the top genres are:
  - 🥇 R&B Pop
  - 🥈 Reggaeton
  - 🥉 Rap
  - Alternative, Pop, Corrido, Country, Rage Rap, Art Rock, Hip Hop
- **Average track popularity by genre** highlights **Brazilian Funk**, **Reggaeton Chileno**, and **Corrido** as the top-performing niche genres — outperforming many mainstream genres.
- This suggests that **niche, culturally specific genres** are gaining significant traction on the platform.

---

### 📌 Page 4 — Album & Release Strategy Analysis

![Album & Release Strategy](./screenshots/page4.png)

**Album Type Breakdown:**

| Album Type | Track Count | Avg. Popularity | % of Total Tracks |
|---|---|---|---|
| Album | 5,856 | 74.56 | 86.52% |
| Single | 2,219 | 58.80 | 3.28% |
| Compilation | 507 | 61.79 | 10.20% |

**Findings:**

- **Albums dominate** the catalogue, accounting for **86.52%** of all tracks in the dataset.
- Albums also record the **highest average track popularity (74.56)**, significantly outperforming singles (58.80) and compilations (61.79).
- The **scatter plot** of track popularity vs. album total tracks reveals that **albums with more tracks** (compilations) cluster at lower popularity, while **focused albums** with moderate track counts show higher popularity scores.
- Singles, while fewer in number, represent a **targeted release strategy** that artists use to maintain chart presence between albums.

---

### 📌 Page 5 — Time-Based Release Trends

![Time-Based Release Trends](./screenshots/page5.png)

**Findings:**

- **January** sees the **highest track release volume** (~1,200 tracks), suggesting labels front-load their annual releases at the start of the year.
- Release count **drops sharply in February** before gradually recovering through mid-year.
- There is a **secondary surge** in track releases from **August through November**, aligning with pre-holiday push strategies.
- **Average track popularity by day of month** fluctuates between **~45–57**, with tracks released around **days 1–10** consistently performing slightly better.
- The **end-of-month releases (days 25–31)** show a notable dip in average popularity, suggesting early-month releases are strategically advantageous.

---

## Recommendations

Based on the findings across all five dashboard pages, the following strategic recommendations are proposed:

### 🎯 For Artists & Labels

1. **Prioritise Album Releases Over Singles for Long-Term Popularity**
   Albums average a popularity score of **74.56** vs. **58.80** for singles. Artists aiming for sustained streaming performance should invest in full album rollouts rather than single-only strategies.

2. **Release Music in January or Late August–October**
   Data shows these months attract the **highest release volumes and listener engagement windows**. Aligning releases with these periods maximises exposure during peak listening activity.

3. **Target Early-Month Release Dates (Days 1–10)**
   Tracks released in the first 10 days of a month exhibit **higher average popularity scores** compared to mid or end-of-month releases.

4. **Invest in Niche Genre Development**
   Genres like **Brazilian Funk, Reggaeton Chileno, and Corrido** show track popularity scores that rival mainstream genres, yet are underrepresented. Early investment in these genres could yield **high returns on low competition**.

5. **Leverage R&B Pop and Reggaeton for Artist Popularity Growth**
   These genres produce the **highest average artist popularity scores**, making them ideal for artists seeking to build a mainstream profile.

### 📊 For Data & Strategy Teams

6. **Build Follower-Weighted Popularity Benchmarks**
   The scatter plot of followers vs. popularity shows that not all high-follower artists have consistently popular tracks. Teams should create **weighted popularity scores** that normalise for follower count.

7. **Monitor the 61–70 Popularity Band**
   The majority of tracks fall in this range. Understanding what separates a track scoring 61 from one scoring 80+ should be a primary research focus.

8. **Flag Explicit Content Strategically**
   Top-followed artists frequently produce explicit content. Platforms and labels should **segment explicit vs. non-explicit performance** across audience demographics to inform content decisions.

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design, data modelling, DAX measures |
| **Microsoft Excel / CSV** | Source data preparation and cleaning |
| **DAX (Data Analysis Expressions)** | KPI calculations, custom measures |
| **Power Query** | Data transformation and genre field splitting |

---

## Dashboard Pages

| Page | Title | Focus Area |
|---|---|---|
| 1 | Artist Performance & Influence | Followers, artist popularity, explicit content |
| 2 | Overall Spotify Content Performance | KPIs, track popularity, record counts |
| 3 | Genre-Based Insights | Genre frequency, popularity by genre |
| 4 | Album & Release Strategy Analysis | Album type comparison, track counts |
| 5 | Time-Based Release Trends | Monthly/daily release patterns |

---

## 📁 Repository Structure

```
📦 spotify-powerbi-dashboard
 ┣ 📂 screenshots
 ┃ ┣ 🖼️ page1.png
 ┃ ┣ 🖼️ page2.png
 ┃ ┣ 🖼️ page3.png
 ┃ ┣ 🖼️ page4.png
 ┃ ┗ 🖼️ page5.png
 ┣ 📊 Spotify_Dashboard.pbix
 ┣ 📄 README.md
 ┗ 📄 spotify_data.csv
```

---

## 👤 Author

**[Your Name]**
Data Analyst | Power BI Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/yourprofile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/yourusername)

---

> *This project was completed as part of a data analytics portfolio to demonstrate proficiency in Power BI, DAX, and data storytelling using real-world streaming data.*
