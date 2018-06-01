---
Description: The EventLogging property retrieves the FaxEventLogging configuration object.
ms.assetid: 9b6faf28-b2da-4c67-ade0-63f2dcf0680b
title: FaxLoggingOptions.EventLogging property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxLoggingOptions.EventLogging property

The **EventLogging** property retrieves the [**FaxEventLogging**](-mfax-faxeventlogging.md) configuration object.

This property is read-only.

## Syntax


```VB
Property EventLogging As IFaxEventLogging
```



## Property value

A variable of type [**IFaxEventLogging**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxeventlogging) that receives a [**FaxEventLogging**](-mfax-faxeventlogging.md) object.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                             |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>FaxComex.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Fxscomex.dll</dt> </dl> |



## See also

<dl> <dt>

[Visual Basic Example](-mfax-setting-logging-options.md)
</dt> <dt>

[**FaxLoggingOptions**](-mfax-faxloggingoptions.md)
</dt> <dt>

[**IFaxLoggingOptions**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxloggingoptions)
</dt> </dl>

 

 



