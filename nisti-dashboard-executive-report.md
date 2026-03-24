# NISTI Executive Dashboard Report

## Document Information
- **Project:** NISTI Executive Dashboard
- **Prepared for:** CEO, Management Team, and HR Leadership
- **Prepared by Team:** HENG OULONG, HOUERN SREYKA, HEM BELLYDAY
- **Document type:** Executive and operational reporting summary
- **Version:** 1.0
- **Date:** 2026-03-24

---

## Executive Summary
The NISTI Executive Dashboard is designed to give leadership one clear view of business performance across operations, finance, quality, and customer intelligence.  
It supports daily decision-making with filter-driven metrics (Daily, Weekly, Monthly, Yearly) and clear issue escalation paths through alerts, issue logs, and root-cause insights.

The current release focuses on:
- consistent KPI logic across pages,
- clear period labeling to reduce interpretation errors,
- actionable alerting for management follow-up,
- mobile-responsive monitoring for on-the-go leadership review.

---

## Dashboard Objectives
The dashboard is built to answer three executive questions quickly:
1. **Are we meeting service and quality expectations?**
2. **Are revenue and customer trends healthy versus targets?**
3. **Where are the highest operational risks, and what action is needed next?**

---

## Audience and Decision Use
- **CEO:** monitor strategic health, forecast variance, and enterprise risk signals.
- **Managers:** identify bottlenecks, quality risks, and department-level workload issues.
- **HR and support leadership:** understand where staffing pressure and process discipline are affecting service performance.

---

## Scope by Page

### 1) Overview
- High-priority KPIs: Revenue, Forecast, Throughput, Critical Alerts.
- SLA and backlog health.
- Business signals (top customer, urgent volume, new customers).
- Designed for fast executive scanning in under 2 minutes.

### 2) Finance & Forecast
- Revenue vs Forecast trend analysis.
- Monthly/Quarterly/Yearly grouping for planning cycles.
- Customer mix and new-vs-returning distribution.
- Retention risk view for account protection.

### 3) Performance & Lab
- Throughput funnel (received -> processing -> released -> pending).
- SLA performance split.
- Data quality and certificate issue tracking.
- Provincial workload distribution.
- Issue Log + Root Cause Summary for escalation and corrective action.

### 4) Customers
- Active customer movement and new/returning behavior.
- High-volume, urgent, and complaint indicators.
- All-time customer base visibility.
- Top customer contribution analysis.

### 5) Settings
- Display preferences and data source status transparency.

---

## KPI Definitions and Logic (Management Reference)

### Revenue KPI (%)
- **Meaning:** variance of actual revenue vs forecast for selected period.
- **Formula:** `(Actual - Forecast) / Forecast * 100`
- **Signal color:** green = above forecast, red = below forecast.

### Lab Throughput
- **Meaning:** released samples as a share of received samples.
- **Formula:** `Released / Received * 100`

### Critical Alerts
- Aggregated from key risk categories:
  - certificate errors,
  - incorrect data entries,
  - quality issues,
  - repeated requests,
  - complaints.
- Alert pills are clickable and filter the Issue Log for fast investigation.

### Avg. Processing Time
- Current version uses a backlog-based operational proxy to indicate pressure level.
- Production recommendation: replace with real timestamp-based turnaround calculation.

### Backlog
- Samples not yet fully released/completed in the selected period.
- Used as leading indicator for SLA risk and processing strain.

### Retention Risk Table
- Highlights previously valuable customers with inactivity risk.
- Supports proactive recovery and account management planning.

---

## Key Functional Improvements Delivered
- Unified date/time filtering across dashboard sections (D/W/M/Y + date picker).
- Added weekly filter support.
- Finance chart grouping control now functional (Monthly/Quarterly/Yearly).
- Donuts and performance widgets now reflect selected period.
- Provincial workload no longer static; updates with filter context.
- Customer metrics separated into period metrics vs all-time base.
- Dynamic sidebar badges for fast high-level status.
- Dynamic Issue Log with root-cause summary and suggested action.
- Improved mobile responsiveness for root-cause content.

---

## Governance and Action Flow
When a critical alert appears:
1. Leadership identifies alert category from Overview.
2. Click alert category to open filtered issues in Performance & Lab.
3. Review Issue Log details (what/where/when/who).
4. Use Root Cause Summary for management-level intervention focus.
5. Assign owner and corrective action with target timeline.

This flow reduces time from detection to decision.

---

## Business Value
- **Faster decisions:** clearer signals, fewer interpretation gaps.
- **Higher accountability:** issue categories link to root-cause context.
- **Operational stability:** better visibility into backlog, SLA, and quality drivers.
- **Financial control:** clearer forecast variance and customer composition insight.
- **Leadership alignment:** single source of truth across executive and operational teams.

---

## Known Assumptions and Next Phase Recommendations
Current version uses generated mock data for demo and design validation.  
Recommended next phase:
- connect real data pipelines (LIMS, finance, CRM, QA),
- add owner/status/SLA due dates in issue workflows,
- create export-ready monthly executive pack (PDF),
- add drill-down pages by department and customer segment.

---

## Screenshot Placeholders (to insert later)

### Desktop Dashboard Screenshot
`[Insert desktop dashboard image here]`

### Mobile Dashboard Screenshot
`[Insert mobile dashboard image here]`

---

## Conclusion
The NISTI dashboard is now positioned as a professional executive monitoring platform with clear KPI logic, actionable risk visibility, and practical decision support for CEO, managers, and HR stakeholders.

It is ready for leadership presentation and can be extended directly into production analytics in the next implementation phase.

