__Omega Portal – Azure AD SAML 2.0 SSO__

Azure AD SAML 2.0 Single Sign-On integration for Omega Portal, enabling ACME employees to log in directly from Azure AD without entering separate credentials.

__Overview__

__Current__: Manual login with Employee Code + password

__Target__: Automatic login via Azure AD SSO (SAML 2.0)

__Key Components__

__IdP__: Azure Active Directory

__SP__: Omega Portal (.NET Framework 4.5)

__Claim Mapping__: employeeId → Employee Code

__Flow__

User logs into Azure AD

Clicks Omega Portal tile

Azure AD sends SAML assertion with Employee Code

Omega Portal validates token and creates session

User lands on homepage authenticated

__Benefits__

No password re-entry

Centralized identity management

Improved security and user experience
