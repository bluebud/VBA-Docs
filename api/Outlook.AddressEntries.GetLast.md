---
title: AddressEntries.GetLast method (Outlook)
keywords: vbaol11.chm34
f1_keywords:
- vbaol11.chm34
ms.prod: outlook
api_name:
- Outlook.AddressEntries.GetLast
ms.assetid: 22b54c0f-5167-ac76-0cff-7ee4a142e1b3
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# AddressEntries.GetLast method (Outlook)

Returns the last object in the  **[AddressEntries](Outlook.AddressEntries.md)** collection.


## Syntax

_expression_. `GetLast`

_expression_ A variable that represents an [AddressEntries](Outlook.AddressEntries.md) object.


## Return value

An **[AddressEntry](Outlook.AddressEntry.md)** object that represents the last object contained by the collection.


## Remarks

It returns  **Nothing** if no last object exists, for example, if the collection is empty. To ensure correct operation of the **[GetFirst](Outlook.AddressEntries.GetFirst.md)**, **GetLast**, **[GetNext](Outlook.AddressEntries.GetNext.md)**, and **[GetPrevious](Outlook.AddressEntries.GetPrevious.md)** methods in a large collection, call **GetFirst** before calling **GetNext** on that collection, and call **GetLast** before calling **GetPrevious**. To ensure that you are always making the calls on the same collection, create an explicit variable that refers to that collection before entering the loop.


## See also


[AddressEntries Object](Outlook.AddressEntries.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]