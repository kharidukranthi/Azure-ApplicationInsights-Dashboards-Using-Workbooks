# 📊 Azure Application Insights Dashboards Using Azure Monitor Workbooks  
Enterprise-grade Performance, Failure & Dependency Analysis Templates for Any Application Insights Resource

---

## 🚀 Overview

This repository contains **Azure Monitor Workbooks** designed to provide both Executive-level and Engineering-level visibility into:

- API performance  
- Failures (new vs existing)  
- Response time trends  
- Dependency bottlenecks  
- User impact  
- Traffic patterns  

All dashboards are built using **Azure Application Insights** and **Kusto Query Language (KQL)**.

### Why these workbooks?

These workbooks are:  

- **Fully reusable** → Copy/paste JSON into any Application Insights resource  
- **Parameter-driven** → Auto-adjust baselines, filters, time ranges  
- **Cloud-agnostic** → No hardcoded resource IDs  
- **Production-tested** → Built for real enterprise monitoring  
- **Scalable** → Easily extended across microservices  

---

## 📁 Repository Structure

<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/8888a30c-0a26-4b07-ae5a-2d1d3b78a33e" />

---

# 📘 Executive Dashboard

### 📍 File  
`/Executive-Performance-Dashboard/Executive_Performance_Workbook.json`

### 🧭 Summary  
An executive-level dashboard focusing on:  
- New vs existing failures  
- Request trends  
- Result code breakdown  
- Baseline comparison windows (7d, 14d, 28d, 60d)  
- Average response times (Now vs Baseline)  

👉 View details inside the folder’s own README.

---

# 📘 Detailed Engineering Dashboard

### 📍 File  
`/Detailed-Performance-Dashboard/Detailed_Performance_Workbook.json`

### 🧭 Summary  
A deep-dive engineering dashboard for:  
- p50 / p95 / p99 latency  
- Operation-level performance  
- Dependency correlation  
- Throttling analysis  
- Error patterns  
- Drilldowns  

👉 View details inside the folder’s own README.

---

# 🛠️ Deployment Instructions

To deploy any workbook:

1. Open **Azure Portal**  
2. Go to **Application Insights → Workbooks**  
3. Click **New**  
4. Click **Advanced Editor**  
5. Paste JSON from this repository  
6. Replace fields containing `{YOUR-...}`  
7. Save the workbook  

That’s it — dashboard ready.

---

# 🔧 Replace Environment-specific Values

Search for:

{YOUR


Replace with:
- Subscription ID  
- Resource group  
- Application Insights resource  
- App or API name  

This makes the dashboards instantly reusable.

---

# 🖼️ Screenshots

Screenshots are included inside each dashboard folder:

- `/Executive-Performance-Dashboard/screenshots/`
- `/Detailed-Performance-Dashboard/screenshots/`

---

# 👏 Contributing

Pull requests are welcome!

You can contribute:
- New visual modules  
- Additional KQL insights  
- More reusable templates  
- Fixes and enhancements  

---

# 📄 License

MIT License – free to use, modify, and distribute.

---
