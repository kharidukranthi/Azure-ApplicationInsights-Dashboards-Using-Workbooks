📊 Azure Application Insights Dashboards Using Azure Monitor Workbooks
Enterprise-grade Performance & Failure Analysis Templates for Any Application Insights Resource
<p align="center"> <img src="Executive-Performance-Dashboard/screenshots/overview.png" width="700"/> </p>
🚀 Overview

This repository contains Azure Monitor Workbooks that provide Executive-level and Engineering-level visibility into application performance, failures, latency, and health — all powered by Azure Application Insights and Kusto Query Language (KQL).

These dashboards are:

Fully reusable → Copy/paste JSON into any Application Insights instance

Parameter-driven → Auto-adjust baseline windows, filters, operations, time ranges

Cloud-agnostic → No resource-specific IDs required

Production-ready → Used in real-world enterprise environments

Designed to scale → Easy to apply across multiple microservices or APIs

📁 Repository Structure
Azure-ApplicationInsights-Dashboards-Using-Workbooks/
│
├── Executive-Performance-Dashboard/
│   ├── Executive_Performance_Workbook.json
│   ├── README.md
│   └── screenshots/
│
├── Detailed-Performance-Dashboard/
│   ├── Detailed_Performance_Workbook.json
│   ├── README.md
│   └── screenshots/
│
└── LICENSE


Each subfolder includes:

The JSON template

A dashboard-specific README

Screenshots of charts, tables, and filters

📈 Included Dashboards
1️⃣ Executive Performance Dashboard

High-level view for managers, architects, and executives.

✔️ New vs Existing Failures (intelligent comparison)
✔️ Response time trends (now vs baseline)
✔️ 400/500 segmentation
✔️ Operation-level drill-downs
✔️ Summary KPIs
✔️ Health indicators

➡️ Open dashboard
/Executive-Performance-Dashboard/Executive_Performance_Workbook.json

2️⃣ Detailed Engineering Dashboard

Deep-dive view for engineers, SREs, developers.

✔️ p50 / p95 / p99 latency
✔️ Dependency bottlenecks
✔️ Operation-level spike analysis
✔️ Drilldown workflows for RCA
✔️ Traffic heatmaps
✔️ User-impact segmentation

➡️ Open dashboard
/Detailed-Performance-Dashboard/Detailed_Performance_Workbook.json

🔧 How to Install These Workbooks

Go to Azure Portal → Application Insights → Workbooks

Click New

Select Advanced Editor

Paste the JSON from this repo:

Executive template

or Detailed engineering template

Click Apply

Update placeholders (search for “{YOUR…}”)

Save the workbook with a custom name

Your dashboard is now fully operational.

🔍 Replace These Values Before Use

Every template includes placeholders like:

{YOUR-SUBSCRIPTIONID}
{YOUR-RESOURCEGROUPNAME}
{YOUR-RESOURCENAME}
{YOUR-APPNAME}


Search for:

{YOUR


…update with your own values.

🎥 Screenshots

Add screenshots inside:

/Executive-Performance-Dashboard/screenshots

/Detailed-Performance-Dashboard/screenshots

Example placeholders:

<p align="center"> <img src="Executive-Performance-Dashboard/screenshots/executive-failures.png" width="700"/> </p> <p align="center"> <img src="Detailed-Performance-Dashboard/screenshots/dependencies.png" width="700"/> </p>
🤝 Contributions

Feel free to:

Open issues

Suggest enhancements

Submit new workbooks

Open PRs

This repository is intended to grow into a public library of reusable Azure Monitor Workbooks.

📝 License

This project is licensed under the MIT License — use it freely in your organization or commercial products.

⭐ Acknowledgements

Created as part of real-world performance engineering work involving:

Application Insights

Azure App Services

Azure API Management

Azure Search (Cognitive Search)

Redis Cache

Blob fallback patterns

Enterprise-scale API monitoring

🙌 Connect

If you need additional dashboards, custom KQL, or want to contribute templates, feel free to reach out.
