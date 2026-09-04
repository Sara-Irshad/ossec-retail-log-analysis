# Log Analysis and Alerting Tool for a Retail Chain - OSSEC Component (Member 4)

##Overview
This repository contains my individual contribution to the Log Analysis and Aleting Tool for a Retail Chain Project, built during SDC Defensive Security 
internship. It implements host-based intusion detection using OSSEC, focused on retail-point -of-sale (POS) terminal security scenarios.

##What's included
-local_rules.xml - 5 custom OSSEC detection rules
-Day_Log_Analysis_Report.pdf - full report with rule documentation, tested alert evidence, sample log-review dashboard, and incident-response 
procedures, Screenshots of setup, rule testing, and live alert generation.

##Detection Rules Summary
Rule 100010 - Failed login on POS admin Terminal - Severity 5
Rule 100011 - Brute-Force attempt on POS admin Terminal - Severity 10
Rule 100012 - Unauthorized Account Creation - SEVERITY 8
Rule 100013 - Privileged Command Execution - Severity 6
Rule 100014 - POS Configuration File Tempering - Severity 7

##Enviroment
Ubuntu Server 26.04.1 LTS on VirtualBox VM, OSSEC-HIDS v3.7.0 installed in local mode. All rules tested against the live OSSEC daemon.

##Author
Sara Irshad, CyberSecurity Student,Institute of Management Sciences (Imsciences), Peshawar
