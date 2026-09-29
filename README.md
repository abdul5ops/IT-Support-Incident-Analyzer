# IT Support Incident Analyzer & ITSM Documenter

##Overview
A Bash automation tool designed for IT Support and Service Desk environments. It parses system logs, counts critical events, and generates a structured Incident Report. 

This project bridges the gap between technical troubleshooting and IT Service Management (ITSM) documentation.

## Features
- Accepts a system log file as input.
- Counts total ERROR and WARNING events.
- Extracts detailed error logs for analysis.
- Generates a timestamped Incident Report (`Incident_Report_YYYY-MM-DD.txt`).
- Includes an ITSM template for Priority, Affected System, Troubleshooting Steps, Resolution, and Status.

## 🚀 How to Run
```bash
bash it_support_analyzer.sh sample_system.log
