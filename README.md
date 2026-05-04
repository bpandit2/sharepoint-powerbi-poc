# Microsoft 365 SPFx Developer Proof of Concept

This repository contains a minimal Proof of Concept focused on
SharePoint Framework (SPFx) development within Microsoft 365.

The project is intended to be used **exclusively in a Microsoft 365
Developer Program sandbox** for development, learning, and testing purposes.

## Goals

- Develop and test SharePoint Framework (SPFx) client-side web parts
- Validate integration with SharePoint Online sites and lists
- Experiment with Microsoft Graph usage from SPFx
- Test permissions and security context (Entra ID)
- Prepare a base for enterprise-grade SharePoint solutions

## Scope

This PoC focuses on:

- SharePoint Online
- SharePoint Framework (SPFx)
- Microsoft Graph (planned)
- Power Platform integration (planned)
- Power BI report embedding in SharePoint pages

No production workloads or real customer data are involved.

## Architecture Overview

- SharePoint Online used as hosting platform
- SPFx web parts deployed to App Catalog
- SharePoint Lists used as lightweight data source
- Microsoft Graph consumed from SPFx using delegated permissions
- Power BI reports embedded using SharePoint web parts

## Development Scenarios

Planned or experimental scenarios include:

- SPFx web part displaying data from SharePoint Lists
- SPFx web part calling Microsoft Graph (e.g. user profile data)
- Use of @microsoft/sp-http and GraphHttpClient
- Embedding Power BI reports into modern SharePoint pages
- Deployment testing via tenant App Catalog

## Target Audience

- Microsoft 365 Developers
- SharePoint / SPFx Developers
- Solution Architects
- Technical Proof of Concept scenarios

## Status

This repository represents an **early-stage developer PoC**
prepared as part of ongoing Microsoft 365 development activities
within a dedicated Microsoft 365 Developer Program sandbox.
