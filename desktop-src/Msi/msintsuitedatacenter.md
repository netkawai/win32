---
Description: On Windows 2000 and later operating systems, the installer sets the MsiNTSuiteDataCenter property to 1 if Windows 2000 Datacenter Server is installed.
ms.assetid: a777e62a-a360-4d8c-b7a6-00d45c17db66
title: MsiNTSuiteDataCenter property
ms.topic: reference
ms.date: 05/31/2018
---

# MsiNTSuiteDataCenter property

On Windows 2000 and later operating systems, the installer sets the **MsiNTSuiteDataCenter** property to 1 if Windows 2000 Datacenter Server is installed. The installer sets this property to 1 only if the VER\_SUITE\_DATACENTER flag is set in the [**OSVERSIONINFOEX**](/windows/win32/api/winnt/ns-winnt-osversioninfoexa) structure. Otherwise, the installer does not set this property.

## Requirements



|                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Version<br/> | Windows Installer 5.0 on Windows Server 2012, Windows 8, Windows Server 2008 R2 or Windows 7. Windows Installer 4.0 or Windows Installer 4.5 on Windows Server 2008 or Windows Vista. Windows Installer on Windows Server 2003 or Windows XP. See the [Windows Installer Run-Time Requirements](windows-installer-portal.md) for information about the minimum Windows service pack that is required by a Windows Installer version.<br/> |



## See also

<dl> <dt>

[Properties](properties.md)
</dt> </dl>

 

 