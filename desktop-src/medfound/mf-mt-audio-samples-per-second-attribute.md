---
Description: Number of audio samples per second in an audio media type.
ms.assetid: f640016d-595e-4b20-8ce8-23a029c2b064
title: MF\_MT\_AUDIO\_SAMPLES\_PER\_SECOND attribute
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MF\_MT\_AUDIO\_SAMPLES\_PER\_SECOND attribute

Number of audio samples per second in an audio media type.

## Data type

**UINT32**

## Remarks

This attribute corresponds to the **nSamplesPerSec** member of the [**WAVEFORMATEX**](https://msdn.microsoft.com/4f3bf6fb-b15f-43b3-82f1-e7a8a3007057) structure.

The GUID constant for this attribute is exported from mfuuid.lib.

## Requirements



|                                     |                                                                                    |
|-------------------------------------|------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps \| UWP apps\]<br/>                              |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps \| UWP apps\]<br/>                        |
| Header<br/>                   | <dl> <dt>Mfapi.h</dt> </dl> |



## See also

<dl> <dt>

[Alphabetical List of Media Foundation Attributes](alphabetical-list-of-media-foundation-attributes.md)
</dt> <dt>

[**IMFAttributes::GetUINT32**](/windows/desktop/api/mfobjects/nf-mfobjects-imfattributes-getuint32)
</dt> <dt>

[**IMFAttributes::SetUINT32**](/windows/desktop/api/mfobjects/nf-mfobjects-imfattributes-setuint32)
</dt> <dt>

[**IMFMediaType**](/windows/desktop/api/mfobjects/nn-mfobjects-imfmediatype)
</dt> <dt>

[Media Type Attributes](media-type-attributes.md)
</dt> <dt>

[**MF\_MT\_AUDIO\_FLOAT\_SAMPLES\_PER\_SECOND**](mf-mt-audio-float-samples-per-second-attribute.md)
</dt> </dl>

 

 



