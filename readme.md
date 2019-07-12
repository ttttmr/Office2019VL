# Office 2019 VOL Install

## Config

Modify the office_vol.xml file according to your needs.

Support for installing Access, Excel, Groove, Lync, OneDrive, OneNote, Outlook, PowerPoint, Publisher, Teams, Word, Visio

By default, Word, Excel, and PowerPoint are installed in Chinese.

## Download & Install

```
setup.exe /download office-vol.xml
setup.exe /configure office-vol.xml
```

## KMS Activtion

**open cmd as admin**

```
cd /d "%ProgramFiles%\Microsoft Office\Office16"
cscript ospp.vbs /sethst:KMS_SERVER
cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP
cscript ospp.vbs /act
```

## More

Source of `setup.exe` : https://www.microsoft.com/en-us/download/details.aspx?id=49117

Deploy docs : https://docs.microsoft.com/en-us/deployoffice/office2019/deploy