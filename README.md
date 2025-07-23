# GoogleApsAnalytics
# 📊 Google Apps Analytics Monitor

## 🔍 Project Overview
This project uses **Google Apps Script** to automate data extraction from **Google Analytics 4 (GA4)** and store it in **Google Sheets**. It enables real-time monitoring, hourly trend analysis, and seamless integration with **Looker Studio** dashboards.

---

## ✨ Features
- ⏱️ Real-time tracking of active users and pageviews
- 📈 Hourly KPI reports for custom events
- 📊 Structured Google Sheets output for easy analysis
- 📡 Looker Studio compatibility for visualization
- 🔔 Trigger-based automation for scheduled data pulls

---

## 🛠️ Technologies Used
- Google Apps Script (JavaScript)
- Google Analytics Data API (GA4)
- Google Sheets
- Looker Studio (optional)

---

## 🚀 Getting Started

### 1. Enable GA4 API
- In Apps Script: `Resources → Advanced Google Services → Enable Google Analytics Data API`

### 2. Create Google Sheets Tabs
- `KPIs`
- `Active Users`
- `Hourly`

### 3. Set Triggers
| Function                | Frequency     | Purpose                          |
|------------------------|---------------|----------------------------------|
| `runKPIsReport()`      | Every 5 mins  | Pulls real-time event data       |
| `runActiveUsersReport()` | Every 5 mins  | Fetches active users + pageviews |
| `runHourlyReport()`    | Every hour    | Historical trend analysis        |

---

## 📦 Folder Structure

```plaintext
├── GA4_AlertScript.js       # Main Apps Script file
├── README.md                # Project documentation
└── /docs                    # Setup guides and screenshots (optional)
