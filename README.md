# SATUSEHAT SSP Monitoring Dashboard

## Overview

Monitoring dashboard and automation system for SATUSEHAT SSP resource delivery, including Encounter, Condition, Medication, and MedicationRequest integration workflows.

## Features

- SATUSEHAT SSP Integration
- Encounter Resource Delivery
- Condition Resource Delivery
- Medication Resource Delivery
- MedicationRequest Delivery
- Retry Failed Request
- Monitoring Dashboard
- Success/Failed Tracking
- Delivery Statistics
- Cronjob Automation
- FHIR Resource Logging
  
## Integration Workflow

The SSP integration system automatically sends healthcare service data into SATUSEHAT FHIR resources.

### Integrated Resources

- Encounter
- Condition
- Medication
- MedicationRequest

### Workflow

1. Clinical transaction recorded
2. Data transformed into FHIR JSON
3. Resource delivery process executed
4. Response logging stored
5. Failed delivery marked for retry
6. Monitoring dashboard updated
 
## Dashboard Monitoring

The dashboard provides real-time monitoring of SSP delivery activities.

### Monitoring Features

- Total delivery statistics
- Success and failed counts
- Monthly statistics graph
- Delivery logs
- Resource category tracking
- Cronjob execution monitoring
- 
## Retry Mechanism

Failed SSP deliveries can be resent automatically or manually using the retry feature available in the monitoring dashboard.

### Features

- Failed request detection
- Retry button execution
- Error response logging
- Delivery status tracking

## Statistics & Reporting

The system provides monitoring statistics and reporting features for SATUSEHAT SSP delivery activities.

### Available Statistics

- Total SSP delivery count
- Success delivery count
- Failed delivery count
- Pending delivery count
- Monthly delivery statistics
- Resource-based delivery statistics

### Monitoring Dashboard

The dashboard allows administrators to monitor delivery performance in real time.

### Reporting Features

- Delivery log report
- Failed request report
- Success transaction report
- Daily and monthly recap
- Resource delivery history

### Visualization

- Bar chart statistics
- Delivery activity summary
- Resource comparison monitoring

## SSP Resources

This system integrates healthcare service data into SATUSEHAT using FHIR R4 resources.

### Supported Resources

#### Encounter
Patient visit and healthcare service activity data.

#### Condition
Patient diagnosis and medical condition information.

#### Medication
Drug and medicine resource data.

#### MedicationRequest
Prescription and medication request information.

### Delivery Method

- JSON FHIR Bundle
- REST API Integration
- OAuth2 Authentication
- SATUSEHAT API Gateway

### Resource Workflow

Clinical Transaction
→ Data Transformation
→ FHIR Bundle Generation
→ API Delivery
→ Response Logging
→ Monitoring Dashboard

## Screenshots
![dashboard1](docs/dashboard_ssp1.png)
![dashboard2](docs/dashboard_ssp2.png)
![dashboard3](docs/dashboard_ssp3.png)

## Technology Stack
- PHP Native / CodeIgniter
- MySQL
- Bootstrap
- Chart.js
- XAMPP
- Cron Job
- SATUSEHAT API
- FHIR R4

## Disclaimer

This repository is intended for portfolio and case study purposes only. Sensitive client data and proprietary business logic have been removed

## Author

Suprayogi
