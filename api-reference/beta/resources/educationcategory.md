---
title: "educationCategory resource type"
description: "A category that can be applied to assignments."
author: "mmast-msft"
localization_priority: Normal
ms.prod: "education"
---

# educationCategory resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

A category that can be applied to assignments.


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get educationCategory](../api/educationcategory-get.md) | [educationCategory](educationCategory.md) | Get an existing **educationCategory**.|
|[Delete category](../api/educationcategory-delete.md) | None | Remove an **educationCategory**.|


## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String|Unique identifier for the category.|
|displayName|String|Unique identifier for the category.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationCategory"
}-->

```json
{
  "id": "String (timestamp)",
  "displayName": "String (timestamp)",
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "educationCategory resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->
