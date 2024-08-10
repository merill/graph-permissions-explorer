# eDiscovery.Read.All

> Allows the app to read eDiscovery objects such as cases, custodians, review sets and other related objects on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/siteSources/{siteSourceId}](https://docs.microsoft.com/graph/api/ediscovery-sitesource-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/userSources/{userSourceId}](https://docs.microsoft.com/graph/api/ediscovery-usersource-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{caseId}/legalHolds/{legalHoldId}](https://docs.microsoft.com/graph/api/ediscovery-legalhold-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{caseId}/tags/{tagId}?forcedelete=true](https://docs.microsoft.com/graph/api/ediscovery-tag-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{id}](https://docs.microsoft.com/graph/api/ediscovery-case-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{id}/custodians/{id}/unifiedGroupSources/{id}](https://docs.microsoft.com/graph/api/ediscovery-unifiedgroupsource-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /compliance/ediscovery/cases/{id}/reviewSets/{id}/queries/{id}](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /security/cases/ediscoveryCases/{ediscoveryCaseId}](https://docs.microsoft.com/graph/api/security-casesroot-delete-ediscoverycases?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}](https://docs.microsoft.com/graph/api/security-ediscoverycase-delete-legalholds?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}](https://docs.microsoft.com/graph/api/security-ediscoverycase-delete-searches?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags/{tagId}](https://docs.microsoft.com/graph/api/security-ediscoverycase-delete-tags?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases](https://docs.microsoft.com/graph/api/ediscovery-case-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caesId}/custodians/{custodianId}](https://docs.microsoft.com/graph/api/ediscovery-custodian-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians](https://docs.microsoft.com/graph/api/ediscovery-case-list-custodians?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/siteSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-list-sitesources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/siteSources/{siteSourceId}](https://docs.microsoft.com/graph/api/ediscovery-sitesource-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/unifiedGroupSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-list-unifiedgroupsources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/unifiedGroupSources/{unifiedGroupSourceId}](https://docs.microsoft.com/graph/api/ediscovery-unifiedgroupsource-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/userSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-list-usersources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/userSources/{userSourceId}](https://docs.microsoft.com/graph/api/ediscovery-usersource-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/legalHolds](https://docs.microsoft.com/graph/api/ediscovery-case-list-legalholds?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}](https://docs.microsoft.com/graph/api/ediscovery-legalhold-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}/siteSources](https://docs.microsoft.com/graph/api/ediscovery-legalhold-list-sitesources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}/userSources](https://docs.microsoft.com/graph/api/ediscovery-legalhold-list-usersources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/noncustodialDataSources](https://docs.microsoft.com/graph/api/ediscovery-noncustodialdatasource-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/noncustodialDataSources/{noncustodialDataSourceId}](https://docs.microsoft.com/graph/api/ediscovery-noncustodialdatasource-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/noncustodialDataSources/{noncustodialDataSourceId}/dataSource](https://docs.microsoft.com/graph/api/ediscovery-noncustodialdatasource-list-datasource?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/operations](https://docs.microsoft.com/graph/api/ediscovery-case-list-operations?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/operations/{operationId}/microsoft.graph.ediscovery.caseExportOperation/getDownloadUrl](https://docs.microsoft.com/graph/api/ediscovery-caseexportoperation-getdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/reviewSets](https://docs.microsoft.com/graph/api/ediscovery-case-list-reviewsets?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/settings](https://docs.microsoft.com/graph/api/ediscovery-casesettings-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections](https://docs.microsoft.com/graph/api/ediscovery-case-list-sourcecollections?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/additionalSources](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-list-additionalsources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/addToReviewSetOperation](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-list-addtoreviewsetoperation?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/custodianSources](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-list-custodiansources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/lastEstimateStatisticsOperation](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-list-lastestimatestatisticsoperation?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/noncustodialSources](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-list-noncustodialsources?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/tags](https://docs.microsoft.com/graph/api/ediscovery-case-list-tags?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/tags/{tagId}](https://docs.microsoft.com/graph/api/ediscovery-tag-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/tags/{tagId}/childTags](https://docs.microsoft.com/graph/api/ediscovery-tag-childtags?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{caseId}/tags/asHierarchy](https://docs.microsoft.com/graph/api/ediscovery-tag-ashierarchy?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{id}](https://docs.microsoft.com/graph/api/ediscovery-case-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{id}/reviewSets/{id}](https://docs.microsoft.com/graph/api/ediscovery-reviewset-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{id}/reviewSets/{id}/queries](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /compliance/ediscovery/cases/{id}/reviewSets/{id}/queries/{id}](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases](https://docs.microsoft.com/graph/api/security-casesroot-list-ediscoverycases?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}](https://docs.microsoft.com/graph/api/security-ediscoverycase-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-custodians?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/siteSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-sitesources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/unifiedGroupSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-unifiedgroupsources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/userSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-usersources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{ediscoveryCustodianId}](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{ediscoverycustodianId}/lastIndexOperation](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-lastindexoperation?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-legalholds?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}](https://docs.microsoft.com/graph/api/security-ediscoveryholdpolicy-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}/userSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-usersources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/{ediscoveryNoncustodialDataSourceId}](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialSources/{ediscoveryNoncustodialDataSourceId}/lastIndexOperation](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-list-lastindexoperation?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/operations](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-operations?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/operations/{eDiscoveryCaseOperationId}/microsoft.graph.security.ediscoveryExportOperation/getDownloadUrl](https://docs.microsoft.com/graph/api/security-ediscoveryexportoperation-getdownloadurl?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-reviewsets?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-list-files?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files/{ediscoveryFileId}](https://docs.microsoft.com/graph/api/security-ediscoveryfile-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files/{ediscoveryFileId}/custodian](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files/{ediscoveryFileId}/tags/{ediscoveryReviewTagId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files/{ediscoveryFileId}/tags/{ediscoveryReviewTagId}/childTags/{ediscoveryReviewTagId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/files/{ediscoveryFileId}/tags/{ediscoveryReviewTagId}/parent](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-list-queries?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries/{queryId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewsetquery-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries/{queryId}/run](https://docs.microsoft.com/graph/api/security-ediscoveryreviewsetquery-run?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{reviewSetId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-searches?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}](https://docs.microsoft.com/graph/api/security-ediscoverysearch-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}/lastEstimateStatisticsOperation](https://docs.microsoft.com/graph/api/security-ediscoverysearch-list-lastestimatestatisticsoperation?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/settings](https://docs.microsoft.com/graph/api/security-ediscoverycasesettings-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-tags?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags/{ediscoveryReviewTagId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags/asHierarchy](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-ashierarchy?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}](https://docs.microsoft.com/graph/api/ediscovery-custodian-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}](https://docs.microsoft.com/graph/api/ediscovery-legalhold-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{caseId}/tags/{tagId}](https://docs.microsoft.com/graph/api/ediscovery-tag-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{id}](https://docs.microsoft.com/graph/api/ediscovery-case-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /compliance/ediscovery/cases/{id}/reviewSets/{id}/queries/{id}](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /security/cases/ediscoveryCases/{ediscoveryCaseId}](https://docs.microsoft.com/graph/api/security-ediscoverycase-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}](https://docs.microsoft.com/graph/api/security-ediscoveryholdpolicy-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries/{queryId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewsetquery-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}](https://docs.microsoft.com/graph/api/security-ediscoverysearch-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags/{ediscoveryReviewTagId}](https://docs.microsoft.com/graph/api/security-ediscoveryreviewtag-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases](https://docs.microsoft.com/graph/api/ediscovery-case-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{CaseId}/close](https://docs.microsoft.com/graph/api/ediscovery-case-close?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/custodians](https://docs.microsoft.com/graph/api/ediscovery-case-post-custodians?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/activate](https://docs.microsoft.com/graph/api/ediscovery-custodian-activate?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/release](https://docs.microsoft.com/graph/api/ediscovery-custodian-release?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/siteSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-post-sitesources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/custodians/{custodianId}/userSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-post-usersources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/legalHolds](https://docs.microsoft.com/graph/api/ediscovery-case-post-legalholds?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}/siteSources](https://docs.microsoft.com/graph/api/ediscovery-legalhold-post-sitesources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/legalHolds/{legalholdId}/userSources](https://docs.microsoft.com/graph/api/ediscovery-legalhold-post-usersources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/noncustodialDataSources](https://docs.microsoft.com/graph/api/ediscovery-noncustodialdatasource-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/noncustodialDataSources/{noncustodialDataSourceId}/release](https://docs.microsoft.com/graph/api/ediscovery-noncustodialdatasource-release?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/reopen](https://docs.microsoft.com/graph/api/ediscovery-case-reopen?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/reviewSets/{reviewsetId}/addToReviewSet](https://docs.microsoft.com/graph/api/ediscovery-reviewset-addtoreviewset?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/reviewsets/{reviewsetId}/export](https://docs.microsoft.com/graph/api/ediscovery-reviewset-export?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/reviewSets/{reviewSetId}/queries/{reviewSetQueryId}/applyTags](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-applytags?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/sourceCollections](https://docs.microsoft.com/graph/api/ediscovery-case-post-sourcecollections?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/additionalSources](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-post-additionalsources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/custodianSources/$ref](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-post-custodiansources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/sourceCollections/{sourceCollectionId}/estimateStatistics](https://docs.microsoft.com/graph/api/ediscovery-sourcecollection-estimatestatistics?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{caseId}/tags](https://docs.microsoft.com/graph/api/ediscovery-case-post-tags?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{id}/custodians/{id}/unifiedGroupSources](https://docs.microsoft.com/graph/api/ediscovery-custodian-post-unifiedgroupsources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{id}/reviewSets](https://docs.microsoft.com/graph/api/ediscovery-case-post-reviewsets?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /compliance/ediscovery/cases/{id}/reviewSets/{id}/queries](https://docs.microsoft.com/graph/api/ediscovery-reviewsetquery-post?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases](https://docs.microsoft.com/graph/api/security-casesroot-post-ediscoverycases?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases('{ediscoveryCaseId}')/searches('{ediscoverySearchId}')/exportReport](https://docs.microsoft.com/graph/api/security-ediscoverysearch-exportreport?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases('{ediscoveryCaseId}')/searches('{ediscoverySearchId}')/exportResult](https://docs.microsoft.com/graph/api/security-ediscoverysearch-exportresult?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/close](https://docs.microsoft.com/graph/api/security-ediscoverycase-close?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians](https://docs.microsoft.com/graph/api/security-ediscoverycase-post-custodians?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/siteSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-post-sitesources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/unifiedGroupSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-post-unifiedgroupsources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{custodianId}/userSources](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-post-usersources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{ediscoveryCustodianId}/activate](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-activate?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{eDiscoveryCustodianId}/applyHold](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-applyhold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{ediscoveryCustodianId}/release](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-release?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{eDiscoveryCustodianId}/removeHold](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-removehold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/{ediscoveryCustodianId}/updateIndex](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-updateindex?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/applyHold](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-applyhold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/removeHold](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-removehold?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/custodians/updateIndex](https://docs.microsoft.com/graph/api/security-ediscoverycustodian-updateindex?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds](https://docs.microsoft.com/graph/api/security-ediscoverycase-post-legalholds?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}/siteSources](https://docs.microsoft.com/graph/api/security-ediscoveryholdpolicy-post-sitesources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/legalHolds/{ediscoveryHoldPolicyId}/userSources](https://docs.microsoft.com/graph/api/security-ediscoveryholdpolicy-post-usersources?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources](https://docs.microsoft.com/graph/api/security-ediscoverycase-list-noncustodialdatasources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/{ediscoverynoncustodialDatasourceId}/applyHold](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-applyhold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/{ediscoveryNoncustodialDataSourceId}/release](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-release?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/{ediscoverynoncustodialDatasourceId}/removeHold](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-removehold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/{ediscoveryNoncustodialDataSourceId}/updateIndex](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-updateindex?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/applyHold](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-applyhold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/noncustodialDataSources/removeHold](https://docs.microsoft.com/graph/api/security-ediscoverynoncustodialdatasource-removehold?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reopen](https://docs.microsoft.com/graph/api/security-ediscoverycase-reopen?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets](https://docs.microsoft.com/graph/api/security-ediscoverycase-post-reviewsets?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{eDiscoveryCaseId}/reviewSets/{eDiscoveryReviewSetId}/addToReviewSet](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-addtoreviewset?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/export](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-export?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries](https://docs.microsoft.com/graph/api/security-ediscoveryreviewset-post-queries?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries/{queryId}/applyTags](https://docs.microsoft.com/graph/api/security-ediscoveryreviewsetquery-applytags?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/reviewSets/{ediscoveryReviewSetId}/queries/{queryId}/export](https://docs.microsoft.com/graph/api/security-ediscoveryreviewsetquery-export?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches](https://docs.microsoft.com/graph/api/security-ediscoverycase-post-searches?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}/estimateStatistics](https://docs.microsoft.com/graph/api/security-ediscoverysearch-estimatestatistics?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}/exportReport](https://docs.microsoft.com/graph/api/security-ediscoverysearch-exportreport?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/searches/{ediscoverySearchId}/exportResult](https://docs.microsoft.com/graph/api/security-ediscoverysearch-exportresult?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /security/cases/ediscoveryCases/{ediscoveryCaseId}/tags](https://docs.microsoft.com/graph/api/security-ediscoverycase-post-tags?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|99201db3-7652-4d5a-809a-bdb94f85fe3c|
|**Consent Type**|Admin|
|**Display String**|Read all eDiscovery objects|
|**Description**|Allows the app to read eDiscovery objects such as cases, custodians, review sets and other related objects on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|50180013-6191-4d1e-a373-e590ff4e66af|
|**Display String**|Read all eDiscovery objects|
|**Description**|Allows the app to read eDiscovery objects such as cases, custodians, review sets and other related objects without a signed-in user.|
## Resources
### [addToReviewSetOperation ](https://docs.microsoft.com/graph/api/resources/ediscovery-addtoreviewsetoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.ediscovery.caseAction| The case action for this entity will always be `addToReviewSet`. Read-only. Inherited from caseOperation.|
|completedDateTime|DateTimeOffset|The date and time the operation was completed. Read-only. Inherited from caseOperation|
|createdBy|identitySet|The user who created the operation. Read-only. Inherited from caseOperation|
|createdDateTime|DateTimeOffset|The date and time the operation was started. Read-only. Inherited from caseOperation|
|id|String| The ID for the operation. Read-only. Inherited from caseOperation.|
|percentProgress|Int32|The progress of the operation. Read-only. Inherited from caseOperation.|
|resultInfo|resultInfo|Contains success and failure-specific result information. Inherited from caseOperation.|
|status|microsoft.graph.ediscovery.caseOperationStatus|The status of the case operation. Inherited from caseOperation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [case ](https://docs.microsoft.com/graph/api/resources/ediscovery-case?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|closedBy|identitySet|The user who closed the case.|
|closedDateTime|DateTimeOffset|The date and time when the case was closed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|createdBy|identitySet|The user who created the case.|
|createdDateTime|DateTimeOffset|The date and time when the entity was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|description|String|The case description.|
|displayName|String|The case name.|
|externalId|String|The external case number for customer reference.|
|id|String| The ID for the eDiscovery case. Read-only. |
|lastModifiedBy|identitySet|The last user who modified the entity.|
|lastModifiedDateTime|DateTimeOffset| The latest date and time when the case was modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|status|microsoft.graph.ediscovery.caseStatus| The case status. Possible values are `unknown`, `active`, `pendingDelete`, `closing`, `closed`, and `closedWithError`. For details, see the following table.|
### [caseExportOperation ](https://docs.microsoft.com/graph/api/resources/ediscovery-caseexportoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.ediscovery.caseAction| The case action for this entity will always be `contentExport`. Inherited from caseOperation.|
|azureBlobContainer|String| The name of the Azure storage location where the export will be stored. This only applies to exports stored in your own Azure storage location. |
|azureBlobToken|String| The SAS token for the Azure storage location.  This only applies to exports stored in your own Azure storage location. |
|completedDateTime|DateTimeOffset| The date and time the export was completed.  Inherited from caseOperation.|
|createdBy|identitySet| The user who initiated the export operation. Inherited from caseOperation.|
|createdDateTime|DateTimeOffset| The date and time the export was created. Inherited from caseOperation.|
|description|String| The description provided for the export. |
|exportOptions|microsoft.graph.ediscovery.exportOptions| The options provided for the export. For more information, see reviewSet: export. Possible values are: `originalFiles`, `text`, `pdfReplacement`, `fileInfo`, `tags`.|
|exportStructure|microsoft.graph.ediscovery.exportFileStructure|The options provided specify the structure of the export. For more information, see reviewSet: export. Possible values are: `none`, `directory`, `pst`.|
|id|String| The ID for the operation. Read-only. Inherited from caseOperation.|
|outputFolderId|String|The output folder ID.|
|outputName|String| The name provided for the export.|
|percentProgress|Int32| The progress of the operation. Inherited from caseOperation.|
|resultInfo|resultInfo|Contains success and failure-specific result information. Inherited from caseOperation.|
|status|microsoft.graph.ediscovery.caseOperationStatus|The status of the case operation. Inherited from caseOperation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [caseOperation ](https://docs.microsoft.com/graph/api/resources/ediscovery-caseoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.ediscovery.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the operation was completed. |
|createdBy|identitySet| The user that created the operation. |
|createdDateTime|DateTimeOffset| The date and time the operation was created. |
|id|String| The ID for the operation. Read-only. |
|percentProgress|Int32| The progress of the operation. |
|resultInfo|resultInfo| Contains success and failure-specific result information. |
|status|microsoft.graph.ediscovery.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [custodian ](https://docs.microsoft.com/graph/api/resources/ediscovery-custodian?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|acknowledgedDateTime|DateTimeOffset|Date and time the custodian acknowledged a hold notification.|
|applyHoldToSources|Boolean|Identifies whether a custodian's sources were placed on hold during creation.|
|createdDateTime|DateTimeOffset|Date and time when the custodian was added to the case.|
|displayName|String|Display name of the custodian.|
|email|String|Email address of the custodian.|
|id|String|The ID for the custodian in the specified case. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time the custodian object was last modified|
|releasedDateTime|DateTimeOffset|Date and time the custodian was released from the case.|
|status|microsoft.graph.ediscovery.custodianStatus|Status of the custodian. Possible values are: `active`, `released`.|
### [dataSource ](https://docs.microsoft.com/graph/api/resources/ediscovery-datasource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **dataSource**.|
|createdDateTime|DateTimeOffset|The date and time the **dataSource** was created.|
|displayName|String|The display name of the **dataSource**, and is the name of the SharePoint site.|
|id|String| The ID of the **d
### [estimateStatisticsOperation ](https://docs.microsoft.com/graph/api/resources/ediscovery-estimatestatisticsoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.ediscovery.caseAction| The type of operation. The case action for this entity will always be `estimateStatistics`. Read-only. Inherited from caseOperation.|
|completedDateTime|DateTimeOffset|The date and time the operation was completed. Read-only. Inherited from caseOperation.|
|createdBy|identitySet|The user who created the operation. Read-only. Inherited from caseOperation.|
|createdDateTime|DateTimeOffset|The date and time the operation was started. Read-only. Inherited from caseOperation.|
|id|String| The ID for the operation. Read-only. Inherited from caseOperation.|
|indexedItemCount|Int64|The estimated count of items for the **sourceCollection** that matched the content query.|
|indexedItemsSize|Int64|The estimated size of items for the **sourceCollection** that matched the content query.|
|mailboxCount|Int32|The number of mailboxes that had search hits.|
|percentProgress|Int32|The progress of the operation. Read-only. Inherited from caseOperation.|
|resultInfo|resultInfo|Contains success and failure-specific result information. Inherited from caseOperation.|
|siteCount|Int32|The number of mailboxes that had search hits.|
|status|microsoft.graph.ediscovery.caseOperationStatus|The status of the case operation. Inherited from caseOperation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
|unindexedItemCount|Int64|The estimated count of unindexed items for the collection.|
|unindexedItemsSize|Int64|The estimated size of unindexed items for the collection.|
### [legalHold ](https://docs.microsoft.com/graph/api/resources/ediscovery-legalhold?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentQuery|String|KQL query that specifies content to be held in the specified locations. To learn more, see Keyword queries and search conditions for Content Search and eDiscovery.  To hold all content in the specified locations, leave **contentQuery** blank. |
|createdBy|identitySet|The user who created the legal hold. |
|createdDateTime|DateTimeOffset|The date and time the legal hold was created. |
|description|String| The legal hold description. |
|displayName|String| The display name of the legal hold. |
|errors|String collection|Lists any errors that happened while placing the hold. |
|id|String|The ID for the eDiscovery case. Read-only. Inherited from entity. |
|isEnabled|Boolean|Indicates whether the hold is enabled and actively holding content. |
|lastModifiedBy|identitySet|the user who last modified the legal hold.|
|lastModifiedDateTime|DateTimeOffset|The date and time the legal hold was last modified. |
|status|microsoft.graph.ediscovery.legalHoldStatus|The status of the legal hold. Possible values are: `Pending`, `Error`, `Success`, `UnknownFutureValue`.|
### [noncustodialDataSource ](https://docs.microsoft.com/graph/api/resources/ediscovery-noncustodialdatasource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applyHoldToSource|Boolean|Indicates if hold is applied to noncustodial data source (such as mailbox or site).|
|createdDateTime|DateTimeOffset|Created date and time of the nonCustodialDataSource. Inherited from microsoft.graph.ediscovery.dataSourceContainer.|
|displayName|String|Display name of the noncustodialDataSource. Inherited from microsoft.graph.ediscovery.dataSourceContainer.|
|id|String|Unique identifier of the nonCustodialDataSource. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|Last modified date and time of the nonCustodialDataSource. Inherited from microsoft.graph.ediscovery.dataSourceContainer.|
|releasedDateTime|DateTimeOffset|Date and time that the nonCustodialDataSource was released from the case. Inherited from microsoft.graph.ediscovery.dataSourceContainer.|
|status|microsoft.graph.ediscovery.dataSourceContainerStatus|Latest status of the nonCustodialDataSource. Inherited from microsoft.graph.ediscovery.dataSourceContainer. Possible values are: `Active`, `Released`.|
### [reviewSet ](https://docs.microsoft.com/graph/api/resources/ediscovery-reviewset?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdBy        | identitySet | The user who created the review set. Read-only. |
|createdDateTime  |DateTimeOffset| The datetime when the review set was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
|displayName      |String| The review set name. The name is unique with a maximum limit of 64 characters. |
|id               |String| The review set unique identifier. Read-only. |
### [reviewSetQuery ](https://docs.microsoft.com/graph/api/resources/ediscovery-reviewsetquery?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| createdBy | identitySet | The user who created the query. |
| createdDateTime |DateTimeOffset| The time and date when the query was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
| displayName | String | The name of the query.|
| id |String| The unique identifier of the query. Read-only.|
| lastModifiedBy | identitySet | The user who last modified the query. |
| lastModifiedDateTime |DateTimeOffset | The date and time the query was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
| query | String | The query string in KQL (Keyword Query Language) query. For details, see Document metadata fields in Advanced eDiscovery.  This field maps directly to the keywords condition.  You can refine searches by using fields listed in the *s
### [siteSource ](https://docs.microsoft.com/graph/api/resources/ediscovery-sitesource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **siteSource**.|
|createdDateTime|DateTimeOffset|The date and time the **siteSource** was created.|
|displayName|String|The display name of the **siteSource**. This will be the name of the SharePoint site.|
|id|String| The ID of the **s
### [sourceCollection ](https://docs.microsoft.com/graph/api/resources/ediscovery-sourcecollection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentQuery|String|The query string in KQL (Keyword Query Language) query. For details, see Keyword queries and search conditions for Content Search and eDiscovery. You can refine searches by using fields paired with values; for example, *subject:"Quarterly Financials" AND Date>=06/01/2016 AND Date<=07/01/2016*.|
|createdBy|identitySet|The user who created the **sourceCollection**.|
|createdDateTime|DateTimeOffset|The date and time the **sourceCollection** was created.|
|dataSourceScopes|microsoft.graph.ediscovery.dataSourceScopes|When specified, the collection spans across a service for an entire workload. Possible values are: `none`, `allTenantMailboxes`, `allTenantSites`, `allCaseCustodians`, `allCaseNoncustodialDataSources`.|
|description|String|The description of the **sourceCollection**.|
|displayName|String|The display name of the **sourceCollection**.|
|id|String| The ID for the **sourceCollection**. Read-only. |
|lastModifiedBy|identitySet|The last user who modified the **sourceCollection**.|
|lastModifiedDateTime|DateTimeOffset|The last date and time the **s
### [tag ](https://docs.microsoft.com/graph/api/resources/ediscovery-tag?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|childSelectability|microsoft.graph.ediscovery.childSelectability|Indicates whether a single or multiple child tags can be associated with a document. Possible values are: `One`, `Many`.  This value controls whether the UX presents the tags as checkboxes or a radio button group.|
|createdBy|identitySet|The user who created the tag.|
|description|String|The description for the tag.|
|displayName|String|Display name of the tag.|
|id|String|Unique identifier for the tag.|
|lastModifiedDateTime|DateTimeOffset|The date and time the tag was last modified.|
### [unifiedGroupSource ](https://docs.microsoft.com/graph/api/resources/ediscovery-unifiedgroupsource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **unifiedGroupSource**.|
|createdDateTime|DateTimeOffset|The date and time the **unifiedGroupSource** was created.|
|displayName|String|The display name of the unified group - This is the name of the group.|
|id|String|The ID of the **unifiedGroupSource**. This isn't the ID of the actual group.|
|includedSources|microsoft.graph.ediscovery.sourceType|Specifies which sources are included in this group. Possible values are: `mailbox`, `site`.|
### [userSource ](https://docs.microsoft.com/graph/api/resources/ediscovery-usersource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **userSource**.|
|createdDateTime|DateTimeOffset|The date and time the **userSource** was created|
|displayName|String|The display name associated with the mailbox and site.|
|email|String|Email address of the user's mailbox.|
|id|String|The ID of the **userSource**. This is not the ID of the actual group|
|includedSources|microsoft.graph.ediscovery.sourceType|Specifies which sources are included in this group. Possible values are: `mailbox`, `site`.|
|siteWebUrl|String|The URL of the user's OneDrive for Business site. Read-only.|
### [caseOperation ](https://docs.microsoft.com/graph/api/resources/security-caseoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the operation was completed. |
|createdBy|identitySet| The user that created the operation. |
|createdDateTime|DateTimeOffset| The date and time the operation was created. |
|id|String| The ID for the operation. Read-only. |
|percentProgress|Int32| The progress of the operation. |
|resultInfo|resultInfo| Contains success and failure-specific result information. |
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [dataSource ](https://docs.microsoft.com/graph/api/resources/security-datasource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **dataSource**.|
|createdDateTime|DateTimeOffset|The date and time the **dataSource** was created.|
|displayName|String|The display name of the **dataSource** and is the name of the SharePoint site.|
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the **dataSource**.The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`|
|id|String| The ID of the **d
### [ediscoveryAddToReviewSetOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryaddtoreviewsetoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the operation was completed. |
|createdBy|identitySet| The user that created the operation. |
|createdDateTime|DateTimeOffset| The date and time the operation was created. |
|id|String| The ID for the operation. Read-only. |
|percentProgress|Int32| The progress of the operation. |
|resultInfo|resultInfo| Contains success and failure-specific result information. |
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [ediscoveryCase ](https://docs.microsoft.com/graph/api/resources/security-ediscoverycase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|closedBy|microsoft.graph.identitySet|The user who closed the case.|
|closedDateTime|DateTimeOffset|The date and time when the case was closed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|createdBy|microsoft.graph.identitySet|The user who created the case.|
|createdDateTime|DateTimeOffset|The date and time when the entity was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|description|String|The case description.|
|displayName|String|The case name.|
|externalId|String|The external case number for customer reference.|
|id|String|The ID for the eDiscovery case. Read-only. |
|lastModifiedBy|microsoft.graph.identitySet|The last user who modified the case.
|lastModifiedDateTime|DateTimeOffset|The latest date and time when the case was modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|status|microsoft.graph.security.caseStatus|The case status. Possible values are `unknown`, `active`, `pendingDelete`, `closing`, `closed`, and `closedWithError`. For details, see the following table.

### [ediscoveryCaseSettings ](https://docs.microsoft.com/graph/api/resources/security-ediscoverycasesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the eDiscovery case. Inherited from entity.|
|ocr|microsoft.graph.security.ocrSettings|The OCR (Optical Character Recognition) settings for the case.|
|redundancyDetection|microsoft.graph.security.redundancyDetectionSettings|The redundancy (near duplicate and email threading) detection settings for the case.|
|topicModeling|microsoft.graph.security.topicModelingSettings|The Topic Modeling (Themes) settings for the case.|
### [ediscoveryCustodian ](https://docs.microsoft.com/graph/api/resources/security-ediscoverycustodian?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|acknowledgedDateTime|DateTimeOffset|Date and time the custodian acknowledged a hold notification.|
|createdDateTime|DateTimeOffset|Date and time when the custodian was added to the case.|
|displayName|String|Display name of the custodian.|
|email|String|Email address of the custodian.|
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the custodian.The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`|
|id|String|The ID for the custodian in the specified case. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time the custodian object was last modified|
|releasedDateTime|DateTimeOffset|Date and time the custodian was released from the case.|
|status|microsoft.graph.security.custodianStatus|Status of the custodian. Possible values are: `active`, `released`.|
### [ediscoveryEstimateOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryestimateoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset|The date and time the operation was completed. Read-only. |
|createdBy|identitySet|The user who created the operation. Read-only. |
|createdDateTime|DateTimeOffset|The date and time the operation was started. Read-only.|
|id|String| The ID for the operation. Read-only.|
|indexedItemCount|Int64|The estimated count of items for the **search** that matched the content query.|
|indexedItemsSize|Int64|The estimated size of items for the **search** that matched the content query.|
|mailboxCount|Int32|The number of mailboxes that had search hits.|
|percentProgress|Int32|The progress of the operation. Read-only. |
|resultInfo|resultInfo|Contains success and failure-specific result information. |
|siteCount|Int32|The number of mailboxes that had search hits.|
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
|unindexedItemCount|Int64|The estimated count of unindexed items for the collection.|
|unindexedItemsSize|Int64|The estimated size of unindexed items for the collection.|
### [ediscoveryExportOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryexportoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the export was completed.|
|createdBy|identitySet| The user who initiated the export operation.|
|createdDateTime|DateTimeOffset| The date and time the export was created.|
|description|String| The description provided for the export.|
|exportFileMetadata | microsoft.graph.security.ediscoveryExportFileMetadata| Contains the properties for an export file metadata, including **downloadUrl**, **fileName**, and **size**.  |
|exportOptions|microsoft.graph.security.exportOptions| The options provided for the export. For more information, see reviewSet: export. Possible values are: `originalFiles`, `text`, `pdfReplacement`,  `tags`.|
|exportStructure|microsoft.graph.security.exportFileStructure|The options that specify the structure of the export. For more information, see reviewSet: export. Possible values are: `none`, `directory`, `pst`.|
|id|String| The ID for the operation. Read-only. |
|outputName|String| The name provided for the export.|
|percentProgress|Int32| The progress of the operation.|
|resultInfo|resultInfo|Contains success and failure-specific result information. Inherited from caseOperation.|
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [ediscoveryFile ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryfile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|Stream|The content stream of the original file.|
|dateTime|DateTimeOffset|The date and time the file was last modified. See dateTime values for more details.|
|extension|String|The file extension of the file such as png, msg, docx etc.|
|extractedTextContent|Stream|The extracted text from the original file. For image based files, this would be the OCR text.|
|id|String|The unique identifier for the file.|
|mediaType|String|mimeType of the file. for example: text/plain, charset=UTF-8, application/vnd.ms-outlook.|
|name|String|The name of the file. Subject of the mail for email.|
|otherProperties|microsoft.graph.security.stringValueDictionary|A list of other properties of the file like titleOfSharepointDocument, emailRecipients. Learn more.|
|processingStatus|microsoft.graph.security.fileProcessingStatus|The processing status after the item was added to a review set. The possible values are: `success`, `internalError`, `unknownError`, `processingTimeout`, `invalidFileId`, `fileSizeIsZero`, `fileSizeIsTooLarge`, `fileDepthLimitExceeded`, `fileBodyIsTooLong`, `fileTypeIsUnknown`, `fileTypeIsNotSupported`, `malformedFile`, `protectedFile`, `poisonFile`, `noReviewSetSummaryGenerated`, `extractionException`, `ocrProcessingTimeout`, `ocrFileSizeExceedsLimit`.|
|senderAuthor|String collection|The sender of the email or authors of the document.|
|size|Int64|size of the file.|
|sourceType|microsoft.graph.security.sourceType|The original source of the content. The possible values are: `mailbox`, `site`.|
|subjectTitle|String|The subject of the email or title of the document|
### [ediscoveryHoldOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryholdoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the operation was completed. |
|createdBy|identitySet| The user that created the operation. |
|createdDateTime|DateTimeOffset| The date and time the operation was created. |
|id|String| The ID for the operation. Read-only. |
|percentProgress|Int32| The progress of the operation. |
|resultInfo|resultInfo| Contains success and failure-specific result information. |
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [ediscoveryHoldPolicy ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryholdpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentQuery|String|KQL query that specifies content to be held in the specified locations. To learn more, see Keyword queries and search conditions for Content Search and eDiscovery.  To hold all content in the specified locations, leave **contentQuery** blank. |
|createdBy|identitySet|The user who created the legal hold. |
|createdDateTime|DateTimeOffset|The date and time the legal hold was created. |
|description|String| The legal hold description. |
|displayName|String| The display name of the legal hold. |
|errors|String collection|Lists any errors that happened while placing the hold. |
|id|String|The ID for the eDiscovery case. Read-only. Inherited from entity. |
|isEnabled|Boolean|Indicates whether the hold is enabled and actively holding content. |
|lastModifiedBy|identitySet|the user who last modified the legal hold.|
|lastModifiedDateTime|DateTimeOffset|The date and time the legal hold was last modified. |
|status|microsoft.graph.security.policyStatus|The status of the legal hold. Possible values are: `Pending`, `Error`, `Success`.|
### [ediscoveryIndexOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryindexoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `addToReviewSet`,`applyTags`,`contentExport`,`convertToPdf`,`estimateStatistics`, `purgeData`|
|completedDateTime|DateTimeOffset| The date and time the operation was completed. |
|createdBy|identitySet| The user that created the operation. |
|createdDateTime|DateTimeOffset| The date and time the operation was created. |
|id|String| The ID for the operation. Read-only. |
|percentProgress|Int32| The progress of the operation. |
|resultInfo|resultInfo| Contains success and failure-specific result information. |
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. Possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`.|
### [ediscoveryNoncustodialDataSource ](https://docs.microsoft.com/graph/api/resources/security-ediscoverynoncustodialdatasource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Created date and time of the nonCustodialDataSource. Inherited from microsoft.graph.security.datasourcecontainer.|
|displayName|String|Display name of the noncustodialDataSource. Inherited from microsoft.graph.security.datasourcecontainer.|
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the nonCustodialDataSource. The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`|
|id|String|Unique identifier of the nonCustodialDataSource. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|Last modified date and time of the nonCustodialDataSource. Inherited from microsoft.graph.security.datasourcecontainer.|
|releasedDateTime|DateTimeOffset|Date and time that the nonCustodialDataSource was released from the case. Inherited from microsoft.graph.security.datasourcecontainer.|
|status|microsoft.graph.security.dataSourceContainerStatus|Latest status of the nonCustodialDataSource. Inherited from microsoft.graph.security.datasourcecontainer. Possible values are: `Active`, `Released`.|
### [ediscoveryReviewSet ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryreviewset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|The user who created the review set. Read-only. |
|createdDateTime|DateTimeOffset|The datetime when the review set was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|The review set name. The name is unique with a maximum limit of 64 characters.|
|id|String|The review set unique identifier. Read-only.|
### [ediscoveryReviewSetQuery ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryreviewsetquery?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| contentQuery | String | The query string in KQL (Keyword Query Language) query. For details, see Document metadata fields in eDiscovery (Premium).  This field maps directly to the keywords condition.  You can refine searches by using fields listed in the *searchable field name* paired with values; for example, *subject:"Quarterly Financials" AND Date>=06/01/2016 AND Date<=07/01/2016*. |
| createdBy | identitySet | The user who created the query. |
| createdDateTime |DateTimeOffset| The time and date when the query was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
| description|String|The description of the **eDiscovery search**.|
| displayName | String | The name of the query.|
| id |String| The unique identifier of the query. Read-only.|
| lastModifiedBy | identitySet | The user who last modified the query. |
| lastModifiedDateTime |DateTimeOffset | The date and time the query was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
### [ediscoveryReviewTag ](https://docs.microsoft.com/graph/api/resources/security-ediscoveryreviewtag?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|childSelectability|microsoft.graph.security.childSelectability|Indicates whether a single or multiple child tags can be associated with a document. Possible values are: `One`, `Many`.  This value controls whether the UX presents the tags as checkboxes or a radio button group.|
|createdBy|identitySet|The user who created the tag.|
|description|String|The description for the tag.|
|displayName|String|Display name of the tag.|
|id|String|Unique identifier for the tag.|
|lastModifiedDateTime|DateTimeOffset|The date and time the tag was last modified.|
### [ediscoverySearch ](https://docs.microsoft.com/graph/api/resources/security-ediscoverysearch?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentQuery|String|The query string in KQL (Keyword Query Language) query. For details, see Keyword queries and search conditions for Content Search and eDiscovery. You can refine searches by using fields paired with values; for example, *subject:"Quarterly Financials" AND Date>=06/01/2016 AND Date<=07/01/2016*.|
|createdBy|identitySet|The user who created the **eDiscovery search**.|
|createdDateTime|DateTimeOffset|The date and time the **eDiscovery search** was created.|
|dataSourceScopes|microsoft.graph.security.dataSourceScopes|When specified, the collection will span across a service for an entire workload. Possible values are: `none`, `allTenantMailboxes`, `allTenantSites`, `allCaseCustodians`, `allCaseNoncustodialDataSources`.|
|description|String|The description of the **eDiscovery search**.|
|displayName|String|The display name of the **eDiscovery search**.|
|id|String| The ID for the **eDiscovery search**. Read-only. |
|lastModifiedBy|identitySet|The last user who modified the **eDiscovery search**.|
|lastModifiedDateTime|DateTimeOffset|The last date and time the **e
### [ediscoverySearchExportOperation ](https://docs.microsoft.com/graph/api/resources/security-ediscoverysearchexportoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.security.caseAction| The type of action the operation represents. Possible values are: `contentExport`,  `applyTags`, `convertToPdf`, `index`, `estimateStatistics`, `addToReviewSet`, `holdUpdate`, `unknownFutureValue`, `purgeData`, `exportReport`, `exportResult`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `purgeData`, `exportReport`, `exportResult`. Inherited from microsoft.graph.security.caseOperation.|
|additionalOptions|microsoft.graph.security.additionalOptions| The additional items to include in the export. The possible values are: `none`, `teamsAndYammerConversations`, `cloudAttachments`, `allDocumentVersions`, `subfolderContents`, `listAttachments`, `unknownFutureValue`.|
|completedDateTime|DateTimeOffset|The date and time when the operation was completed. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from microsoft.graph.security.caseOperation.|
|createdBy|microsoft.graph.identitySet|The user who created the operation. Inherited from microsoft.graph.security.caseOperation.|
|createdDateTime|DateTimeOffset|The date and time when the operation was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. Inherited from microsoft.graph.security.caseOperation.|
|description|String|The name of export provided by the user.|
|displayName|String|The description of the export by the user.|
|exportCriteria|microsoft.graph.security.exportCriteria|Items to be included in the export. The possible values are: `searchHits`, `partiallyIndexed`, `unknownFutureValue`.|
|exportFileMetadata|microsoft.graph.security.ediscoveryExportFileMetadata collection|Contains the properties for an export file metadata, including **downloadUrl**, **fileName**, and **size**.|
|exportFormat|microsoft.graph.security.exportFormat|Format of the emails of the export. The possible values are: `pst`, `msg`, `eml`, `unknownFutureValue`.|
|exportLocation|microsoft.graph.security.exportLocation| Location scope for partially indexed items. You can choose to include partially indexed items only in responsive locations with search hits or in all targeted locations. The possible values are: `responsiveLocations`, `nonresponsiveLocations`, `unknownFutureValue`.|
|exportSingleItems|Boolean|Indicates whether to export single items.|
|id|String| The ID for the operation. Read-only. Inherited from microsoft.graph.security.caseOperation.|
|percentProgress|Int32|The progress of the operation. Inherited from microsoft.graph.security.caseOperation.|
|resultInfo|microsoft.graph.resultInfo|Contains success and failure-specific result information. Inherited from microsoft.graph.security.caseOperation.|
|status|microsoft.graph.security.caseOperationStatus| The status of the case operation. The possible values are: `notStarted`, `submissionFailed`, `running`, `succeeded`, `partiallySucceeded`, `failed`, `unknownFutureValue`. Inherited from microsoft.graph.security.caseOperation.|
### [siteSource ](https://docs.microsoft.com/graph/api/resources/security-sitesource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **siteSource**.|
|createdDateTime|DateTimeOffset|The date and time the **siteSource** was created.|
|displayName|String|The display name of the **siteSource**. This is the name of the SharePoint site.|
|id|String| The ID of the **siteSource**. |
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the **s
### [unifiedGroupSource ](https://docs.microsoft.com/graph/api/resources/security-unifiedgroupsource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **unifiedGroupSource**.|
|createdDateTime|DateTimeOffset|The date and time the **unifiedGroupSource** was created.|
|displayName|String|The display name of the unified group, which is the name of the group.|
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the **unifiedGroupSource**. The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`|
|id|String|The ID of the **unifiedGroupSource**. This isn't the ID of the actual group.|
|includedSources|microsoft.graph.security.sourceType|Specifies which sources are included in this group. Possible values are: `mailbox`, `site`.|
### [userSource ](https://docs.microsoft.com/graph/api/resources/security-usersource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The user who created the **userSource**.|
|createdDateTime|DateTimeOffset|The date and time the **userSource** was created.|
|displayName|String|The display name associated with the mailbox and site.|
|email|String|Email address of the user's mailbox.|
|holdStatus|microsoft.graph.security.dataSourceHoldStatus|The hold status of the **userSource**. The possible values are: `notApplied`, `applied`, `applying`, `removing`, `partial`.|
|id|String|The ID of the **userSource**. This isn't the ID of the actual group.|
|includedSources|microsoft.graph.security.sourceType|Specifies which sources are included in this group. Possible values are: `mailbox`, `site`.|
|siteWebUrl|String|The URL of the user's OneDrive for Business site. Read-only.|
