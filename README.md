# O365-Security
Mail Flow Rules in use to secure Office 365. Many of these are adapted from SwiftOnSecurity Office365 management rules.

Implement rules in the following order of priority:

1. BlockExternalForwards
2. RejectNoReply-Stage1
3. RejectNoReply-Stage2
4. AutoPurge-TLDs
5. Autopurge-Gibberish-Domains
6. Autopurge-LeadRecruiter-Domains
7. Autopurge-JunkSpam-Domains
8. Autopurge-PhishEmailPatterns
9. Autopurge-People
10. VIP_Spoof_Protection
11. Quarantine-Header
12. Quarantine-Content
13. Quarantine-Sender
14. Warn-HighRiskDomain
15. Warn-PhishingContent
16. Warn-SuspiciousAttachments
