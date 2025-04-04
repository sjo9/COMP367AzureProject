# COMP367AzureProject

2025-04-04T23:34:05.5964377Z ##[section]Starting: IIS Web App Manage
2025-04-04T23:34:05.6019304Z ==============================================================================
2025-04-04T23:34:05.6019887Z Task         : IIS web app manage
2025-04-04T23:34:05.6020143Z Description  : Create or update websites, web apps, virtual directories, or application pools
2025-04-04T23:34:05.6020725Z Version      : 0.241.1
2025-04-04T23:34:05.6020957Z Author       : Microsoft Corporation
2025-04-04T23:34:05.6024482Z Help         : https://docs.microsoft.com/azure/devops/pipelines/tasks/deploy/iis-web-app-management-on-machine-group
2025-04-04T23:34:05.6025097Z ==============================================================================
2025-04-04T23:34:15.4043576Z ##[error]Cannot find appcmd.exe location. Verify IIS is configured on DESLAB-006 and try operation again.
2025-04-04T23:34:15.4793639Z ##[section]Finishing: IIS Web App Manage

Enable-WindowsOptionalFeature -Online -FeatureName IIS-WebServerRole -All
