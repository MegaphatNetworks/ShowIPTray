# SHOW IP TRAY
A PowerShell script for Microsoft Windows that will display an IP address in the system notifications (Toast) as well as add an icon in the system tray displaying the last Octet of your IPv4 address.  This is especially useful when in a corporate environment and you are roaming from computer to computer and need to provide your IT group the last Octet of the computer you are using in order for them to provide you with support.

The System Tray icon will be a simple Yellow font with 3 numbers representing your D octet.

In order to properly run this code you should use the following snippet:  
`powershell.exe -WindowStyle Hidden -NoExit -File .\ShowTrayIP.ps1`

The reason is because once PowerShell closes, the Icon has no process to attach itself to, therefore if you hover over the icon it will disappear.  The above snippet allows PowerShell to run in the background without a window or task bar icon to confuse the user.

### Common Questions  
- Q: Are you making money at this?  
- A: No but I would appreciate any donations for all of my time and effort.
---
- Q: Do you have a website?  
- A: You can check out [my personal site](http://www.megaphat.info)
---
- Q: Can I contact you with any questions or for a custom script?  
- A: Sure, just go to [my personal site](http://www.megaphat.info) to reach out to me.
---
