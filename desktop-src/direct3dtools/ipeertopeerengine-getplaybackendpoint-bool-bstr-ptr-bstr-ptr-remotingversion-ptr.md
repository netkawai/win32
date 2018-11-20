---
Description: Gets the endpoint address of a remote engine.
MS-HAID: vspixengine.IPeerToPeerEngine\_GetPlaybackEndpoint\_BOOL\_BSTR\_ptr\_BSTR\_ptr\_RemotingVersion\_ptr
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: IPeerToPeerEngine::GetPlaybackEndpoint method
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.ipeertopeerengine_getplaybackendpoint_bool_bstr_ptr_bstr_ptr_remotingversion_ptr"></span>IPeerToPeerEngine::GetPlaybackEndpoint method

Gets the endpoint address of a remote engine.

## Syntax


```C++
);
```

## Parameters

*bUseAuthentication*   
true if the remote engine uses authentication; otherwise, false.

*pEndpoint*   
On return, a COM string containing the endpoint address of the remote playback machine.

*sessionKey*   
On return, a COM string containing the session key used for encryption.

*pRemoteVersion*   
On return, the version of the remote engine.

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Header</p></td><td>Vspixengine.h</td></tr></tbody></table>

## <span id="see_also"></span>See also

[**IPeerToPeerEngine**](https://msdn.microsoft.com/library/windows/desktop/mt432712)

 

 


