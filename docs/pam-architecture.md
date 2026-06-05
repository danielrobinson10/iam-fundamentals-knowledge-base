# PAM Architecture

## Overview

A PAM architecture includes the systems and workflows used to control privileged access.

## Credential Vault

A credential vault securely stores privileged account passwords.

Important controls:

- Encryption
- Access control
- Credential rotation
- Checkout tracking

## Session Manager

A session manager proxies privileged connections so sessions can be monitored, recorded, and isolated from end-user devices.

## Access Workflow Engine

An access workflow engine manages requests, approvals, and provisioning for privileged access.

## Monitoring and Analytics

Monitoring and analytics track privileged activity and detect unusual behavior.

## Architecture Components

| Component | Purpose |
|---|---|
| Credential Vault | Secure privileged credential storage |
| Session Manager | Monitor and record privileged sessions |
| Workflow Engine | Manage requests and approvals |
| Analytics | Detect abnormal privileged activity |

## Key Takeaways

- PAM architecture should protect credentials and sessions.
- Approval workflows reduce unmanaged privileged access.
- Monitoring supports investigation and compliance.
