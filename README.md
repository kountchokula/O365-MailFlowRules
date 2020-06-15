# O365-Security
Mail Flow Rules in use to secure Office 365. Implement rules in the following order of priority:

1. BlockExternalForwards
2. RejectNoReply-Stage1
3. RejectNoReply-Stage2
4. AutoPurge-TLDs
5. Autopurge-Gibberish-Domains
6. Autopurge-LeadRecruiter-Domains
7. Autopurge-JunkSpam-Domains
8. Autopurge-PhishEmailPatterns
9. VIP_Spoof_Protection
10. Quarantine-Header
11. Quarantine-Content
12. Quarantine-Sender
13. Warn-HighRiskDomain
14. Warn-PhishingContent
15. Warn-SuspiciousAttachments
