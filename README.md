# Website-Engagement-LinkedIn-Analysis

This repository contains a Power BI report that analyzes **website traffic** and **LinkedIn outreach performance** to measure overall **marketing effectiveness**.

The goal of the project is to give founders/marketing teams a single place to answer:

- *How healthy is our website traffic?*  
- *Is our LinkedIn outreach converting to calls and opportunities?*  
- *How are these metrics trending over time?*

---

## 1. Dashboard Overview

The report is organized into three main views, accessible from the left-hand navigation or from the landing page.

### 1.1 Google Analytics View

Focus: **Website performance & user engagement**

Key metrics:

- **Sessions**
- **Engagement Rate**
- **Total Users**
- **New Users %**
- **Bounce Rate**

Key visuals:

- **Traffic & Engagement by Source**  
  Breakdown of sessions, users, page views, engagement rate and bounce rate by first user source (e.g. Google, LinkedIn, Direct, etc.).

- **Traffic & Engagement by Region**  
  Aggregated metrics by continent to understand geographic performance.

- **Traffic by User Type**  
  New vs returning users.

- **Traffic by Device**  
  Desktop vs mobile usage.

- **Monthly Engagement & Users**  
  Combined line/area chart showing engagement rate alongside total users by year.

- **Sessions by Day of Week**  
  Helps identify which days drive the most traffic.

Filters:

- **Year**
- **Device Category**
- **Month**

---

### 1.2 LinkedIn Outreach View

Focus: **Prospecting, messaging, and conversion funnel**

Top KPIs:

- **Total Leads Contacted**
- **Messages Sent**
- **Response Rate %**
- **Calls Booked**
- **Post Engagement %**
- **Conversion Rate**

Key visuals:

- **LinkedIn Lead-to-Call Funnel**  
  Messages sent → replies → emails sent → calls booked.

- **Top LinkedIn Posts by Engagement Rate**  
  Table of posts with URLs and engagement rate, to highlight best-performing content.

- **Response & Conversion Rates by Power BI Use**  
  Simple comparison chart (Yes/No) to demonstrate how usage of data/BI might relate to performance.

- **Daily Outreach Messages Sent**  
  Time-series of messages sent over the outreach period.

- **Lead Demographics Overview**  
  Average percentage breakdown by:
  - Company size  
  - Industry  
  - Job title  
  - Location  
  - Seniority  

Filters:

- **Contact Date (date range slider)**
- **Company**

---

### 1.3 Time Series Analysis View

Focus: **Week-by-week LinkedIn & content performance**

Top KPIs:

- **Impressions**
- **Members Reached**

Key visuals:

- **Weekly LinkedIn Outreach Performance**  
  Stacked area chart showing messages sent, messages replied, and calls booked by week.

- **Weekly Response Rate**  
  Line chart tracking response rate over weeks.

- **Content Impressions & Engagement**  
  Bar + line combo chart showing total impressions and total engagements per month.

- **Posts per Week and Followers**  
  Posts per week vs follower count to see how content volume relates to audience growth.

Filters:

- **Contact Date (date range slider)**
- **Company**

---

## 2. Data & Assumptions

> ⚠️ **Important:**  
> For portfolio purposes, it is recommended to use **synthetic or anonymized data** instead of real company data.

Typical data sources used for this report:

- Exported **Google Analytics** data (sessions, engagement, users, geography, device, etc.)
- Exported **LinkedIn outreach** & **content performance** data (messages, replies, calls, impressions, demographics, etc.)

You can replace these with your own exports or simulated datasets while keeping the same data model and visuals.

---

## 3. Features & Skills Demonstrated

- End-to-end **Power BI report development**
- Data modeling for multi-source marketing data
- Creation of **DAX measures** for:
  - Engagement rate
  - New users %
  - Bounce rate
  - Response rate %
  - Conversion rate
- KPI cards, funnel charts, time-series, and comparison visuals
- UX design:
  - Landing page with clear navigation
  - Consistent layout and color theme
  - Page-level and report-level slicers
- Interpretation of marketing metrics for business stakeholders

---
