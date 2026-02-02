# Phishing Detection & SOC Alert Triage

This project documents hands-on phishing detection and alert triage performed in a simulated Security Operations Center (SOC) environment. The focus is on identifying true positive phishing alerts, validating indicators of compromise (IOCs), and distinguishing legitimate business communications from malicious activity using SIEM data, email analysis, and firewall logs.

## Objective

Investigate inbound email alerts, classify them accurately, and apply SOC-style decision-making to support mitigation and escalation actions.
<img width="1197" height="420" alt="image" src="https://github.com/user-attachments/assets/b4a9ba8d-760f-4262-8d8b-b8a73b26d1d0" />

## Tools & Technologies

* SIEM Platform, Email Security Logs and Firewall / Proxy Logs
* URL Reputation & Threat Intelligence and SOC Alert Dashboard

## Scope of Work

* Investigated inbound email alerts flagged for suspicious external links
* Analyzed email headers, sender domains, URLs, and message content
* Correlated email alerts with firewall and proxy logs
* Classified alerts as **True Positive (TP)** or **False Positive (FP)**

## Alert Investigation Summary

| Alert ID | Description                      | Evidence / Indicators                                                                                 | Classification | Action / Outcome                                      |
| -------- | -------------------------------- | ----------------------------------------------------------------------------------------------------- | -------------- | ----------------------------------------------------- |
| 8814     | Inbound Email with External Link | Internal HR confirmation via SIEM logs                                                                | False Positive | Alert closed without escalation                       |
| 8815     | Suspicious Amazon-Themed Email   | Look-alike sender domain (amazon.biz), Obfuscated short URL (bit.ly), User attempted access (blocked) | True Positive  | User awareness recommendation; no escalation required |
| 8816     | Blacklisted URL Access Attempt   | Firewall alert, Previously identified malicious bit.ly link                                           | True Positive  | Connection blocked; recommended domain review         |
| 8817     | Microsoft Account Phishing Email | Look-alike domain (m1crosoftsupport.co), Urgency/fear language, Suspicious login URL                  | True Positive  | Recommended domain blocking and escalation            |
| 8818     | Duplicate HR Onboarding Email    | Same legitimate HR communication as earlier alert                                                     | False Positive | Alert closed                                          |
<img width="1189" height="459" alt="image" src="https://github.com/user-attachments/assets/25e4f8db-c26f-45fa-86e1-f1a6dc20e48b" />
<img width="1117" height="692" alt="image" src="https://github.com/user-attachments/assets/834c691e-1260-494e-b8bd-168aff0a0351" />

## Key Outcomes
<img width="889" height="587" alt="image" src="https://github.com/user-attachments/assets/07d167cc-40f2-4975-a20f-dc00641e983b" />

* Identified and closed multiple true positive phishing alerts
* Prevented successful phishing attempts through firewall correlation
* Differentiated legitimate business emails from malicious activity
* Applied SOC Level-1 workflows for alert triage and escalation
* Documented incidents using structured SOC reporting standards

## Skills Demonstrated

* Phishing detection & analysis
* SIEM log correlation
* Firewall & proxy log analysis
* Alert triage and incident classification

## Project Status

✔ Completed
✔ All alerts triaged and classified
✔ True positives successfully identified

