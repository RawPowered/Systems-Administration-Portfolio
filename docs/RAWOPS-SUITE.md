# RawOps Suite: application operations, access and visibility

[Portfolio overview](../README.md) · [RawOps Suite](https://github.com/RawPowered/RawOps-Suite) · [Evidence scope](EVIDENCE.md)

![RawOps case: Application operations, access and visibility](../assets/rawops/section.svg)

RawOps Suite gives you a source-level view of how I designed administration around daily work: role-specific workspaces, learning progress, usage reporting and explicit access checks.

**Status:** Preserved partial history of a previously functional PHP/MySQL business system. This case supports application-operations experience; infrastructure administration and recovery results retain their separate evidence requirements.

## 1. Give administrators a useful operating view

The platform brought CRM, learning, legal and operational tools into role-specific workspaces. The historical operating overview displays 51 leads, 10 sales agents and 16 users in training in its selected window. These are dated counts, useful for understanding the administrative surface.

[Admin interface](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/evidence/GALLERY.md#admin-module-navigation--20-october-2025) · [Operating overview](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/evidence/GALLERY.md#operating-overview--29-september-2025) · [Training heartbeat](https://github.com/RawPowered/RawOps-Suite/blob/main/api/training-heartbeat.php) · [Usage reporting](https://github.com/RawPowered/RawOps-Suite/blob/main/api/admin-usage-analytics.php)

**Evidence boundary:** The heartbeat checks the requested user against the signed-in session and records activity/idle state. Activity and usage records support follow-up; they do not establish employee productivity or a service-availability target.

## 2. Review access at the record boundary

The legal workspace provides a concrete access-review case. Its helper combines legal role and case membership; its API routes expose evidence metadata and team actions. The publication review also records a broader role-based auto-unlock path in the evidence locker.

[Case permissions](https://github.com/RawPowered/RawOps-Suite/blob/main/required/legal-permissions.php) · [Case services](https://github.com/RawPowered/RawOps-Suite/blob/main/required/legal-case-service.php) · [Security review](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/SECURITY-AND-PRIVACY.md)

**Evidence boundary:** A restoration review needs consistent case authorization across pages, endpoints and stored files. Identifying the inconsistent route is part of the case. No comprehensive isolation test or independent security audit is claimed.

## 3. Treat changing content as an operational dependency

Product prices and descriptions feed training and email rendering through shared shortcodes. Enabled-product synchronization and reference checks help maintain the learning material. This creates a useful change-management question: which values refresh from the catalog, and which explanations still need an editor?

[Product and learning design](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/PRODUCT-LEARNING-DESIGN.md) · [Reference checks](https://github.com/RawPowered/RawOps-Suite/blob/main/required/training-sync-checker.php) · [Synchronization service](https://github.com/RawPowered/RawOps-Suite/blob/main/required/training-auto-sync.php)

**Evidence boundary:** The source establishes rendering and maintenance mechanisms. Automatic propagation from every recipe or catalog edit is unverified. A restore, backup validation and allowed/denied access exercise remain proposed work.

## Discuss the work

Ask me to trace a product change through its dependent learning content, or to explain how I would close the documented case-access gap.

The [systems diagram](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/SYSTEMS-ORCHESTRATION.md) provides the wider context. The [feature walkthrough](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/FEATURE-WALKTHROUGH.md) and [capability catalog](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/CAPABILITY-CATALOG.md) cover the rest of the platform.

## Evidence and maintenance

The source project preserves partial history of a previously functional application. Its published gallery contains 11 genuine historical captures with opaque redactions. [Publication checks](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/PUBLICATION-REVIEW.md) cover syntax and secret scanning; business workflows were not executed by those checks. Review [security and privacy](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/SECURITY-AND-PRIVACY.md) before considering restoration.

This case was added October 26, 2026. Project source and evidence remain authoritative in RawOps Suite. No live CRM records were changed and no flows were run for this portfolio update.
