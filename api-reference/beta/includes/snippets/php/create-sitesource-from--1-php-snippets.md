---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new SiteSource();
$site = new Site();
$site->setWebUrl('https://contoso.sharepoint.com/sites/HumanResources');


$requestBody->setSite($site);


$requestResult = $graphServiceClient->compliance()->ediscovery()->casesById('case-id')->custodiansById('custodian-id')->siteSources()->post($requestBody);


```