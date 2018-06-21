---
title: Tasks.Creator Property (Word)
keywords: vbawd10.chm159581161
f1_keywords:
- vbawd10.chm159581161
ms.prod: word
api_name:
- Word.Tasks.Creator
ms.assetid: 9a545b9d-09eb-4fd8-c3e3-802de2736183
ms.date: 06/08/2017
---


# Tasks.Creator Property (Word)

Returns a 32-bit integer that indicates the application in which the specified object was created. Read-only  **Long** .


## Syntax

 _expression_. 'Creator'

 _expression_ Required. A variable that represents a '[Tasks](Word.tasks.md)' collection.


## Remarks

If the object was created in Microsoft Word, the  **Creator** property returns the hexadecimal number 4D535744, which represents the string "MSWD." This property was primarily designed to be used on the Macintosh, where each application has a four-character creator code. For example, Microsoft Word has the creator code MSWD. For additional information about this property, consult the language reference Help included with Microsoft Office Macintosh Edition.


## See also


[Tasks Collection Object](Word.tasks.md)
