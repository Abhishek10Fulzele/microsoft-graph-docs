---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new AuthenticationMethodsPolicy();
$registrationEnforcement = new RegistrationEnforcement();
$registrationEnforcementAuthenticationMethodsRegistrationCampaign = new AuthenticationMethodsRegistrationCampaign();
$registrationEnforcementAuthenticationMethodsRegistrationCampaign->setSnoozeDurationInDays(snoozeDurationInDays);

$registrationEnforcementAuthenticationMethodsRegistrationCampaign->setState(new AdvancedConfigState('enabled'));

$registrationEnforcementAuthenticationMethodsRegistrationCampaign->setExcludeTargets(]);

$includeTargetsAuthenticationMethodsRegistrationCampaignIncludeTarget1 = new AuthenticationMethodsRegistrationCampaignIncludeTarget();
$additionalData = [
'id' => '3ee3a9de-0a86-4e12-a287-9769accf1ba2', 
'targetType' => 'group', 
'targetedAuthenticationMethod' => 'microsoftAuthenticator', 
];
$includeTargetsAuthenticationMethodsRegistrationCampaignIncludeTarget1->setAdditionalData($additionalData);



$includeTargetsArray []= $includeTargetsAuthenticationMethodsRegistrationCampaignIncludeTarget1;
$registrationEnforcementAuthenticationMethodsRegistrationCampaign->setIncludeTargets($includeTargetsArray);



$registrationEnforcement->setAuthenticationMethodsRegistrationCampaign($registrationEnforcementAuthenticationMethodsRegistrationCampaign);

$requestBody->setRegistrationEnforcement($registrationEnforcement);


$graphServiceClient->policies()->authenticationMethodsPolicy()->patch($requestBody);


```