# Release notes

## 1.0.1 — August 31, 2026

Listing-materials update to the locally prepared 1.0.0 bundle. Neither version has been submitted to or published in the OpenAI Plugins Directory.

- Added a plugin logo and public support, privacy, and terms documents.
- Added the policy URLs and logo references to the plugin manifest.
- Preserved the existing skill instructions, descriptions, starter prompts, and automatic skill discovery.
- Added a listing worksheet recording the submission fields and remaining publisher decisions.
- Recorded the publisher's regional policy: all OpenAI-supported countries and territories for ChatGPT/Codex, subject to platform restrictions, with English-language best-effort support. Portal selections have not yet been applied.

The plugin remains instructions-only: no runtime dependencies, executable helpers, MCP server, extension, or automatic browser-setting changes. No software has been installed by preparing this release.

### Verification and limitations

The 1.0.1 bundle passed both plugin and skill validators before and after ZIP extraction. Checks confirmed archive integrity, the six-file package contents, unchanged skill instructions, valid local documentation links, preserved automatic discovery, and a square opaque PNG logo. The original 1.0.0 ZIP is retained locally.

The 1.0.0 package passed plugin and skill structural validation, ZIP integrity checks, and checks of metadata, internal reference links, and unchanged skill content. The skill was also evaluated during development using temporary fixtures and mocks covering forms, SPA logic, URL-only adapters, invalid input, stale state, cancellation, and cleanup.

These checks do not establish native WebMCP or target-agent compatibility. Native-browser and target-agent verification remain outstanding. Browser support, permissions, inaccessible functionality, and client capabilities can prevent an integration from working. Reviewer test cases and publisher identity verification are separate submission tasks.

### Text for the submission release-notes field

Initial directory submission of WebMCP Enable, a skills-only plugin for adding, repairing, and verifying browser WebMCP integrations using existing website source or a narrowly scoped session-local adapter. Version 1.0.1 adds listing assets and public support, privacy, and terms pages to the previously prepared local bundle. The instructions preserve application validation, authentication, confirmation, and ordinary UI behavior. Local structural checks and development mocks are available; native-browser and target-agent compatibility have not been verified. No hosted MCP server, extension, or runtime dependencies are included.
