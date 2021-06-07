# Enterprise G conversion processing/mass activation deployment program for Win10 1703+
https://03k.org/1803entg.html  
This program converts the 1703+ Windows 10 system to Enterprise G by importing the certificate, and the conversion is also reversible. For example, it was originally the enterprise version. If you want to use the enterprise version back, you can directly import the key of the enterprise version. Enterprise G has two One advantage is the 400-year kms grace period and the inability to upgrade the version. It is also convenient for students who do not want to update Windows and can also be converted back at any time.  

## [Convert program download](https://github.com/lixuy/EnterpriseGconvert/releases/download/1/EnterpriseGconvert.cmd).
#### Note: This program only performs conversion operations, please handle system activation by yourself.
After downloading, right-click the administrator to run it.

## [Convert program one-click automatic activation version download](https://github.com/lixuy/EnterpriseGconvert/releases/download/1/EnterpriseGconvert_auto.cmd).
#### Note: This program is for deployment reference only, please modify the kmsserver parameter to your own server address.

## Example of reverse convert back to Enterprise Edition:
>slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43  
Other version reference https://docs.microsoft.com/zh-cn/windows-server/get-started/kmsclientkeys  

## System version tested 
#### The following is the version that passed the test
>Windows 10 Home/Professional/Education/Enterprise 1703  
Windows 10 Home/Professional/Education/Enterprise 1709  
Windows 10 Home/Professional/Education/Enterprise 1803  
Windows 10 Home/Professional/Education/Enterprise 1809  
Windows 10 LTSC 2019  
#### The following is the version that failed the test
>Windows 10 Home/Professional/Education/Enterprise 1511  
Windows 10 Home/Professional/Education/Enterprise 1607  
Windows 10 LTSB 2015  
Windows 10 LTSB 2016
