# Cyber Threat Monitoring and Prioritization Pipeline

A cybersecurity intelligence pipeline that collects threat-related information from security news sources, blogs, and vulnerability databases, correlates relevant CVEs, prioritizes threats based on severity, and generates professional PDF reports.

The system helps security teams and analysts stay informed about emerging threats by automatically gathering intelligence from multiple sources and presenting the most important findings in a structured report.

## Features

- Automated collection of threat intelligence from:
  - Security News APIs
  - Security Blog RSS Feeds
  - NVD CVE Database

- Correlation of reported incidents with known CVEs

- Threat prioritization using:
  - CVSS severity scores
  - Threat-related keywords
  - Vulnerability impact indicators

- Historical intelligence tracking using JSON storage

- Automated PDF report generation

- Modular architecture for adding new intelligence sources

## Workflow

1. Collect cybersecurity news and threat reports
2. Retrieve relevant CVE information from NVD
3. Correlate vulnerabilities with reported incidents
4. Calculate threat priority scores
5. Store intelligence records
6. Generate a structured PDF report


## System architecture overview diagram
<img width="1842" height="854" alt="System_architecture_Threat_Intelligence_Pipeline" src="https://github.com/user-attachments/assets/6f2a890c-24f1-424d-bc20-2488cbbd21d2" />



## Technologies Used

- Python 3.11
- LangChain
- Groq (Llama 3.1 8B Instant)
- Requests
- Feedparser
- ReportLab

## Generated Report Includes

- Executive Summary
- Top Prioritized Threats
- Related CVEs
- Threat Severity Scores
- Key Findings
- Recommended Actions

## Use Cases

- Cyber Threat Monitoring
- Vulnerability Awareness
- Threat Intelligence Research
- Weekly Security Reporting
- Security Operations Support

## Future Improvements

- IOC extraction
- Threat actor mapping
- Threat trend analysis
- Dashboard visualization
- SIEM integration
