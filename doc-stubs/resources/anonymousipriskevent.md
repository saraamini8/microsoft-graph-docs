---
title: "anonymousIpRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# anonymousIpRiskEvent resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [locatedRiskEvent](../resources/locatedriskevent.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List anonymousIpRiskEvents](../api/anonymousipriskevent-list.md)|[anonymousIpRiskEvent](../resources/anonymousipriskevent.md) collection|Get a list of the [anonymousIpRiskEvent](../resources/anonymousipriskevent.md) objects and their properties.|
|[Create anonymousIpRiskEvent](../api/anonymousipriskevent-post-anonymousipriskevents.md)|[anonymousIpRiskEvent](../resources/anonymousipriskevent.md)|Create a new [anonymousIpRiskEvent](../resources/anonymousipriskevent.md) object.|
|[Get anonymousIpRiskEvent](../api/anonymousipriskevent-get.md)|[anonymousIpRiskEvent](../resources/anonymousipriskevent.md)|Read the properties and relationships of an [anonymousIpRiskEvent](../resources/anonymousipriskevent.md) object.|
|[Update anonymousIpRiskEvent](../api/anonymousipriskevent-update.md)|[anonymousIpRiskEvent](../resources/anonymousipriskevent.md)|Update the properties of an [anonymousIpRiskEvent](../resources/anonymousipriskevent.md) object.|
|[Delete anonymousIpRiskEvent](../api/anonymousipriskevent-delete.md)|None|Deletes an [anonymousIpRiskEvent](../resources/anonymousipriskevent.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|id|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|ipAddress|String|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md).|
|location|[signInLocation](../resources/signinlocation.md)|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md).|
|riskEventDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|riskEventStatus|riskEventStatus|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `active`, `remediated`, `dismissedAsFixed`, `dismissedAsFalsePositive`, `dismissedAsIgnore`, `loginBlocked`, `closedMfaAuto`, `closedMultipleReasons`.|
|riskEventType|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|riskLevel|riskLevel|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|userDisplayName|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|userId|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|
|userPrincipalName|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.anonymousIpRiskEvent",
  "baseType": "Microsoft.IdentityProtectionServices.locatedRiskEvent",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.anonymousIpRiskEvent",
  "id": "String (identifier)",
  "userDisplayName": "String",
  "userPrincipalName": "String",
  "riskEventDateTime": "String (timestamp)",
  "riskEventType": "String",
  "riskLevel": "String",
  "riskEventStatus": "String",
  "closedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "userId": "String",
  "location": {
    "@odata.type": "microsoft.graph.signInLocation"
  },
  "ipAddress": "String"
}
```
