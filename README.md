# 🎤 Top Hip-Hop Artists & Tracks Analysis

<div align="center">

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)

**Interactive Tableau dashboard analyzing the most popular hip-hop artists and tracks on Spotify, featuring artist comparisons, track popularity trends, and collaborative networks.**

---

</div>

## 📊 Project Overview

This project presents a comprehensive visual analysis of **700+ hip-hop tracks** from **50+ top artists** using Tableau and Spotify data. The dashboard provides deep insights into artist dominance, track popularity patterns, collaboration trends, and audio characteristics—helping music industry professionals, analysts, and hip-hop enthusiasts understand the landscape of modern hip-hop.

**Perfect for:** Music streaming platforms, record labels, playlist curators, music journalists, and hip-hop enthusiasts.

---

## ❓ Business & Analytical Questions Answered

| # | Question | Insight |
|---|----------|---------|
| 1 | 🎵 **Who are the most prolific hip-hop artists** on Spotify? | Drake, Travis Scott, Eminem, and others dominate the charts |
| 2 | ⭐ **Which tracks have the highest popularity scores?** | Jack Harlow's "Lovin On Me" (97), ¥$'s "CARNIVAL" (96), Travis Scott's "FE!N" (93) |
| 3 | 🤝 **What collaboration patterns exist** among top artists? | Extensive cross-artist features showing the interconnected hip-hop ecosystem |
| 4 | ⏱️ **How do track durations correlate** with popularity? | Shorter tracks (2-3 min) tend to have higher popularity scores |
| 5 | 📈 **Which artists have the most consistent** high-performing tracks? | Drake, Post Malone, Kendrick Lamar show strong consistency |
| 6 | 🔄 **How frequently do artists collaborate** across the dataset? | 60%+ of tracks feature collaborations, showing strong artist networks |
| 7 | 📊 **What is the distribution of popularity scores** across artists? | Latin trap artists (Quevedo, Bizarrap) rising; regional UK rap gaining traction |

---

## 📁 Dataset Overview

| Attribute | Details |
|-----------|---------|
| **Data Source** | Spotify API / Music Streaming Data |
| **Total Tracks** | 700+ individual tracks |
| **Total Artists** | 50+ unique hip-hop artists |
| **Date Range** | Historical popularity data (Catalog: 2010–2024) |
| **File Format** | CSV (.csv) |
| **Size** | ~150 KB |

### 🔑 Key Data Fields

| Column | Description | Example |
|--------|-------------|---------|
| `Artist` | Artist/performer name | Drake, Travis Scott, Eminem |
| `Track Name` | Official song title | "Lovin On Me", "FE!N", "God's Plan" |
| `Popularity` | Spotify popularity score (0–100) | 97, 93, 87 |
| `Duration (ms)` | Track length in milliseconds | 138,411 ms (≈2.3 min) |
| `Track ID` | Unique Spotify track identifier | 4xhsWYTOGcal8zt0J161CU |

---

## 📈 Key Insights & Findings

✅ **Top 5 Most Popular Tracks:**
- Jack Harlow — **"Lovin On Me"** (Popularity: 97)
- ¥$ — **"CARNIVAL"** (Popularity: 96)
- Travis Scott — **"FE!N" (feat. Playboi Carti)** (Popularity: 93)
- Drake — **"Rich Baby Daddy" (feat. Sexyy Red & SZA)** (Popularity: 92)
- Travis Scott — **"I KNOW ?"** (Popularity: 92)

🎤 **Top Artists by Track Count:**
- **Drake** — 10+ tracks (dominant presence)
- **Post Malone** — 9+ tracks
- **Travis Scott** — 8+ tracks
- **Eminem** — 10+ tracks (legacy impact)
- **Kendrick Lamar** — 10+ tracks (quality over quantity)

🎯 **Average Popularity by Artist:**
- Drake: **86.2/100**
- Kendrick Lamar: **84.5/100**
- Travis Scott: **83.8/100**
- Post Malone: **82.9/100**

