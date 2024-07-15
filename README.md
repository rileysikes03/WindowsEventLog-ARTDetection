# Windows Event Log + Atomic Red Team (ART) Detection

## Objective
This project aims to enhance threat detection capabilities in a Windows environment by leveraging Windows Event Logs and Atomic Red Team (ART) tests. By correlating event log data with known adversary techniques provided by ART, the goal is to improve the detection and response to potential security threats.

## Skills Learned
- Advanced Windows Event Log monitoring and analysis.
- Implementation of Atomic Red Team tests for detection.
- Scripting and automation using PowerShell.
- Threat hunting methodologies and techniques.


## Tools Used
- Atomic Red Team: Framework for simulating adversary behaviors.
- Windows Event Logs: Source of system and security events.
- PowerShell: Scripting for automation and executing ART tests.
- Splunk: Centralized log collection, analysis, and correlation.
- Sysmon: Enhanced Windows system monitoring for detailed event logging.

## Steps

### 1. Understanding Adversary Techniques
- Familiarize with MITRE ATT&CK framework for common adversary techniques.

### 2. Environment Setup
- Configure Windows environment with Sysmon to capture detailed system activity.
- Install Splunk for centralized log collection, analysis, and real-time correlation of events.

### 3. Deploying Atomic Red Team
- Install and configure Atomic Red Team on Windows machine.
- Use PowerShell to execute ART tests and generate telemetry data.

### 4. Correlating Events with Adversary Techniques
- Develop queries in Splunk to correlate event log data with ART adversary techniques.
- Create alerts based on identified patterns indicative of malicious activity.

### 5. Automation and Response
- Develop PowerShell scripts to automate periodic execution of ART tests.
- Implement automated response mechanisms based on detection outcomes.

## Conclusion
By integrating Windows Event Log monitoring with ART tests, and utilizing Splunk and Sysmon, this project aims to proactively detect and respond to various adversary techniques. Continuous refinement of detection mechanisms will strengthen overall security posture and readiness against cyber threats.

## Screenshots
![Capture](https://github.com/user-attachments/assets/77ed4ccf-238c-490d-be24-d9370ed75e26)

![Capture2](https://github.com/user-attachments/assets/ade38e61-38cd-4e1a-9984-d740be013c32)
