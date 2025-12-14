# Lab Setup

## 1. Install Splunk
- Download Splunk Enterprise
- Enable receiving on port 9997

## 2. Windows Log Collection
- Install Universal Forwarder
- Enable Sysmon
- Forward EventCode 1, 3, 7, 10

## 3. Apache Logs
- Configure Apache access logs
- Forward to Splunk via file monitor

## 4. Indexes
- windows
- apache
