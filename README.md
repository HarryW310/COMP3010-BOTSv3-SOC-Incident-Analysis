# BOTSv3 SOC Incident Analysis – COMP3010
## Author
Name: Harry Wilson

Module: COMP3010 – Security Operations

Institution: University of Plymouth

## Overview
This repository contains the investigation and analysis conducted as part of the COMP3010 Security Operations coursework. The project uses the Boss of the SOC v3 (BOTSv3) dataset and Splunk Enterprise to simulate real-world SOC investigation tasks involving cloud, endpoint, and log-based security monitoring.

The aim of this work is to demonstrate SOC-relevant skills including log ingestion, threat detection, incident analysis, and security interpretation.

## Objectives
Analyse AWS CloudTrail logs to identify insecure IAM activity

Detect cloud misconfigurations involving publicly accessible S3 buckets

Identify evidence of exploitation through S3 access logs

Perform endpoint analysis using Windows host monitoring data

Apply SOC concepts such as detection, attribution, and impact assessment

##Tools + Technologies
Splunk Enterprise

BOTSv3 Dataset

AWS CloudTrail Logs

AWS S3 Access Logs

##summary
Multiple IAM users accessed AWS services without MFA enabled

An S3 bucket (frothlywebcode) was made publicly accessible via a PutBucketAcl API call

The misconfiguration was exploited, evidenced by a successful file upload

Endpoint analysis revealed deviations from the Windows OS baseline
