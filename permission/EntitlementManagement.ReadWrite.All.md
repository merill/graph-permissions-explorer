# EntitlementManagement.ReadWrite.All

> Allows the app to request access to and management of access packages and related entitlement management resources on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{id}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{id}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/customAccessPackageWorkflowExtensions/{customAccessPackageWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackageCatalogs/{id}](https://docs.microsoft.com/graph/api/accesspackagecatalog-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{accessPackageId}](https://docs.microsoft.com/graph/api/accesspackage-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{id}](https://docs.microsoft.com/graph/api/accesspackage-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{id}/accessPackageResourceRoleScopes/{id}](https://docs.microsoft.com/graph/api/accesspackage-delete-accesspackageresourcerolescopes?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleAccessPackages/{id}/$ref](https://docs.microsoft.com/graph/api/accesspackage-delete-incompatibleaccesspackage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleGroups/{id}/$ref](https://docs.microsoft.com/graph/api/accesspackage-delete-incompatiblegroup?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/accessPackages/{id}/resourceRoleScopes/{id}](https://docs.microsoft.com/graph/api/accesspackage-delete-resourcerolescopes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/assignmentPolicies/{accessPackageAssignmentPolicyId}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/assignmentRequests/{accessPackageAssignmentRequestId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/catalogs/{accessPackageCatalogId}](https://docs.microsoft.com/graph/api/accesspackagecatalog-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions/{customAccessPackageWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/connectedOrganizations/{connectedOrganizationId}](https://docs.microsoft.com/graph/api/connectedorganization-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/connectedOrganizations/{connectedOrganizationId}/externalSponsors/{id}/$ref](https://docs.microsoft.com/graph/api/connectedorganization-delete-externalsponsors?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/entitlementManagement/connectedOrganizations/{connectedOrganizationId}/internalSponsors/{id}/$ref](https://docs.microsoft.com/graph/api/connectedorganization-delete-internalsponsors?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/entitlementManagement/connectedOrganizations/{id}](https://docs.microsoft.com/graph/api/connectedorganization-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{accessPackageAssignmentRequestId}](https://docs.microsoft.com/graph/api/approval-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{accessPackageAssignmentRequestId}/stages](https://docs.microsoft.com/graph/api/approval-list-stages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{accessPackageAssignmentRequestId}/stages/{approvalStageId}](https://docs.microsoft.com/graph/api/approvalstage-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{id}](https://docs.microsoft.com/graph/api/approval-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{id}/steps](https://docs.microsoft.com/graph/api/approval-list-steps?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{id}/steps/{id}](https://docs.microsoft.com/graph/api/approvalstep-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/filterByCurrentUser(on='approver')](https://docs.microsoft.com/graph/api/approval-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageassignmentpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{id}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageassignmentrequests?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{id}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentResourceRoles](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageassignmentresourceroles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignmentResourceRoles/{id}](https://docs.microsoft.com/graph/api/accesspackageassignmentresourcerole-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageAssignments](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageassignments?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignments/additionalAccess(accessPackageId='parameterValue',incompatibleAccessPackageId='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignment-additionalaccess?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /identityGovernance/entitlementManagement/accessPackageAssignments/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignment-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackagecatalogs?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/accessPackageCustomWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-accesspackagecustomworkflowextensions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/accessPackageCustomWorkflowExtensions/{accessPackageCustomWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/accessPackageResourceRoles?$filter=(originSystem+eq+%27{originSystemType}%27+and+accessPackageResource/id+eq+%27{resourceId}%27)&$expand=accessPackageResource](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-accesspackageresourceroles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/customAccessPackageWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-customaccesspackageworkflowextensions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/customAccessPackageWorkflowExtensions/{customAccessPackageWorkflowExtensionId}](https://docs.microsoft.com/graph/api/customaccesspackageworkflowextension-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{id}](https://docs.microsoft.com/graph/api/accesspackagecatalog-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{id}/accessPackageResources](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-accesspackageresources?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageResourceEnvironments/{accessPackageResourceEnvironmentId}](https://docs.microsoft.com/graph/api/accesspackageresourceenvironment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackageResourceRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageresourcerequests?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{accessPackageId}](https://docs.microsoft.com/graph/api/accesspackage-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}](https://docs.microsoft.com/graph/api/accesspackage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}?$expand=accessPackageResourceRoleScopes($expand=accessPackageResourceRole,accessPackageResourceScope)](https://docs.microsoft.com/graph/api/accesspackage-list-accesspackageresourcerolescopes?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}?$expand=resourceRoleScopes($expand=role,scope)](https://docs.microsoft.com/graph/api/accesspackage-list-resourcerolescopes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}/accessPackagesIncompatibleWith](https://docs.microsoft.com/graph/api/accesspackage-list-accesspackagesincompatiblewith?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleAccessPackages](https://docs.microsoft.com/graph/api/accesspackage-list-incompatibleaccesspackages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleGroups](https://docs.microsoft.com/graph/api/accesspackage-list-incompatiblegroups?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/accessPackages/filterByCurrentUser(on='allowedRequestor')](https://docs.microsoft.com/graph/api/accesspackage-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignmentPolicies](https://docs.microsoft.com/graph/api/entitlementmanagement-list-assignmentpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignmentPolicies/{accessPackageAssignmentPolicyId}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignmentRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-list-assignmentrequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignmentRequests/{accessPackageAssignmentRequestId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/assignmentRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignments](https://docs.microsoft.com/graph/api/entitlementmanagement-list-assignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignments/{accessPackageAssignmentId}](https://docs.microsoft.com/graph/api/accesspackageassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/assignments/additionalAccess(accessPackageId='parameterValue',incompatibleAccessPackageId='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignment-additionalaccess?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/entitlementManagement/assignments/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/accesspackageassignment-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs](https://docs.microsoft.com/graph/api/entitlementmanagement-list-catalogs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs/{accessPackageCatalogId}](https://docs.microsoft.com/graph/api/accesspackagecatalog-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-accesspackagecustomworkflowextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions/{accessPackageCustomWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs/{catalogId}/resourceRoles?$filter=(originSystem+eq+%27{originSystemType}%27+and+resource/id+eq+%27{resourceId}%27)&$expand=resource](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-resourceroles?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/catalogs/{id}/resources](https://docs.microsoft.com/graph/api/accesspackagecatalog-list-resources?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/connectedOrganizations](https://docs.microsoft.com/graph/api/entitlementmanagement-list-connectedorganizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/connectedOrganizations/{connectedOrganizationId}](https://docs.microsoft.com/graph/api/connectedorganization-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/connectedOrganizations/{id}](https://docs.microsoft.com/graph/api/connectedorganization-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/connectedOrganizations/{id}/externalSponsors](https://docs.microsoft.com/graph/api/connectedorganization-list-externalsponsors?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/connectedOrganizations/{id}/internalSponsors](https://docs.microsoft.com/graph/api/connectedorganization-list-internalsponsors?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/resourceRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-list-resourcerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/entitlementManagement/settings](https://docs.microsoft.com/graph/api/entitlementmanagementsettings-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/entitlementManagement/subjects(objectId='{objectIdOfUser}')](https://docs.microsoft.com/graph/api/accesspackagesubject-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET identityGovernance/entitlementManagement/accessPackageResourceEnvironments?$filter=originSystem eq 'SharePointOnline'](https://docs.microsoft.com/graph/api/entitlementmanagement-list-accesspackageresourceenvironment?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET identityGovernance/entitlementManagement/resourceEnvironments?$filter=originSystem eq 'SharePointOnline'](https://docs.microsoft.com/graph/api/entitlementmanagement-list-resourceenvironments?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{accessPackageAssignmentRequestId}/stages/{approvalStageId}](https://docs.microsoft.com/graph/api/approvalstage-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /identityGovernance/entitlementManagement/accessPackageAssignmentApprovals/{id}/steps/{id}](https://docs.microsoft.com/graph/api/approvalstep-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /identityGovernance/entitlementManagement/accessPackageCatalogs/{accessPackageCatalogId}](https://docs.microsoft.com/graph/api/accesspackagecatalog-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/entitlementManagement/accessPackages/{accessPackageId}](https://docs.microsoft.com/graph/api/accesspackage-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/entitlementManagement/catalogs/{accessPackageCatalogId}](https://docs.microsoft.com/graph/api/accesspackagecatalog-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/entitlementManagement/connectedOrganizations/{connectedOrganizationId}](https://docs.microsoft.com/graph/api/connectedorganization-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identityGovernance/entitlementManagement/connectedOrganizations/{id}](https://docs.microsoft.com/graph/api/connectedorganization-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/entitlementManagement/settings](https://docs.microsoft.com/graph/api/entitlementmanagementsettings-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identityGovernance/entitlementManagement/subjects(objectId='{objectIdOfUser}')](https://docs.microsoft.com/graph/api/accesspackagesubject-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies](https://docs.microsoft.com/graph/api/entitlementmanagement-post-accesspackageassignmentpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageAssignmentRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-post-accesspackageassignmentrequests?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{accessPackageAssignmentRequestId}/resume](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-resume?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{id}/cancel](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-cancel?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{id}/reprocess](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-reprocess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageAssignments/{id}/reprocess ](https://docs.microsoft.com/graph/api/accesspackageassignment-reprocess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageCatalogs](https://docs.microsoft.com/graph/api/entitlementmanagement-post-accesspackagecatalogs?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageCatalogs/{accessPackageCatalogId}/accessPackageResources/{accessPackageResourceId}/refresh](https://docs.microsoft.com/graph/api/accesspackageresource-refresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/accessPackageCustomWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-post-accesspackagecustomworkflowextensions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/customAccessPackageWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-post-customaccesspackageworkflowextensions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackageResourceRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-post-accesspackageresourcerequests?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/accessPackages](https://docs.microsoft.com/graph/api/entitlementmanagement-post-accesspackages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /identityGovernance/entitlementManagement/accessPackages/{accessPackageId}/getApplicablePolicyRequirements](https://docs.microsoft.com/graph/api/accesspackage-getapplicablepolicyrequirements?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackages/{accessPackageId}/moveToCatalog](https://docs.microsoft.com/graph/api/accesspackage-movetocatalog?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/entitlementManagement/accessPackages/{id}/accessPackageResourceRoleScopes](https://docs.microsoft.com/graph/api/accesspackage-post-accesspackageresourcerolescopes?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /identityGovernance/entitlementManagement/accessPackages/{id}/getApplicablePolicyRequirements](https://docs.microsoft.com/graph/api/accesspackage-getapplicablepolicyrequirements?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleAccessPackages/$ref](https://docs.microsoft.com/graph/api/accesspackage-post-incompatibleaccesspackage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/accessPackages/{id}/incompatibleGroups/$ref](https://docs.microsoft.com/graph/api/accesspackage-post-incompatiblegroup?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/accessPackages/{id}/resourceRoleScopes](https://docs.microsoft.com/graph/api/accesspackage-post-resourcerolescopes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/assignmentPolicies](https://docs.microsoft.com/graph/api/entitlementmanagement-post-assignmentpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/assignmentRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-post-assignmentrequests?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /identityGovernance/entitlementManagement/assignmentRequests/{accessPackageAssignmentRequestId}/cancel](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/assignmentRequests/{accessPackageAssignmentRequestId}/resume](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-resume?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/assignmentRequests/{id}/reprocess](https://docs.microsoft.com/graph/api/accesspackageassignmentrequest-reprocess?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/assignments/{id}/reprocess ](https://docs.microsoft.com/graph/api/accesspackageassignment-reprocess?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/catalogs](https://docs.microsoft.com/graph/api/entitlementmanagement-post-catalogs?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-post-accesspackagecustomworkflowextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/connectedOrganizations](https://docs.microsoft.com/graph/api/entitlementmanagement-post-connectedorganizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/connectedOrganizations/{id}/externalSponsors/$ref](https://docs.microsoft.com/graph/api/connectedorganization-post-externalsponsors?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/connectedOrganizations/{id}/internalSponsors/$ref](https://docs.microsoft.com/graph/api/connectedorganization-post-internalsponsors?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/entitlementManagement/resourceRequests](https://docs.microsoft.com/graph/api/entitlementmanagement-post-resourcerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-post-roleassignments?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /identityGovernance/entitlementManagement/accessPackageCatalogs/{catalogId}/customAccessPackageWorkflowExtensions/{customAccessPackageWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /identityGovernance/entitlementManagement/assignmentPolicies/{accessPackageAssignmentPolicyId}](https://docs.microsoft.com/graph/api/accesspackageassignmentpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions/{customAccessPackageWorkflowExtensionId}](https://docs.microsoft.com/graph/api/accesspackageassignmentrequestworkflowextension-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ae7a573d-81d7-432b-ad44-4ed5c9d89038|
|**Consent Type**|Admin|
|**Display String**|Read and write entitlement management resources|
|**Description**|Allows the app to request access to and management of access packages and related entitlement management resources on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9acd699f-1e81-4958-b001-93b1d2506e19|
|**Display String**|Read and write all entitlement management resources|
|**Description**|Allows the app to read and write access packages and related entitlement management resources without a signed-in user.|
## Resources
### [accessPackage ](https://docs.microsoft.com/graph/api/resources/accesspackage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|The description of the access package.|
|displayName|String|Required. The display name of the access package. Supports $filter (`eq`, `contains`).|
|id|String|Read-only.|
|isHidden|Boolean|Indicates whether the access package is hidden from the requestor.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
### [accessPackageAssignment ](https://docs.microsoft.com/graph/api/resources/accesspackageassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|customExtensionCalloutInstances|customExtensionCalloutInstance collection|Information about all the custom extension calls that were made during the access package assignment workflow.|
|expiredDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|id|String|Read-only.|
|schedule|entitlementManagementSchedule|When the access assignment is to be in place. Read-only.|
|state|accessPackageAssignmentState|The state of the access package assignment. The possible values are: `delivering`, `partiallyDelivered`, `delivered`, `expired`, `deliveryFailed`, `unknownFutureValue`. Read-only. Supports `$filter` (`eq`).|
|status|String|More information about the assignment lifecycle. Possible values include `Delivering`, `Delivered`, `NearExpiry1DayNotificationTriggered`, or `ExpiredNotificationTriggered`. Read-only.|
### [accesspackageassignment-accesspackageassignmentfilterbycurrentuseroptions](https://docs.microsoft.com/graph/api/resources/accesspackageassignment-accesspackageassignmentfilterbycurrentuseroptions?view=graph-rest-1.0&tabs=http)

### [accesspackageassignmentapprovalsettings](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentapprovalsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isApprovalRequiredForAdd|Boolean|If `false,` then approval isn't required for new requests in this policy.|
|isApprovalRequiredForUpdate|Boolean|If `false`, then approval isn't required for updates to requests in this policy.|
|stages|accessPackageApprovalStage collection|If approval is required, the one, two or three elements of this collection define each of the stages of approval. An empty array is present if no approval is required.|
### [accessPackageAssignmentPolicy ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedTargetScope|allowedTargetScope|Principals that can be assigned the access package through this policy. The possible values are: `notSpecified`, `specificDirectoryUsers`, `specificConnectedOrganizationUsers`, `specificDirectoryServicePrincipals`, `allMemberUsers`, `allDirectoryUsers`, `allDirectoryServicePrincipals`, `allConfiguredConnectedOrganizationUsers`, `allExternalUsers`, `unknownFutureValue`.|
|automaticRequestSettings|accessPackageAutomaticRequestSettings|This property is only present for an auto assignment policy; if absent, this is a request-based policy.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|The description of the policy.|
|displayName|String|The display name of the policy.|
|expiration|expirationPattern|The expiration date for assignments created in this policy.|
|id|String|Read only.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|requestApprovalSettings|accessPackageAssignmentApprovalSettings|Specifies the settings for approval of requests for an access package assignment through this policy. For example, if approval is required for new requests.|
|requestorSettings|accessPackageAssignmentRequestorSettings|Provides additional settings to select who can create a request for an access package assignment through this policy, and what they can include in their request.|
|reviewSettings|accessPackageAssignmentReviewSettings|Settings for access reviews of assignments through this policy.|
|specificAllowedTargets|subjectSet collection|The principals that can be assigned access from an access package through this policy.|
### [accessPackageAssignmentRequest ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|answers|accessPackageAnswer collection|Answers provided by the requestor to accessPackageQuestions asked of them at the time of request.|
|completedDateTime|DateTimeOffset|The date of the end of processing, either successful or failure, of a request. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|customExtensionCalloutInstances|customExtensionCalloutInstance collection|Information about all the custom extension calls that were made during the access package assignment workflow.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Supports `$filter`.|
|id|String|Read-only.|
|requestType|accessPackageRequestType|The type of the request. The possible values are: `notSpecified`, `userAdd`, `UserExtend`, `userUpdate`, `userRemove`, `adminAdd`, `adminUpdate`, `adminRemove`, `systemAdd`, `systemUpdate`, `systemRemove`, `onBehalfAdd` (not supported), `unknownFutureValue`. Requests from the user have a **requestType** of `userAdd`, `userUpdate`, or `userRemove`. This property can't be changed once set.|
|schedule|entitlementManagementSchedule|The range of dates that access is to be assigned to the requestor. This property can't be changed once set.|
|state|accessPackageRequestState|The state of the request. The possible values are: `submitted`, `pendingApproval`, `delivering`, `delivered`, `deliveryFailed`, `denied`, `scheduled`, `canceled`, `partiallyDelivered`, `unknownFutureValue`. Read-only. Supports `$filter` (`eq`). |
|status|String|More information on the request processing status. Read-only.|
### [accesspackageassignmentrequest-accesspackageassignmentrequestfilterbycurrentuseroptions](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequest-accesspackageassignmentrequestfilterbycurrentuseroptions?view=graph-rest-1.0&tabs=http)

### [accessPackageAssignmentRequestCallbackData ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequestcallbackdata?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|customExtensionStageInstanceId|String|Unique identifier of the callout to the custom extension.|
|customExtensionStageInstanceDetail|String|Details for the callback.|
|stage|accessPackageCustomExtensionStage|Indicates the stage at which the custom callout extension is executed. The possible values are: `assignmentRequestCreated`, `assignmentRequestApproved`, `assignmentRequestGranted`, `assignmentRequestRemoved`, `assignmentFourteenDaysBeforeExpiration`, `assignmentOneDayBeforeExpiration`, `unknownFutureValue`.|
|state|accessPackageRequestState|Allow the extension to be able to deny or cancel the request submitted by the requestor. The supported values are `Denied` and `Canceled`. This property can only be set for an `assignmentRequestCreated` stage.|
### [accessPackageAssignmentRequestorSettings ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequestorsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowCustomAssignmentSchedule|Boolean|`False` indicates that the requestor isn't permitted to include a schedule in their request.|
|enableOnBehalfRequestorsToAddAccess|Boolean|`True` allows on-behalf-of requestors to create a request to add access for another principal.|
|enableOnBehalfRequestorsToRemoveAccess|Boolean|`True` allows on-behalf-of requestors to create a request to remove access for another principal.|
|enableOnBehalfRequestorsToUpdateAccess|Boolean|`True` allows on-behalf-of requestors to create a request to update access for another principal.|
|enableTargetsToSelfAddAccess|Boolean|`True` allows requestors to create a request to add access for themselves.|
|enableTargetsToSelfRemoveAccess|Boolean|`True` allows requestors to create a request to remove their access.|
|enableTargetsToSelfUpdateAccess|Boolean|`True` allows requestors to create a request to update their access.|
|onBehalfRequestors|subjectSet collection|The principals who can request on-behalf-of others.|
### [accessPackageAssignmentRequestRequirements ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequestrequirements?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowCustomAssignmentSchedule|Boolean|Indicates whether the requestor is allowed to set a custom schedule.|
|isApprovalRequiredForAdd|Boolean|Indicates whether a request to add must be approved by an approver.|
|isApprovalRequiredForUpdate|Boolean|Indicates whether a request to update must be approved by an approver.|
|policyDescription|String|The description of the policy that the user is trying to request access using.|
|policyDisplayName|String|The display name of the policy that the user is trying to request access using.|
|policyId|String|The identifier of the policy that these requirements are associated with. This identifier can be used when creating a new assignment request.|
| questions | accessPackageQuestion collection | Questions that are configured on the policy. The questions can be required or optional; callers can determine whether a question is required or optional based on the **isRequired** property on **accessPackageQuestion**. |
|schedule|entitlementManagementSchedule|Schedule restrictions enforced, if any.|
### [accessPackageAssignmentRequestWorkflowExtension ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequestworkflowextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|callbackConfiguration|customExtensionCallbackConfiguration|The callback configuration for a custom extension.|
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|createdBy|String|The userPrincipalName of the user or identity of the subject that created this resource. Read-only.|
|createdDateTime|DateTimeOffset|When the object was created.|
|description|String|Description for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow. Inherited from customCalloutExtension.|
|id|String|Read-only.|
|lastModifiedBy|String|The userPrincipalName of the identity that last modified the object. |
|lastModifiedDateTime|DateTimeOffset|When the object was last modified.|
### [accessPackageAssignmentResourceRole ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentresourcerole?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| Read-only.|
|originId|String|A unique identifier relative to the origin system, corresponding to the originId property of the accessPackageResourceRole. |
|originSystem|String|The system where the role assignment is to be created or has been created for an access package assignment, such as `SharePointOnline`, `AadGroup`, or `AadApplication`, corresponding to the originSystem property of the accessPackageResourceRole.|
|status|String|The value is `PendingFulfillment` before the access package assignment is delivered to the origin system, and `Fulfilled` after the access package assignment is delivered to the origin system.|
### [accesspackageassignmentreviewsettings](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentreviewsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|expirationBehavior|accessReviewExpirationBehavior|The default decision to apply if the access is not reviewed. The possible values are: `keepAccess`, `removeAccess`, `acceptAccessRecommendation`, `unknownFutureValue`.|
|fallbackReviewers|subjectSet collection|This collection specifies the users who will be the fallback reviewers when the primary reviewers don't respond.|
|isEnabled|Boolean|If `true`, access reviews are required for assignments through this policy.|
|isRecommendationEnabled|Boolean|Specifies whether to display recommendations to the reviewer. The default value is `true`.|
|isReviewerJustificationRequired|Boolean|Specifies whether the reviewer must provide justification for the approval. The default value is `true`.|
|isSelfReview|Boolean|Specifies whether the principals can review their own assignments.|
|primaryReviewers|subjectSet collection|This collection specifies the users or group of users who will review the access package assignments.|
|schedule|entitlementManagementSchedule|When the first review should start and how often it should recur.|
### [accessPackageAssignmentWorkflowExtension ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentworkflowextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|callbackConfiguration|customExtensionCallbackConfiguration|The callback configuration for a custom extension.|
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app. The settings define how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|createdBy|String|The userPrincipalName of the user or identity of the subject that created this resource. Read-only.|
|createdDateTime|DateTimeOffset|When the entity was created.|
|description|String|Description for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow. Inherited from customCalloutExtension.|
|id|String|Read-only.|
|lastModifiedBy|String|The userPrincipalName of the identity that last modified the entity. |
|lastModifiedDateTime|DateTimeOffset|When the entity was last modified.|
### [accessPackageCatalog ](https://docs.microsoft.com/graph/api/resources/accesspackagecatalog?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|catalogType|accessPackageCatalogType|Whether the catalog is created by a user or entitlement management. The possible values are: `userManaged`, `serviceDefault`, `serviceManaged`, `unknownFutureValue`.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|The description of the access package catalog.|
|displayName|String|The display name of the access package catalog.|
|id|String|Read-only.|
|isExternallyVisible|Boolean|Whether the access packages in this catalog can be requested by users outside of the tenant.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
|state|accessPackageCatalogState|Has the value `published` if the access packages are available for management. The possible values are: `unpublished`, `published`, `unknownFutureValue`.|
### [accessPackageQuestion ](https://docs.microsoft.com/graph/api/resources/accesspackagequestion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String| ID of the question.|
|isAnswerEditable|Boolean| Specifies whether the requestor is allowed to edit answers to questions for an assignment by posting an update to accessPackageAssignmentRequest. |
|isRequired|Boolean| Whether the requestor is required to supply an answer or not.|
|localizations|accessPackageLocalizedText collection|The text of the question represented in a format for a specific locale.|
|text|String|The text of the question to show to the requestor.|
|sequence|Int32| Relative position of this question when displaying a list of questions to the requestor.|
### [accessPackageResource ](https://docs.microsoft.com/graph/api/resources/accesspackageresource?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|attributes|accessPackageResourceAttribute collection|Contains information about the attributes to be collected from the requestor and sent to the resource application.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|A description for the resource.|
|displayName|String|The display name of the resource, such as the application name, group name or site name.|
|id|String| Read-only.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|originId|String|The unique identifier of the resource in the origin system. For a Microsoft Entra group, this is the identifier of the group. |
|originSystem|String|The type of the resource in the origin system, such as `SharePointOnline`, `AadApplication` or `AadGroup`.|
### [accessPackageResourceEnvironment ](https://docs.microsoft.com/graph/api/resources/accesspackageresourceenvironment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|connectionInfo|connectionInfo|Connection information of an environment used to connect to a resource. |
|createdDateTime|DateTimeOffset|The date and time that this object was created. <br>The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|The description of this object.|
|displayName|String|The display name of this object.|
|id|String|The system-assigned unique identifier of the object.|
|isDefaultEnvironment|Boolean|Determines whether this is default environment or not. It is set to `true` for all static origin systems, such as Microsoft Entra groups and Microsoft Entra Applications.|
|modifiedDateTime|DateTimeOffset|The date and time that this object was last modified. <br>The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|originId|String|The unique identifier of this environment in the origin system.|
|originSystem|String|The type of the resource in the origin system, that is, `SharePointOnline`. Requires `$filter` (`eq`).|
### [accessPackageResourceRequest ](https://docs.microsoft.com/graph/api/resources/accesspackageresourcerequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|id|String| Read-only.|
|requestType|accessPackageRequestType|The type of the request. Use `adminAdd` to add a resource, if the caller is an administrator or resource owner, `adminUpdate` to update a resource, or `adminRemove` to remove a resource. |
|state|accessPackageRequestState| The outcome of whether the service was able to add the resource to the catalog. The value is `delivered` if the resource was added or removed, and `deliveryFailed` if it couldn't be added or removed. Read-only.|
### [accessPackageResourceRole ](https://docs.microsoft.com/graph/api/resources/accesspackageresourcerole?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String|A description for the resource role.|
|displayName|String|The display name of the resource role such as the role defined by the application.|
|id|String| Read-only.|
|originId|String|The unique identifier of the resource role in the origin system. For a SharePoint Online site, the originId is the sequence number of the role in the site. |
|originSystem|String|The type of the resource in the origin system, such as `SharePointOnline`, `AadApplication`, or `AadGroup`.|
### [accessPackageResourceRoleScope ](https://docs.microsoft.com/graph/api/resources/accesspackageresourcerolescope?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|id|String| Read-only.|
### [accessPackageResourceScope ](https://docs.microsoft.com/graph/api/resources/accesspackageresourcescope?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String|The description of the scope.|
|displayName|String|The display name of the scope.|
|id|String| Read-only.|
|isRootScope|Boolean|True if the scopes are arranged in a hierarchy and this is the top or root scope of the resource.|
|originId|String|The unique identifier for the scope in the resource as defined in the origin system.|
|originSystem|String|The origin system for the scope.|
### [accessPackageSubject ](https://docs.microsoft.com/graph/api/resources/accesspackagesubject?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the subject.|
|email|String|The email address of the subject.|
|id|String|Read-only.|
|objectId|String|The object identifier of the subject. `null` if the subject isn't yet a user in the tenant.|
|onPremisesSecurityIdentifier|String|A string representation of the principal's security identifier, if known, or `null` if the subject doesn't have a security identifier.|
|principalName|String|The principal name, if known, of the subject.|
|subjectType|accessPackageSubjectType|The resource type of the subject. The possible values are: `notSpecified`, `user`, `servicePrincipal`, `unknownFutureValue`.|
### [approval ](https://docs.microsoft.com/graph/api/resources/approval?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier of the approval decision. <br/><li>In PIM for groups, it's the same identifier as the identifier of the assignment schedule request.|
### [approvalSettings ](https://docs.microsoft.com/graph/api/resources/approvalsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|approvalMode|String|One of `SingleStage`, `Serial`, `Parallel`, `NoApproval` (default). `NoApproval` is used when `isApprovalRequired` is `false`.|
|approvalStages|unifiedApprovalStage collection|If approval is required, the one or two elements of this collection define each of the stages of approval. An empty array if no approval is required.|
|isApprovalRequired|Boolean|Indicates whether approval is required for requests in this policy.|
|isApprovalRequiredForExtension|Boolean|Indicates whether approval is required for a user to extend their assignment.|
|isRequestorJustificationRequired|Boolean|Indicates whether the requestor is required to supply a justification in their request.|
### [approvalStage ](https://docs.microsoft.com/graph/api/resources/approvalstage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignedToMe|Boolean|Indicates whether the stage is assigned to the calling user to review. Read-only.|
|displayName|String|The label provided by the policy creator to identify an approval stage. Read-only.|
|id|String|The identifier of the stage associated with an approval object. Read-only.|
|justification|String|The justification associated with the approval stage decision.|
|reviewResult|String|The result of this approval record. Possible values include: `NotReviewed`, `Approved`, `Denied`.|
|reviewedBy|identity | The identifier of the reviewer. `00000000-0000-0000-0000-000000000000` if the assigned reviewer hasn't reviewed. Read-only.|
|reviewedDateTime|DateTimeOffset|The date and time when a decision was recorded. The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|status|String|The stage status. Possible values: `InProgress`, `Initializing`, `Completed`, `Expired`. Read-only.|
### [approvalStep ](https://docs.microsoft.com/graph/api/resources/approvalstep?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignedToMe|Boolean|Indicates whether the step is assigned to the calling user to review. Read-only.|
|displayName|String|The label provided by the policy creator to identify an approval step. Read-only.|
|id|String|The identifier of the step associated with an approval object. Read-only.|
|justification|String|The justification associated with the approval step decision.|
|reviewResult|String|The result of this approval record. Possible values include: `NotReviewed`, `Approved`, `Denied`.|
|reviewedBy|userIdentity collection | The identifier of the reviewer. `00000000-0000-0000-0000-000000000000` if the assigned reviewer hasn't reviewed. Read-only.|
|reviewedDateTime|DateTimeOffset|The date and time when a decision was recorded. The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|status|String|The step status. Possible values: `InProgress`, `Initializing`, `Completed`, `Expired`. Read-only.|
### [assignmentReviewSettings ](https://docs.microsoft.com/graph/api/resources/assignmentreviewsettings?view=graph-rest-1.0&tabs=http)
| Property                     | Type                      | Description |
| :--------------------------- | :------------------------ | :---------- |
| accessReviewTimeoutBehavior | accessReviewTimeoutBehavior | The default decision to apply if the request isn't reviewed within the period specified in **durationInDays**. The possible values are: `acceptAccessRecommendation`, `keepAccess`, `removeAccess`, and `unknownFutureValue`. |
| durationInDays | Int32 | The number of days within which reviewers should provide input.|
| isAccessRecommendationEnabled | Boolean | Specifies whether to display recommendations to the reviewer. The default value is `true` |
| isApprovalJustificationRequired | Boolean | Specifies whether the reviewer must provide justification for the approval. The default value is `true`. |
| isEnabled| Boolean | If true, access reviews are required for assignments from this policy. |
| recurrenceType | String | The interval for recurrence, such as `monthly` or `quarterly`. |
| reviewerType | String | Who should be asked to do the review, either `Self`, `Reviewers` or `Manager`. |
| reviewers | userSet collection | If the reviewerType is `Reviewers`, this collection specifies the users who will be reviewers, either by ID or as members of a group, using a collection of singleUser and groupMembers. |
| startDateTime | DateTimeOffset | When the first review should start. |
### [azureActiveDirectoryTenant ](https://docs.microsoft.com/graph/api/resources/azureactivedirectorytenant?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the Microsoft Entra tenant. Read only. |
|tenantId|String|The ID of the Microsoft Entra tenant. Read only. |
### [connectedOrganization ](https://docs.microsoft.com/graph/api/resources/connectedorganization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|The description of the connected organization.|
|displayName|String|The display name of the connected organization. Supports `$filter` (`eq`).|
|id|String|Read-only.|
|identitySources|identitySource collection|The identity sources in this connected organization, one of azureActiveDirectoryTenant, crossCloudAzureActiveDirectoryTenant, domainIdentitySource, externalDomainFederation, or socialIdentitySource. Nullable.|
|modifiedDateTime|DateTimeOffset|*The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|state|connectedOrganizationState|The state of a connected organization defines whether assignment policies with requestor scope type `AllConfiguredConnectedOrganizationSubjects` are applicable or not.  The possible values are: `configured`, `proposed`, `unknownFutureValue`.|
### [customaccesspackageworkflowextension](https://docs.microsoft.com/graph/api/resources/customaccesspackageworkflowextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|createdDateTime|DateTimeOffset|Represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|Description for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension. Read only.|
|displayName|String|Display name for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension. Read only. Supports `$filter` (`contains`).|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow. Inherited from customCalloutExtension.|  
|id|String|Identifier for the customAccessPackageWorkflowExtension object. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|Represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
### [customCalloutExtension ](https://docs.microsoft.com/graph/api/resources/customcalloutextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. |
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed.|
|description|String|Description for the customCalloutExtension object.|
|displayName|String|Display name for the customCalloutExtension object.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow.|
|id|String|Identifier for the customCalloutExtension object. Inherited from entity.|
### [customExtensionAuthenticationConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionauthenticationconfiguration?view=graph-rest-1.0&tabs=http)

### [customExtensionCallbackConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensioncallbackconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|timeoutDuration|Duration|The maximum duration in ISO 8601 format that Microsoft Entra ID will wait for a resume action for the callout it sent to the logic app. The valid range for custom extensions in lifecycle workflows is five minutes to three hours. The valid range for custom extensions in entitlement management is between 5 minutes and 14 days. For example, `PT3H` refers to three hours, `P3D` refers to three days, `PT10M` refers to ten minutes.|
### [customExtensionEndpointConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionendpointconfiguration?view=graph-rest-1.0&tabs=http)

### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [domainIdentitySource ](https://docs.microsoft.com/graph/api/resources/domainidentitysource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the identity source, typically also the domain name. Read only. |
|domainName|String|The domain name. Read only. |
### [entitlementmanagement-overview](https://docs.microsoft.com/graph/api/resources/entitlementmanagement-overview?view=graph-rest-1.0&tabs=http)

### [entitlementManagementSettings ](https://docs.microsoft.com/graph/api/resources/entitlementmanagementsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|durationUntilExternalUserDeletedAfterBlocked|Duration|If **externalUserLifecycleAction** is `blockSignInAndDelete`, the duration, typically many days, after an external user is blocked from sign in before their account is deleted.|
|externalUserLifecycleAction|accessPackageExternalUserLifecycleAction|Automatic action that the service should take when an external user's last access package assignment is removed. The possible values are: `none`, `blockSignIn`, `blockSignInAndDelete`, `unknownFutureValue`.|
|id|String|A constant. Read-only.|
### [expirationPattern ](https://docs.microsoft.com/graph/api/resources/expirationpattern?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|duration|Duration|The requestor's desired duration of access represented in ISO 8601 format for durations. For example, PT3H refers to three hours.  If specified in a request, **endDateTime** should not be present and the **type** property should be set to `afterDuration`.|
|endDateTime|DateTimeOffset|Timestamp of date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|type|expirationPatternType|The requestor's desired expiration pattern type. The possible values are: `notSpecified`, `noExpiration`, `afterDateTime`, `afterDuration`. |
### [externalDomainFederation ](https://docs.microsoft.com/graph/api/resources/externaldomainfederation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the identity source, typically also the domain name. Read only. |
|domainName|String|The domain name. Read only. |
|issuerUri|String|The issuerURI of the incoming federation. Read only. |
### [externalsponsors](https://docs.microsoft.com/graph/api/resources/externalsponsors?view=graph-rest-1.0&tabs=http)

### [group ](https://docs.microsoft.com/graph/api/resources/group?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-|:-|:-|
| allowExternalSenders | Boolean | Indicates if people external to the organization can send messages to the group. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| assignedLabels | assignedLabel collection | The list of sensitivity label pairs (label ID, label name) associated with a Microsoft 365 group. <br><br>Returned only on `$select`. |
| assignedLicenses | assignedLicense collection | The licenses that are assigned to the group. <br><br>Returned only on `$select`. Supports `$filter` (`eq`).Read-only. |
| autoSubscribeNewMembers | Boolean | Indicates if new members added to the group are autosubscribed to receive email notifications. You can set this property in a PATCH request for the group; don't set it in the initial POST request that creates the group. Default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| classification | String | Describes a classification for the group (such as low, medium, or high business impact). Valid values for this property are defined by creating a ClassificationList setting value, based on the template definition.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| createdDateTime | DateTimeOffset | Timestamp of when the group was created. The value can't be modified and is automatically populated when the group is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. |
| deletedDateTime | DateTimeOffset | For some Microsoft Entra objects (user, group, application), if the object is deleted, it's first logically deleted, and this property is updated with the date and time when the object was deleted. Otherwise this property is `null`. If the object is restored, this property is updated to `null`. Inherited from directoryObject.  |
| description | String | An optional description for the group. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| displayName | String | The display name for the group. This property is required when a group is created and can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| expirationDateTime | DateTimeOffset | Timestamp of when the group is set to expire. It's `null` for security groups, but for Microsoft 365 groups, it represents when the group is set to expire as defined in the groupLifecyclePolicy. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| groupTypes | String collection | Specifies the group type and its membership. <br><br>If the collection contains `Unified`, the group is a Microsoft 365 group; otherwise, it's either a security group or a distribution group. For details, see groups overview.<br><br>If the collection includes `DynamicMembership`, the group has dynamic membership; otherwise, membership is static. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| hasMembersWithLicenseErrors | Boolean | Indicates whether there are members in this group that have license errors from its group-based license assignment. <br><br>This property is never returned on a GET operation. You can use it as a $filter argument to get groups that have members with license errors (that is, filter for this property being true). See an example. <br><br>Supports `$filter` (`eq`). |
| hideFromAddressLists | Boolean | True if the group isn't displayed in certain parts of the Outlook UI: the **Address Book**, address lists for selecting message recipients, and the **Browse Groups** dialog for searching groups; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| hideFromOutlookClients | Boolean | True if the group isn't displayed in Outlook clients, such as Outlook for Windows and Outlook on the web; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| id | String | The unique identifier for the group. <br><br>Returned by default. Inherited from directoryObject. Key. Not nullable. Read-only.<br><br>Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| isArchived | Boolean | When a group is associated with a team, this property determines whether the team is in read-only mode.<br/>To read this property, use the `/group/{groupId}/team` endpoint or the Get team API. To update this property, use the archiveTeam and unarchiveTeam APIs. |
| isAssignableToRole | Boolean | Indicates whether this group can be assigned to a Microsoft Entra role. Optional. <br><br>This property can only be set while creating the group and is immutable. If set to `true`, the **securityEnabled** property must also be set to `true`, **visibility** must be `Hidden`, and the group can't be a dynamic group (that is, **groupTypes** can't contain `DynamicMembership`). <br/><br/>Only callers with at least the Privileged Role Administrator role can set this property. The caller must also be assigned the _RoleManagement.ReadWrite.Directory_ permission to set this property or update the membership of such groups. For more, see Using a group to manage Microsoft Entra role assignments<br><br>Using this feature requires a Microsoft Entra ID P1 license. Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| isSubscribedByMail | Boolean | Indicates whether the signed-in user is subscribed to receive email conversations. The default value is `true`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| licenseProcessingState | String | Indicates the status of the group license assignment to all group members. The default value is `false`. Read-only. Possible values: `QueuedForProcessing`, `ProcessingInProgress`, and `ProcessingComplete`.<br><br>Returned only on `$select`. Read-only. |
| mail | String | The SMTP address for the group, for example, "serviceadmins@contoso.com". <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| mailEnabled | Boolean | Specifies whether the group is mail-enabled. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| mailNickname | String | The mail alias for the group, unique for Microsoft 365 groups in the organization. Maximum length is 64 characters. This property can contain only characters in the ASCII character set 0 - 127 except the following characters: ` @ () \ [] " ; : <> , SPACE`. <br><br>Required. Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| membershipRule | String | The rule that determines members for this group if the group is a dynamic group (groupTypes contains `DynamicMembership`). For more information about the syntax of the membership rule, see Membership Rules syntax. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| membershipRuleProcessingState | String | Indicates whether the dynamic membership processing is on or paused. Possible values are `On` or `Paused`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| onPremisesDomainName | String | Contains the on-premises **domain FQDN**, also called **dnsDomainName** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesLastSyncDateTime | DateTimeOffset | Indicates the last time at which the group was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
| onPremisesNetBiosName | String | Contains the on-premises **netBios name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | Errors when using Microsoft synchronization product during provisioning. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| onPremisesSamAccountName | String | Contains the on-premises **SAM account name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`). Read-only. |
| onPremisesSecurityIdentifier | String | Contains the on-premises security identifier (SID) for the group synchronized from on-premises to the cloud. Read-only. <br><br>Returned by default. Supports `$filter` (`eq` including on `null` values). |
| onPremisesSyncEnabled | Boolean | `true` if this group is synced from an on-premises directory; `false` if this group was originally synced from an on-premises directory but is no longer synced; **null** if this object has never synced from an on-premises directory (default). <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
| preferredDataLocation | String | The preferred data location for the Microsoft 365 group. By default, the group inherits the group creator's preferred data location. To set this property, the calling app must be granted the *Directory.ReadWrite.All* permission and the user be assigned at least one of the following Microsoft Entra roles: <br><ul>User Account Administrator <li>Directory Writer <li> Exchange Administrator <li> SharePoint Administrator </ul><br/> For more information about this property, see OneDrive Online Multi-Geo. <br><br>Nullable. Returned by default. |
| preferredLanguage | String | The preferred language for a Microsoft 365 group. Should follow ISO 639-1 Code; for example, `en-US`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| proxyAddresses | String collection | Email addresses for the group that direct to the same group mailbox. For example: `["SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. The **any** operator is required to filter expressions on multi-valued properties. <br><br>Returned by default. Read-only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`). |
| renewedDateTime | DateTimeOffset | Timestamp of when the group was last renewed. This value can't be modified directly and is only updated via the renew service action. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| securityEnabled | Boolean | Specifies whether the group is a security group. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| securityIdentifier | String | Security identifier of the group, used in Windows scenarios. Read-only. <br><br>Returned by default. |
| serviceProvisioningErrors | serviceProvisioningError collection | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a group object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance). |
| theme | string | Specifies a Microsoft 365 group's color theme. Possible values are `Teal`, `Purple`, `Green`, `Blue`, `Pink`, `Orange`, or `Red`. <br><br>Returned by default. |
| uniqueName | String | The unique identifier that can be assigned to a group and used as an alternate key. Immutable. Read-only. |
| unseenCount | Int32 | Count of conversations that received new posts since the signed-in user last visited the group. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| visibility | String | Specifies the group join policy and group content visibility for groups. Possible values are: `Private`, `Public`, or `HiddenMembership`. `HiddenMembership` can be set only for Microsoft 365 groups when the groups are created. It can't be updated later. Other values of visibility can be updated after group creation.<br> If visibility value isn't specified during group creation on Microsoft Graph, a security group is created as `Private` by default, and the Microsoft 365 group is `Public`. Groups assignable to roles are always `Private`. To learn more, see group visibility options. <br><br>Returned by default. Nullable. |
### [identitySource ](https://docs.microsoft.com/graph/api/resources/identitysource?view=graph-rest-1.0&tabs=http)

