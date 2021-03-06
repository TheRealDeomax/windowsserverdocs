---
title: bitsadmin resume
description: "Windows Commands topic for **bitsadmin resume** - Activates a new or suspended job in the transfer queue."
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 7c7540a9-a11a-4910-923a-2a2a61cbf11d
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# bitsadmin resume

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Activates a new or suspended job in the transfer queue.
## Syntax
```
bitsadmin /Resume <Job>
```
## Parameters
|Parameter|Description|
|-------|--------|
|Job|The job's display name or GUID|
## <a name="BKMK_examples"></a>Examples
The following example resumes the job named *myDownloadJob*.
```
C:\>bitsadmin /Resume myDownloadJob
```
additional references
[Command-Line Syntax Key](command-line-syntax-key.md)
