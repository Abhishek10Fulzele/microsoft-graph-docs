---
title: "List auditLogQueries"
description: "Get a list of the microsoft.graph.security.auditLogQuery objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://aka.ms/msgo?pagePath=Document-APIs/Guidelines/Metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://aka.ms/msgo?pagePath=Document-APIs/Guidelines/Metadata)**"
doc_type: apiPageType
---

# List auditLogQueries
Namespace: microsoft.graph.security

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /security/auditCore/auditLogQueries
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [auditLogQuery](../resources/auditlogquery.md) objects in the response body.

## Examples

### Request
The following is an example of a request.
<!-- {
  "blockType": "request",
  "name": "list_auditlogquery"
}
-->
``` http
GET https://graph.microsoft.com/beta/security/auditCore/auditLogQueries
```


### Response
The following is an example of the response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.security.auditLogQuery)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.security.auditLogQuery",
      "id": "168ec429-084b-a489-90d8-504a87846305",
      "displayName": "String",
      "filterStartDateTime": "String (timestamp)",
      "filterEndDateTime": "String (timestamp)",
      "recordTypeFilter": "String",
      "keywordFilter": "String",
      "serviceFilter": "String",
      "operationFilters": [
        "String"
      ],
      "userPrincipalNameFilters": [
        "String"
      ],
      "ipAddressFilters": [
        "String"
      ],
      "objectIdFilters": [
        "String"
      ],
      "administrativeUnitIdFilters": [
        "String"
      ],
      "status": "String"
    }
  ]
}
```