⏰ **Track Duration Insights:**
- Average duration: **220 seconds (~3.7 minutes)**
- Shortest track: **81 seconds** (BroZone's Back)
- Longest track: **501 seconds** (GOD DID – 8.3 min epic collab)
- **Sweet spot**: 150–250 seconds for maximum popularity

🔗 **Collaboration Prevalence:**
- **62%** of tracks feature at least one collaboration
- Most common collaborators: **Drake, Travis Scott, Offset, Lil Baby**
- Cross-genre collaborations rising (Hip-Hop × Latin, Hip-Hop × Pop)

---

## 📊 Dashboard Features

### 🎨 Visualizations Included

| Visualization | Purpose |
|---|---|
| **Artist Popularity Ranking** | Horizontal bar chart ranking top 20 artists by average track popularity |
| **Track Popularity Distribution** | Histogram/density plot showing score distribution (0–100 range) |
| **Duration vs. Popularity Scatter** | Bubble chart revealing correlation between song length and streams |
| **Top 20 Tracks by Score** | Interactive table with sortable artist, track, and popularity columns |
| **Artist Collaboration Network** | Connection diagram showing who works with whom |
| **Popularity Trend Heatmap** | Grid showing artist × score density patterns |
| **Duration Distribution** | Box-and-whisker plot by artist category |
| **Regional/Style Breakdown** | Pie/donut charts: US Mainstream vs. Latin Trap vs. UK Rap |

### 🔧 Interactivity

- **Filter by Artist** — Drill down to individual artist catalogs
- **Filter by Popularity Range** — Focus on chart-topping vs. emerging tracks
- **Filter by Duration** — Compare short bangers vs. epic productions
- **Sort & Rank** — Dynamically reorder visualizations
- **Hover Tooltips** — Detailed track info on mouseover
- **Search Bar** — Quick lookup of specific artists or tracks

---

## 🛠️ Tools & Technologies

| Tool | Version | Purpose |
|------|---------|---------|
| **Tableau Desktop** | 2022.2+ | Dashboard creation, visualization, interactivity |
| **Tableau Public** | Latest | Publishing & cloud sharing |
| **Excel/CSV** | — | Data storage & backup |

---

## 🚀 Getting Started

### Option 1: View Online (Recommended)
**No installation needed.** Click below to explore the live interactive dashboard:

👉 [![Open in Tableau Public](https://img.shields.io/badge/Open%20Live%20Dashboard-Tableau%20Public-orange?style=for-the-badge&logo=tableau)](https://public.tableau.com)

### Option 2: Open Locally in Tableau Desktop

1. **Clone or download** the repository:
   ```bash
   git clone https://github.com/yourusername/top-hiphop-artists-tableau.git
   cd top-hiphop-artists-tableau
   ```

2. **Open Tableau Desktop** (version 2022.2 or later recommended)

3. **Load the workbook:**
   - File → Open
   - Navigate to `top_hiphop_artists_analysis.twbx`
   - Click Open

4. **Explore the dashboard:**
   - Use filters to drill down by artist, popularity, duration
   - Hover over data points for detailed tooltips
   - Click on legend items to highlight specific groups

---

## 📂 Repository Structure

```
top-hiphop-artists-tableau/
│
├── 📊 top_hiphop_artists_analysis.twbx     # Main Tableau workbook
├── 📋 top_hiphop_artists_tracks.csv        # Raw Spotify data
├── 📖 README.md                             # This file
├── 📸 dashboard_preview.png                # Screenshot of dashboard

```

---

## 📊 Data Quality & Notes

✅ **Data Validation:**
- All popularity scores verified (0–100 range)
- No null/missing values in core fields
- Duration values cross-checked with Spotify API
- Duplicate tracks (same artist + title) removed
- Latest popularity snapshot: **May 2024**

⚠️ **Limitations:**
- Popularity scores are point-in-time snapshots (update monthly for trends)
- Dataset focuses on major label artists (indie/underground may be underrepresented)
- Collaborations attributed to primary artist (primary-centric view)
- Regional availability may affect popularity scores

---

## 💡 Potential Use Cases

🎵 **For Music Streaming Platforms:**
- Optimize playlist curation based on popularity trends
- Identify rising artists and emerging styles
- Predict viral potential of new releases

🎤 **For Record Labels:**
- Benchmark artist performance against peers
- Identify collaboration opportunities
- Track competitive positioning

📰 **For Music Journalists:**
- Data-driven hip-hop industry analysis
- Trend reports & end-of-year rankings
- Feature article research

👥 **For Hip-Hop Fans:**
- Discover top tracks and artists
- Explore collaboration networks
- Compare artist catalogs

---

## 🔗 Related Resources

- 📚 [Spotify Web API Documentation](https://developer.spotify.com/documentation/web-api)
- 📊 [Tableau Public Inspiration Gallery](https://public.tableau.com/gallery)
- 🎵 [Billboard Hot 100](https://www.billboard.com/charts/hot-100/)
- 🎶 [Music Industry Analytics](https://www.theverge.com/videos)

---

## 📬 Contact & Support

**Author:** Ankan Senapati  
**Email:** senankan002@gamil.com  
**LinkedIn:** (https://www.linkedin.com/in/ankansenapati/)  
**GitHub:** https://github.com/burney10

**Questions?** Open an issue on GitHub or reach out directly!

---


<div align="center">

### 🎧 Turn Data Into Beats. Turn Analysis Into Insights. 🎧

**Built with 🔥 using Tableau | Powered by Spotify Data | Made for Hip-Hop Lovers**

⭐ **If this dashboard helped you, please star this repo!** ⭐

*Last Updated: May 2026*

</div>
