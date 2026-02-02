# LIAO Attendance Dashboard

![Dashboard Preview][([https://via.placeholder.com/1200x800/2563EB/FFFFFF?text=LIAO+Dashboard](https://imgur.com/a/YCigON3))]
## Description
Clean, member-focused **Looker Studio** dashboard for tracking meeting attendance metrics in the **LIAO** student league. Each member gets personalized self-service access through an **email filter**.

## Key Features
- **Personalized KPIs**: Overall presence %, assigned meetings, total attendance time, total absences
- **Trend charts**: Presence and time per month (multi-year support)
- **Distribution visuals**: Presence vs absence % and meeting type breakdown
- **Detailed table**: Full history with date, meeting type, duration, status, and justifications
- **Email filter**: Members access only their own data via simple dropdown filter

## How to use
1. Select your **email** in the top filter
2. View main KPIs in cards
3. Track monthly evolution in charts
4. Check specific details in bottom table

## Data Structure
Meeting Date | Type | Total Time (min) | Name | Stay Time | % | Status | Justification | ID


## Tech Stack
- **Looker Studio** (Google Data Studio)
- **Calculated fields** (CASE WHEN, AVG, SUM, COUNT_DISTINCT)
- **Responsive design** with custom KPI cards

## 🚀 Quick Setup
1. Duplicate the Looker Studio report
2. Connect to your Google Sheets data source
3. Share with league members (they'll filter by their email)

## Authors
Developed by **Pedro Rodriguez** and **Pedro Silva** on behalf of **LIAO**.

<div align="center">
  <small>Made with ❤️ for LIAO members</small>
</div>
