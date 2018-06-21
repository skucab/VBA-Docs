---
title: TextEffectFormat.Creator Property (Word)
keywords: vbawd10.chm164561897
f1_keywords:
- vbawd10.chm164561897
ms.prod: word
api_name:
- Word.TextEffectFormat.Creator
ms.assetid: 08cd4c8d-0a3c-4746-d339-01d03fb277a7
ms.date: 06/08/2017
---


# TextEffectFormat.Creator Property (Word)

Returns a 32-bit integer that indicates the application in which the specified object was created. Read-only  **Long** .


## Syntax

 _expression_. 'Creator'

 _expression_ Required. A variable that represents a '[TextEffectFormat](Word.TextEffectFormat.md)' object.


## Remarks

If the object was created in Microsoft Word, the  **Creator** property returns the hexadecimal number 4D535744, which represents the string "MSWD." This property was primarily designed to be used on the Macintosh, where each application has a four-character creator code. For example, Microsoft Word has the creator code MSWD. For additional information about this property, consult the language reference Help included with Microsoft Office Macintosh Edition.


## See also


[TextEffectFormat Object](Word.TextEffectFormat.md)
