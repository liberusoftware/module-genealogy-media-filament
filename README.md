# Genealogy Media filament

This package is the one-to-one **filament** presentation adapter for `liberusoftware/module-genealogy-media`.

It owns only filament transport/presentation integration. Domain rules, persistence, authorization, tenancy, and lifecycle behavior remain in the matching core package.

- Composer package: `liberusoftware/module-genealogy-media-filament`
- Installer name: `genealogy-media-filament`
- Package type: `liberu-module`

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-genealogy-media`.
- Actual Composer identity: `liberusoftware/module-genealogy-media-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/genealogy/filament/media.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [Genealogy](https://github.com/liberusoftware/project-genealogy-laravel-filament): Family trees, research, evidence and collaboration.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
