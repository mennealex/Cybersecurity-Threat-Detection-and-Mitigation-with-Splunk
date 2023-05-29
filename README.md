# Cybersecurity-Threat-Detection-and-Mitigation-with-Splunk

## **Project Summary**
In this project, I was engaged as a Security Operations Center (SOC) Analyst at Vandalay Industries, an import and export company. The company was dealing with multiple security incidents that were adversely impacting their online systems. As part of my role, I had to utilize Splunk within an Ubuntu Virtual Machine environment to develop an effective monitoring solution that could help protect the company against future cybersecurity attacks.

The project involved various stages including research and addition of new apps, installation of new apps, file uploading, Splunk searching, field usage, as well as creation of custom reports and alerts.

## **Stage 1: Network Speed Monitoring**

The first task involved addressing DDOS attacks that were causing significant latency to Vandaly's web servers, thereby affecting upload and download speeds. I analyzed network speed data from the time of the attack to determine its impact on the server speeds. Using Splunk, I created a custom field to calculate the ratio of upload speed to download speed and created a statistical report to display various fields including timestamp, IP address, download and upload speeds, and their ratio. This report helped in determining the approximate date and time of the attack and recovery time of the systems.

## **Stage 2: Vulnerability Assessment**

Next, I was tasked with ensuring the safety of sensitive customer data on the servers from frequent attacks. Using data from Nessus vulnerability scans, I created a report to determine the count of critical vulnerabilities on the customer data server. I then designed an alert to notify the team daily if a critical vulnerability was found on this server. This proactive approach aimed to quickly address any potential vulnerabilities and safeguard the sensitive customer data.

## **Stage 3: Baseline Monitoring for Brute Force Attacks**

Lastly, I was tasked to address the issue of brute force attacks on Vandaly's administrator account. To protect against these attacks, I analyzed the administrator login logs to create a baseline of normal activity and established a threshold to indicate a potential brute force attack. I also created an alert to check this threshold every hour, sending an email notification to the SOC team if a possible attack was detected.

Overall, this project served as a comprehensive exploration of Splunk's capabilities in a live cyber-threat environment, honing my skills in cybersecurity threat detection, analysis, and mitigation.
