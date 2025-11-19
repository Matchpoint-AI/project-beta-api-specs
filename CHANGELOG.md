# Changelog

All notable changes to the Project Beta API specification will be documented in this file.

## [v0.0.316] - 2025-11-19

### Changes
- 📚 Create Database Migration Safety Guidelines (Phase 0 - P0) (#423)

**Source:** project-beta-api@6c8b624 "📚 Create Database Migration Safety Guidelines (Phase 0 - P0) (#423)"

## [v0.0.315] - 2025-11-19

### Changes
- 📋 Create V2 API Design Standards (Phase 0 - P0) (#422)

**Source:** project-beta-api@d21b526 "📋 Create V2 API Design Standards (Phase 0 - P0) (#422)"

## [v0.0.314] - 2025-11-19

### Changes
- 🚨 Add OpenAPI Breaking Change Detector (Phase 0 - P0) (#420)

**Source:** project-beta-api@c939256 "🚨 Add OpenAPI Breaking Change Detector (Phase 0 - P0) (#420)"

## [v0.0.313] - 2025-11-19

### Changes
- fix: remove has_brand column references after migration 548e5a2dc7a4 (#419)

**Source:** project-beta-api@24e9999 "fix: remove has_brand column references after migration 548e5a2dc7a4 (#419)"

## [v0.0.312] - 2025-11-19

### Changes
- fix: Fix RMM-2 Violation: Remove POST /api/v2/images/generate endpoint (#418)

**Source:** project-beta-api@2361bb3 "fix: Fix RMM-2 Violation: Remove POST /api/v2/images/generate endpoint (#418)"

## [v0.0.311] - 2025-11-19

### Changes
- feat: Add RMM Level 2 Compliance Validator Script (#414)

**Source:** project-beta-api@3345525 "feat: Add RMM Level 2 Compliance Validator Script (#414)"

## [v0.0.310] - 2025-11-19

### Changes
- fix: remove duplicate UserService DI binding (#413)

**Source:** project-beta-api@2faef8b "fix: remove duplicate UserService DI binding (#413)"

## [v0.0.309] - 2025-11-18

### Changes
- fix: add missing SignupService DI bindings + container structure test (#412)

**Source:** project-beta-api@9891aca "fix: add missing SignupService DI bindings + container structure test (#412)"

## [v0.0.308] - 2025-11-17

### Changes
- fix: validate Cloud SQL proxy configuration at startup (#410)

**Source:** project-beta-api@e1f6532 "fix: validate Cloud SQL proxy configuration at startup (#410)"

## [v0.0.307] - 2025-11-17

### Changes
- fix: improve JSON parsing error messages in validation handler (#408)

**Source:** project-beta-api@adaf618 "fix: improve JSON parsing error messages in validation handler (#408)"

## [v0.0.306] - 2025-11-17

### Changes
- docs: add V2 epic blocking workflow guidance to AI agent workflows (#407)

**Source:** project-beta-api@a5cab21 "docs: add V2 epic blocking workflow guidance to AI agent workflows (#407)"

## [v0.0.305] - 2025-11-17

### Changes
- fix: add CLOUD_SQL_INSTANCE env var support for database connection (#394)

**Source:** project-beta-api@0d6192d "fix: add CLOUD_SQL_INSTANCE env var support for database connection (#394)"

## [v0.0.304] - 2025-11-15

### Changes
- feat: migrate scene-mix endpoints to campaign-based pattern (#371) (#377)

**Source:** project-beta-api@a492956 "feat: migrate scene-mix endpoints to campaign-based pattern (#371) (#377)"

## [v0.0.303] - 2025-11-15

### Changes
- docs: complete investigation of OpenAPI spec completeness for SceneMix endpoints (#393)

**Source:** project-beta-api@1098fc3 "docs: complete investigation of OpenAPI spec completeness for SceneMix endpoints (#393)"

## [v0.0.302] - 2025-11-15

### Changes
- fix: parse Cloud SQL instance from DATABASE_URL (#392)

**Source:** project-beta-api@5714a24 "fix: parse Cloud SQL instance from DATABASE_URL (#392)"

## [v0.0.301] - 2025-11-15

### Changes
- feat: implement POST /api/v2/content/{content_id}/images endpoint (#370) (#388)

**Source:** project-beta-api@10fd595 "feat: implement POST /api/v2/content/{content_id}/images endpoint (#370) (#388)"

## [v0.0.300] - 2025-11-15

### Changes
- docs: add API naming conventions to .ai directory (#341) (#391)

**Source:** project-beta-api@7b292d2 "docs: add API naming conventions to .ai directory (#341) (#391)"

## [v0.0.299] - 2025-11-15

### Changes
- feat: add missing fields to SceneMixPolicyResponse schema (#390)

**Source:** project-beta-api@a7ce6d7 "feat: add missing fields to SceneMixPolicyResponse schema (#390)"

## [v0.0.298] - 2025-11-15

### Changes
- fix: add CLOUD_SQL_INSTANCE env var fallback for database configuration (#389)

**Source:** project-beta-api@8326a97 "fix: add CLOUD_SQL_INSTANCE env var fallback for database configuration (#389)"

## [v0.0.297] - 2025-11-15

### Changes
- fix: restore user registration endpoint (#386)

**Source:** project-beta-api@a029c7e "fix: restore user registration endpoint (#386)"

## [v0.0.296] - 2025-11-15

### Changes
- fix: add UserService->UserServiceImpl binding to DI container (#384) (#385)

**Source:** project-beta-api@5057b57 "fix: add UserService->UserServiceImpl binding to DI container (#384) (#385)"

## [v0.0.295] - 2025-11-15

### Changes
- fix: restore user registration endpoint and configure dependencies (#383)

**Source:** project-beta-api@c495baa "fix: restore user registration endpoint and configure dependencies (#383)"

## [v0.0.294] - 2025-11-15

### Changes
- docs: document dependency injection validation pattern (#381)

**Source:** project-beta-api@961c7a6 "docs: document dependency injection validation pattern (#381)"

## [v0.0.293] - 2025-11-14

### Changes
- test: add dependency injection validation to container structure tests (#379)

**Source:** project-beta-api@206e4d4 "test: add dependency injection validation to container structure tests (#379)"

## [v0.0.292] - 2025-11-14

### Changes
- refactor: remove dead has_brand field from User model (#374) (#378)

**Source:** project-beta-api@b1f7946 "refactor: remove dead has_brand field from User model (#374) (#378)"

## [v0.0.291] - 2025-11-14

### Changes
- fix: add missing users table columns (firebase_uid, email_verified, has_brand) (#373)

**Source:** project-beta-api@b37cb69 "fix: add missing users table columns (firebase_uid, email_verified, has_brand) (#373)"

## [v0.0.290] - 2025-11-14

### Changes
- chore: Remove flaky E2E Docker tests from CI (#376)

**Source:** project-beta-api@b71a903 "chore: Remove flaky E2E Docker tests from CI (#376)"

## [v0.0.289] - 2025-11-14

### Changes
- feat: Implement V2 threads endpoints (RMM L2 compliant) (#367)

**Source:** project-beta-api@8b92d33 "feat: Implement V2 threads endpoints (RMM L2 compliant) (#367)"

## [v0.0.288] - 2025-11-13

### Changes
- feat: implement V2 threads API with RMM Level 2 compliance (#363)

**Source:** project-beta-api@87e1ed0 "feat: implement V2 threads API with RMM Level 2 compliance (#363)"

## [v0.0.287] - 2025-11-13

### Changes
- feat: add crawl analytics endpoints for monitoring dashboard (#492) (#364)

**Source:** project-beta-api@3e92de2 "feat: add crawl analytics endpoints for monitoring dashboard (#492) (#364)"

## [v0.0.286] - 2025-11-13

### Changes
- fix: Enable Playwright browser automation for Cloud Run deployment (issue #365) (#366)

**Source:** project-beta-api@696219e "fix: Enable Playwright browser automation for Cloud Run deployment (issue #365) (#366)"

## [v0.0.285] - 2025-11-12

### Changes
- feat: add Playwright service for JavaScript rendering support

**Source:** project-beta-api@abeb259 "feat: add Playwright service for JavaScript rendering support"

## [v0.0.284] - 2025-11-12

### Changes
- feat: enable local CI execution with nektos/act (#361)

**Source:** project-beta-api@ad35b35 "feat: enable local CI execution with nektos/act (#361)"

## [v0.0.283] - 2025-11-12

### Changes
- feat: add V2 website content endpoints (issue #354) (#356)

**Source:** project-beta-api@6d8f1ab "feat: add V2 website content endpoints (issue #354) (#356)"

## [v0.0.282] - 2025-11-12

### Changes
- feat: add error categorization and retry logic for web crawling (#358) (#359)

**Source:** project-beta-api@65fd8e8 "feat: add error categorization and retry logic for web crawling (#358) (#359)"

## [v0.0.281] - 2025-11-12

### Changes
- feat: Add GET /api/v2/brands/{brand_id}/knowledge/summary endpoint (#347)

**Source:** project-beta-api@d41affc "feat: Add GET /api/v2/brands/{brand_id}/knowledge/summary endpoint (#347)"

## [v0.0.280] - 2025-11-11

### Changes
- feat: Add POST /api/v2/brands/{brandId}/knowledge/extract-batch endpoint (#348)

**Source:** project-beta-api@dec65c0 "feat: Add POST /api/v2/brands/{brandId}/knowledge/extract-batch endpoint (#348)"

## [v0.0.279] - 2025-11-11

### Changes
- feat: Add weeks structure to SceneMixPlanResponse for detailed content planning (#355)

**Source:** project-beta-api@0c3e120 "feat: Add weeks structure to SceneMixPlanResponse for detailed content planning (#355)"

## [v0.0.278] - 2025-11-11

### Changes
- feat: add brand knowledge summary endpoint (#352)

**Source:** project-beta-api@39f4983 "feat: add brand knowledge summary endpoint (#352)"

## [v0.0.277] - 2025-11-11

### Changes
- feat: add pagination support to brand knowledge endpoint (#338) (#346)

**Source:** project-beta-api@5d5333b "feat: add pagination support to brand knowledge endpoint (#338) (#346)"

## [v0.0.276] - 2025-11-10

### Changes
- docs: add PR mergeable status troubleshooting to API workflow docs (#349)

**Source:** project-beta-api@d3842a8 "docs: add PR mergeable status troubleshooting to API workflow docs (#349)"

## [v0.0.275] - 2025-11-10

### Changes
- feat: add POST /api/v2/brands/{brandId}/extractions endpoint (#342)

**Source:** project-beta-api@4029be8 "feat: add POST /api/v2/brands/{brandId}/extractions endpoint (#342)"

## [v0.0.274] - 2025-11-10

### Changes
- docs: add AI agent startup workflow documentation

**Source:** project-beta-api@a667ba8 "docs: add AI agent startup workflow documentation"

## [v0.0.273] - 2025-11-10

### Changes
- feat: Implement brand knowledge list/extract-batch/summary endpoints (#331) (#332)

**Source:** project-beta-api@8b117b7 "feat: Implement brand knowledge list/extract-batch/summary endpoints (#331) (#332)"

## [v0.0.272] - 2025-11-10

### Changes
- test: fix logging setup tests with isolation fixture (#309) (#333)

**Source:** project-beta-api@80b6552 "test: fix logging setup tests with isolation fixture (#309) (#333)"

## [v0.0.271] - 2025-11-10

### Changes
- docs: add dev reference documentation for AI agents (#1301) (#330)

**Source:** project-beta-api@796c0e5 "docs: add dev reference documentation for AI agents (#1301) (#330)"

## [v0.0.270] - 2025-11-10

### Changes
- feat: implement POST /api/v2/signups endpoint for landing page beta signups (#327)

**Source:** project-beta-api@d4891ca "feat: implement POST /api/v2/signups endpoint for landing page beta signups (#327)"

## [v0.0.269] - 2025-11-10

### Changes
- fix: replace hardcoded api.example.com with configurable API_BASE_URL (#325)

**Source:** project-beta-api@6a6bc99 "fix: replace hardcoded api.example.com with configurable API_BASE_URL (#325)"

## [v0.0.268] - 2025-11-09

### Changes
- fix: implement proper user isolation for campaigns (issue #317) (#322)

**Source:** project-beta-api@0458d8c "fix: implement proper user isolation for campaigns (issue #317) (#322)"

## [v0.0.267] - 2025-11-08

### Changes
- fix: replace hardcoded API base URL with configurable setting (#324)

**Source:** project-beta-api@fd298cd "fix: replace hardcoded API base URL with configurable setting (#324)"

## [v0.0.266] - 2025-11-07

### Changes
- fix: replace hardcoded API base URL with configurable setting (#323)

**Source:** project-beta-api@f7c2a77 "fix: replace hardcoded API base URL with configurable setting (#323)"

## [v0.0.265] - 2025-11-07

### Changes
- fix: implement extractor service knowledge persistence (#314) (#320)

**Source:** project-beta-api@46b58d7 "fix: implement extractor service knowledge persistence (#314) (#320)"

## [v0.0.264] - 2025-11-07

### Changes
- fix: implement actual GCS file deletion - resolves #313 (#316)

**Source:** project-beta-api@41b4b9f "fix: implement actual GCS file deletion - resolves #313 (#316)"

## [v0.0.263] - 2025-11-07

### Changes
- fix: migrate CorrelationIDMiddleware to pure ASGI to support exception handlers (#315)

**Source:** project-beta-api@19e32af "fix: migrate CorrelationIDMiddleware to pure ASGI to support exception handlers (#315)"

## [v0.0.262] - 2025-11-07

### Changes
- docs(tests): add GitHub issue references to skipped tests (#311)

**Source:** project-beta-api@bd0cde0 "docs(tests): add GitHub issue references to skipped tests (#311)"

## [v0.0.261] - 2025-11-06

### Changes
- chore: package alembic migrations for automation (#308)

**Source:** project-beta-api@dca26f7 "chore: package alembic migrations for automation (#308)"

## [v0.0.260] - 2025-11-06

### Changes
- fix: resolve remaining mypy type errors with targeted ignores (#307)

**Source:** project-beta-api@e459648 "fix: resolve remaining mypy type errors with targeted ignores (#307)"

## [v0.0.259] - 2025-11-05

### Changes
- feat: implement real Firebase email verification for user registration (#304)

**Source:** project-beta-api@72a61c6 "feat: implement real Firebase email verification for user registration (#304)"

## [v0.0.258] - 2025-11-05

### Changes
- test: enable skipped coverage gaps (#300)

**Source:** project-beta-api@1555d6a "test: enable skipped coverage gaps (#300)"

## [v0.0.257] - 2025-11-04

### Changes
- docs: standardize AI assistant config files to reference AGENTS.md

**Source:** project-beta-api@a7ec064 "docs: standardize AI assistant config files to reference AGENTS.md"

## [v0.0.256] - 2025-11-03

### Changes
- feat: Add local API development environment with Cloud SQL proxy (#290) (#293)

**Source:** project-beta-api@d9d4314 "feat: Add local API development environment with Cloud SQL proxy (#290) (#293)"

## [v0.0.255] - 2025-11-03

### Changes
- fix: add validation for Cloud SQL proxy configuration and improve error logging (#292)

**Source:** project-beta-api@6b1caae "fix: add validation for Cloud SQL proxy configuration and improve error logging (#292)"

## [v0.0.254] - 2025-11-03

### Changes
- fix: add missing CLOUD_SQL_INSTANCE parameter for Unix socket connections (#289)

**Source:** project-beta-api@8417aac "fix: add missing CLOUD_SQL_INSTANCE parameter for Unix socket connections (#289)"

## [v0.0.253] - 2025-11-03

### Changes
- fix: add DATABASE_URL environment variable support for Cloud Run (#288)

**Source:** project-beta-api@a198920 "fix: add DATABASE_URL environment variable support for Cloud Run (#288)"

## [v0.0.252] - 2025-11-03

### Changes
- docs: Add Steps to Reproduce section to API issue template (#284)

**Source:** project-beta-api@f90d142 "docs: Add Steps to Reproduce section to API issue template (#284)"

## [v0.0.251] - 2025-11-03

### Changes
- fix: add DATABASE_URL environment variable support for Cloud Run (#286)

**Source:** project-beta-api@9736c23 "fix: add DATABASE_URL environment variable support for Cloud Run (#286)"

## [v0.0.250] - 2025-11-03

### Changes
- docs: add Progress Documentation Protocol to workflow guidelines (#283)

**Source:** project-beta-api@c75ca89 "docs: add Progress Documentation Protocol to workflow guidelines (#283)"

## [v0.0.249] - 2025-11-02

### Changes
- fix: add CORS middleware to allow frontend origins (#282)

**Source:** project-beta-api@f1cddfb "fix: add CORS middleware to allow frontend origins (#282)"

## [v0.0.248] - 2025-11-02

### Changes
- docs: add PR reference requirements for AI agents (#281)

**Source:** project-beta-api@116abb5 "docs: add PR reference requirements for AI agents (#281)"

## [v0.0.247] - 2025-11-02

### Changes
- docs: add agent status update requirement to workflow guidelines (#280)

**Source:** project-beta-api@14c8e54 "docs: add agent status update requirement to workflow guidelines (#280)"

## [v0.0.246] - 2025-11-02

### Changes
- docs: add AI agent workflow best practices (#273)

**Source:** project-beta-api@91bc858 "docs: add AI agent workflow best practices (#273)"

## [v0.0.245] - 2025-11-02

### Changes
- refactor: remove deprecated RMM L2 non-compliant API endpoints (#272)

**Source:** project-beta-api@bf71e70 "refactor: remove deprecated RMM L2 non-compliant API endpoints (#272)"

## [v0.0.244] - 2025-11-01

### Changes
- test: increase test coverage for PR #269 compliance (#270)

**Source:** project-beta-api@2f6c91a "test: increase test coverage for PR #269 compliance (#270)"

## [v0.0.243] - 2025-11-01

### Changes
- refactor: split large coding-guidelines.md into focused sections (#271)

**Source:** project-beta-api@59e6858 "refactor: split large coding-guidelines.md into focused sections (#271)"

## [v0.0.242] - 2025-11-01

### Changes
- Delete trigger_ci_1758492039 (#267)

**Source:** project-beta-api@74132e4 "Delete trigger_ci_1758492039 (#267)"

## [v0.0.241] - 2025-11-01

### Changes
- Delete monitor_ci.sh (#268)

**Source:** project-beta-api@90666e3 "Delete monitor_ci.sh (#268)"

## [v0.0.240] - 2025-11-01

### Changes
- Delete trigger_ci_1759386332 (#266)

**Source:** project-beta-api@8c99cf8 "Delete trigger_ci_1759386332 (#266)"

## [v0.0.239] - 2025-11-01

### Changes
- Delete monitor_all_ci.sh (#264)

**Source:** project-beta-api@cae5f99 "Delete monitor_all_ci.sh (#264)"

## [v0.0.238] - 2025-11-01

### Changes
- Delete monitor_new_ci.sh (#265)

**Source:** project-beta-api@0fd18d1 "Delete monitor_new_ci.sh (#265)"

## [v0.0.237] - 2025-11-01

### Changes
- Delete openapi_ci.json (#263)

**Source:** project-beta-api@962f973 "Delete openapi_ci.json (#263)"

## [v0.0.236] - 2025-11-01

### Changes
- docs: Add OpenAPI workflow and cross-repo deployment guide (#262)

**Source:** project-beta-api@07b2572 "docs: Add OpenAPI workflow and cross-repo deployment guide (#262)"

## [v0.0.217] - 2025-10-20

### Changes
- feat: Add RMM-2 compliant queue endpoint (RETROFIT-006) (#243)

**Source:** project-beta-api@956be69 "feat: Add RMM-2 compliant queue endpoint (RETROFIT-006) (#243)"

## [v0.0.216] - 2025-10-20

### Changes
- Create API style guide (docs/api-style.md) (#241)

**Source:** project-beta-api@6a6ae59 "Create API style guide (docs/api-style.md) (#241)"

## [v0.0.215] - 2025-10-20

### Changes
- feat: Add RMM-2 compliant /queue/next endpoint (RETROFIT-005) (#242)

**Source:** project-beta-api@2d2d9cc "feat: Add RMM-2 compliant /queue/next endpoint (RETROFIT-005) (#242)"

## [v0.0.214] - 2025-10-19

### Changes
- feat: Add RMM-2 compliant queue initialization endpoint (RETROFIT-004) (#239)

**Source:** project-beta-api@209e9de "feat: Add RMM-2 compliant queue initialization endpoint (RETROFIT-004) (#239)"

## [v0.0.213] - 2025-10-19

### Changes
- docs: Add comprehensive API style guide (RMM-2) (#240)

**Source:** project-beta-api@ea37958 "docs: Add comprehensive API style guide (RMM-2) (#240)"

## [v0.0.212] - 2025-10-19

### Changes
- feat: Rename crawl-queue to queue for RMM L2 compliance (RETROFIT-003) (#238)

**Source:** project-beta-api@5ae0131 "feat: Rename crawl-queue to queue for RMM L2 compliance (RETROFIT-003) (#238)"

## [v0.0.211] - 2025-10-19

### Changes
- feat: Add V2 bulk content approval endpoint (BACKEND-029) (#233)

**Source:** project-beta-api@53bb353 "feat: Add V2 bulk content approval endpoint (BACKEND-029) (#233)"

## [v0.0.210] - 2025-10-19

### Changes
- feat: add RMM-2 compliant PATCH /brands/{brandId}/status endpoint (RETROFIT-002) (#237)

**Source:** project-beta-api@d27c3d5 "feat: add RMM-2 compliant PATCH /brands/{brandId}/status endpoint (RETROFIT-002) (#237)"

## [v0.0.209] - 2025-10-19

### Changes
- feat: add V2 URL content fetching endpoint (BACKEND-032)

**Source:** project-beta-api@45c6b76 "feat: add V2 URL content fetching endpoint (BACKEND-032)"

## [v0.0.208] - 2025-10-19

### Changes
- feat(api): Deprecate /with-files endpoints for RMM-2 compliance (RETROFIT-001) (#236)

**Source:** project-beta-api@c326aeb "feat(api): Deprecate /with-files endpoints for RMM-2 compliance (RETROFIT-001) (#236)"

## [v0.0.207] - 2025-10-18

### Changes
- Add V2 campaign PDF export endpoint (#234)

**Source:** project-beta-api@d582ae6 "Add V2 campaign PDF export endpoint (#234)"

## [v0.0.206] - 2025-10-16

### Changes
- feat: add V2 bulk content approval endpoint (BACKEND-029) (#231)

**Source:** project-beta-api@c213ded "feat: add V2 bulk content approval endpoint (BACKEND-029) (#231)"

## [v0.0.205] - 2025-10-16

### Changes
- feat: add GET /api/v2/campaigns/{id}/export/approval-status endpoint (BACKEND-028) (#230)

**Source:** project-beta-api@7b6143c "feat: add GET /api/v2/campaigns/{id}/export/approval-status endpoint (BACKEND-028) (#230)"

## [v0.0.204] - 2025-10-14

### Changes
- feat: implement GET /api/v2/campaigns/{id}/approval-status endpoint (BACKEND-021) (#224)

**Source:** project-beta-api@9364f9d "feat: implement GET /api/v2/campaigns/{id}/approval-status endpoint (BACKEND-021) (#224)"

## [v0.0.203] - 2025-10-13

### Changes
- feat: implement content images API (BACKEND-022b,c,d) (#226)

**Source:** project-beta-api@f8915eb "feat: implement content images API (BACKEND-022b,c,d) (#226)"

## [v0.0.202] - 2025-10-13

### Changes
- feat: implement /api/v2/threads/{id}/messages endpoints (BACKEND-024) (#229)

**Source:** project-beta-api@c7a4ef0 "feat: implement /api/v2/threads/{id}/messages endpoints (BACKEND-024) (#229)"

## [v0.0.201] - 2025-10-12

### Changes
- feat: implement content images API endpoints (BACKEND-022a-d) (#227)

**Source:** project-beta-api@c8a92fb "feat: implement content images API endpoints (BACKEND-022a-d) (#227)"

## [v0.0.200] - 2025-10-12

### Changes
- feat: add bulk approval endpoint for campaigns (BACKEND-023) (#228)

**Source:** project-beta-api@e44e457 "feat: add bulk approval endpoint for campaigns (BACKEND-023) (#228)"

## [v0.0.199] - 2025-10-12

### Changes
- feat: add content_images table and SQLAlchemy model (BACKEND-022a) (#225)

**Source:** project-beta-api@1a20ea9 "feat: add content_images table and SQLAlchemy model (BACKEND-022a) (#225)"

## [v0.0.198] - 2025-10-12

### Changes
- feat: implement GET /api/v2/users/me endpoint (BACKEND-020) (#223)

**Source:** project-beta-api@d2d3b21 "feat: implement GET /api/v2/users/me endpoint (BACKEND-020) (#223)"

## [v0.0.197] - 2025-10-11

### Changes
- test: increase user_controller coverage to 95%+ (#166)

**Source:** project-beta-api@4d47c26 "test: increase user_controller coverage to 95%+ (#166)"

## [v0.0.196] - 2025-10-11

### Changes
- docs: Add comprehensive V2 coding guidelines (#222)

**Source:** project-beta-api@7549915 "docs: Add comprehensive V2 coding guidelines (#222)"

## [v0.0.195] - 2025-10-11

### Changes
- docs: rewrite AGENTS.md to V2 target state (4571→803 lines) (#220)

**Source:** project-beta-api@7c7ee9d "docs: rewrite AGENTS.md to V2 target state (4571→803 lines) (#220)"

## [v0.0.194] - 2025-10-11

### Changes
- Phase 4: Add V1 to V2 endpoint mapping document (#172)

**Source:** project-beta-api@ade272f "Phase 4: Add V1 to V2 endpoint mapping document (#172)"

## [v0.0.193] - 2025-10-11

### Changes
- test: Verify CI baseline checks on main (#175)

**Source:** project-beta-api@77a6d99 "test: Verify CI baseline checks on main (#175)"

## [v0.0.192] - 2025-10-11

### Changes
- test: add E2E tests for audience suggestions endpoint (#216)

**Source:** project-beta-api@a25536c "test: add E2E tests for audience suggestions endpoint (#216)"

## [v0.0.191] - 2025-10-11

### Changes
- docs: consolidate .ai directory to single README.md file (#219)

**Source:** project-beta-api@013ccf0 "docs: consolidate .ai directory to single README.md file (#219)"

## [v0.0.190] - 2025-10-11

### Changes
- docs: rewrite AGENTS.md to reflect V2 target state (#218)

**Source:** project-beta-api@f02ef8a "docs: rewrite AGENTS.md to reflect V2 target state (#218)"

## [v0.0.189] - 2025-10-11

### Changes
- docs: create .ai directory structure for project-beta-api (#217)

**Source:** project-beta-api@ccf09e0 "docs: create .ai directory structure for project-beta-api (#217)"

## [v0.0.188] - 2025-10-10

### Changes
- feat: implement Instagram OAuth integration endpoint (#213)

**Source:** project-beta-api@c3c33ed "feat: implement Instagram OAuth integration endpoint (#213)"

## [v0.0.187] - 2025-10-10

### Changes
- feat: Instagram OAuth Integration Endpoint (BACKEND-020) (#215)

**Source:** project-beta-api@d5166a2 "feat: Instagram OAuth Integration Endpoint (BACKEND-020) (#215)"

## [v0.0.186] - 2025-10-10

### Changes
- Phase 3: Remove Terraform from API repo (#171)

**Source:** project-beta-api@09c11c5 "Phase 3: Remove Terraform from API repo (#171)"

## [v0.0.185] - 2025-10-09

### Changes
- feat: add E2E tests for campaign content generation (#212)

**Source:** project-beta-api@f14255f "feat: add E2E tests for campaign content generation (#212)"

## [v0.0.184] - 2025-10-09

### Changes
- test: add E2E tests for campaign specifications endpoint (#214)

**Source:** project-beta-api@470ae51 "test: add E2E tests for campaign specifications endpoint (#214)"

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