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

2025-04-04T23:42:08.7324033Z ##[section]Starting: IIS Web App Deploy
2025-04-04T23:42:08.7361614Z ==============================================================================
2025-04-04T23:42:08.7362189Z Task         : IIS web app deploy
2025-04-04T23:42:08.7362453Z Description  : Deploy a website or web application using Web Deploy
2025-04-04T23:42:08.7362968Z Version      : 0.246.1
2025-04-04T23:42:08.7363242Z Author       : Microsoft Corporation
2025-04-04T23:42:08.7363536Z Help         : https://docs.microsoft.com/azure/devops/pipelines/tasks/deploy/iis-web-app-deployment-on-machine-group
2025-04-04T23:42:08.7364151Z ==============================================================================
2025-04-04T23:42:09.8966718Z ##[error]Error: No package found with specified pattern.<br/>Check if the package mentioned in the task is published as an artifact in the build or a previous stage and downloaded in the current job.
2025-04-04T23:42:09.9130385Z ##[section]Finishing: IIS Web App Deploy

2025-04-04T23:50:09.6339445Z ##[section]Starting: IIS Web App Deploy
2025-04-04T23:50:09.6386268Z ==============================================================================
2025-04-04T23:50:09.6386815Z Task         : IIS web app deploy
2025-04-04T23:50:09.6387066Z Description  : Deploy a website or web application using Web Deploy
2025-04-04T23:50:09.6387646Z Version      : 0.246.1
2025-04-04T23:50:09.6387921Z Author       : Microsoft Corporation
2025-04-04T23:50:09.6388183Z Help         : https://docs.microsoft.com/azure/devops/pipelines/tasks/deploy/iis-web-app-deployment-on-machine-group
2025-04-04T23:50:09.6388735Z ==============================================================================
2025-04-04T23:50:10.8855913Z ##[error]Error: No package found with specified pattern.<br/>Check if the package mentioned in the task is published as an artifact in the build or a previous stage and downloaded in the current job.
2025-04-04T23:50:10.8879283Z ##[section]Finishing: IIS Web App Deploy
