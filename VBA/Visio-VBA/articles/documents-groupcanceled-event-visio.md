---
title: Documents.GroupCanceled Event (Visio)
keywords: vis_sdr.chm10662005
f1_keywords:
- vis_sdr.chm10662005
ms.prod: visio
api_name:
- Visio.Documents.GroupCanceled
ms.assetid: c48b1467-1e99-524c-c62e-0505de982888
ms.date: 06/08/2017
---


# Documents.GroupCanceled Event (Visio)

Occurs after an event handler has returned  **True** (cancel) to a **QueryCancelGroup** event.


## Syntax

Private Sub  _expression_ _**GroupCanceled**( **_ByVal Selection As [IVSELECTION]_** )

 _expression_ A variable that represents a **Documents** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Selection_|Required| **[IVSELECTION]**|The selection of shapes that was going to be grouped.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


