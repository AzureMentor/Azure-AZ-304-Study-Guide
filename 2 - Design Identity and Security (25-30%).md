# AZ-304: Design Identity and Security (25-30%)

## Design authentication
- Recommend a solution for single-sign on (SSO)
  - [What is single sign-on (SSO)?](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on)
  - [Azure Active Directory Seamless Single Sign-On](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso)
  - [Azure Active Directory Seamless Single Sign-On: FAQ](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-faq)
  - [Azure Active Directory Seamless Single Sign-On: Quickstart](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start)
  - [Configure SaaS apps for B2B collaboration](https://docs.microsoft.com/en-us/azure/active-directory/external-identities/configure-saas-apps)
- Recommend a solution for authentication
  - [Authentication flows and application scenarios](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-flows-app-scenarios)
  - [Authentication vs. authorization](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-vs-authorization)
- Recommend a solution for Conditional Access, including:
  - Multi-factor authentication (MFA)
    - [Conditional Access: Require MFA for all users](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-all-users-mfa)
    - [Tutorial: Secure user sign-in events with Azure AD MFA](https://docs.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-azure-mfa)
    - [Conditional Access: Sign-in risk-based Conditional Access](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-risk)
- Recommend a solution for network access authentication
  - [Using the location condition in a Conditional Access policy](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/location-condition)
- Recommend a solution for a hybrid identity including:
  - Azure AD Connect
    - [What is Azure AD Connect?](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-azure-ad-connect)
    - [Select which installation type to use for Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-select-installation)
    - [Custom installation of Azure Active Directory Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-custom)
  - [Azure AD Connect Health](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-health-operations)
- Recommend a solution for user self-service
  - [Plan an Azure Active Directory self-service password reset deployment](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-deployment)
- Recommend and implement a solution for B2B integration
  - [What is guest user access in Azure Active Directory B2B?](https://docs.microsoft.com/en-us/azure/active-directory/external-identities/what-is-b2b)
  - [What are External Identities in Azure Active Directory?](https://docs.microsoft.com/en-us/azure/active-directory/external-identities/compare-with-b2c)
- NOT: Federation with ADFS or PingFederate

## Design authorization
- Choose an authorization approach
  - [Authentication vs. authorization](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-vs-authorization)
- Recommend a hierarchical structure that includes:
  - [Management groups](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)
    - [Quickstart: Create a management group](https://docs.microsoft.com/en-us/azure/governance/management-groups/create-management-group-portal)
  - [Subscriptions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits)
  - [Resource groups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal)
- Recommend an access management solution including:
  - [RBAC policies](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview)
  - [Access reviews](https://docs.microsoft.com/en-us/azure/active-directory/governance/access-reviews-overview)
    - [Quickstart: Check access for a user to Azure resources](https://docs.microsoft.com/en-us/azure/role-based-access-control/check-access)
  - [Role assignments](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal)
  - [Privileged Identity Management (PIM)](https://docs.microsoft.com/en-us/azure/active-directory/privileged-identity-management/pim-configure)
  - [Azure AD Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection)
  - [Just In Time (JIT) access](https://docs.microsoft.com/en-us/azure/security-center/security-center-just-in-time)

## Design governance
- [Recommend a strategy for Tagging](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources)
- [Recommend a solution for using Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/overview)
  - [Tutorial: Create and manage policies to enforce compliance](https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage)
- [Recommend a solution for using Azure Blueprints](https://docs.microsoft.com/en-us/azure/governance/blueprints/overview)
  - [Quickstart: Define and assign a blueprint in the portal](https://docs.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-portal)
- [Recommend a solution that leverages Azure Resource Graph](https://docs.microsoft.com/en-ca/azure/governance/resource-graph/overview)

## Design security for applications
- [Recommend a solution that includes **KeyVault**](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)
  - [Azure Key Vault keys, secrets and certificates overview](https://docs.microsoft.com/en-us/azure/key-vault/general/about-keys-secrets-certificates)
- [Recommend a solution that includes **Managed Identities**](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview)
  - [Use a Windows VM system-assigned managed identity to access Resource Manager](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/tutorial-windows-vm-access-arm)
- [Recommend a solution for **integrating applications into Azure AD**](https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications)

[Return to Table of Contents](README.md)