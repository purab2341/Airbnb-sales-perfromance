# 🏠 Global Airbnb Performance Dashboard

> **An interactive business intelligence dashboard that analyzes Airbnb marketplace performance across listings, cities, hosts, property types, reviews, market share, pricing, and guest ratings.**

![Global Airbnb Performance Dashboard](assets/global_airbnb_dashboard_overview.png)

## 📌 Project Overview

The **Global Airbnb Performance Dashboard** provides a management-level view of Airbnb performance and customer experience across **10 cities**.

The dashboard combines portfolio-level KPIs with time-series analysis, city-level market concentration, property-type pricing, and rating analysis. The objective is to move from a large marketplace dataset to a **clear visual story that helps stakeholders understand growth, market concentration, pricing patterns, and service quality**.

Rather than focusing on a single metric, the dashboard connects **scale → growth → market share → pricing → ratings** in one analytical experience.

---

## 🎯 Business Objectives

The dashboard is designed to answer key business questions such as:

- How large is the Airbnb marketplace represented in the dataset?
- How have new listings changed over time?
- Which cities account for the largest share of listings?
- How concentrated is the market across the top cities?
- How do average prices differ by property type?
- Which cities receive stronger guest ratings?
- How do detailed rating dimensions such as cleanliness, communication, check-in, location, and value vary across cities?
- Which areas of the marketplace may deserve deeper commercial or operational investigation?

---

## 📊 Executive KPIs

| KPI | Value |
|---|---:|
| **Listings** | **279,712** |
| **Cities** | **10** |
| **Hosts** | **182,024** |
| **Property Types** | **144** |
| **Reviews** | **5.373M** |

These headline KPIs establish the scale and breadth of the marketplace represented in the dashboard.

---

## 📈 Dashboard Analysis

### 1. Listing Growth & Market Evolution

![Listing Growth](assets/global_airbnb_dashboard_overview.png)

The first dashboard view focuses on the evolution of new listings over time.

The visualization separates listing trends across:

- **Private Room**
- **Shared Room**
- **Hotel Room**
- **Entire Place**

The timeline covers **2008–2020** and uses milestone annotations such as the **take-off period**, **peak point**, changes in the market environment, and the later disruption highlighted in the dashboard narrative.

### What this view helps answer

- When did listing growth accelerate?
- Which accommodation types contributed to listing growth?
- Where did the market reach a peak?
- How did the market change after the peak period?

---

### 2. City Market Share

![Market Share by City](assets/global_airbnb_market_share_ratings.png)

The market-share view compares the largest cities using:

- Total listings
- Superhost listings
- Non-Superhost listings
- Cumulative percentage

The cumulative curve shows that **Paris, New York City, and Sydney together reach approximately 48.4% of the listings represented in the chart**. The dashboard narrative also states that these three cities account for **48% of total reviews**.

This makes the city comparison useful for understanding **market concentration rather than only absolute listing volume**.

---

### 3. Average Price by Property Type

The dashboard compares average prices across four accommodation types:

| Property Type | Average Price |
|---|---:|
| **Hotel Room** | **$800** |
| **Entire Place** | **$673** |
| **Shared Room** | **$580** |
| **Private Room** | **$462** |

This view makes it possible to compare the pricing structure of different accommodation formats and connect **property type with revenue potential and positioning**.

---

### 4. Guest Ratings & Service Quality

![Ratings Analysis](assets/global_airbnb_ratings_detail.png)

The ratings analysis provides two complementary perspectives.

#### Overall rating by city

The displayed city-level average ratings range from:

- **Hong Kong — 89.7**
- **Istanbul — 91.1**
- **Bangkok — 93.0**
- **Paris — 93.1**
- **Sydney — 93.2**
- **Rome — 93.5**
- **New York — 93.8**
- **Cape Town — 94.4**
- **Rio de Janeiro — 94.6**
- **Mexico City — 94.8**

#### Detailed rating dimensions

The dashboard also breaks guest experience into:

**Accuracy | Cleanliness | Communication | Check-in | Location | Value**

For the cities shown in the detailed-rating table, this makes it possible to move beyond a single overall score and identify **which customer-experience dimensions are relatively stronger or weaker**.

