# MatterPosh
PowerShell module that wraps around Mattermost Server v4 API

# Using in your projects
Simply use standard procedure of importing a powershell module!
```
Import-module ./MatterPosh/MatterPosh.psm1
```
# Functions
```Get-MMChannel``` 
Returns PS Object for a specific channel
```Get-MMTeams``` 
Searches or Gets Teams
```Find-MMChannel``` 
Searches Channels by name
```Add-MMPost``` 
Sends a post to Mattermost. this can be a channel or direct message.
```Remove-MMPost``` 
Removes a message (post) from given Channel. permission is required.