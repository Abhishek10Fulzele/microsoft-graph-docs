---
title: "auditLogQuery resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://aka.ms/msgo?pagePath=Document-APIs/Guidelines/Metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://aka.ms/msgo?pagePath=Document-APIs/Guidelines/Metadata)**"
doc_type: resourcePageType
---

# auditLogQuery resource type

Namespace: microsoft.graph.security

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [microsoft.graph.entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List auditLogQueries](../api/security-auditcoreroot-list-auditlogqueries.md)|[microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) collection|Get a list of the [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) objects and their properties.|
|[Create auditLogQuery](../api/security-auditcoreroot-post-auditlogqueries.md)|[microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md)|Create a new [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) object.|
|[Get auditLogQuery](../api/security-auditlogquery-get.md)|[microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md)|Read the properties and relationships of a [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) object.|
|[Update auditLogQuery](../api/security-auditlogquery-update.md)|[microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md)|Update the properties of a [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) object.|
|[Delete auditLogQuery](../api/security-auditcoreroot-delete-auditlogqueries.md)|None|Delete a [microsoft.graph.security.auditLogQuery](../resources/security-auditlogquery.md) object.|
|[List records](../api/security-auditlogquery-list-records.md)|[microsoft.graph.security.auditLogRecord](../resources/security-auditlogrecord.md) collection|Get the auditLogRecord resources from the records navigation property.|
|[Create auditLogRecord](../api/security-auditlogquery-post-records.md)|[microsoft.graph.security.auditLogRecord](../resources/security-auditlogrecord.md)|Create a new auditLogRecord object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|administrativeUnitIdFilters|String collection|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|filterEndDateTime|DateTimeOffset|**TODO: Add Description**|
|filterStartDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [microsoft.graph.entity](../resources/entity.md).|
|ipAddressFilters|String collection|**TODO: Add Description**|
|keywordFilter|String|**TODO: Add Description**|
|objectIdFilters|String collection|**TODO: Add Description**|
|operationFilters|String collection|**TODO: Add Description**|
|recordTypeFilter|microsoft.graph.security.auditLogRecordType|**TODO: Add Description**.The possible values are: `exchangeAdmin`, `exchangeItem`, `exchangeItemGroup`, `sharePoint`, `syntheticProbe`, `sharePointFileOperation`, `oneDrive`, `azureActiveDirectory`, `azureActiveDirectoryAccountLogon`, `dataCenterSecurityCmdlet`, `complianceDLPSharePoint`, `sway`, `complianceDLPExchange`, `sharePointSharingOperation`, `azureActiveDirectoryStsLogon`, `skypeForBusinessPSTNUsage`, `skypeForBusinessUsersBlocked`, `securityComplianceCenterEOPCmdlet`, `exchangeAggregatedOperation`, `powerBIAudit`, `crm`, `yammer`, `skypeForBusinessCmdlets`, `discovery`, `microsoftTeams`, `threatIntelligence`, `mailSubmission`, `microsoftFlow`, `aeD`, `microsoftStream`, `complianceDLPSharePointClassification`, `threatFinder`, `project`, `sharePointListOperation`, `sharePointCommentOperation`, `dataGovernance`, `kaizala`, `securityComplianceAlerts`, `threatIntelligenceUrl`, `securityComplianceInsights`, `mipLabel`, `workplaceAnalytics`, `powerAppsApp`, `powerAppsPlan`, `threatIntelligenceAtpContent`, `labelContentExplorer`, `teamsHealthcare`, `exchangeItemAggregated`, `hygieneEvent`, `dataInsightsRestApiAudit`, `informationBarrierPolicyApplication`, `sharePointListItemOperation`, `sharePointContentTypeOperation`, `sharePointFieldOperation`, `microsoftTeamsAdmin`, `hrSignal`, `microsoftTeamsDevice`, `microsoftTeamsAnalytics`, `informationWorkerProtection`, `campaign`, `dlpEndpoint`, `airInvestigation`, `quarantine`, `microsoftForms`, `applicationAudit`, `complianceSupervisionExchange`, `customerKeyServiceEncryption`, `officeNative`, `mipAutoLabelSharePointItem`, `mipAutoLabelSharePointPolicyLocation`, `microsoftTeamsShifts`, `secureScore`, `mipAutoLabelExchangeItem`, `cortanaBriefing`, `search`, `wdatpAlerts`, `powerPlatformAdminDlp`, `powerPlatformAdminEnvironment`, `mdatpAudit`, `sensitivityLabelPolicyMatch`, `sensitivityLabelAction`, `sensitivityLabeledFileAction`, `attackSim`, `airManualInvestigation`, `securityComplianceRBAC`, `userTraining`, `airAdminActionInvestigation`, `mstic`, `physicalBadgingSignal`, `teamsEasyApprovals`, `aipDiscover`, `aipSensitivityLabelAction`, `aipProtectionAction`, `aipFileDeleted`, `aipHeartBeat`, `mcasAlerts`, `onPremisesFileShareScannerDlp`, `onPremisesSharePointScannerDlp`, `exchangeSearch`, `sharePointSearch`, `privacyDataMinimization`, `labelAnalyticsAggregate`, `myAnalyticsSettings`, `securityComplianceUserChange`, `complianceDLPExchangeClassification`, `complianceDLPEndpoint`, `mipExactDataMatch`, `msdeResponseActions`, `msdeGeneralSettings`, `msdeIndicatorsSettings`, `ms365DCustomDetection`, `msdeRolesSettings`, `mapgAlerts`, `mapgPolicy`, `mapgRemediation`, `privacyRemediationAction`, `privacyDigestEmail`, `mipAutoLabelSimulationProgress`, `mipAutoLabelSimulationCompletion`, `mipAutoLabelProgressFeedback`, `dlpSensitiveInformationType`, `mipAutoLabelSimulationStatistics`, `largeContentMetadata`, `microsoft365Group`, `cdpMlInferencingResult`, `filteringMailMetadata`, `cdpClassificationMailItem`, `cdpClassificationDocument`, `officeScriptsRunAction`, `filteringPostMailDeliveryAction`, `cdpUnifiedFeedback`, `tenantAllowBlockList`, `consumptionResource`, `healthcareSignal`, `dlpImportResult`, `cdpCompliancePolicyExecution`, `multiStageDisposition`, `privacyDataMatch`, `filteringDocMetadata`, `filteringEmailFeatures`, `powerBIDlp`, `filteringUrlInfo`, `filteringAttachmentInfo`, `coreReportingSettings`, `complianceConnector`, `powerPlatformLockboxResourceAccessRequest`, `powerPlatformLockboxResourceCommand`, `cdpPredictiveCodingLabel`, `cdpCompliancePolicyUserFeedback`, `webpageActivityEndpoint`, `omePortal`, `cmImprovementActionChange`, `filteringUrlClick`, `mipLabelAnalyticsAuditRecord`, `filteringEntityEvent`, `filteringRuleHits`, `filteringMailSubmission`, `labelExplorer`, `microsoftManagedServicePlatform`, `powerPlatformServiceActivity`, `scorePlatformGenericAuditRecord`, `filteringTimeTravelDocMetadata`, `alert`, `alertStatus`, `alertIncident`, `incidentStatus`, `case`, `caseInvestigation`, `recordsManagement`, `privacyRemediation`, `dataShareOperation`, `cdpDlpSensitive`, `ehrConnector`, `filteringMailGradingResult`, `publicFolder`, `privacyTenantAuditHistoryRecord`, `aipScannerDiscoverEvent`, `eduDataLakeDownloadOperation`, `m365ComplianceConnector`, `microsoftGraphDataConnectOperation`, `microsoftPurview`, `filteringEmailContentFeatures`, `powerPagesSite`, `powerAppsResource`, `plannerPlan`, `plannerCopyPlan`, `plannerTask`, `plannerRoster`, `plannerPlanList`, `plannerTaskList`, `plannerTenantSettings`, `projectForTheWebProject`, `projectForTheWebTask`, `projectForTheWebRoadmap`, `projectForTheWebRoadmapItem`, `projectForTheWebProjectSettings`, `projectForTheWebRoadmapSettings`, `quarantineMetadata`, `microsoftTodoAudit`, `timeTravelFilteringDocMetadata`, `teamsQuarantineMetadata`, `sharePointAppPermissionOperation`, `microsoftTeamsSensitivityLabelAction`, `filteringTeamsMetadata`, `filteringTeamsUrlInfo`, `filteringTeamsPostDeliveryAction`, `mdcAssessments`, `mdcRegulatoryComplianceStandards`, `mdcRegulatoryComplianceControls`, `mdcRegulatoryComplianceAssessments`, `mdcSecurityConnectors`, `mdaDataSecuritySignal`, `vivaGoals`, `filteringRuntimeInfo`, `attackSimAdmin`, `microsoftGraphDataConnectConsent`, `filteringAtpDetonationInfo`, `privacyPortal`, `managedTenants`, `unifiedSimulationMatchedItem`, `unifiedSimulationSummary`, `updateQuarantineMetadata`, `ms365DSuppressionRule`, `purviewDataMapOperation`, `filteringUrlPostClickAction`, `irmUserDefinedDetectionSignal`, `teamsUpdates`, `plannerRosterSensitivityLabel`, `ms365DIncident`, `filteringDelistingMetadata`, `complianceDLPSharePointClassificationExtended`, `microsoftDefenderForIdentityAudit`, `supervisoryReviewDayXInsight`, `defenderExpertsforXDRAdmin`, `cdpEdgeBlockedMessage`, `hostedRpa`, `cdpContentExplorerAggregateRecord`, `cdpHygieneAttachmentInfo`, `cdpHygieneSummary`, `cdpPostMailDeliveryAction`, `cdpEmailFeatures`, `cdpHygieneUrlInfo`, `cdpUrlClick`, `cdpPackageManagerHygieneEvent`, `filteringDocScan`, `timeTravelFilteringDocScan`, `mapgOnboard`, `unknownFutureValue`.|
|serviceFilter|String|**TODO: Add Description**|
|status|microsoft.graph.security.auditLogQueryStatus|**TODO: Add Description**.The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `cancelled`, `unknownFutureValue`.|
|userPrincipalNameFilters|String collection|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|records|[microsoft.graph.security.auditLogRecord](../resources/security-auditlogrecord.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.security.auditLogQuery",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.security.auditLogQuery",
  "id": "String (identifier)",
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
```

