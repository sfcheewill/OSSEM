# DeviceInfo
###### Version: 0

## Description
Machine information, including OS information

## Data Dictionary
|Standard Name|Field Name|Type|Description|Sample Value|
|---|---|---|---|---|
|event_date_creation|Timestamp|date|Date and time when the event was recorded|``|
|machine_id|DeviceId|string|Unique identifier for the machine in the service|``|
|computer_name|DeviceName|string|Fully qualified domain name (FQDN) of the machine|``|
|client_version|ClientVersion||Version of the endpoint agent or sensor running on the device|``|
|public_ip|PublicIP|string|Public IP address used by the onboarded device to connect to the Microsoft Defender ATP service. This could be the IP address of the device itself, a NAT device, or a proxy|``|
|os_architecture|OSArchitecture|string|Architecture of the operating system running on the machine|``|
|os_platform|OSPlatform|string|Platform of the operating system running on the machine. This indicates specific operating systems, including variations within the same family, such as Windows 10 and Windows 7.|``|
|os_build|OSBuild|string|Build version of the operating system running on the machine|``|
|is_azure_ad_joined|ISAzureADJoined|boolean|Boolean indicator of whether machine is joined to the Azure Active Directory|``|
|logged_on_users|LoggedOnUsers|string|List of all users that are logged on the machine at the time of the event in JSON array format|``|
|registry_device_tag|RegistryDeviceTag|string|Device tag added through the registry|``|
|report_id|ReportId|long|Event identifier based on a repeating counter. To identify unique events, this column must be used in conjunction with the ComputerName and EventTime columns.|``|
|os_version|OSVersion||Version of the operating system running on the device|``|
|machine_group|MachineGroup|string|Machine group of the machine. This group is used by role-based access control to determine access to the machine|``|
