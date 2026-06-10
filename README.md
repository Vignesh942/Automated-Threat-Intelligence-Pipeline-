# Automated Threat Intelligence Pipeline

An automated threat intelligence pipeline that collects cybersecurity threat data from multiple sources, correlates related events and vulnerabilities, prioritizes threats based on severity, and generates professional PDF reports.

The project aggregates information from security news feeds, blogs, and CVE databases to provide a consolidated view of emerging threats. It helps security analysts quickly identify high-priority risks and actionable intelligence without manually reviewing multiple sources.

## Features

- Collects threat intelligence from multiple sources:
  - Security News APIs
  - Security Blog RSS Feeds
  - NVD CVE Database

- Correlates reported incidents with known CVEs

- Calculates threat scores using:
  - CVSS severity
  - Threat-related keywords
  - Source intelligence

- Maintains historical intelligence records using JSON-based storage

- Generates structured threat intelligence reports in PDF format

- Modular architecture for easy integration of additional data sources

## System Architecture

### Data Collection Layer
Retrieves threat intelligence data from news feeds, security blogs, and vulnerability databases.

### Processing Layer
Normalizes collected data, correlates related threats and CVEs, and performs threat prioritization.

### Intelligence Storage Layer
Stores processed intelligence and historical records for future analysis.

### Report Generation Layer
Creates structured threat intelligence reports containing summaries, findings, and recommendations.

### Output Layer
Exports finalized reports as professional PDF documents.

## Technologies Used

- Python 3.11
- LangGraph
- LangChain
- Groq (Llama 3.1 8B Instant)
- Requests
- Feedparser
- ReportLab

## Sample Report Contents

Each generated report includes:

- Executive Summary
- Top Prioritized Threats
- Related CVEs
- Threat Scores
- Key Findings
- Security Recommendations

## Use Cases

- Threat Intelligence Monitoring
- Security Operations Support
- Vulnerability Awareness
- Weekly Security Reporting
- Cyber Threat Research

## Future Enhancements

- Additional threat intelligence feeds
- Threat actor attribution
- IOC extraction and enrichment
- Threat trend visualization dashboard
- SIEM integration
