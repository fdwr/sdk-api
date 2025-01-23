---
UID: NF:windns.DnsIsZtEnabled
tech.root: DNS
title: DnsIsZtEnabled
ms.date: 01/22/2025
targetos: Windows
description: Gets a value that specifies whether Zero Trust DNS (ZTDNS) is enabled on the current device.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: windns.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - windns.h
api_name:
 - DnsIsZtEnabled
f1_keywords:
 - DnsIsZtEnabled
 - windns/DnsIsZtEnabled
dev_langs:
 - c++
helpviewer_keywords:
 - DnsIsZtEnabled
---

## -description

Gets a value that specifies whether Zero Trust DNS (ZTDNS) is enabled on the current device.

## -returns

True if ZTDNS is enabled; otherwise, false.

## -remarks

Because there is no import library for this function, you must use [GetProcAddress](/windows/desktop/api/libloaderapi/nf-libloaderapi-getprocaddress).

## -see-also

