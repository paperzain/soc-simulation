# Phishing Detection & SOC Alert Triage


<img width="1873" height="708" alt="image" src="https://github.com/user-attachments/assets/301bd885-5da4-4643-8da3-a3067552d536" />
This project documents hands-on phishing detection and alert triage performed in a simulated Security Operations Center (SOC) environment. The focus is on identifying true positive phishing alerts, validating indicators of compromise (IOCs), and distinguishing legitimate business communications from malicious activity using SIEM data, email analysis, and firewall logs.

## Objective
Investigate inbound email alerts, classify them accurately, and apply SOC-style decision-making to support mitigation and escalation actions.
<img width="1512" height="766" alt="image" src="https://github.com/user-attachments/assets/4006c145-99c2-4513-9cdf-34f389960ca8" />

## Tools & Technologies



* SIEM Platform, Email Security Logs and Firewall / Proxy Logs
* URL Reputation & Threat Intelligence and SOC Alert Dashboard

## Scope of Work
<img width="1521" height="798" alt="image" src="https://github.com/user-attachments/assets/00335b82-1f3c-4598-aff8-8be86999bb39" />
<img width="1380" height="714" alt="image" src="https://github.com/user-attachments/assets/82e155a8-afb1-441d-9a4d-c4fdf5cd6059" />



## Alert Investigation Summary

| Alert ID | Description                      | Evidence / Indicators                                                                                 | Classification | Action / Outcome                                      |
| -------- | -------------------------------- | ----------------------------------------------------------------------------------------------------- | -------------- | ----------------------------------------------------- |
| 8814     | Inbound Email with External Link | Internal HR confirmation via SIEM logs                                                                | False Positive | Alert closed without escalation                       |
| 8815     | Suspicious Amazon-Themed Email   | Look-alike sender domain (amazon.biz), Obfuscated short URL (bit.ly), User attempted access (blocked) | True Positive  | User awareness recommendation; no escalation required |
| 8816     | Blacklisted URL Access Attempt   | Firewall alert, Previously identified malicious bit.ly link                                           | True Positive  | Connection blocked; recommended domain review         |
| 8817     | Microsoft Account Phishing Email | Look-alike domain (m1crosoftsupport.co), Urgency/fear language, Suspicious login URL                  | True Positive  | Recommended domain blocking and escalation            |
| 8818     | Duplicate HR Onboarding Email    | Same legitimate HR communication as earlier alert                                                     | False Positive | Alert closed                                          |


## Key Outcomes

* Identified and closed multiple true positive phishing alerts
* Prevented successful phishing attempts through firewall correlation
* Differentiated legitimate business emails from malicious activity
* Applied SOC Level-1 workflows for alert triage and escalation
* Documented incidents using structured SOC reporting standards
<img width="1561" height="673" alt="image" src="https://github.com/user-attachments/assets/7636a9c0-b7c4-482b-aa03-cab6712011d0" />

## Skills Demonstrated

* Phishing detection & analysis
* SIEM log correlation
* Firewall & proxy log analysis
* Alert triage and incident classification
<img width="1283" height="867" alt="image" src="https://github.com/user-attachments/assets/9af09803-5d7b-4e7f-946b-231e5d238c59" />

## Project Status

✔ Completed
✔ All alerts triaged and classified
✔ True positives successfully identified