For example, **Mexico City** is shown with high values across the displayed detailed metrics, including **9.7 accuracy, 9.6 cleanliness, 9.8 communication, 9.8 check-in, 9.8 location, and 9.6 value**.

---

## 🔍 Key Insights

### Market concentration

The dashboard indicates a highly concentrated city market: **Paris, New York City, and Sydney reach approximately 48.4% cumulative listing share** in the market-share visualization.

### Pricing differences

Average pricing varies substantially by accommodation type, with **Hotel Rooms at $800** and **Private Rooms at $462** in the displayed comparison.

### Customer experience

City-level rating analysis shows differences across overall ratings and individual service dimensions. This allows the dashboard to identify not just **where ratings are high**, but also **which aspects of the guest experience contribute to the rating profile**.

### Scale of the marketplace

With **279,712 listings, 182,024 hosts, 144 property types, and 5.373M reviews** represented by the dashboard, the analysis provides a broad marketplace view rather than a narrow product-level report.

### Growth over time

The time-series visualization shows a long-term increase in new listings followed by a decline after the market's peak period, giving stakeholders a visual way to explore how marketplace growth changed over time.

---

## 🧠 Analytical Questions Addressed

This dashboard brings together several analytical lenses:

**Performance**
- How many listings, hosts, cities, property types, and reviews are represented?

**Growth**
- How has listing activity changed from 2008 to 2020?

**Market Share**
- Which cities contribute the largest share of the marketplace?
- How quickly does cumulative market share build across cities?

**Pricing**
- How does average price vary by property type?

**Customer Experience**
- Which cities have stronger overall ratings?
- Which cities show stronger performance across accuracy, cleanliness, communication, check-in, location, and value?

---

## 🎨 Dashboard Design & Data Storytelling

A key strength of the dashboard is its **layered visual storytelling**.

The report moves from:

**Executive KPIs → Growth Trend → City Market Share → Pricing → Ratings → Detailed Experience Metrics**

This hierarchy allows a stakeholder to start with the overall scale of the business and progressively drill into **market structure and customer experience**.

The use of KPI cards, trend lines, combination charts, bar charts, cumulative percentages, and rating heatmaps keeps different analytical questions visually distinct while maintaining one consistent dashboard theme.

---

## 💼 Business Value

The dashboard can support conversations around:

- **Market expansion** by comparing city-level concentration
- **Pricing strategy** through property-type comparisons
- **Marketplace growth** by analyzing listing trends over time
- **Host performance analysis** through Superhost vs. non-Superhost views
- **Customer experience improvement** using detailed rating dimensions
- **City-level benchmarking** across overall ratings and service quality

The dashboard is therefore positioned as a **decision-support report**, not simply a collection of charts.

---

## 🧩 Skills Demonstrated

### Data Analytics
- KPI analysis
- Trend analysis
- Market-share analysis
- Cumulative percentage analysis
- Comparative city analysis
- Pricing analysis
- Rating and customer-experience analysis

### Business Intelligence
- Executive dashboard design
- KPI storytelling
- Interactive analytical views
- Stakeholder-focused visualization
- Multi-dimensional performance analysis

### Data Visualization
- Time-series visualization
- Combination charts
- Bar charts
- KPI cards
- Heatmaps / rating matrices
- Comparative visual analysis

---

## 🏆 Why This Project Matters

This project demonstrates the ability to take a marketplace-style dataset and turn it into a **structured business narrative**.

Instead of presenting isolated metrics, the dashboard answers a sequence of practical questions:

> **How big is the marketplace? → How is it growing? → Where is the market concentrated? → How does pricing vary? → How is customer experience performing?**

That combination of **business framing, analytical thinking, and visual communication** is central to effective BI and data-analytics work.

---

## 📷 Dashboard Views

### Executive Overview

![Executive Overview](assets/global_airbnb_dashboard_overview.png)

### Market Share & Ratings

![Market Share and Ratings](assets/global_airbnb_market_share_ratings.png)

### Ratings Detail

![Ratings Detail](assets/global_airbnb_ratings_detail.png)

---

## 📌 Project Source

The dataset/project was developed from a **YouTube-based learning project** and analyzed using Excel, SQL, and Power BI.

**Source:** YouTube
