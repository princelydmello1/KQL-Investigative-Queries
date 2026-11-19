# KQL-Investigative-Queries
A curated collection of reusable Kusto Query Language (KQL) queries designed to accelerate security incident investigations across Microsoft Defender XDR and Microsoft Sentinel.

1. **UserSigninSummaryByIp.yaml**: Summarizes interactive and non-interactive Microsoft Entra ID sign-in activity for a specific user, grouped by IP address (SigninLogs, AADNoninteractiveUserSignInLogs).
2. **UserMFAAdditions.yaml**: Identifies newly registered multi-factor authentication (MFA) methods for a target user (AuditLogs).
3. **EmailAccessByIP.yaml**: Identifies emails accessed, their associated URLs, and attachments from an IP of interest (OfficeActivity).
4. **ProcessActionsByHash.yaml**: Identifies all recorded actions performed by a process with a specific file hash (DeviceProcessEvents, DeviceNetworkEvents, DeviceFileEvents, DeviceRegistryEvents, DeviceImageLoadEvents, DeviceEvents).