### [internalsponsors](https://docs.microsoft.com/graph/api/resources/internalsponsors?view=graph-rest-1.0&tabs=http)

### [privilegedAccessGroupAssignmentScheduleRequest ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupassignmentschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of a membership or ownership assignment relationship to the group. Required. The possible values are: `owner`, `member`, `unknownFutureValue`.|
|action|String|Represents the type of operation on the group membership or ownership assignment request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`. <br/><ul><li>`adminAssign`: For administrators to assign group membership or ownership to principals.</li><li>`adminRemove`: For administrators to remove principals from group membership or ownership.</li><li> `adminUpdate`: For administrators to change existing group membership or ownership assignments.</li><li>`adminExtend`: For administrators to extend expiring assignments.</li><li>`adminRenew`: For administrators to renew expired assignments.</li><li>`selfActivate`: For principals to activate their assignments.</li><li>`selfDeactivate`: For principals to deactivate their active assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request. Read-only.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|groupId|String|The identifier of the group representing the scope of the membership or ownership assignment through PIM for groups. Required.|
|id|String|The unique identifier for the **privilegedAccessGroupAssignmentScheduleRequest** object. Key, not nullable, Read-only. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when they create the **privilegedAccessGroupAssignmentScheduleRequest** object.|
|principalId|String|The identifier of the principal whose membership or ownership assignment to the group is managed through PIM for groups. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the group membership or ownership assignment. Recurring schedules are currently unsupported.|
|status|String|The status of the group membership or ownership assignment request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String| The identifier of the schedule that's created from the membership or ownership assignment request. Supports `$filter` (`eq`, `ne`).|
|ticketInfo|ticketInfo|Ticket details linked to the group membership or ownership assignment request including details of the ticket number and ticket system.|
### [privilegedidentitymanagement-for-groups-api-overview](https://docs.microsoft.com/graph/api/resources/privilegedidentitymanagement-for-groups-api-overview?view=graph-rest-1.0&tabs=http)

### [privilegedidentitymanagementv3-overview](https://docs.microsoft.com/graph/api/resources/privilegedidentitymanagementv3-overview?view=graph-rest-1.0&tabs=http)

### [requestorSettings ](https://docs.microsoft.com/graph/api/resources/requestorsettings?view=graph-rest-1.0&tabs=http)
| Property                     | Type                      | Description |
| :--------------------------- | :------------------------ | :---------- |
| scopeType |String |Who can request. One of `NoSubjects`, `SpecificDirectorySubjects`, `SpecificConnectedOrganizationSubjects`, `AllConfiguredConnectedOrganizationSubjects`, `AllExistingConnectedOrganizationSubjects`, `AllExistingDirectoryMemberUsers`, `AllExistingDirectorySubjects` or `AllExternalSubjects`.  |
| acceptRequests | Boolean | Indicates whether new requests are accepted on this policy. |
| allowedRequestors | userSet collection| The users who are allowed to request on this policy, which can be singleUser, groupMembers, and connectedOrganizationMembers. |
### [servicePrincipal ](https://docs.microsoft.com/graph/api/resources/serviceprincipal?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| accountEnabled |Boolean| `true` if the service principal account is enabled; otherwise, `false`. If set to `false`, then no users are able to sign in to this app, even if they're assigned to it. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| addIns | addIn collection | Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on.|
|alternativeNames|String collection| Used to retrieve service principals by subscription, identify resource group and full resource IDs for managed identities. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|appDescription|String|The description exposed by the associated application.|
|appDisplayName|String|The display name exposed by the associated application.|
|appId|String|The unique identifier for the associated application (its **appId** property). Alternate key. Supports `$filter` (`eq`, `ne`, `not`, `in`, `startsWith`).|
|applicationTemplateId|String|Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the service principal wasn't created from an application template.|
|appOwnerOrganizationId|Guid|Contains the tenant ID where the application is registered. This is applicable only to service principals backed by applications. Supports `$filter` (`eq`, `ne`, `NOT`, `ge`, `le`).|
|appRoleAssignmentRequired|Boolean|Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens. The default value is `false`. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `NOT`). |
|appRoles|appRole collection|The roles exposed by the application that's linked to this service principal. For more information, see the **appRoles** property definition on the application entity. Not nullable. |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). Filter value is case sensitive.|
| deletedDateTime | DateTimeOffset | The date and time the service principal was deleted. Read-only. |
| description | String | Free text field to provide an internal end-user facing description of the service principal. End-user portals such MyApps displays the application description in this field. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`).  |
|displayName|String|The display name for the service principal. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
|homepage|String|Home page or landing page of the application.|
|id|String|The unique identifier for the service principal. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| info | informationalUrl | Basic profile information of the acquired application such as app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values).  |
|keyCredentials|keyCredential collection|The collection of key credentials associated with the service principal. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`).            |
|loginUrl|String|Specifies the URL where the service provider redirects the user to Microsoft Entra ID to authenticate. Microsoft Entra ID uses the URL to launch the application from Microsoft 365 or the Microsoft Entra My Apps. When blank, Microsoft Entra ID performs IdP-initiated sign-on for applications configured with SAML-based single sign-on. The user launches the application from Microsoft 365, the Microsoft Entra My Apps, or the Microsoft Entra SSO URL.|
|logoutUrl|String| Specifies the URL that the Microsoft's authorization service uses to sign out a user using OpenID Connect front-channel, back-channel, or SAML sign out protocols.|
|notes|String|Free text field to capture information about the service principal, typically used for operational purposes. Maximum allowed size is 1,024 characters.|
|notificationEmailAddresses|String collection|Specifies the list of email addresses where Microsoft Entra ID sends a notification when the active certificate is near the expiration date. This is only for the certificates used to sign the SAML token issued for Microsoft Entra Gallery applications.|
|oauth2PermissionScopes|permissionScope collection|The delegated permissions exposed by the application. For more information, see the **oauth2PermissionScopes** property on the application entity's **api** property. Not nullable.|
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
|preferredSingleSignOnMode|string|Specifies the single sign-on mode configured for this application. Microsoft Entra ID uses the preferred single sign-on mode to launch the application from Microsoft 365 or the My Apps portal. The supported values are `password`, `saml`, `notSupported`, and `oidc`.|
|preferredTokenSigningKeyThumbprint|String|This property can be used on SAML applications (apps that have **preferredSingleSignOnMode** set to `saml`) to control which certificate is used to sign the SAML responses. For applications that aren't SAML, don't write or otherwise rely on this property.|
|replyUrls|String collection|The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application. Not nullable. |
|resourceSpecificApplicationPermissions|resourceSpecificPermission collection|The resource-specific application permissions exposed by this application. Currently, resource-specific permissions are only supported for Teams apps accessing to specific chats and teams using Microsoft Graph. Read-only.|
|samlSingleSignOnSettings|samlSingleSignOnSettings|The collection for settings related to saml single sign-on.|
|servicePrincipalNames|String collection|Contains the list of **identifiersUris**, copied over from the associated application. Additional values can be added to hybrid applications. These values can be used to identify the permissions exposed by this app within Microsoft Entra ID. For example,<ul><li>Client apps can specify a resource URI that is based on the values of this property to acquire an access token, which is the URI returned in the "aud" claim.</li></ul><br>The any operator is required for filter expressions on multi-valued properties. Not nullable. <br><br> Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|servicePrincipalType|String|Identifies whether the service principal represents an application, a managed identity, or a legacy application. This is set by Microsoft Entra ID internally. The **servicePrincipalType** property can be set to three different values: <ul><li>__Application__ - A service principal that represents an application or service. The **appId** property identifies the associated app registration, and matches the **appId** of an application, possibly from a different tenant. If the associated app registration is missing, tokens aren't issued for the service principal.</li><li>__ManagedIdentity__ - A service principal that represents a managed identity. Service principals representing managed identities can be granted access and permissions, but can't be updated or modified directly.</li><li>__Legacy__ - A service principal that represents an app created before app registrations, or through legacy experiences. A legacy service principal can have credentials, service principal names, reply URLs, and other properties that are editable by an authorized user, but doesn't have an associated app registration. The **appId** value doesn't associate the service principal with an app registration. The service principal can only be used in the tenant where it was created.</li><li>__SocialIdp__ - For internal use. </ul>|
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. Read-only. <br><br>Supported values are:<ul><li>`AzureADMyOrg`: Users with a Microsoft work or school account in my organization's Microsoft Entra tenant (single-tenant).</li><li>`AzureADMultipleOrgs`: Users with a Microsoft work or school account in any organization's Microsoft Entra tenant (multitenant).</li><li>`AzureADandPersonalMicrosoftAccount`: Users with a personal Microsoft account, or a work or school account in any organization's Microsoft Entra tenant.</li><li>`PersonalMicrosoftAccount`: Users with a personal Microsoft account only.</li></ul> |
|tags|String collection| Custom strings that can be used to categorize and identify the service principal. Not nullable. The value is the union of strings set here and on the associated application entity's **tags** property.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID issues tokens for this application encrypted using the key specified by this property. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application that's linked to this service principal.

### [site ](https://docs.microsoft.com/graph/api/resources/site?view=graph-rest-1.0&tabs=http)
| Property            | Type                                | Description                                                                                    |
| :----------------------- | :---------------------------------- | :--------------------------------------------------------------------------------------------- |
| **createdDateTime**      | DateTimeOffset                      | The date and time the item was created. Read-only.                                             |
| **description**          | string                              | The descriptive text for the site.                                                             |
| **displayName**          | string                              | The full title for the site. Read-only.                                                        |
| **eTag**                 | string                              | ETag for the item. Read-only.                                                                  |
| **id**                   | string                              | The unique identifier of the item. Read-only.                                                  |
| **isPersonalSite**       | bool                                | Identifies whether the site is personal or not. Read-only.                                                  |
| **lastModifiedDateTime** | DateTimeOffset                      | The date and time the item was last modified. Read-only.                                       |
| **name**                 | string                              | The name/title of the item.                                                                  |
| **root**                 | root                     | If present, provides the root site in the site collection. Read-only.            |
| **sharepointIds**        | sharepointIds   | Returns identifiers useful for SharePoint REST compatibility. Read-only.                       |
| **siteCollection**       | siteCollection | Provides details about the site's site collection. Available only on the root site. Read-only. |
| **webUrl**               | string (url)                        | URL that displays the item in the browser. Read-only.                                          |
### [subjectset](https://docs.microsoft.com/graph/api/resources/subjectset?view=graph-rest-1.0&tabs=http)

### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
### [unifiedRoleAssignmentScheduleRequest ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|String|Represents the type of the operation on the role assignment request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`, `selfExtend`, `selfRenew`, `unknownFutureValue`. <br/><ul><li>`adminAssign`: For administrators to assign roles to principals.</li><li>`adminRemove`: For administrators to remove principals from roles.</li><li> `adminUpdate`: For administrators to change existing role assignments.</li><li>`adminExtend`: For administrators to extend expiring assignments.</li><li>`adminRenew`: For administrators to renew expired assignments.</li><li>`selfActivate`: For principals to activate their assignments.</li><li>`selfDeactivate`: For principals to deactivate their active assignments.</li><li>`selfExtend`: For principals to request to extend their expiring assignments.</li><li>`selfRenew`: For principals to request to renew their expired assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|appScopeId|String|Identifier of the app-specific scope when the assignment is scoped to an app. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request. Read-only.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|id|String|The unique identifier for the **unifiedRoleAssignmentScheduleRequest** object. Key, not nullable, Read-only. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when create they create the **unifiedRoleAssignmentScheduleRequest** object.|
|principalId|String|Identifier of the principal that has been granted the assignment. Can be a user, role-assignable group, or a service principal. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the role assignment. Recurring schedules are currently unsupported.|
|status|String|The status of the role assignment request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String|Identifier of the schedule object that's linked to the assignment request. Supports `$filter` (`eq`, `ne`).|
|ticketInfo|ticketInfo|Ticket details linked to the role assignment request including details of the ticket number and ticket system.|
### [unifiedRoleDefinition ](https://docs.microsoft.com/graph/api/resources/unifiedroledefinition?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| The description for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. |
|displayName|String| The display name for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. Required.  Supports $filter (`eq`, `in`).|
|id|String| The unique identifier for the role definition. Key, not nullable, Read-only. Inherited from entity. Supports $filter (`eq`, `in`). |
|isBuiltIn|Boolean| Flag indicating whether the role definition is part of the default set included in Microsoft Entra or a custom definition. Read-only. Supports $filter (`eq`, `in`). |
|isEnabled|Boolean| Flag indicating whether the role is enabled for assignment. If `false` the role is not available for assignment. Read-only when **isBuiltIn** is true. |
|resourceScopes|String collection| List of the scopes or permissions the role definition applies to. Currently only `/` is supported. Read-only when **isBuiltIn** is true. **DO NOT USE. This will be deprecated soon. Attach scope to role assignment.** | 
|rolePermissions|unifiedRolePermission collection| List of permissions included in the role. Read-only when **isBuiltIn** is `true`. Required. |
|templateId|String| Custom template identifier that can be set when **isBuiltIn** is `false` but is read-only when **isBuiltIn** is `true`. This identifier is typically used if one needs an identifier to be the same across different directories. |
|version|String| Indicates version of the role definition. Read-only when **i
### [user ](https://docs.microsoft.com/graph/api/resources/user?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|aboutMe|String|A freeform text entry field for the user to describe themselves. Returned only on `$select`.|
|accountEnabled|Boolean| `true` if the account is enabled; otherwise, `false`. This property is required when a user is created. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).    |
|ageGroup|ageGroup|Sets the age group of the user. Allowed values: `null`, `Minor`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|assignedLicenses|assignedLicense collection|The licenses that are assigned to the user, including inherited (group-based) licenses. This property doesn't differentiate between directly assigned and inherited licenses. Use the **licenseAssignmentStates** property to identify the directly assigned and inherited licenses. Not nullable. Returned only on `$select`. Supports `$filter` (`eq`, `not`, `/$count eq 0`, `/$count ne 0`).           |
|assignedPlans|assignedPlan collection|The plans that are assigned to the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq` and `not`). |
|birthday|DateTimeOffset|The birthday of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|businessPhones|String collection|The telephone numbers for the user. NOTE: Although it's a string collection, only one number can be set for this property. Read-only for users synced from the on-premises directory. <br><br>Returned by default. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|city|String|The city where the user is located. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|companyName | String | The name of the company that the user is associated with. This property can be useful for describing the company that a guest comes from. The maximum length is 64 characters.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|consentProvidedForMinor|consentProvidedForMinor|Sets whether consent was obtained for minors. Allowed values: `null`, `Granted`, `Denied`, and `NotRequired`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|country|String|The country/region where the user is located; for example, `US` or `UK`. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|createdDateTime | DateTimeOffset |The date and time the user was created, in ISO 8601 format and UTC. The value can't be modified and is automatically populated when the entity is created. Nullable. For on-premises users, the value represents when they were first created in Microsoft Entra ID. Property is `null` for some users created before June 2018 and on-premises users that were synced to Microsoft Entra ID before June 2018. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| creationType | String | Indicates whether the user account was created through one of the following methods: <br/> <ul><li>As a regular school or work account (`null`). <li>As an external account (`Invitation`). <li>As a local account for an Azure Active Directory B2C tenant (`LocalAccount`). <li>Through self-service sign-up by an internal user using email verification (`EmailVerified`). <li>Through self-service sign-up by a guest signing up through a link that is part of a user flow (`SelfServiceSignUp`).</ul> <br>Read-only.<br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). The filter value is case-sensitive.|
|deletedDateTime| DateTimeOffset | The date and time the user was deleted. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
|department|String|The name of the department in which the user works. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, and `eq` on `null` values).|
|displayName|String|The name displayed in the address book for the user. This value is usually the combination of the user's first name, middle initial, and family name. This property is required when a user is created and it can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$orderby`, and `$search`.|
| employeeHireDate | DateTimeOffset |The date and time when the user was hired or will start work in a future hire. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeLeaveDateTime | DateTimeOffset | The date and time when the user left or will leave the organization. <br><br>To read this property, the calling app must be assigned the *User-LifeCycleInfo.Read.All* permission. To write this property, the calling app must be assigned the *User.Read.All* and *User-LifeCycleInfo.ReadWrite.All* permissions. To read this property in delegated scenarios, the admin needs at least one of the following Microsoft Entra roles: *Lifecycle Workflows Administrator*, *Global Reader*. To write this property in delegated scenarios, the admin needs the *Global Administrator* role. <br><br>Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`). <br><br>For more information, see Configure the employeeLeaveDateTime property for a user.|
| employeeId | String | The employee identifier assigned to the user by the organization. The maximum length is 16 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|employeeOrgData|employeeOrgData |Represents organization data (for example, division and costCenter) associated with a user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeType | String | Captures enterprise worker type. For example, `Employee`, `Contractor`, `Consultant`, or `Vendor`. Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`).|
|externalUserState|String|For a guest invited to the tenant using the invitation API, this property represents the invited user's invitation status. For invited users, the state can be `PendingAcceptance` or `Accepted`, or `null` for all other users. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|externalUserStateChangeDateTime|DateTimeOffset|Shows the timestamp for the latest change to the **externalUserState** property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|faxNumber|String|The fax number of the user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|givenName|String|The given name (first name) of the user. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| hireDate | DateTimeOffset | The hire date of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`. <br> **Note:** This property is specific to SharePoint in Microsoft 365. We recommend using the native **employeeHireDate** property to set and update hire date values using Microsoft Graph APIs. |
|id|String|The unique identifier for the user. Should be treated as an opaque identifier. Inherited from directoryObject. Key. Not nullable. Read-only. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
|identities|objectIdentity collection| Represents the identities that can be used to sign in to this user account. Microsoft (also known as a local account), organizations, or social identity providers such as Facebook, Google, and Microsoft can provide identity and tie it to a user account. It might contain multiple items with the same **signInType** value. <br><br>Returned only on `$select`. <br><br> Supports `$filter` (`eq`) with limitations. <!--Supports `$filter` (`eq`) including on `null` values, only where the **signInType** is not `userPrincipalName`.-->|
|imAddresses|String collection|The instant message voice-over IP (VOIP) session initiation protocol (SIP) addresses for the user. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|interests|String collection|A list for the user to describe their interests. <br><br>Returned only on `$select`.|
|isResourceAccount|Boolean| Don't use – reserved for future use.|
|jobTitle|String|The user's job title. Maximum length is 128 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|lastPasswordChangeDateTime| DateTimeOffset | The time when this Microsoft Entra user last changed their password or when their password was created, whichever date the latest action was performed. The date and time information uses ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|legalAgeGroupClassification|legalAgeGroupClassification| Used by enterprise applications to determine the legal age group of the user. This property is read-only and calculated based on **ageGroup** and **consentProvidedForMinor** properties. Allowed values: `null`, `MinorWithOutParentalConsent`, `MinorWithParentalConsent`, `MinorNoParentalConsentRequired`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`.|
|licenseAssignmentStates|licenseAssignmentState collection|State of license assignments for this user. Also indicates licenses that are directly assigned or the user inherited through group memberships. Read-only. <br><br>Returned only on `$select`.|
|mail|String|The SMTP address for the user, for example, `jeff@contoso.com`. Changes to this property update the user's **proxyAddresses** collection to include the value as an SMTP address. This property can't contain accent characters. <br/> **NOTE:** We don't recommend updating this property for Azure AD B2C user profiles. Use the **otherMails** property instead. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, and `eq` on `null` values).|
|mailboxSettings|mailboxSettings|Settings for the primary mailbox of the signed-in user. You can get or update settings for sending automatic replies to incoming messages, locale, and time zone. <br><br>Returned only on `$select`.|
|mailNickname|String|The mail alias for the user. This property must be specified when a user is created. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|mobilePhone|String|The primary cellular telephone number for the user. Read-only for users synced from the on-premises directory. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values) and `$search`. |
|mySite|String|The URL for the user's site. <br><br>Returned only on `$select`.|
|officeLocation|String|The office location in the user's place of business. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|onPremisesDistinguishedName|String| Contains the on-premises Active Directory `distinguished name` or `DN`. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. |
|onPremisesDomainName|String| Contains the on-premises `domainFQDN`, also called dnsDomainName synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`.|
|onPremisesExtensionAttributes|onPremisesExtensionAttributes|Contains extensionAttributes1-15 for the user. These extension attributes are also known as Exchange custom attributes 1-15. <br><li>For an **onPremisesSyncEnabled** user, the source of authority for this set of properties is the on-premises and is read-only. </li><li>For a cloud-only user (where **onPremisesSyncEnabled** is `false`), these properties can be set during the creation or update of a user object.  </li><li>For a cloud-only user previously synced from on-premises Active Directory, these properties are read-only in Microsoft Graph but can be fully managed through the Exchange Admin Center or the Exchange Online V2 module in PowerShell.</li><br> Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|onPremisesImmutableId|String|This property is used to associate an on-premises Active Directory user account to their Microsoft Entra user object. This property must be specified when creating a new user account in the Graph if you're using a federated domain for the user's **userPrincipalName** (UPN) property. **NOTE:** The **$** and **\_** characters can't be used when specifying this property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                            |
|onPremisesLastSyncDateTime|DateTimeOffset|Indicates the last time at which the object was synced with the on-premises directory; for example: `2013-02-16T03:04:54Z`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).|
|onPremisesProvisioningErrors|onPremisesProvisioningError collection| Errors when using Microsoft synchronization product during provisioning. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|onPremisesSamAccountName|String| Contains the on-premises `samAccountName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|onPremisesSecurityIdentifier|String|Contains the on-premises security identifier (SID) for the user that was synchronized from on-premises to the cloud. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq` including on `null` values). |
|onPremisesSyncEnabled|Boolean| `true` if this user object is currently being synced from an on-premises Active Directory (AD); otherwise the user isn't being synced and can be managed in Microsoft Entra ID. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|onPremisesUserPrincipalName|String| Contains the on-premises `userPrincipalName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|otherMails|String collection| A list of other email addresses for the user; for example: `["bob@contoso.com", "Robert@fabrikam.com"]`. <br>NOTE: This property can't contain accent characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|passwordPolicies|String|Specifies password policies for the user. This value is an enumeration with one possible value being `DisableStrongPassword`, which allows weaker passwords than the default policy to be specified. `DisablePasswordExpiration` can also be specified. The two might be specified together; for example: `DisablePasswordExpiration, DisableStrongPassword`. <br><br>Returned only on `$select`. For more information on the default password policies, see Microsoft Entra password policies. Supports `$filter` (`ne`, `not`, and `eq` on `null` values).|
|passwordProfile|passwordProfile|Specifies the password profile for the user. The profile contains the user's password. This property is required when a user is created. The password in the profile must satisfy minimum requirements as specified by the **passwordPolicies** property. By default, a strong password is required. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|pastProjects|String collection|A list for the user to enumerate their past projects. <br><br>Returned only on `$select`.|
|postalCode|String|The postal code for the user's postal address. The postal code is specific to the user's country/region. In the United States of America, this attribute contains the ZIP code. Maximum length is 40 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| preferredDataLocation | String | The preferred data location for the user. For more information, see OneDrive Online Multi-Geo.|
|preferredLanguage|String|The preferred language for the user. The preferred language format is based on RFC 4646. The name is a combination of an ISO 639 two-letter lowercase culture code associated with the language, and an ISO 3166 two-letter uppercase subculture code associated with the country or region. Example: "en-US", or "es-ES". <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values)|
|preferredName|String|The preferred name for the user. **Not Supported. This attribute returns an empty string.**<br><br>Returned only on `$select`.|
|provisionedPlans|provisionedPlan collection|The plans that are provisioned for the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|proxyAddresses|String collection|For example: `"SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. Changes to the **mail** property update this collection to include the value as an SMTP address. For more information, see [mail and proxyAddresses properties. The proxy address prefixed with `SMTP` (capitalized) is the primary proxy address, while those addresses prefixed with `smtp` are the secondary proxy addresses. For Azure AD B2C accounts, this property has a limit of 10 unique addresses. Read-only in Microsoft Graph; you can update this property only through the Microsoft 365 admin center. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|refreshTokensValidFromDateTime|DateTimeOffset|Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. <br><br>Returned only on `$select`. Read-only. |
|responsibilities|String collection|A list for the user to enumerate their responsibilities. <br><br>Returned only on `$select`.|
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a user object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
|schools|String collection|A list for the user to enumerate the schools they attended. <br><br>Returned only on `$select`.|
|securityIdentifier| String | Security identifier (SID) of the user, used in Windows scenarios. <br><br>Read-only. Returned by default. <br>Supports `$select` and `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
|showInAddressList|Boolean|**Do not use in Microsoft Graph. Manage this property through the Microsoft 365 admin center instead.** Represents whether the user should be included in the Outlook global address list. See Known issue.|
|signInActivity | signInActivity | Get the last signed-in date and request ID of the sign-in for a given user. Read-only.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`) *but not with any other filterable properties*. <br><br>**Note:** <br/><li>Details for this property require a Microsoft Entra ID P1 or P2 license and the **AuditLog.Read.All** permission.<li>This property isn't returned for a user who never signed in or last signed in before April 2020.|
|signInSessionsValidFromDateTime|DateTimeOffset| Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. Read-only. Use revokeSignInSessions to reset. <br><br>Returned only on `$select`.|
|skills|String collection|A list for the user to enumerate their skills. <br><br>Returned only on `$select`.|
|state|String|The state or province in the user's address. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|streetAddress|String|The street address of the user's place of business. Maximum length is 1,024 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|surname|String|The user's surname (family name or last name). Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|usageLocation|String|A two-letter country code (ISO standard 3166). Required for users that are assigned licenses due to legal requirements to check for availability of services in countries. Examples include: `US`, `JP`, and `GB`. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|userPrincipalName|String|The user principal name (UPN) of the user. The UPN is an Internet-style sign-in name for the user based on the Internet standard RFC 822. By convention, this value should map to the user's email name. The general format is alias@domain, where the domain must be present in the tenant's collection of verified domains. This property is required when a user is created. The verified domains for the tenant can be accessed from the **verifiedDomains** property of organization.<br>NOTE: This property can't contain accent characters. Only the following characters are allowed `A - Z`, `a - z`, `0 - 9`, ` ' . - _ ! # ^ ~`. For the complete list of allowed characters, see username policies. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`) and `$orderby`.
|userType|String|A string value that can be used to classify user types in your directory. The possible values are `Member` and `Guest`. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). **N
