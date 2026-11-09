# KQL-Investigative-Queries
This repo contains a list of KQL queries that are useful in investigating security incidents in Microsoft Defender/Sentinel.

1. UserSigninsByIpOverview.yaml: gives a summarisation of all logon activity for a user from each IP using the SigninLogs and AADNoninteractiveUserSignInLogs tables
2. InvestigateAuditlogs.yaml: can be used to investigate user actions in the AuditLogs table, such as credential resets, addition of new MFA methods, or Azure AD device registrations
