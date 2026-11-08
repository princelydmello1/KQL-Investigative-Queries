# KQL-Investigative-Queries
This repo contains a list of KQL queries that can be useful in investigating security incidents in Microsoft Defender/Sentinel.

1. UserSigninsByIpOverview: gives a summarisation of all logon activity fon a user from each ip using the SigninLogs, AADNoninteractiveUserSignInLogs tables
2. InvestigateAuditlogs: can be used to investigate user actions in the AuditLogs table such as credential resets, addition of new MFA methods or azure AD device registrations
