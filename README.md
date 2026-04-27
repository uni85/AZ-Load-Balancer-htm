## Load Balancer Verification
To verify that the Azure Load Balancer was correctly distributing traffic, I accessed the Public IP address from two different sessions. 

### Traffic routed to VM1:
![VM1 Confirmation](images/image_d5db57.png)

### Traffic routed to VM2:
![VM2 Confirmation](images/image_d5db55.png)

### Troubleshooting: PowerShell Typo
During the setup, I encountered a `CommandNotFoundException` because of a space in the `Install-WindowsFeature` cmdlet. I resolved this by using the correct hyphenated syntax.
![PowerShell Error](images/image_d6cbb5.png)
