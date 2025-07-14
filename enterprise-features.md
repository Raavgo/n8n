## EnterpriseEditionFeature
Provides a mapping of all enterprise features available in the project as defined in `packages/frontend/editor-ui/src/constants.ts`.
These include:
- advancedExecutionFilters
- sharing
- ldap
- logStreaming
- variables
- saml
- oidc
- mfaEnforcement
- sourceControl
- externalSecrets
- auditLogs
- debugInEditor
- workflowHistory
- workerView
- advancedPermissions
- apiKeyScopes

## isEnterpriseFeatureEnabled
Located in `packages/frontend/editor-ui/src/utils/rbac/checks/isEnterpriseFeatureEnabled.ts`. Determines if one or more enterprise features are active based on the settings store. Features can be evaluated in `allOf` or `any` mode.

## isEnterpriseFeatureEnabled (settings store)
Computed property in `packages/frontend/editor-ui/src/stores/settings.store.ts` returning the object that indicates which enterprise features are enabled.
