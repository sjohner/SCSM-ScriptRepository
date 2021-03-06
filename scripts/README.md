# System Center Service Manager scripts
Multiple PowerShell Scripts to be used with System Center Service Manager. Most of them make use of the SCSM PowerShell Cmdlets available on [Codeplex](https://smlets.codeplex.com/).

## Available scripts in this repository
### Check-SCSMNotificationTemplateUsage.ps1
Checks for a given notification template if it is used in any notification subscription.

### Delete-PendingActivities
Deletes all pending activities. Be careful!

### Get-SCSMReviewActivities.ps1
Recursively gets all Review Activities which are related to a given WorkItem.

### Get-SCSMReviewers.ps1
Gets all Reviewers (Users) for a given Review Activity. 

### Install-SCSM2016
Installs prerequisites and Service Manager Management server

### Update-SCSMEnumList.ps1
Updates Service Manager enum lists based on results of a given MySQL query.
