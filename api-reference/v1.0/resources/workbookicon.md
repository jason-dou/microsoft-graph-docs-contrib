---
title: "workbookIcon resource type"
description: "Represents a cell icon."
ms.localizationpriority: medium
doc_type: resourcePageType
ms.subservice: "excel"
author: "ruoyingl"
toc.title: Icon
ms.date: 07/30/2024
---

# workbookIcon resource type

Namespace: microsoft.graph

Represents an icon in a cell in an Excel workbook.


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get](../api/icon-get.md) | [workbookIcon](workbookicon.md) |Read the properties and relationships of a workbookIcon object.|
|[Update](../api/icon-update.md) | [workbookIcon](workbookicon.md)	|Update a workbookIcon object. |

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|index|int|The index of the icon in the given set.|
|set|string|The set that the icon is part of. The possible values are: `Invalid`, `ThreeArrows`, `ThreeArrowsGray`, `ThreeFlags`, `ThreeTrafficLights1`, `ThreeTrafficLights2`, `ThreeSigns`, `ThreeSymbols`, `ThreeSymbols2`, `FourArrows`, `FourArrowsGray`, `FourRedToBlack`, `FourRating`, `FourTrafficLights`, `FiveArrows`, `FiveArrowsGray`, `FiveRating`, `FiveQuarters`, `ThreeStars`, `ThreeTriangles`, `FiveBoxes`.|

## Relationships
None.


## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.workbookIcon"
}-->

```json
{
  "index": "int",
  "set": "string"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Icon resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->

