# Add-ReceiveConnectorIpAddress
Add remote IP address ranges to an Exchange Server 2013/2016 receive connctor.

## Description
Add IP address(es) to an existing receive connector on selected or all Exchange 2013 Servers

## Parameters
### ConnectorName  
Name of the connector the new IP addresses should be added to  

### FileName
Name of the input file name containing IP addresses

### ViewEntireForest
View entire Active Directory forest (default FALSE)

## Examples
Add IP addresses from ip.txt to MYCONNECTOR
```
.\Add-ReceiveConnectorIpAddress.ps1 -ConnectorName MYCONNECTOR -FileName D:\Scripts\ip.txt
```

```
.\Add-ReceiveConnectorIpAddress.ps1 -ConnectorName REMOTECONNECTOR -FileName .\ip-new.txt -ViewEntireForest $true
```
## Note
THIS CODE IS MADE AVAILABLE AS IS, WITHOUT WARRANTY OF ANY KIND. THE ENTIRE  
RISK OF THE USE OR THE RESULTS FROM THE USE OF THIS CODE REMAINS WITH THE USER.

## TechNet Gallery
Find the script at TechNet Gallery
* https://gallery.technet.microsoft.com/Add-remote-IP-address-59b84634

## Credits
Written by: Thomas Stensitzki

Stay connected:

* My Blog: http://justcantgetenough.granikos.eu
* Twitter: https://twitter.com/stensitzki
* LinkedIn:	http://de.linkedin.com/in/thomasstensitzki
* Github: https://github.com/Apoc70

For more Office 365, Cloud Security and Exchange Server stuff checkout services provided by Granikos

* Blog: http://blog.granikos.eu/
* Website: https://www.granikos.eu/en/
* Twitter: https://twitter.com/granikos_de
