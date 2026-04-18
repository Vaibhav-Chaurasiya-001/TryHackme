# Advent of Cyber 2024 – Day 7 Notes
## Topic: OPSEC & SOC Analysis
## 1. What is OPSEC (Operational Security)?

Operational Security (OPSEC) is the practice of protecting sensitive information from being exposed to attackers.

-> Common OPSEC Mistakes:
* Reusing usernames or email IDs
- Leaving metadata in files (documents, images)
- Sharing personal information online
- Not using a VPN (real IP gets exposed)

## 2. Real-Life OPSEC Failures

Attackers often get caught due to small mistakes:
- Same username used across multiple platforms
- Cryptocurrency linked to real identity
- Activity revealing timezone or location

## True Positive vs False Positive
    Term	                        Meaning
    True Positive (TP)	    Real attack correctly identified
    False Positive (FP)	    Normal activity flagged as attack

--> Differentiating between TP and FP is a key challenge in cybersecurity.

## 4. SOC Analyst Decision Making

SOC (Security Operations Center) analysts must carefully analyze alerts.

-> Impact of Wrong Decisions:
- Marking TP as FP → Real attack missed 
- Marking FP as TP → Time and resources wasted 

## 5. SOC “Superpower”

SOC analysts can verify suspicious activity by contacting:
- Users
- System administrators
-> Limitations:
- No proper change request system
- Insider threats
- Social engineering attacks

## 6. Practical Exercise (Hands-on)
- Used Elastic SIEM for log analysis
- Investigated alerts within a specific time range
- Analyzed suspicious PowerShell activity

## Summary
**Day 7 highlights:**

- Importance of good OPSEC practices.
- How attackers get caught due to small mistakes.
- Challenges in distinguishing real threats vs false alerts.
- Role of SIEM tools in SOC investigations.

**Answer the questions below:**   
Q-1 What is the other activity made by the user glitch aside from the ListObject action?
```
PutObject
```
Q-2 What is the source IP related to the S3 bucket activities of the user glitch?
```
53.94.201.69
```
Q-3 Based on the eventSource field, what AWS service generates the ConsoleLogin event?
```
signin.amazonaws.com
```
Q-4 When did the anomalous user trigger the ConsoleLogin event?
```
2024-11-28T15:21:54Z
```
Q-5 What was the name of the user that was created by the mcskidy user?
```
glitch
```
Q-6 What type of access was assigned to the anomalous user?
```
AdministratorAccess
```
Q-7 Which IP does Mayor Malware typically use to log into AWS?
```
53.94.201.69
```
Q-8 What is McSkidy's actual IP address?
```
31.210.15.79
```
Q-9 What is the bank account number owned by Mayor Malware?
```
2394 6912 7723 1294
```
Q-10 Want to learn more about log analysis and how to interpret logs from different sources? Check out the Log Universe room!
```
No Answer Needed
```
----