# VRV-Security-s-Python-Intern-Assignment
# VRV-Security-s-Python-Intern-Assignment
## 🔒 Overview
This Python script is a sophisticated log analysis tool developed for VRV Security's internship assignment. It provides comprehensive analysis of network log files, focusing on identifying potential security threats and usage patterns.
## 🚀 Features
* IP Request Tracking: Counts and ranks requests by IP address
* Endpoint Analysis: Identifies the most frequently accessed web endpoints
* Suspicious Activity Detection: Flags potential brute force login attempts
* Flexible Reporting: Generates both terminal and CSV output
## 📊 Output
The script generates two types of output:

1. Terminal Report:

* Requests per IP address
* Most accessed endpoint
* Suspicious login activities


2. CSV Report (log_analysis_results.csv):

* Detailed breakdown of IP requests
* Endpoint access statistics
* Flagged IP addresses with failed login attempts

## 🔍 Detailed Analysis Breakdown
1. IP Request Tracking

* Counts total requests for each unique IP address
* Sorts results in descending order
* Helps identify most active network sources

2. Endpoint Analysis

* Tracks access to different web endpoints
* Identifies the most frequently visited resource
* Provides insights into application usage patterns

3. Suspicious Activity Detection

* Monitors failed login attempts
* Configurable threshold for flagging potential threats
* Helps identify potential brute force attack attempts

## 🛡️ Security Considerations
* Configurable threshold for suspicious activities
* Comprehensive logging without storing sensitive information
* Designed with cybersecurity best practices in mind

## 📝 Logging Methodology
* Parses standard Apache/Nginx log format
* Supports various HTTP methods (GET, POST, PUT, DELETE)
* Handles different status codes and log entry variations
