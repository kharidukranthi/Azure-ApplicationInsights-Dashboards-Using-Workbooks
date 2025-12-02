📊 Azure Application Insights Dashboards Using Azure Monitor Workbooks
Enterprise-grade Performance, Failure & Dependency Analysis Templates for Any Application Insights Resource
🚀 Overview

This repository contains Azure Monitor Workbooks designed to provide both Executive-level and Engineering-level visibility into:

API performance

Failures (new vs existing)

Response time trends

Dependency bottlenecks

User impact

Traffic patterns

All dashboards are built using Azure Application Insights and Kusto Query Language (KQL).

These workbooks are:

Fully reusable → Copy/paste JSON into any Application Insights resource

Parameter-driven → Auto-adjust baselines, filters, time ranges

Cloud-agnostic → No hardcoded resource IDs

Production-tested → Built for real enterprise monitoring

Scalable → Easily extended across microservices

📁 Repository Structure
Azure-ApplicationInsights-Dashboards-Using-Workbooks/
│
├── Executive-Performance-Dashboard/
│   ├── Executive_Performance_Workbook.json
│   ├── Executive_Performance_Workbook Screenshot.png
│   └── README.md
│
├── Detailed-Perfromance-Dashboard/
│   ├── Detailed_Performance_Workbook.JSON
│   ├── Detailed_Performance_Workbook Screenshot.png
│   └── README.md
│
├── LICENSE
└── README.md   <-- (this file)


Each dashboard folder contains:

The Workbook JSON template

A dashboard-specific README

A sample screenshot

📈 Dashboards Included
1️⃣ Executive Performance Dashboard

High-level KPI-focused visualization intended for:

Leadership

Product owners

Architecture teams

Daily health checks

Features:

New vs Existing Failure Analysis

Response Time (now vs baseline)

Result-code segmentation (400s, 500s)

Trend charts

Per-operation filtering

➡️ Folder:
Executive-Performance-Dashboard/

2️⃣ Detailed Engineering Dashboard

Deep-dive investigation dashboard for:

Developers

SRE / DevOps Teams

Performance Engineers

Features:

p50 / p95 / p99 latency

Operation-level heatmaps

Slow dependency detection

Error spikes

Drill-down workflows

End-to-end request investigation

➡️ Folder:
Detailed-Perfromance-Dashboard/

🛠️ How to Install These Workbooks

Open Azure Portal

Go to Application Insights → Workbooks

Click New → Advanced Editor

Paste the JSON from the dashboard folder

Replace required placeholders (search for {YOUR )

Save the workbook with your own name

Done! Your dashboard is live.

🔍 Replace These Values Before Use

Look for values like:

{YOUR-SUBSCRIPTIONID}
{YOUR-RESOURCEGROUPNAME}
{YOUR-RESOURCENAME}
{YOUR-APPNAME}


Search for:

{YOUR


…and update them with your environment.

📷 Screenshots
Executive Dashboard

Detailed Performance Dashboard

🤝 Contributions

Feel free to:

Submit issues

Suggest enhancements

Create pull requests

Add your own Azure Workbooks

This project aims to become a community hub for reusable Azure Monitor Workbooks.

📝 License

This repository uses the MIT License, allowing personal and commercial use.
