# AI Threat Detection & Auto Mitigation Engine

AI-powered cybersecurity analytics platform for detecting threats from endpoint, server, and cloud security events.

## Features

- Real-time security event processing
- Kafka based streaming pipeline
- Windows Event Log analysis
- AWS CloudTrail analysis
- Sigma rule detection
- MITRE ATT&CK mapping
- Machine Learning anomaly detection
- User behavior learning
- LLM-powered threat explanation
- Automated mitigation recommendations


## Architecture

Data Sources

Windows Systems
Windows Servers
AWS CloudTrail

        |
        v

Winlogbeat / Cloud Logs

        |
        v

Kafka

        |
        v

Detection Engine

        |
        +--> Sigma Rule Engine

        +--> MITRE ATT&CK Mapping

        +--> Isolation Forest ML Model

        +--> LLM Security Analyzer

        |
        v

Threat Score + Mitigation


## Machine Learning

Algorithm:

- Isolation Forest

Features:

- Command line entropy
- Suspicious PowerShell detection
- Process behavior
- User activity patterns
- Login time behavior
- Security event patterns


## Tech Stack

- Python
- Apache Kafka
- Elasticsearch
- Logstash
- Winlogbeat
- AWS CloudTrail
- Scikit-Learn
- Sigma Rules
- MITRE ATT&CK
- LLM Integration
