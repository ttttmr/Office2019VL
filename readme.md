# Office 2019 VOL Install

## Config

Modify the office_vol.xml file according to your needs. 

By default, only Word, Excel and PowerPoint are installed.

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

https://docs.microsoft.com/en-us/deployoffice/office2019/deploy