# Event ID 5028: The Windows Firewall Service was unable to parse the new security policy. The service will continue with currently enforced policy.
###### Version: 0

## Description
This error indicates one of two situations, low memory resources or Windows Firewall group policy registry corruption.

## Data Dictionary
|Standard Name|Field Name|Type|Description|Sample Value|
|---|---|---|---|---|
|error_code|ErrorCode|UInt32|unique error code.|`2147942413`|

## References
* [MS Source](https://github.com/MicrosoftDocs/windows-itpro-docs/blob/public/windows/security/threat-protection/auditing/event-5028.md)
* [MS Security Auditing Category - System](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/advanced-security-audit-policy-settings#system)
* [MS Security Auditing Sub-category - Audit Other System Events](https://github.com/MicrosoftDocs/windows-itpro-docs/tree/master/windows/security/threat-protection/auditing/audit-other-system-events.md)

## Tags
* etw_level_Informational
* etw_task_task_0
* System
* Audit Other System Events