# Operational Risk SLA Pressure Monitoring Framework

## 📌 Overview
This project develops a risk-based monitoring framework for identifying SLA compliance pressure, remediation backlog growth, and escalation risk across business units and owners.

The model enables leadership to proactively detect control weaknesses before regulatory or operational impact occurs.

---

## 🎯 Business Problem
Operational issues often accumulate silently until:

- SLA compliance declines
- Overdue backlog grows
- Aging exposure exceeds tolerance thresholds

Risk teams require structured prioritization to identify escalation pressure early.

This dashboard answers:

> Where is remediation pressure building, and which issues require immediate intervention?

---

## 🧠 Analytical Approach
The framework incorporates:

- SLA compliance trend monitoring
- Net issue growth detection
- Aging exposure segmentation
- Overdue ratio tracking
- Risk-adjusted prioritization scoring

Two prioritization models are compared:

1. **Provided Priority Score**
2. **Risk-Adjusted Priority Score (Custom Weighted Model)**

Custom scoring incorporates:
- Risk severity weighting
- Overdue escalation multiplier
- Aging exposure adjustment

---

## 📊 Dashboard Structure

### Executive Overview
High-level KPI monitoring:
- Open Issues
- Open Overdue
- SLA Compliance Rate
- 90+ Day Exposure
- Backlog Trend Indicator

### Business Unit Drill-Down
- Pressure concentration by business unit
- Net growth acceleration
- Aging distribution patterns

### Owner Remediation Profile
- Risk-adjusted scoring
- Overdue status visibility
- Escalation flagging

---

## 🚀 Strategic Value
This framework enables:

- Proactive escalation management
- Capacity reallocation decisions
- Control environment assessment
- Risk concentration identification

---

## 🛠 Tools Used
- Power BI
- DAX
- Risk-weighted modeling logic
- Governance-focused KPI design

- ## 📈 Risk-Adjusted Priority Scoring Logic

A custom prioritization model was developed to improve transparency and defensibility over the provided dataset score.

The Risk-Adjusted Priority Score incorporates:

- Risk severity weighting (Low–Critical)
- Overdue escalation multiplier
- Aging exposure factor

This enables leadership to identify issues most likely to escalate into operational or regulatory risk.

## 🗣 Executive Framing

If presenting this dashboard to leadership, I would focus on:

- Concentration of overdue issues by business unit
- Sustained positive net issue growth trends
- 90+ day exposure as a leading indicator of control breakdown
- Escalation prioritization using risk-adjusted scoring

The objective is proactive remediation before SLA breaches evolve into regulatory or operational impact.
