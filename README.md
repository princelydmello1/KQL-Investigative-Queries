# KQL-Investigative-Queries
This repo contains a list of KQL queries that are useful in investigating security incidents in Microsoft Defender/Sentinel.

1. **UserSigninSummaryByIp.yaml**: Summarizes all Entra logon activity for a user by IP using the SigninLogs and AADNoninteractiveUserSignInLogs tables.
2. **UserMFAAdditions.yaml**: Identifies new MFA additions for a user using the AuditLogs table. 
3. **EmailAccessByIP.yaml**: Identifies email access from an IP using the OfficeActivity table. 
4. **ProcessActionsByHash.yaml**: Identifies all available actions performed by a process with a specific file hash. 
   
