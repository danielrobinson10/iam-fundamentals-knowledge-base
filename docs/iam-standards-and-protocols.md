# IAM Standards and Protocols

## Overview

IAM standards and protocols allow different systems to securely exchange identity and access information.

## SAML 2.0

Security Assertion Markup Language, or SAML, is an XML-based protocol used to exchange authentication and authorization data between an identity provider and a service provider.

### Common Use

SAML is widely used for enterprise Single Sign-On.

### Example

A user signs into Okta. Okta sends a SAML assertion to a business application. The application trusts Okta and grants access.

## OAuth 2.0

OAuth 2.0 is an authorization framework that allows third-party applications to access resources without sharing a user's password.

### Common Use

OAuth is commonly used to grant limited access to user data, such as allowing an app to access a calendar or profile.

## OpenID Connect

OpenID Connect, or OIDC, is an authentication layer built on top of OAuth 2.0.

### Common Use

OIDC is commonly used for modern web and mobile application login.

## SCIM

System for Cross-domain Identity Management, or SCIM, simplifies user provisioning and deprovisioning across multiple systems.

### Common Use

SCIM helps automate account creation, updates, and removal across applications.

## Comparison Table

| Standard | Main Purpose | Common Use |
|---|---|---|
| SAML 2.0 | Authentication and SSO | Enterprise application login |
| OAuth 2.0 | Authorization | Delegated application access |
| OpenID Connect | Authentication | Modern app login |
| SCIM | User lifecycle automation | Provisioning and deprovisioning |

## Key Takeaways

- SAML is common for enterprise SSO.
- OAuth 2.0 is mainly for delegated authorization.
- OIDC adds authentication to OAuth 2.0.
- SCIM automates user lifecycle management across systems.
