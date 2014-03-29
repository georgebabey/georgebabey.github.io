##  Publish via Powershell

1. Install [Windows Azure Powershell](http://www.windowsazure.com/en-us/documentation/articles/install-configure-powershell/) (from Web Platform Installer)
2. Configure powershell to an account by:
  ```
  Add-AzureAccount
  ```
  or
  ```
  Get-AzurePublishSettingsFile
  Import-AzurePublishSettingsFile
  ```
3. Create a new service
  ```
  New-AzureService -ServiceName "mytestcloudservice" -Location 
  "North Central US" -Label "mytestcloudservice"
  ```