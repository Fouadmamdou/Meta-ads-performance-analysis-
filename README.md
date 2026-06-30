# 📊 Meta Ad Performance Dashboard

An interactive Power BI dashboard for tracking and analyzing **Meta (Facebook & Instagram) ad campaign performance** — built to give marketers a fast, visual read on reach, engagement, and conversion metrics across campaigns, demographics, and time.

![Dashboard Preview](meta.png)

## 🧭 Overview

This dashboard consolidates Meta Ads data into a single, decision-ready view. It surfaces top-line KPIs alongside breakdowns by **audience demographics, geography, ad type, and time**, so stakeholders can quickly spot trends and reallocate budget toward what's working.

## ✨ Key Features

- **At-a-glance KPI cards** for the metrics that matter most to ad performance
- **Dynamic measure selector** — swap the underlying metric (e.g., Shares, Clicks, Engagements) across visuals without rebuilding the report
- **Campaign-level filtering** by name and target interest segments
- **Time intelligence** via weekly trend, hourly trend, and a month/calendar picker
- **Demographic breakdowns** by gender and age
- **Geographic breakdown** with an interactive map of shares by country
- **Ad-type performance table** comparing Carousel, Stories, Image, and Video formats

## 📈 KPIs Tracked

| Metric | Description |
|---|---|
| Impressions | Total ad views |
| Clicks | Total ad clicks |
| Shares | Total content shares |
| Comments | Total comments received |
| Purchases | Total conversions to purchase |
| Engagements | Total likes, comments, shares, and clicks combined |
| CTR | Click-Through Rate |
| Engagement Rate | Engagements ÷ Impressions |
| Purchase Rate | Purchases ÷ Clicks (or relevant base) |
| Conversion Rate | Purchases ÷ Total Engagements |
| Total Budget | Aggregate ad spend across campaigns |
| Avg. Budget per Campaign | Mean spend per campaign |

## 🔍 Visualizations

- **Shares by Gender** — donut chart comparing male vs. female engagement
- **Shares by Age** — distribution bar chart across age groups
- **Weekly Shares Trend** — stacked bar chart of shares over weeks, segmented by category
- **Hourly Shares Trend** — line chart showing intraday engagement peaks
- **Shares by Country** — geo map of share volume by location
- **Analysis by Month** — calendar-style date picker for period drill-down
- **Analysis by Ad Type** — table comparing impressions, clicks, CTR, purchase rate, engagement rate, and conversion rate across ad formats

## 🎛️ Filters & Interactivity

- Dynamic measure dropdown to re-context all visuals around a chosen metric
- Campaign name multi-select (e.g., Campaign_1_Launch, Campaign_10_Winter)
- Target interest multi-select (e.g., art, news)
- Month/date selector with calendar navigation

## 🛠️ Tech Stack

- **Power BI** — report design, DAX measures, and data modeling
- **Meta Ads data** (Facebook & Instagram) as the underlying data source

## 🚀 Getting Started

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Connect/refresh the data source with your own Meta Ads export
4. Use the dynamic measure selector and filters to explore the data

## 💡 Insights Enabled

- Identify which **ad formats** (Carousel, Stories, Image, Video) drive the strongest CTR and conversion rate
- Spot **peak engagement hours/days** to optimize ad scheduling
- Understand **audience composition** by age and gender to refine targeting
- Track **share volume by country** to prioritize high-performing regions
- Monitor **budget efficiency** via spend-per-campaign against engagement and conversion outcomes

## 📌 Notes

- Replace sample/demo data with live Meta Ads API exports for production use
- KPI thresholds and color formatting can be adjusted to match brand guidelines

---

*Built with Power BI to turn raw ad data into actionable marketing insights.*
