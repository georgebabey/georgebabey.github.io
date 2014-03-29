## Publish via Powershell (cont.)

4. Save the [PublishCloudService.ps1](http://www.windowsazure.com/en-us/documentation/articles/cloud-services-dotnet-continuous-delivery/#script)

5. Run the PublishCloudService.ps1 script
```
PowerShell c:\scripts\windowsazure\PublishCloudService.ps1 
-environment Staging 
-serviceName mycloudservice
-packageLocation c:\drops\app.publish\ContactManager.Azure.cspkg 
-cloudConfigLocation c:\drops\app.publish\ServiceConfiguration.Cloud.cscfg
-subscriptionDataFile c:\scripts\default.publishsettings
```

[More Information](http://www.windowsazure.com/en-us/documentation/articles/cloud-services-dotnet-continuous-delivery/#step4)