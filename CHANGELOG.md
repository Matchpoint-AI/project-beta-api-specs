# Changelog

All notable changes to the Project Beta API specification will be documented in this file.

## [v0.0.183] - 2025-10-08

### Changes
- feat: initialize Alembic for database migrations (INFRA-012) (#211)

**Source:** project-beta-api@21b7947 "feat: initialize Alembic for database migrations (INFRA-012) (#211)"

## [v0.0.182] - 2025-10-08

### Changes
- test: add E2E tests for brand knowledge workflow endpoints (#210)

**Source:** project-beta-api@e9247d2 "test: add E2E tests for brand knowledge workflow endpoints (#210)"

## [v0.0.181] - 2025-10-08

### Changes
- feat: Set up Alembic database migrations for project-beta-api (#209)

**Source:** project-beta-api@8ee60db "feat: Set up Alembic database migrations for project-beta-api (#209)"

## [v0.0.180] - 2025-10-08

### Changes
- feat: add LLM dry-run mode for E2E testing (#207)

**Source:** project-beta-api@d8d7c16 "feat: add LLM dry-run mode for E2E testing (#207)"

## [v0.0.179] - 2025-10-08

### Changes
- refactor: improve dependency injection with proper injector patterns (#206)

**Source:** project-beta-api@ed15a63 "refactor: improve dependency injection with proper injector patterns (#206)"

## [v0.0.178] - 2025-10-08

### Changes
- chore: Remove terraform infrastructure from API repo (#193)

**Source:** project-beta-api@9366f3a "chore: Remove terraform infrastructure from API repo (#193)"

## [v0.0.177] - 2025-10-08

### Changes
- feat: Add campaign specifications endpoint (BACKEND-013) (#205)

**Source:** project-beta-api@078dd4d "feat: Add campaign specifications endpoint (BACKEND-013) (#205)"

## [v0.0.176] - 2025-10-08

### Changes
- feat: Add brand file upload with LLM extraction (BACKEND-011) (#204)

**Source:** project-beta-api@9a6ea5b "feat: Add brand file upload with LLM extraction (BACKEND-011) (#204)"

## [v0.0.175] - 2025-10-08

### Changes
- Add POST endpoint for AI-powered audience suggestions (BACKEND-014) (#203)

**Source:** project-beta-api@22985c2 "Add POST endpoint for AI-powered audience suggestions (BACKEND-014) (#203)"

## [v0.0.174] - 2025-10-07

### Changes
- feat: add POST /campaigns/{campaignId}/specifications endpoint (#202)

**Source:** project-beta-api@71b46dc "feat: add POST /campaigns/{campaignId}/specifications endpoint (#202)"

## [v0.0.173] - 2025-10-07

### Changes
- feat: add POST /brands/{brandId}/summary endpoint (V1→V2 port) (#201)

**Source:** project-beta-api@1cc2659 "feat: add POST /brands/{brandId}/summary endpoint (V1→V2 port) (#201)"

## [v0.0.172] - 2025-10-05

### Changes
- feat: Add brand file upload with LLM extraction (BACKEND-011) (#200)

**Source:** project-beta-api@4c35146 "feat: Add brand file upload with LLM extraction (BACKEND-011) (#200)"

## [v0.0.171] - 2025-10-05

### Changes
- feat: Add color name conversion endpoint (BACKEND-010d-1) (#196)

**Source:** project-beta-api@29fe6f3 "feat: Add color name conversion endpoint (BACKEND-010d-1) (#196)"

## [v0.0.170] - 2025-10-04

### Changes
- feat(BACKEND-010b-1): Campaign export repository with 90%+ test coverage (#198)

**Source:** project-beta-api@245f372 "feat(BACKEND-010b-1): Campaign export repository with 90%+ test coverage (#198)"

## [v0.0.169] - 2025-10-04

### Changes
- Add server-authoritative calculated fields to campaign responses (#197)

**Source:** project-beta-api@c55fb91 "Add server-authoritative calculated fields to campaign responses (#197)"

## [v0.0.168] - 2025-10-04

### Changes
- feat: implement explicit brand knowledge workflow trigger endpoint (#195)

**Source:** project-beta-api@6689f2a "feat: implement explicit brand knowledge workflow trigger endpoint (#195)"

## [v0.0.167] - 2025-10-03

### Changes
- docs: migrate CLAUDE.md guidance to AGENTS (#194)

**Source:** project-beta-api@a2acd21 "docs: migrate CLAUDE.md guidance to AGENTS (#194)"

## [v0.0.166] - 2025-10-03

### Changes
- feat: implement PATCH /content/{contentId}/status endpoint (BACKEND-008) (#192)

**Source:** project-beta-api@ee14abe "feat: implement PATCH /content/{contentId}/status endpoint (BACKEND-008) (#192)"

## [v0.0.165] - 2025-10-02

### Changes
- feat: Implement POST /v2/content/{contentId}/approvals (BACKEND-001) (#178)

**Source:** project-beta-api@8ea79ea "feat: Implement POST /v2/content/{contentId}/approvals (BACKEND-001) (#178)"

## [v0.0.164] - 2025-10-02

### Changes
- feat: Add V2 content export tracking endpoints (#191)

**Source:** project-beta-api@63ee7dd "feat: Add V2 content export tracking endpoints (#191)"

## [v0.0.163] - 2025-10-02

### Changes
- feat: implement POST /campaigns/{campaignId}/publications endpoint (BACKEND-009) (#189)

**Source:** project-beta-api@58bfe01 "feat: implement POST /campaigns/{campaignId}/publications endpoint (BACKEND-009) (#189)"

## [v0.0.162] - 2025-10-02

### Changes
- feat: PATCH /content/{contentId}/status endpoint (BACKEND-008) (#190)

**Source:** project-beta-api@6040982 "feat: PATCH /content/{contentId}/status endpoint (BACKEND-008) (#190)"

## [v0.0.161] - 2025-10-02

### Changes
- feat: Implement RMM L2 compliant content versioning endpoint (#187)

**Source:** project-beta-api@be9d0cd "feat: Implement RMM L2 compliant content versioning endpoint (#187)"

## [v0.0.160] - 2025-10-02

### Changes
- fix: use E2_HIGHCPU_8 machine type (N1 not supported in region) (#188)

**Source:** project-beta-api@a9dbe1f "fix: use E2_HIGHCPU_8 machine type (N1 not supported in region) (#188)"

## [v0.0.159] - 2025-10-02

### Changes
- docs: Add RMM L2 compliance tracking to CLAUDE.md (#185)

**Source:** project-beta-api@a2d2845 "docs: Add RMM L2 compliance tracking to CLAUDE.md (#185)"

## [v0.0.158] - 2025-10-02

### Changes
- infra: add Cloud Build configuration (INFRA-000a) (#186)

**Source:** project-beta-api@4249f62 "infra: add Cloud Build configuration (INFRA-000a) (#186)"

## [v0.0.157] - 2025-10-02

### Changes
- feat: implement GET /v2/users/me/regeneration-quota endpoint (#183)

**Source:** project-beta-api@e33dec7 "feat: implement GET /v2/users/me/regeneration-quota endpoint (#183)"

## [v0.0.156] - 2025-10-02

### Changes
- Add /brands/{id}/files endpoint aliases for frontend compatibility (#182)

**Source:** project-beta-api@2e4bc61 "Add /brands/{id}/files endpoint aliases for frontend compatibility (#182)"

## [v0.0.155] - 2025-10-02

### Changes
- Implement POST /v2/content/{contentId}/text-versions (BACKEND-006) (#184)

**Source:** project-beta-api@22eeadc "Implement POST /v2/content/{contentId}/text-versions (BACKEND-006) (#184)"

## [v0.0.154] - 2025-10-02

### Changes
- Implement POST /v2/content/{contentId}/regenerate (BACKEND-003) (#181)

**Source:** project-beta-api@02080e2 "Implement POST /v2/content/{contentId}/regenerate (BACKEND-003) (#181)"

## [v0.0.153] - 2025-10-02

### Changes
- feat: Implement GET /v2/campaigns/{campaignId}/content (BACKEND-002) (#179)

**Source:** project-beta-api@48e7e56 "feat: Implement GET /v2/campaigns/{campaignId}/content (BACKEND-002) (#179)"

## [v0.0.152] - 2025-10-02

### Changes
- refactor: remove /images/models endpoint (#180)

**Source:** project-beta-api@0147ff3 "refactor: remove /images/models endpoint (#180)"

## [v0.0.151] - 2025-10-02

### Changes
- refactor: Remove generic /plans endpoint (#177)

**Source:** project-beta-api@20dca2b "refactor: Remove generic /plans endpoint (#177)"

## [v0.0.150] - 2025-10-01

### Changes
- docs: Add Gemini CLI guidance for large codebase analysis (#174)

**Source:** project-beta-api@acfb392 "docs: Add Gemini CLI guidance for large codebase analysis (#174)"

## [v0.0.149] - 2025-09-30

### Changes
- feat: Phase 4 V2 Content Approval & Campaign Publishing Endpoints (#173)

**Source:** project-beta-api@882a7b5 "feat: Phase 4 V2 Content Approval & Campaign Publishing Endpoints (#173)"

## [v0.0.148] - 2025-09-29

### Changes
- feat: Increase content_repository coverage to 98% (#168)

**Source:** project-beta-api@4049006 "feat: Increase content_repository coverage to 98% (#168)"

## [v0.0.147] - 2025-09-28

### Changes
- test: increase firebase_auth_service coverage to 100% (#165)

**Source:** project-beta-api@d776a9c "test: increase firebase_auth_service coverage to 100% (#165)"

## [v0.0.146] - 2025-09-28

### Changes
- Increase campaign_controller test coverage from 71.9% to 100% (#167)

**Source:** project-beta-api@91b11d7 "Increase campaign_controller test coverage from 71.9% to 100% (#167)"

## [v0.0.145] - 2025-09-28

### Changes
- feat: Add v2 user management endpoints (#163)

**Source:** project-beta-api@81dd254 "feat: Add v2 user management endpoints (#163)"

## [v0.0.144] - 2025-09-28

### Changes
- Remove deprecated project_beta_api module from terraform configuration (#164)

**Source:** project-beta-api@d2d0581 "Remove deprecated project_beta_api module from terraform configuration (#164)"

## [v0.0.143] - 2025-09-25

### Changes
- AI PR pr393-brand-onboarding-progress: Implement PATCH /brands/{brandId}/onboarding/progress (#161)

**Source:** project-beta-api@3862815 "AI PR pr393-brand-onboarding-progress: Implement PATCH /brands/{brandId}/onboarding/progress (#161)"

## [v0.0.142] - 2025-09-25

### Changes
- fix: update file upload error messages (pr388-patch-brand-onboarding-progress) (#160)

**Source:** project-beta-api@0d658ed "fix: update file upload error messages (pr388-patch-brand-onboarding-progress) (#160)"

## [v0.0.141] - 2025-09-23

### Changes
- Implement T16 Knowledge Extraction API with comprehensive testing (#129)

**Source:** project-beta-api@1ba3bdf "Implement T16 Knowledge Extraction API with comprehensive testing (#129)"

## [v0.0.140] - 2025-09-22

### Changes
- feat: Add comprehensive error handling and logging standards (#131)

**Source:** project-beta-api@1cfdf78 "feat: Add comprehensive error handling and logging standards (#131)"

## [v0.0.139] - 2025-09-22

### Changes
- feat: implement missing v2 API endpoints for content generation (#157)

**Source:** project-beta-api@675001f "feat: implement missing v2 API endpoints for content generation (#157)"

## [v0.0.138] - 2025-09-22

### Changes
- feat: Add automatic OpenAPI version update to match Git tags (#159)

**Source:** project-beta-api@1f224bd "feat: Add automatic OpenAPI version update to match Git tags (#159)"

## [v0.0.137] - 2025-09-22

### Changes
- docs: Add architecture highlights section to README (#158)

**Source:** project-beta-api@eeb9706 "docs: Add architecture highlights section to README (#158)"

## [v0.0.136] - 2025-09-22

### Changes
- feat: Complete v1→v2 API consolidation with LLM integration (#151)

**Source:** project-beta-api@d259e06 "feat: Complete v1→v2 API consolidation with LLM integration (#151)"

## [v0.0.135] - 2025-09-22

### Changes
- Merge pull request #156 from Matchpoint-AI/task-1758508791

**Source:** project-beta-api@348a49f "Merge pull request #156 from Matchpoint-AI/task-1758508791"

## [v0.0.134] - 2025-09-20

### Changes
- Merge pull request #137 from Matchpoint-AI/task-1758384992

**Source:** project-beta-api@2d5bfcc "Merge pull request #137 from Matchpoint-AI/task-1758384992"

## [v0.0.133] - 2025-09-20

### Changes
- Fix Terraform workspace selection in CloudBuild workflow (#146)

**Source:** project-beta-api@813d7f2 "Fix Terraform workspace selection in CloudBuild workflow (#146)"

## [v0.0.132] - 2025-09-20

### Changes
- Add Google Cloud Workflows module for brand knowledge extraction (#138)

**Source:** project-beta-api@2414830 "Add Google Cloud Workflows module for brand knowledge extraction (#138)"

## [v0.0.131] - 2025-09-20

### Changes
- Merge pull request #145 from Matchpoint-AI/feat/fix-workflow-1758400330

**Source:** project-beta-api@32c87f9 "Merge pull request #145 from Matchpoint-AI/feat/fix-workflow-1758400330"

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.0.124] - 2025-09-20

### Changed
- Refactor: Rename /assets endpoints to /files to match frontend expectations

**Source:** project-beta-api@d302c03 "refactor: Rename /assets endpoints to /files to match frontend expectations"

## Initial Release

This repository was created to provide public access to Project Beta API specifications, replacing the git subtree approach previously used in the frontend repository.