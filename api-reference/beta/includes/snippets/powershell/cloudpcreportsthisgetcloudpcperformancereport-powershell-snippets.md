---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Beta.DeviceManagement.Actions

$params = @{
	reportName = "performanceTrendReport"
	filter = "EventDateTime gt datetime'2023-10-13T00:00:00.000Z'"
	select = @(
	"EventDateTime"
"SlowRoundTripTimeCloudPcCount"
"LowUdpConnectionPercentageCount"
"NoActiveTimeConnectedCount"
"LowActiveTimeConnectedCount"
)
search = ""
skip = 0
top = 50
}

Get-MgBetaDeviceManagementVirtualEndpointReportCloudPcPerformanceReport -BodyParameter $params

```