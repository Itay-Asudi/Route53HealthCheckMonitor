# Route53HealthCheckMonitor

## Overview
`Route53HealthCheckMonitor` is a Python script designed for monitoring AWS Route 53 Health Checks. It seamlessly integrates with monitoring solutions like Nagios and Icinga, providing a simple yet effective way to ensure the health of AWS services. This tool checks the health status of AWS Route 53 health checks and reports back with detailed status information.

## Features
- Easy integration with Nagios and Icinga.
- Customizable AWS region and health check IDs.
- Clear output indicating the health status of AWS Route 53 services.

## Prerequisites
- Python 3.x
- Boto3 library
- AWS account with access to Route 53
- Valid AWS Access Key ID and Secret Access Key

## Installation
a. Clone the repository:
   ```bash
git clone https://github.com/Itay-Asudi/Route53HealthCheckMonitor.git
```
b. Navigate to the cloned directory:
```bash
cd Route53HealthCheckMonitor
```
c. Install required packages:  
```bash
pip install -r requirements.txt
```

## Usage
Run the script with the necessary arguments:
```bash
python route53_health_check_monitor.py --health-check-id [Your Health Check ID] --region [Your AWS Region] --Key [Your AWS Access Key ID] --SKey [Your AWS Secret Access Key]
```
