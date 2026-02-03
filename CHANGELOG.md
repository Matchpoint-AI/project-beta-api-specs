# Changelog

All notable changes to the Project Beta API specification will be documented in this file.

## [v0.7.942] - 2026-02-03

### Changes
- docs(specs): add CI/CD bypass policy for dev environment (#2766)

**Source:** project-beta-api@120c26d2

## [v0.7.941] - 2026-02-03

### Changes
- fix(api): remove model passthrough to Post Generator (#2765)

**Source:** project-beta-api@a9f81fd5

## [v0.7.940] - 2026-02-03

### Changes
- fix: Use claude-sonnet-4.5 as default text model (INVARIANT) (#2764)

**Source:** project-beta-api@d5bf9402

## [v0.7.939] - 2026-02-03

### Changes
- fix: Update deprecated gemini model to gemini-3-flash-preview

**Source:** project-beta-api@594b19fa

## [v0.7.938] - 2026-02-03

### Changes
- fix: Remove webhook callback endpoints (sync architecture) (#2759)

**Source:** project-beta-api@a3cd97e4

## [v0.7.937] - 2026-02-03

### Changes
- fix: Add camelCase aliases to content approval schemas (#2751) (#2756)

**Source:** project-beta-api@a0a0e856

## [v0.7.936] - 2026-02-03

### Changes
- fix: Add PostExportService and PostExportRepository DI bindings (#2757)

**Source:** project-beta-api@5f339da5

## [v0.7.935] - 2026-02-03

### Changes
- fix: Return null instead of 404 for missing campaign policy (#2755)

**Source:** project-beta-api@8e3f7e33

## [v0.7.934] - 2026-02-03

### Changes
- fix: Ensure text_prompt is never empty for image generation (#2750)

**Source:** project-beta-api@217aa4b7

## [v0.7.933] - 2026-02-03

### Changes
- fix: Use campaign.platforms (list) not campaign.platform (500 error) (#2749)

**Source:** project-beta-api@2450004a

## [v0.7.932] - 2026-02-02

### Changes
- fix: bypass content-designer for image regeneration and use correct models (#2748)

**Source:** project-beta-api@02011150

## [v0.7.931] - 2026-02-02

### Changes
- fix: Handle schema mismatches in Content Designer output parsing (#2746)

**Source:** project-beta-api@cbc8554c

## [v0.7.930] - 2026-02-02

### Changes
- fix: Add missing controllers to asgi.py (content generation broken) (#2745)

**Source:** project-beta-api@6538f710

## [v0.7.929] - 2026-02-02

### Changes
- fix(cost): Change default FAL models to cheap alternatives (#2733)

**Source:** project-beta-api@99650b3a

## [v0.7.928] - 2026-02-02

### Changes
- fix(cost): Add billing exhaustion detection to video_generation_client (#2734)

**Source:** project-beta-api@3668b319

## [v0.7.927] - 2026-02-02

### Changes
- fix: Sync media URLs to Posts.image_urls on generation completion

**Source:** project-beta-api@996fb7d8

## [v0.7.926] - 2026-02-02

### Changes
- feat: Add media sync and parallel content generation improvements (#2741)

**Source:** project-beta-api@976946a7

## [v0.7.925] - 2026-02-02

### Changes
- fix: Remove model overrides from API messages to post-generator (#2740)

**Source:** project-beta-api@0ccaff82

## [v0.7.924] - 2026-02-01

### Changes
- feat: Media-centric progress tracking and async media handling (#2739)

**Source:** project-beta-api@e73202ba

## [v0.7.923] - 2026-02-01

### Changes
- feat: Add callbacks controller for async fal.ai webhooks (#2737)

**Source:** project-beta-api@806a02b8

## [v0.7.922] - 2026-02-01

### Changes
- feat(media): Add external_request_id for async webhook callbacks (#2736)

**Source:** project-beta-api@f496e0e1

## [v0.7.921] - 2026-02-01

### Changes
- feat: Add user-friendly prompt support for media items (#2738)

**Source:** project-beta-api@980acd62

## [v0.7.920] - 2026-02-01

### Changes
- spec: Add async media generation with fal.ai webhooks (#2735)

**Source:** project-beta-api@39ef2c74

## [v0.7.919] - 2026-01-30

### Changes
- fix: Return 500 for batch publish failures to trigger Pub/Sub retry (#2716)

**Source:** project-beta-api@a7099530

## [v0.7.918] - 2026-01-30

### Changes
- fix: Use session_maker pattern in BrandEngagementHistoryRepository (#2715)

**Source:** project-beta-api@46456369

## [v0.7.917] - 2026-01-30

### Changes
- fix: Add json_typeof check before json_array_length to prevent scalar error (#2714)

**Source:** project-beta-api@29448cab

## [v0.7.916] - 2026-01-30

### Changes
- fix: Inject BrandEngagementHistoryRepository into ScheduleOptimizerService (#2713)

**Source:** project-beta-api@1a3f6dc4

## [v0.7.915] - 2026-01-30

### Changes
- feat: Emit workflow events to Pub/Sub for pulse-manager (#2710)

**Source:** project-beta-api@984fee81

## [v0.7.914] - 2026-01-29

### Changes
- fix: Remove 10 unused constants from constants.py (#2711)

**Source:** project-beta-api@51391c3d

## [v0.7.913] - 2026-01-29

### Changes
- refactor: Clean dead code comments from dependencies.py (#2706)

**Source:** project-beta-api@86959db3

## [v0.7.912] - 2026-01-29

### Changes
- fix: Remove unused metrics functions (0 callers) (#2708)

**Source:** project-beta-api@cf1eb4d4

## [v0.7.911] - 2026-01-29

### Changes
- fix: Remove duplicate utils/logging_config.py superseded by config version (#2705)

**Source:** project-beta-api@7b188b7d

## [v0.7.910] - 2026-01-29

### Changes
- fix: Remove dead LLMModelRegistry utility class (0 imports) (#2704)

**Source:** project-beta-api@f4fdd0a1

## [v0.7.909] - 2026-01-29

### Changes
- fix: Remove dead research_summary.py schema (0 imports, feature never implemented) (#2707)

**Source:** project-beta-api@5d596e0d

## [v0.7.908] - 2026-01-29

### Changes
- fix: Remove dead pubsub_video_processing_publisher.py (0 imports, no consumer) (#2703)

**Source:** project-beta-api@c8779df6

## [v0.7.907] - 2026-01-29

### Changes
- fix: Content generation E2E pipeline fixes (#2702)

**Source:** project-beta-api@66fc3f0b

## [v0.7.906] - 2026-01-29

### Changes
- spec: Complete Contextual Scene Policy (REQ-9A) (#2684)

**Source:** project-beta-api@ff2cfd46

## [v0.7.905] - 2026-01-29

### Changes
- fix(schema): Handle None values in BrandVoice and TargetAudience (#2701)

**Source:** project-beta-api@7eb4798b

## [v0.7.904] - 2026-01-29

### Changes
- fix: Add missing DI binding for AgenticContentGenerationPublisher (#2699)

**Source:** project-beta-api@a8afb6d4

## [v0.7.903] - 2026-01-29

### Changes
- feat: Add API domains to CORS allowed origins (#2698)

**Source:** project-beta-api@f41e3ea7

## [v0.7.902] - 2026-01-29

### Changes
- feat(tests): Auto-mark tests for fast local iteration (#2695)

**Source:** project-beta-api@29b035b7

## [v0.7.901] - 2026-01-29

### Changes
- perf(tests): Use DROP TABLE instead of DROP/CREATE SCHEMA for test isolation (#2694)

**Source:** project-beta-api@ea4d7b27

## [v0.7.900] - 2026-01-29

### Changes
- spec: ML Rationale Explanation for Human-Readable Decisions (#2683)

**Source:** project-beta-api@b3c297a4

## [v0.7.899] - 2026-01-29

### Changes
- docs(specs): Add post regeneration action types to agentic messages spec (#2681)

**Source:** project-beta-api@b1f9bbc4

## [v0.7.898] - 2026-01-29

### Changes
- perf(tests): Replace time.sleep with freezegun for instant time control (#2693)

**Source:** project-beta-api@c8fb2aef

## [v0.7.897] - 2026-01-29

### Changes
- fix(di): Add ContextualBanditService dependency injection binding (#2696)

**Source:** project-beta-api@cc652c22

## [v0.7.896] - 2026-01-29

### Changes
- perf(tests): Make coverage collection optional for faster local runs (#2692)

**Source:** project-beta-api@75d04406

## [v0.7.895] - 2026-01-29

### Changes
- spec: ML UI Components for V2 Compliance (REQ-15) (#2685)

**Source:** project-beta-api@c5fe910a

## [v0.7.894] - 2026-01-29

### Changes
- feat: Add API fan-out from Content Designer to Post Generator (#2676)

**Source:** project-beta-api@c1a6b042

## [v0.7.893] - 2026-01-29

### Changes
- fix(di): Use interface instead of concrete class in Thompson provider (#2686)

**Source:** project-beta-api@e48bf526

## [v0.7.892] - 2026-01-29

### Changes
- fix: register contextual bandit controller (#2671)

**Source:** project-beta-api@fff812f9

## [v0.7.891] - 2026-01-29

### Changes
- feat: Implement engagement feedback processor for Thompson Sampling (#2672)

**Source:** project-beta-api@c15f1ee9

## [v0.7.890] - 2026-01-29

### Changes
- feat: Wire Phase 3 and Phase 4 ML features to Pub/Sub messages (#2663)

**Source:** project-beta-api@7003f582

## [v0.7.889] - 2026-01-28

### Changes
- feat(ml): Add ML model monitoring and alerting service (#2673)

**Source:** project-beta-api@b00255e9

## [v0.7.888] - 2026-01-28

### Changes
- fix: reduce test connection pool size to prevent exhaustion (#2668)

**Source:** project-beta-api@24a0ed46

## [v0.7.887] - 2026-01-28

### Changes
- docs(specs): Add Phase 3/4 ML and post regeneration to agentic messages spec (#2680)

**Source:** project-beta-api@a9581a29

## [v0.7.886] - 2026-01-28

### Changes
- docs(ml): Add unified ML data flow specification (#2679)

**Source:** project-beta-api@49c24adc

## [v0.7.885] - 2026-01-28

### Changes
- feat(ml): Add hierarchical priors for cold-start handling (#2674)

**Source:** project-beta-api@734bbeb7

## [v0.7.884] - 2026-01-28

### Changes
- refactor: Remove current_ prefix from schema field names (#2667)

**Source:** project-beta-api@40905afd

## [v0.7.883] - 2026-01-28

### Changes
- test: Add timeout tests for PubSubAgenticContentGenerationPublisher (#2669)

**Source:** project-beta-api@916802e2

## [v0.7.882] - 2026-01-28

### Changes
- fix: Remove hardcoded 10% progress, align with pulse-message spec (#2658)

**Source:** project-beta-api@cafc422f

## [v0.7.881] - 2026-01-28

### Changes
- feat(schemas): Add unified media fields for Post model unification (#2664)

**Source:** project-beta-api@a583371e

## [v0.7.880] - 2026-01-28

### Changes
- refactor(specs): Consolidate .ai directory content into /specs (#2665)

**Source:** project-beta-api@ddc073ee

## [v0.7.879] - 2026-01-28

### Changes
- fix(schemas): Add PARTIAL status and imagePromptUsed alias for E2E (#2661)

**Source:** project-beta-api@386a986b

## [v0.7.878] - 2026-01-28

### Changes
- refactor(db): Extract scene_type from Post.data JSON to dedicated column (#2662)

**Source:** project-beta-api@b046650e

## [v0.7.877] - 2026-01-28

### Changes
- fix: add 10s timeout to Pub/Sub future.result() calls (#2660)

**Source:** project-beta-api@9d5aecfe

## [v0.7.876] - 2026-01-28

### Changes
- docs: rename content-generator references to content-designer (#2659)

**Source:** project-beta-api@5a9fd1a5

## [v0.7.875] - 2026-01-28

### Changes
- fix: Update migration workflow to use arc-runner-sa service account (#2656)

**Source:** project-beta-api@d58dde0d

## [v0.7.874] - 2026-01-28

### Changes
- feat: Implement Phase 4 Contextual Bandits + Advanced ML (#2654)

**Source:** project-beta-api@2b37cb56

## [v0.7.873] - 2026-01-28

### Changes
- refactor: rename agentic-brand-crawler references to brand-crawler (#2652)

**Source:** project-beta-api@8f043167

## [v0.7.872] - 2026-01-28

### Changes
- feat(ml): Phase 3 - Schedule Optimization + Performance Prediction (#2653)

**Source:** project-beta-api@d913ae42

## [v0.7.871] - 2026-01-28

### Changes
- chore: Rename AGENTIC_CONTENT_GENERATOR_TOPIC to CONTENT_DESIGNER_TOPIC (#2651)

**Source:** project-beta-api@70abc153

## [v0.7.870] - 2026-01-28

### Changes
- docs: API phase tracking specification (#2648)

**Source:** project-beta-api@72fdb8f6

## [v0.7.869] - 2026-01-28

### Changes
- chore: Remove pubsub webhook alias endpoint (#2649)

**Source:** project-beta-api@4cebfe6f

## [v0.7.868] - 2026-01-28

### Changes
- docs: Rename agentic-content-designer to content-designer (#2650)

**Source:** project-beta-api@62bfede7

## [v0.7.867] - 2026-01-28

### Changes
- fix: Add graceful error handling and test coverage for learning state (#2644 follow-up) (#2647)

**Source:** project-beta-api@eae8ff9b

## [v0.7.866] - 2026-01-28

### Changes
- chore: Remove dead SSE endpoint - frontend uses polling (#2646)

**Source:** project-beta-api@965002f4

## [v0.7.865] - 2026-01-28

### Changes
- P0 Fix: Wire Thompson Sampling learning state to Content Designer (#2644)

**Source:** project-beta-api@15368a95

## [v0.7.864] - 2026-01-28

### Changes
- docs: Emphasize API as hub in hub-and-spoke architecture (#2645)

**Source:** project-beta-api@dbfa39b0

## [v0.7.863] - 2026-01-28

### Changes
- refactor(tests): Update content-generator refs to service split names (#2628)

**Source:** project-beta-api@d0666790

## [v0.7.862] - 2026-01-28

### Changes
- chore: Enforce 90% test coverage threshold (#2643)

**Source:** project-beta-api@16b15269

## [v0.7.861] - 2026-01-28

### Changes
- chore(specs): Enforce folder-based specification structure (#2637)

**Source:** project-beta-api@c2013349

## [v0.7.860] - 2026-01-28

### Changes
- test: Add tests for scene_performance_metrics and policy_version repositories (#2636)

**Source:** project-beta-api@aa100f14

## [v0.7.859] - 2026-01-28

### Changes
- chore: update content-generator refs in controllers (#2627)

**Source:** project-beta-api@f3156e91

## [v0.7.858] - 2026-01-28

### Changes
- refactor: Remove unused WebSocket dead code (#2640)

**Source:** project-beta-api@2ac300dd

## [v0.7.857] - 2026-01-27

### Changes
- test: Add comprehensive tests for session service (#2639)

**Source:** project-beta-api@31d517d6

## [v0.7.856] - 2026-01-27

### Changes
- docs(specs): Add repository specifications for tested components (#2641)

**Source:** project-beta-api@92e2ccaf

## [v0.7.855] - 2026-01-27

### Changes
- refactor(schemas): Update content-generator refs to post-generator (#2625)

**Source:** project-beta-api@178bbf66

## [v0.7.854] - 2026-01-27

### Changes
- test: Add comprehensive tests for scene mix plan repository (#2635)

**Source:** project-beta-api@43047e7f

## [v0.7.853] - 2026-01-27

### Changes
- docs(specs): Add hub-and-spoke architecture documentation (#2638)

**Source:** project-beta-api@560cedbe

## [v0.7.852] - 2026-01-27

### Changes
- test: Add comprehensive tests for crawler brief repository (#2634)

**Source:** project-beta-api@727501c6

## [v0.7.851] - 2026-01-27

### Changes
- test: Add tests for brand_guardrail and campaign_post repositories (#2633)

**Source:** project-beta-api@c836b557

## [v0.7.850] - 2026-01-27

### Changes
- test: Add comprehensive tests for content generator output repository (#2632)

**Source:** project-beta-api@b0b3411a

## [v0.7.849] - 2026-01-27

### Changes
- test: Add comprehensive tests for session repository (#2630)

**Source:** project-beta-api@7e3ac31e

## [v0.7.848] - 2026-01-27

### Changes
- test: Add comprehensive tests for dead letter queue repository (#2631)

**Source:** project-beta-api@a9c7766c

## [v0.7.847] - 2026-01-27

### Changes
- refactor(services): Rename content-generator to post-generator (#2626)

**Source:** project-beta-api@45b29a4d

## [v0.7.846] - 2026-01-27

### Changes
- chore: Add CODEOWNERS to protect specs/ directory (#2624)

**Source:** project-beta-api@9549f58e

## [v0.7.845] - 2026-01-27

### Changes
- chore: Baseline coverage configuration for 90% target (#2623)

**Source:** project-beta-api@1ff519a3

## [v0.7.844] - 2026-01-27

### Changes
- docs: Update documentation for content generator service split (#2629)

**Source:** project-beta-api@60ef5b33

## [v0.7.843] - 2026-01-27

### Changes
- Remove orphaned url_fetch_service, utility schemas, and broken task import (YAGNI) (#2622)

**Source:** project-beta-api@185df809

## [v0.7.842] - 2026-01-27

### Changes
- feat(ml): Add Phase 2 Thompson Sampling for scene selection (#2618)

**Source:** project-beta-api@f8aea9bf

## [v0.7.841] - 2026-01-27

### Changes
- Remove dead test_seed_controller and version_controller (YAGNI) (#2619)

**Source:** project-beta-api@b42ddda1

## [v0.7.840] - 2026-01-27

### Changes
- docs(specs): Add ML Features spec for Phases 2-4 (#2616)

**Source:** project-beta-api@20460b33

## [v0.7.839] - 2026-01-27

### Changes
- Remove unused notification system and brand_users model (YAGNI) (#2613)

**Source:** project-beta-api@38a25d50

## [v0.7.838] - 2026-01-27

### Changes
- feat: Add learning state to agentic content generation message (#2611)

**Source:** project-beta-api@0e0de669

## [v0.7.837] - 2026-01-27

### Changes
- spec: Add agentic message schema - learning state extension (#2610)

**Source:** project-beta-api@7dd5d643

## [v0.7.836] - 2026-01-27

### Changes
- feat: Add ML feedback API endpoints for Phase 1 (#2609)

**Source:** project-beta-api@bd824179

## [v0.7.835] - 2026-01-27

### Changes
- chore: Remove BuildKit caching (#2608)

**Source:** project-beta-api@0b870f06

## [v0.7.834] - 2026-01-27

### Changes
- feat(test): Add endpoint to force-verify users for E2E testing (#2606)

**Source:** project-beta-api@6535aa66

## [v0.7.833] - 2026-01-27

### Changes
- feat(test): Add endpoint to seed brand knowledge for E2E testing (#2605)

**Source:** project-beta-api@f5fb53d5

## [v0.7.832] - 2026-01-27

### Changes
- fix: Ensure brand knowledge_status updates correctly from crawler output (#2602)

**Source:** project-beta-api@21a08768

## [v0.7.831] - 2026-01-27

### Changes
- feat(specs): Add functional requirements v2 for scene mix planner and APIs (#2604)

**Source:** project-beta-api@774afd57

## [v0.7.830] - 2026-01-27

### Changes
- chore: Remove dead schema files (audience_suggestions, locations) (#2603)

**Source:** project-beta-api@320b50e7

## [v0.7.829] - 2026-01-27

### Changes
- feat(api): Simplify knowledge status enum to 3 values (#1042) (#2601)

**Source:** project-beta-api@5ded0a4a

## [v0.7.828] - 2026-01-27

### Changes
- docs(specs): Add spec ethos guidelines to README (#2600)

**Source:** project-beta-api@cdf0f1b1

## [v0.7.827] - 2026-01-27

### Changes
- docs(specs): Update brands invariants and SPEC for simplified crawl (#2598)

**Source:** project-beta-api@997a199f

## [v0.7.826] - 2026-01-27

### Changes
- docs(specs): Update flow.md for single-output brand crawl architecture (#2596)

**Source:** project-beta-api@78450bdc

## [v0.7.825] - 2026-01-27

### Changes
- feat: Add handler for simplified brand crawl output (#2592)

**Source:** project-beta-api@e58ff8b8

## [v0.7.824] - 2026-01-27

### Changes
- docs: Update crawler specs for single-output architecture (#2594)

**Source:** project-beta-api@5263a1d5

## [v0.7.823] - 2026-01-26

### Changes
- feat(api): Add DELETE /brands/{brand_id} endpoint (#2589)

**Source:** project-beta-api@c228d75e

## [v0.7.822] - 2026-01-26

### Changes
- docs(spec): Remove pulse infrastructure from crawler specs (#2587)

**Source:** project-beta-api@080ba0a8

## [v0.7.821] - 2026-01-25

### Changes
- fix(cors): Add missing CORS origins to rate limiter (Issue #2582) (#2583)

**Source:** project-beta-api@f0c7010f

## [v0.7.820] - 2026-01-25

### Changes
- fix(deps): Pin bcrypt <5.0 for passlib 1.7.4 compatibility (#2578)

**Source:** project-beta-api@e02fcc3e

## [v0.7.819] - 2026-01-25

### Changes
- docs(specs): Add README.md with specification standards and index (#2580)

**Source:** project-beta-api@9502c638

## [v0.7.818] - 2026-01-25

### Changes
- feat(security): Add password complexity requirements for user registration (#2546)

**Source:** project-beta-api@4a040aa7

## [v0.7.817] - 2026-01-25

### Changes
- fix(docker): Align Playwright version with base image to fix release builds (Issue #2576) (#2577)

**Source:** project-beta-api@7ebc3d7a

## [v0.7.816] - 2026-01-25

### Changes
- chore: Remove deprecated image regeneration endpoint (Issue #2506) (#2569)

**Source:** project-beta-api@014dc830

## [v0.7.815] - 2026-01-25

### Changes
- feat(brands): persist full brand crawler data to PostgreSQL (Issue #2183) (#2555)

**Source:** project-beta-api@f361529e

## [v0.7.814] - 2026-01-25

### Changes
- feat: Add progress and estimatedTimeRemaining to VideoJobStatusResponse (#2570)

**Source:** project-beta-api@c4476829

## [v0.7.813] - 2026-01-25

### Changes
- fix: SQLAlchemy enum case and post ID uniqueness issues (#2472)

**Source:** project-beta-api@9818a75a

## [v0.7.812] - 2026-01-25

### Changes
- Merge pull request #2497 from Matchpoint-AI/fix/2494-brand-creation

**Source:** project-beta-api@c2d35df7

## [v0.7.811] - 2026-01-25

### Changes
- chore: trigger release workflow (2nd attempt) (Issue #2571) (#2573)

**Source:** project-beta-api@ceea0658

## [v0.7.811] - 2026-01-25

### Changes
- chore: trigger release workflow after tag deletion (Issue #2571) (#2572)

**Source:** project-beta-api@52eb3a06

## [v0.7.811] - 2026-01-25

### Changes
- docker: bump playwright/python from v1.48.0-noble to v1.57.0-noble (#2327)

**Source:** project-beta-api@6d675e81

## [v0.7.810] - 2026-01-25

### Changes
- ci: Bump actions/setup-python from 5 to 6 (#2528)

**Source:** project-beta-api@544fa6c2

## [v0.7.809] - 2026-01-25

### Changes
- feat(deps): Register PostMediaPersistenceService for GCS media persistence (#2565)

**Source:** project-beta-api@95ff1f0e

## [v0.7.808] - 2026-01-25

### Changes
- fix(security): Add authentication to /api/v2/metrics endpoint (Issue #2556) (#2564)

**Source:** project-beta-api@a62b13fd

## [v0.7.807] - 2026-01-25

### Changes
- fix(security): Add authentication to /pulses/{correlation_id} endpoint (Issue #2557) (#2561)

**Source:** project-beta-api@e637aaac

## [v0.7.806] - 2026-01-25

### Changes
- fix(security): Add authentication to /campaigns/{campaign_id}/scheduled-posts endpoint (Issue #2558) (#2562)

**Source:** project-beta-api@490058b6

## [v0.7.805] - 2026-01-25

### Changes
- fix(security): Add authentication to brand knowledge endpoints (Issue #2553) (#2560)

**Source:** project-beta-api@9a474ba7

## [v0.7.804] - 2026-01-25

### Changes
- fix(auth): Add authentication to content captions GET/DELETE endpoints (#2559)

**Source:** project-beta-api@10d1013c

## [v0.7.803] - 2026-01-25

### Changes
- fix(content-export): Fix TypeError in content exports endpoint (Issue #2547) (#2552)

**Source:** project-beta-api@603afb37

## [v0.7.802] - 2026-01-25

### Changes
- fix(auth): Support direct login with email/password at POST /auth/session (Issue #2549) (#2551)

**Source:** project-beta-api@1639b00e

## [v0.7.801] - 2026-01-25

### Changes
- fix(security): Add authentication to content prompt endpoints (#2550)

**Source:** project-beta-api@5b636da6

## [v0.7.800] - 2026-01-25

### Changes
- docs: Add CORS & rate-limit checklist to PR template (#2545)

**Source:** project-beta-api@cea71aee

## [v0.7.799] - 2026-01-24

### Changes
- deps(deps-dev): Bump black from 25.1.0 to 26.1.0 (#2531)

**Source:** project-beta-api@cbfce841

## [v0.7.798] - 2026-01-24

### Changes
- deps(deps-dev): Bump ruff from 0.7.0 to 0.14.14 (#2532)

**Source:** project-beta-api@72caa386

## [v0.7.797] - 2026-01-24

### Changes
- docs(specs): add SPEC.md and invariants.md for spec directory compliance (#2543)

**Source:** project-beta-api@62610687

## [v0.7.796] - 2026-01-24

### Changes
- fix(email): validate SendGrid API key at initialization (Issue #2541) (#2542)

**Source:** project-beta-api@e0de095d

## [v0.7.795] - 2026-01-24

### Changes
- fix(pulses): return 'pending' status instead of 404 when no pulse exists (#2538) (#2539)

**Source:** project-beta-api@aa8257dc

## [v0.7.794] - 2026-01-24

### Changes
- Merge pull request #2537 from Matchpoint-AI/fix/924-rate-limiter-users-me

**Source:** project-beta-api@68f35407

## [v0.7.793] - 2026-01-23

### Changes
- fix(brand-crawler): increase timeout from 600s to 900s (#2535)

**Source:** project-beta-api@41573e7d

## [v0.7.792] - 2026-01-23

### Changes
- Merge pull request #2523 from Matchpoint-AI/fix/2522-rate-limiter-polling

**Source:** project-beta-api@f8431748

## [v0.7.791] - 2026-01-23

### Changes
- Merge pull request #2151 from Matchpoint-AI/feat/2127-policy-versioning

**Source:** project-beta-api@b7ee27dd

## [v0.7.790] - 2026-01-23

### Changes
- Merge pull request #2521 from Matchpoint-AI/fix/2517

**Source:** project-beta-api@0e98d534

## [v0.7.789] - 2026-01-23

### Changes
- Merge pull request #2520 from Matchpoint-AI/fix/2519-cors-rate-limit

**Source:** project-beta-api@d53ccf65

## [v0.7.788] - 2026-01-23

### Changes
- Merge pull request #2516 from Matchpoint-AI/fix/2515-sse-pulse-ttl

**Source:** project-beta-api@7acfcede

## [v0.7.787] - 2026-01-23

### Changes
- Merge pull request #2514 from Matchpoint-AI/feat/2212-gcs-media-persistence

**Source:** project-beta-api@cfd1d5c6

## [v0.7.786] - 2026-01-23

### Changes
- docs: Update README with accurate counts and fix broken links (#2512)

**Source:** project-beta-api@9545fbc6

## [v0.7.785] - 2026-01-23

### Changes
- Merge pull request #2510 from Matchpoint-AI/fix/2509

**Source:** project-beta-api@50c2fcec

## [v0.7.784] - 2026-01-23

### Changes
- Merge pull request #2511 from Matchpoint-AI/fix/2406

**Source:** project-beta-api@43929e45

## [v0.7.783] - 2026-01-23

### Changes
- Merge pull request #2507 from Matchpoint-AI/fix/2505

**Source:** project-beta-api@1964ee03

## [v0.7.782] - 2026-01-23

### Changes
- feat: Add undo/revert capability for approval decisions (#2062)

**Source:** project-beta-api@5c242c5e

## [v0.7.781] - 2026-01-23

### Changes
- Merge pull request #2503 from Matchpoint-AI/fix/2502-cors-rate-limit

**Source:** project-beta-api@e9e99234

## [v0.7.780] - 2026-01-23

### Changes
- Merge pull request #2501 from Matchpoint-AI/fix/2496-idempotent-verification

**Source:** project-beta-api@94de0b46

## [v0.7.779] - 2026-01-23

### Changes
- Merge pull request #2495 from Matchpoint-AI/fix/2494-brand-creation-flow

**Source:** project-beta-api@c363b98f

## [v0.7.778] - 2026-01-23

### Changes
- Merge pull request #2493 from Matchpoint-AI/fix/2492-sse-cors-consistency

**Source:** project-beta-api@a94f8733

## [v0.7.777] - 2026-01-23

### Changes
- Merge pull request #2491 from Matchpoint-AI/fix/2490-sse-cors

**Source:** project-beta-api@b9eed441

## [v0.7.776] - 2026-01-23

### Changes
- feat(pulses): Add SSE streaming endpoint for real-time progress updates (#2489)

**Source:** project-beta-api@e7619346

## [v0.7.775] - 2026-01-22

### Changes
- Merge pull request #2487 from Matchpoint-AI/fix/2393-code-coverage

**Source:** project-beta-api@299dc914

## [v0.7.774] - 2026-01-22

### Changes
- Merge pull request #2486 from Matchpoint-AI/fix/2485-password-reset

**Source:** project-beta-api@86d9a42c

## [v0.7.773] - 2026-01-22

### Changes
- fix: Require brand_id in BrandDataMessage schema (Issue #2451) (#2483)

**Source:** project-beta-api@540c1eb0

## [v0.7.772] - 2026-01-22

### Changes
- docs: Update README to fat message + status cache architecture (#2482)

**Source:** project-beta-api@d9bf7db9

## [v0.7.771] - 2026-01-22

### Changes
- feat: Add strict validation mode for brand briefs (Issue #2453) (#2481)

**Source:** project-beta-api@f4b3daac

## [v0.7.770] - 2026-01-22

### Changes
- Merge pull request #2480 from Matchpoint-AI/fix/2446-pubsub-brand-crawl-events

**Source:** project-beta-api@d120042a

## [v0.7.769] - 2026-01-22

### Changes
- Merge pull request #2479 from Matchpoint-AI/fix/2808-avro-hyphen

**Source:** project-beta-api@2dc146e0

## [v0.7.768] - 2026-01-22

### Changes
- Merge pull request #2478 from Matchpoint-AI/fix/2477-timeout

**Source:** project-beta-api@99f4b224

## [v0.7.767] - 2026-01-22

### Changes
- Merge pull request #2475 from Matchpoint-AI/fix/2442-cache-status

**Source:** project-beta-api@27bf5e2b

## [v0.7.766] - 2026-01-21

### Changes
- fix: Add missing scene_mix_controller to asgi.py CONTROLLERS (#2474)

**Source:** project-beta-api@4116f608

## [v0.7.765] - 2026-01-21

### Changes
- Merge pull request #2471 from Matchpoint-AI/fix/2461-color-role-mapping

**Source:** project-beta-api@af5bb634

## [v0.7.764] - 2026-01-21

### Changes
- Merge pull request #2469 from Matchpoint-AI/fix/2459-scene-mix-endpoint

**Source:** project-beta-api@333bf25d

## [v0.7.763] - 2026-01-21

### Changes
- Merge pull request #2449 from Matchpoint-AI/feat/remove-signup-industry

**Source:** project-beta-api@e9920115

## [v0.7.762] - 2026-01-21

### Changes
- test: increase test coverage toward 90% goal (#2241)

**Source:** project-beta-api@a0a1dd14

## [v0.7.761] - 2026-01-21

### Changes
- Merge pull request #2466 from Matchpoint-AI/fix/crawler-format-tolerances

**Source:** project-beta-api@52676ee9

## [v0.7.760] - 2026-01-21

### Changes
- Merge pull request #2463 from Matchpoint-AI/fix/deep-brief-schema-validators

**Source:** project-beta-api@953d7e18

## [v0.7.759] - 2026-01-20

### Changes
- Merge pull request #2448 from Matchpoint-AI/fix/2447-deep-data-schema

**Source:** project-beta-api@b29030cf

## [v0.7.758] - 2026-01-20

### Changes
- Merge pull request #2445 from Matchpoint-AI/fix/2441-brand-analysis-status

**Source:** project-beta-api@835d7328

## [v0.7.757] - 2026-01-20

### Changes
- Merge pull request #2457 from Matchpoint-AI/docs/spec-api-endpoints

**Source:** project-beta-api@e6023e91

## [v0.7.756] - 2026-01-19

### Changes
- fix(briefs): Lookup brand_id from DB when not in DEEP message (#2452)

**Source:** project-beta-api@f20791c1

## [v0.7.755] - 2026-01-18

### Changes
- Merge pull request #2440 from Matchpoint-AI/fix/2439-buildkit-cache

**Source:** project-beta-api@d931727b

## [v0.7.754] - 2026-01-18

### Changes
- fix(crawl-analytics): Handle NULL values in SQL aggregation results (#2438)

**Source:** project-beta-api@912753da

## [v0.7.753] - 2026-01-18

### Changes
- fix: use brand workflow_id as correlation_id for pulse polling (#2434) (#2435)

**Source:** project-beta-api@d0f56aa0

## [v0.7.752] - 2026-01-18

### Changes
- feat(ci): add BuildKit cache-dance for faster Docker builds (#2433)

**Source:** project-beta-api@4b77f621

## [v0.7.751] - 2026-01-18

### Changes
- Merge pull request #2430 from Matchpoint-AI/fix/2428

**Source:** project-beta-api@6bf12a2f

## [v0.7.750] - 2026-01-18

### Changes
- Merge pull request #2426 from Matchpoint-AI/fix/2425-pulses-endpoint

**Source:** project-beta-api@f0618a0c

## [v0.7.749] - 2026-01-18

### Changes
- Merge pull request #2421 from Matchpoint-AI/feat/2530-audience-brief-persistence

**Source:** project-beta-api@e532fc33

## [v0.7.748] - 2026-01-18

### Changes
- chore(#2422): Merge Alembic migration branches (#2423)

**Source:** project-beta-api@d7f1bc1a

## [v0.7.747] - 2026-01-18

### Changes
- Merge pull request #2420 from Matchpoint-AI/fix/api-readme-agentic-status

**Source:** project-beta-api@ae925108

## [v0.7.746] - 2026-01-17

### Changes
- Merge pull request #2416 from Matchpoint-AI/feat/860-api-agentic-docs

**Source:** project-beta-api@a55f6413

## [v0.7.745] - 2026-01-17

### Changes
- Merge pull request #2390 from Matchpoint-AI/fix/2061

**Source:** project-beta-api@7e14aed4

## [v0.7.744] - 2026-01-17

### Changes
- Merge pull request #2415 from Matchpoint-AI/fix/2414-remove-cloud-workflows-references

**Source:** project-beta-api@513834e7

## [v0.7.743] - 2026-01-17

### Changes
- Merge pull request #2391 from Matchpoint-AI/fix/2060

**Source:** project-beta-api@939450d1

## [v0.7.742] - 2026-01-17

### Changes
- Merge pull request #2363 from Matchpoint-AI/fix/2362

**Source:** project-beta-api@c41cda9e

## [v0.7.741] - 2026-01-17

### Changes
- Merge pull request #2413 from Matchpoint-AI/fix/2412-cors-frontend-version

**Source:** project-beta-api@38058db2

## [v0.7.740] - 2026-01-17

### Changes
- Merge pull request #2409 from Matchpoint-AI/fix/2408

**Source:** project-beta-api@0f984538

## [v0.7.739] - 2026-01-17

### Changes
- Merge pull request #2407 from Matchpoint-AI/docs/api-access-architecture-2633

**Source:** project-beta-api@967571b8

## [v0.7.738] - 2026-01-17

### Changes
- Merge pull request #2401 from Matchpoint-AI/fix/2394-posts-failed-v3

**Source:** project-beta-api@b342742d

## [v0.7.737] - 2026-01-17

### Changes
- fix(schemas): Add camelCase serialization to scheduled_post.py schemas (#2402)

**Source:** project-beta-api@5a0c5a25

## [v0.7.736] - 2026-01-17

### Changes
- fix: Use str type for campaign_id in generate_scene_mix_plan_async (#2404)

**Source:** project-beta-api@adfe7914

## [v0.7.735] - 2026-01-17

### Changes
- fix: Add camelCase serialization to media.py schemas (#2403)

**Source:** project-beta-api@a1d8dd7f

## [v0.7.734] - 2026-01-17

### Changes
- Merge pull request #2398 from Matchpoint-AI/fix/2396-correlation-id

**Source:** project-beta-api@407e88f6

## [v0.7.733] - 2026-01-17

### Changes
- Merge pull request #2400 from Matchpoint-AI/fix/2395-accurate-counts

**Source:** project-beta-api@fe630fc3

## [v0.7.732] - 2026-01-17

### Changes
- fix(#818): Remove all Firestore references from project-beta-api (#2397)

**Source:** project-beta-api@0afc67f5

## [v0.7.731] - 2026-01-17

### Changes
- fix: Suppress Pydantic protected namespace warnings for model_used fields (#2266)

**Source:** project-beta-api@54361b34

## [v0.7.730] - 2026-01-17

### Changes
- Merge pull request #2159 from Matchpoint-AI/feat/2059-workflow-notifications

**Source:** project-beta-api@664421c8

## [v0.7.729] - 2026-01-17

### Changes
- Merge pull request #2381 from Matchpoint-AI/fix/2364

**Source:** project-beta-api@5fc4aa74

## [v0.7.728] - 2026-01-17

### Changes
- Merge pull request #2154 from Matchpoint-AI/feat/2067-asset-availability

**Source:** project-beta-api@ea8896d0

## [v0.7.727] - 2026-01-17

### Changes
- Merge pull request #2157 from Matchpoint-AI/feat/2063-soft-delete

**Source:** project-beta-api@c13f1e87

## [v0.7.726] - 2026-01-17

### Changes
- fix(schemas): Add camelCase serialization to version schemas (#2383)

**Source:** project-beta-api@0d82f28a

## [v0.7.725] - 2026-01-17

### Changes
- Merge pull request #2380 from Matchpoint-AI/fix/2066

**Source:** project-beta-api@17714855

## [v0.7.724] - 2026-01-17

### Changes
- Merge pull request #2378 from Matchpoint-AI/fix/2252

**Source:** project-beta-api@bf7e073f

## [v0.7.723] - 2026-01-17

### Changes
- Merge pull request #2323 from Matchpoint-AI/fix/2300

**Source:** project-beta-api@d321f90e

## [v0.7.722] - 2026-01-17

### Changes
- Merge pull request #2376 from Matchpoint-AI/fix/2315

**Source:** project-beta-api@a9637763

## [v0.7.721] - 2026-01-17

### Changes
- Merge pull request #2375 from Matchpoint-AI/fix/2293

**Source:** project-beta-api@7eba94d3

## [v0.7.720] - 2026-01-17

### Changes
- Merge pull request #2377 from Matchpoint-AI/fix/2372-dead-code-removal

**Source:** project-beta-api@fc7769a8

## [v0.7.719] - 2026-01-17

### Changes
- Merge pull request #2324 from Matchpoint-AI/fix/2310

**Source:** project-beta-api@8f03dfa7

## [v0.7.718] - 2026-01-17

### Changes
- Merge pull request #2320 from Matchpoint-AI/fix/2302

**Source:** project-beta-api@cb83ab0a

## [v0.7.717] - 2026-01-17

### Changes
- Merge pull request #2325 from Matchpoint-AI/fix/2317

**Source:** project-beta-api@0720016f

## [v0.7.716] - 2026-01-16

### Changes
- Merge pull request #2374 from Matchpoint-AI/fix/2282

**Source:** project-beta-api@e31e0218

## [v0.7.715] - 2026-01-16

### Changes
- Merge pull request #2371 from Matchpoint-AI/fix/2215

**Source:** project-beta-api@98ecc660

## [v0.7.714] - 2026-01-16

### Changes
- Merge pull request #2366 from Matchpoint-AI/fix/2365

**Source:** project-beta-api@8b8c6e2d

## [v0.7.713] - 2026-01-16

### Changes
- Merge pull request #2319 from Matchpoint-AI/fix/2307

**Source:** project-beta-api@98f83fc2

## [v0.7.712] - 2026-01-16

### Changes
- Merge pull request #2321 from Matchpoint-AI/fix/2306

**Source:** project-beta-api@9d1ff15c

## [v0.7.711] - 2026-01-16

### Changes
- Merge pull request #2318 from Matchpoint-AI/fix/2305

**Source:** project-beta-api@8a529b0b

## [v0.7.710] - 2026-01-16

### Changes
- Merge pull request #2348 from Matchpoint-AI/fix/2346

**Source:** project-beta-api@654ebd6c

## [v0.7.709] - 2026-01-16

### Changes
- Merge pull request #2349 from Matchpoint-AI/fix/2345

**Source:** project-beta-api@bffcb908

## [v0.7.708] - 2026-01-16

### Changes
- Merge pull request #2352 from Matchpoint-AI/fix/2125

**Source:** project-beta-api@d4bcd885

## [v0.7.707] - 2026-01-16

### Changes
- Merge pull request #2357 from Matchpoint-AI/fix/2247

**Source:** project-beta-api@cb02cd98

## [v0.7.706] - 2026-01-16

### Changes
- Merge pull request #2351 from Matchpoint-AI/fix/2258

**Source:** project-beta-api@33c1953d

## [v0.7.705] - 2026-01-16

### Changes
- Merge pull request #2335 from Matchpoint-AI/dependabot/pip/pytest-xdist-3.8.0

**Source:** project-beta-api@5f2215a0

## [v0.7.704] - 2026-01-16

### Changes
- Merge pull request #2356 from Matchpoint-AI/fix/2249-legacy-cleanup

**Source:** project-beta-api@fdfe0510

## [v0.7.703] - 2026-01-16

### Changes
- Merge pull request #2343 from Matchpoint-AI/fix/2298

**Source:** project-beta-api@a3c3b9c4

## [v0.7.702] - 2026-01-16

### Changes
- Merge pull request #2355 from Matchpoint-AI/fix/2354-startdate-schema

**Source:** project-beta-api@4eb17ef5

## [v0.7.701] - 2026-01-16

### Changes
- Merge pull request #2334 from Matchpoint-AI/dependabot/pip/pytest-env-1.2.0

**Source:** project-beta-api@b445fa48

## [v0.7.700] - 2026-01-16

### Changes
- Merge pull request #2336 from Matchpoint-AI/dependabot/pip/pytest-mock-3.15.1

**Source:** project-beta-api@498515e4

## [v0.7.699] - 2026-01-16

### Changes
- Merge pull request #2347 from Matchpoint-AI/fix/2248

**Source:** project-beta-api@2fc25877

## [v0.7.698] - 2026-01-16

### Changes
- Merge pull request #2339 from Matchpoint-AI/dependabot/pip/ruff-0.14.13

**Source:** project-beta-api@7b33c266

## [v0.7.697] - 2026-01-16

### Changes
- Merge pull request #2340 from Matchpoint-AI/dependabot/pip/pytest-8.4.2

**Source:** project-beta-api@cd170b4e

## [v0.7.696] - 2026-01-16

### Changes
- Merge pull request #2309 from Matchpoint-AI/fix/2295

**Source:** project-beta-api@40fc8b0c

## [v0.7.695] - 2026-01-16

### Changes
- Merge pull request #2350 from Matchpoint-AI/fix/2245

**Source:** project-beta-api@f7a5577f

## [v0.7.694] - 2026-01-16

### Changes
- Merge pull request #2337 from Matchpoint-AI/dependabot/pip/pytest-asyncio-1.3.0

**Source:** project-beta-api@e2792a82

## [v0.7.693] - 2026-01-16

### Changes
- Merge pull request #2338 from Matchpoint-AI/dependabot/pip/black-25.12.0

**Source:** project-beta-api@5fcc5f0f

## [v0.7.692] - 2026-01-16

### Changes
- Merge pull request #2331 from Matchpoint-AI/dependabot/github_actions/tj-actions/changed-files-47

**Source:** project-beta-api@b0d29ac6

## [v0.7.691] - 2026-01-16

### Changes
- Merge pull request #2341 from Matchpoint-AI/dependabot/pip/pytest-cov-7.0.0

**Source:** project-beta-api@5ebf3cb8

## [v0.7.690] - 2026-01-16

### Changes
- Merge pull request #2344 from Matchpoint-AI/fix/2246

**Source:** project-beta-api@f1a084a7

## [v0.7.689] - 2026-01-16

### Changes
- Merge pull request #2342 from Matchpoint-AI/fix/2250

**Source:** project-beta-api@192ebda6

## [v0.7.688] - 2026-01-16

### Changes
- Merge pull request #2322 from Matchpoint-AI/fix/2297

**Source:** project-beta-api@7f447a9d

## [v0.7.687] - 2026-01-16

### Changes
- Merge pull request #2326 from Matchpoint-AI/fix/2312

**Source:** project-beta-api@f4fc3bde

## [v0.7.686] - 2026-01-16

### Changes
- fix(security): Mask email addresses in log statements (#2296)

**Source:** project-beta-api@90e20b5c

## [v0.7.685] - 2026-01-16

### Changes
- feat: Add notification system for post status changes (#2289)

**Source:** project-beta-api@bc267ed7

## [v0.7.684] - 2026-01-16

### Changes
- Merge pull request #2275 from Matchpoint-AI/fix/2264

**Source:** project-beta-api@76e2ce0d

## [v0.7.683] - 2026-01-16

### Changes
- Merge pull request #2294 from Matchpoint-AI/fix/2285

**Source:** project-beta-api@58417610

## [v0.7.682] - 2026-01-16

### Changes
- fix(deps): Update aiohttp to 3.12.14 to fix CVE-2025-53643 (#2290)

**Source:** project-beta-api@9fcda98f

## [v0.7.681] - 2026-01-16

### Changes
- Merge pull request #2280 from Matchpoint-AI/fix/2274

**Source:** project-beta-api@91e346f6

## [v0.7.680] - 2026-01-16

### Changes
- feat: Add brand-specific prior lookup from database (#2288)

**Source:** project-beta-api@18a96b67

## [v0.7.679] - 2026-01-16

### Changes
- Merge pull request #2237 from Matchpoint-AI/chore/2190-remove-llm-code

**Source:** project-beta-api@ddfc789e

## [v0.7.678] - 2026-01-16

### Changes
- Merge pull request #2278 from Matchpoint-AI/fix/2270-content-generation-posts

**Source:** project-beta-api@96dfe9f9

## [v0.7.677] - 2026-01-16

### Changes
- Merge pull request #2279 from Matchpoint-AI/fix/2268-remove-print

**Source:** project-beta-api@ac4206cb

## [v0.7.676] - 2026-01-16

### Changes
- Merge pull request #2283 from Matchpoint-AI/fix/2281

**Source:** project-beta-api@01009ace

## [v0.7.675] - 2026-01-16

### Changes
- Merge pull request #2287 from Matchpoint-AI/fix/2254

**Source:** project-beta-api@0d1ceaa9

## [v0.7.674] - 2026-01-16

### Changes
- Merge pull request #2277 from Matchpoint-AI/fix/2261

**Source:** project-beta-api@4548a292

## [v0.7.673] - 2026-01-16

### Changes
- Merge pull request #2276 from Matchpoint-AI/fix/2268

**Source:** project-beta-api@06dce37f

## [v0.7.672] - 2026-01-16

### Changes
- Merge pull request #2273 from Matchpoint-AI/fix/2265

**Source:** project-beta-api@a6550df6

## [v0.7.671] - 2026-01-16

### Changes
- Merge pull request #2271 from Matchpoint-AI/fix/2260

**Source:** project-beta-api@1c45565f

## [v0.7.670] - 2026-01-16

### Changes
- Merge pull request #2242 from Matchpoint-AI/feat/coverage-gates-647

**Source:** project-beta-api@b1b0b4ec

## [v0.7.669] - 2026-01-16

### Changes
- Merge pull request #2244 from Matchpoint-AI/fix/2243-add-fsspec

**Source:** project-beta-api@e62fe76e

## [v0.7.668] - 2026-01-16

### Changes
- test: Improve post_service.py test coverage to 97% (#2240)

**Source:** project-beta-api@60a97a35

## [v0.7.667] - 2026-01-16

### Changes
- Merge pull request #2170 from Matchpoint-AI/feat/2098-edit-diff-tracking

**Source:** project-beta-api@b5f3a2ce

## [v0.7.666] - 2026-01-16

### Changes
- Merge pull request #2239 from Matchpoint-AI/fix/2238-coverage-threshold

**Source:** project-beta-api@e5556f20

## [v0.7.665] - 2026-01-16

### Changes
- Merge pull request #2214 from Matchpoint-AI/chore/remove-deprecated-fetch-url-content

**Source:** project-beta-api@dcce7395

## [v0.7.664] - 2026-01-16

### Changes
- Merge pull request #2197 from Matchpoint-AI/chore/remove-content-text-versions

**Source:** project-beta-api@754a74af

## [v0.7.663] - 2026-01-16

### Changes
- feat(#2124): add HITL selection tracking for feedback loop (#2145)

**Source:** project-beta-api@c315c614

## [v0.7.662] - 2026-01-16

### Changes
- Merge pull request #2236 from Matchpoint-AI/feat/2218-fsspec-filesystem

**Source:** project-beta-api@2d1882cd

## [v0.7.661] - 2026-01-16

### Changes
- feat: Add GET /briefs/{correlation_id} endpoint for crawl status (#2232)

**Source:** project-beta-api@4302b60a

## [v0.7.660] - 2026-01-16

### Changes
- feat: Migrate post regeneration to agentic architecture (#2231)

**Source:** project-beta-api@b9d825e4

## [v0.7.659] - 2026-01-16

### Changes
- Merge pull request #2227 from Matchpoint-AI/fix/2226-post-id-type

**Source:** project-beta-api@6fb60faf

## [v0.7.658] - 2026-01-16

### Changes
- Merge pull request #2228 from Matchpoint-AI/fix/2224-update-brand-on-core

**Source:** project-beta-api@f1ba9ce0

## [v0.7.657] - 2026-01-16

### Changes
- feat: Add correlation_id to ContentGenerationResponse (#2235)

**Source:** project-beta-api@435bc68a

## [v0.7.656] - 2026-01-16

### Changes
- feat(content-gen): pre-create posts with DB IDs before triggering generation (#2229)

**Source:** project-beta-api@359eee28

## [v0.7.655] - 2026-01-16

### Changes
- Merge pull request #2211 from Matchpoint-AI/fix/2193

**Source:** project-beta-api@d31e813e

## [v0.7.654] - 2026-01-16

### Changes
- Merge pull request #2220 from Matchpoint-AI/fix/remove-dead-deprecation-middleware

**Source:** project-beta-api@7acd4f6c

## [v0.7.653] - 2026-01-16

### Changes
- Merge pull request #2201 from Matchpoint-AI/feat/video-schema-support

**Source:** project-beta-api@74fd9d0e

## [v0.7.652] - 2026-01-16

### Changes
- feat: Add scene_performance_metrics table and API endpoints (#2160)

**Source:** project-beta-api@c47993d8

## [v0.7.651] - 2026-01-16

### Changes
- Merge pull request #2217 from Matchpoint-AI/fix/remove-unused-linucb-bandit

**Source:** project-beta-api@b28f3d67

## [v0.7.650] - 2026-01-16

### Changes
- feat(campaign): switch API routes to AgenticContentGenerationPublisher (#2199)

**Source:** project-beta-api@f71f53c8

## [v0.7.649] - 2026-01-16

### Changes
- Merge pull request #2216 from Matchpoint-AI/chore/remove-research-services

**Source:** project-beta-api@7c5457cc

## [v0.7.648] - 2026-01-16

### Changes
- Merge pull request #2191 from Matchpoint-AI/fix/agentic-pubsub-endpoint

**Source:** project-beta-api@d41ece0f

## [v0.7.647] - 2026-01-16

### Changes
- fix(api): Remove ImageGenerationRetryService (Issue #2137) (#2146)

**Source:** project-beta-api@5613471a

## [v0.7.646] - 2026-01-16

### Changes
- fix(brand): Make brand creation idempotent (#2163) (#2169)

**Source:** project-beta-api@db969e8d

## [v0.7.645] - 2026-01-16

### Changes
- Merge pull request #2204 from Matchpoint-AI/chore/remove-dynamic-prompt-composer

**Source:** project-beta-api@e63f1be7

## [v0.7.644] - 2026-01-16

### Changes
- Merge pull request #2203 from Matchpoint-AI/chore/remove-linucb-bandit

**Source:** project-beta-api@437d2a25

## [v0.7.643] - 2026-01-16

### Changes
- Merge pull request #2202 from Matchpoint-AI/chore/remove-video-cost-estimator

**Source:** project-beta-api@c0cadd80

## [v0.7.642] - 2026-01-16

### Changes
- Merge pull request #2200 from Matchpoint-AI/docs/update-versioning-docs

**Source:** project-beta-api@fb98049a

## [v0.7.641] - 2026-01-16

### Changes
- Merge pull request #2198 from Matchpoint-AI/chore/remove-image-prompt-schema

**Source:** project-beta-api@752917f9

## [v0.7.640] - 2026-01-16

### Changes
- Merge pull request #2195 from Matchpoint-AI/chore/remove-manual-research

**Source:** project-beta-api@0d86c0fc

## [v0.7.639] - 2026-01-15

### Changes
- feat: add is_ready_for_campaigns computed property to BrandResponse (#2189)

**Source:** project-beta-api@bd7effa0

## [v0.7.638] - 2026-01-15

### Changes
- Merge pull request #2188 from Matchpoint-AI/feat/2187-agentic-publishers

**Source:** project-beta-api@e82f820a

## [v0.7.637] - 2026-01-15

### Changes
- Merge pull request #2185 from Matchpoint-AI/feat/content-generator-endpoints

**Source:** project-beta-api@fa50bf5f

## [v0.7.636] - 2026-01-15

### Changes
- Merge pull request #2180 from Matchpoint-AI/feat/crawler-messages-endpoint

**Source:** project-beta-api@e0cf6840

## [v0.7.635] - 2026-01-14

### Changes
- feat: Add Manual Research Entry Capability (#2177)

**Source:** project-beta-api@f3f61e3c

## [v0.7.634] - 2026-01-14

### Changes
- Merge pull request #2174 from Matchpoint-AI/feat/2087-confidence-scoring

**Source:** project-beta-api@a49af1fc

## [v0.7.633] - 2026-01-14

### Changes
- Merge pull request #2176 from Matchpoint-AI/feat/2088-research-summarization

**Source:** project-beta-api@e153e6b6

## [v0.7.632] - 2026-01-14

### Changes
- Merge pull request #2175 from Matchpoint-AI/feat/2086-research-caching

**Source:** project-beta-api@dd3141fb

## [v0.7.631] - 2026-01-14

### Changes
- Merge pull request #2173 from Matchpoint-AI/feat/2068-websocket-support

**Source:** project-beta-api@46aea104

## [v0.7.630] - 2026-01-14

### Changes
- Merge pull request #2167 from Matchpoint-AI/feat/2071-social-media-analyzer

**Source:** project-beta-api@47086e2a

## [v0.7.629] - 2026-01-14

### Changes
- fix(migrations): Make media table migration idempotent (#2165) (#2168)

**Source:** project-beta-api@b58641d0

## [v0.7.628] - 2026-01-14

### Changes
- feat(cache): implement Redis distributed caching layer (#2161)

**Source:** project-beta-api@d8253af3

## [v0.7.627] - 2026-01-14

### Changes
- Merge pull request #2149 from Matchpoint-AI/feat/2058-rejection-reasons

**Source:** project-beta-api@83d2835a

## [v0.7.626] - 2026-01-14

### Changes
- Merge pull request #2150 from Matchpoint-AI/feat/2126-brand-fields

**Source:** project-beta-api@8e5c997b

## [v0.7.625] - 2026-01-14

### Changes
- Merge pull request #2148 from Matchpoint-AI/feat/2064-seed-data

**Source:** project-beta-api@61b4d0e6

## [v0.7.624] - 2026-01-14

### Changes
- fix(api): Remove analyze_content_tone() and generate_brand_content() from PostService (Issue #2131) (#2147)

**Source:** project-beta-api@0384e15f

## [v0.7.623] - 2026-01-14

### Changes
- Merge pull request #2109 from Matchpoint-AI/fix/2052

**Source:** project-beta-api@5571ee60

## [v0.7.622] - 2026-01-14

### Changes
- feat(#2046): define ImagePromptSchema Pydantic model (#2113)

**Source:** project-beta-api@8d31884e

## [v0.7.621] - 2026-01-14

### Changes
- Merge pull request #2108 from Matchpoint-AI/fix/2044

**Source:** project-beta-api@82425192

## [v0.7.620] - 2026-01-14

### Changes
- Merge pull request #2106 from Matchpoint-AI/fix/2043-remove-hardcoded-ratios

**Source:** project-beta-api@568bbde5

## [v0.7.619] - 2026-01-14

### Changes
- Merge pull request #2105 from Matchpoint-AI/feat/2053-brand-guardrails-quality

**Source:** project-beta-api@2bf8a4ea

## [v0.7.618] - 2026-01-14

### Changes
- Merge pull request #2111 from Matchpoint-AI/feat/2047-online-learning

**Source:** project-beta-api@bf719f47

## [v0.7.617] - 2026-01-14

### Changes
- Merge pull request #2104 from Matchpoint-AI/fix/2042-linucb

**Source:** project-beta-api@8bfd4925

## [v0.7.616] - 2026-01-14

### Changes
- Merge pull request #2107 from Matchpoint-AI/fix/2057

**Source:** project-beta-api@1c64b074

## [v0.7.615] - 2026-01-14

### Changes
- feat(#2025): add convert-static endpoint for video HITL workflow (#2034)

**Source:** project-beta-api@910f08a2

## [v0.7.614] - 2026-01-14

### Changes
- Merge pull request #2040 from Matchpoint-AI/fix/1756-e712-boolean

**Source:** project-beta-api@b2cc0e2b

## [v0.7.613] - 2026-01-14

### Changes
- Merge pull request #2039 from Matchpoint-AI/fix/1755-update-scheduler-docs

**Source:** project-beta-api@0af3b1aa

## [v0.7.612] - 2026-01-14

### Changes
- Merge pull request #2038 from Matchpoint-AI/fix/2027-reject-tests

**Source:** project-beta-api@3e0b3c4d

## [v0.7.611] - 2026-01-14

### Changes
- Merge pull request #2037 from Matchpoint-AI/fix/1779-remove-dead-tests

**Source:** project-beta-api@72e5651e

## [v0.7.610] - 2026-01-14

### Changes
- Merge pull request #2036 from Matchpoint-AI/feat/2024-video-regenerate

**Source:** project-beta-api@aa524484

## [v0.7.609] - 2026-01-14

### Changes
- feat(video): add video approve endpoint (Issue #2022) (#2033)

**Source:** project-beta-api@9280b5b2

## [v0.7.608] - 2026-01-14

### Changes
- feat: add video HITL reject endpoint (#2032)

**Source:** project-beta-api@053f2d0e

## [v0.7.607] - 2026-01-14

### Changes
- Merge pull request #2020 from Matchpoint-AI/feat/2019-nano-banana-pro

**Source:** project-beta-api@d32ce869

## [v0.7.606] - 2026-01-13

### Changes
- Merge pull request #2018 from Matchpoint-AI/fix/2017-schema-drift

**Source:** project-beta-api@a4c652cd

## [v0.7.605] - 2026-01-13

### Changes
- Merge pull request #2015 from Matchpoint-AI/fix/2013-brand-knowledge-max-length

**Source:** project-beta-api@2e7e412d

## [v0.7.604] - 2026-01-13

### Changes
- [P0 Fix] Increase max_length for brand description fields - unblocks user login (#2014)

**Source:** project-beta-api@3c849549

## [v0.7.603] - 2026-01-13

### Changes
- Merge pull request #2012 from Matchpoint-AI/feat/652-vscode-settings

**Source:** project-beta-api@d4604fd7

## [v0.7.602] - 2026-01-13

### Changes
- Merge pull request #2011 from Matchpoint-AI/feat/1957-security-checklist

**Source:** project-beta-api@d6bfd6c8

## [v0.7.601] - 2026-01-13

### Changes
- Merge pull request #2010 from Matchpoint-AI/fix/1959-pubsub-debugging

**Source:** project-beta-api@d9fced9f

## [v0.7.600] - 2026-01-13

### Changes
- Merge pull request #2006 from Matchpoint-AI/fix/2005-regenerate-404

**Source:** project-beta-api@217e7e9e

## [v0.7.599] - 2026-01-13

### Changes
- Merge pull request #2009 from Matchpoint-AI/fix/1962-openapi-workflow

**Source:** project-beta-api@28cc1874

## [v0.7.598] - 2026-01-13

### Changes
- feat: add database migration CI failure prevention (#1961)

**Source:** project-beta-api@e59ecf99

## [v0.7.597] - 2026-01-13

### Changes
- fix(audit): integrate AuditService into PostStatusService (#1808)

**Source:** project-beta-api@96a6d5f6

## [v0.7.596] - 2026-01-13

### Changes
- Merge pull request #2001 from Matchpoint-AI/fix/1999

**Source:** project-beta-api@ba1ac0a6

## [v0.7.595] - 2026-01-12

### Changes
- feat: add X-Git-SHA header for deployment tracking (#1958)

**Source:** project-beta-api@e5d0f29e

## [v0.7.594] - 2026-01-12

### Changes
- fix: consolidate SSL context building in campaign_export_repository (#1789)

**Source:** project-beta-api@e6bc7f80

## [v0.7.593] - 2026-01-12

### Changes
- Merge pull request #1994 from Matchpoint-AI/feat/1993-auth-image-regen

**Source:** project-beta-api@644a04ce

## [v0.7.592] - 2026-01-12

### Changes
- ci: remove continue-on-error from schema drift check (#1990)

**Source:** project-beta-api@7dc4e43f

## [v0.7.591] - 2026-01-12

### Changes
- Merge pull request #1991 from Matchpoint-AI/feat/1989-brand-filter

**Source:** project-beta-api@7231926b

## [v0.7.590] - 2026-01-12

### Changes
- fix: add validation for malformed content data (#1983)

**Source:** project-beta-api@0ec64832

## [v0.7.589] - 2026-01-12

### Changes
- fix: centralize environment variable access via pydantic-settings (#1826) (#1982)

**Source:** project-beta-api@0d4955db

## [v0.7.588] - 2026-01-12

### Changes
- fix: relax schema drift check to ignore cosmetic differences (#1988)

**Source:** project-beta-api@9bb460a8

## [v0.7.587] - 2026-01-10

### Changes
- docs: add cross-repo type generation reminder to PR template (#1981)

**Source:** project-beta-api@46bff095

## [v0.7.586] - 2026-01-10

### Changes
- fix: add missing prompt_revisions table migration (#1978)

**Source:** project-beta-api@a38ba80f

## [v0.7.585] - 2026-01-10

### Changes
- Merge pull request #1975 from Matchpoint-AI/fix/1974-datetime

**Source:** project-beta-api@feab244c

## [v0.7.584] - 2026-01-10

### Changes
- Merge pull request #1973 from Matchpoint-AI/fix/1784-remove-deprecated

**Source:** project-beta-api@82aa5b05

## [v0.7.583] - 2026-01-10

### Changes
- Merge pull request #1972 from Matchpoint-AI/fix/1776-httpx-consolidation

**Source:** project-beta-api@a99b3f17

## [v0.7.582] - 2026-01-10

### Changes
- perf: migrate from stdlib json to orjson for 3-10x faster serialization (#1971)

**Source:** project-beta-api@6898a4d7

## [v0.7.581] - 2026-01-09

### Changes
- Merge pull request #1970 from Matchpoint-AI/fix/1969-cloud-run-migrations

**Source:** project-beta-api@1f8a1dda

## [v0.7.580] - 2026-01-09

### Changes
- feat(api): add v2 brand costs endpoint with RMM L2 compliance (#1952)

**Source:** project-beta-api@be49a61b

## [v0.7.579] - 2026-01-09

### Changes
- Merge pull request #1967 from Matchpoint-AI/fix/1963-migration-private-ip

**Source:** project-beta-api@ebf49244

## [v0.7.578] - 2026-01-09

### Changes
- Merge pull request #1966 from Matchpoint-AI/fix/1963-migration-netcat-python

**Source:** project-beta-api@d7d59b6b

## [v0.7.577] - 2026-01-09

### Changes
- Merge pull request #1964 from Matchpoint-AI/fix/1963-migration-workflow

**Source:** project-beta-api@2b6af01c

## [v0.7.576] - 2026-01-09

### Changes
- feat: implement video generation cost estimation service (#1702) (#1940)

**Source:** project-beta-api@ae92d883

## [v0.7.575] - 2026-01-09

### Changes
- feat: add GET /video-jobs/{job_id} status endpoint (#1697) (#1939)

**Source:** project-beta-api@2b7f8de6

## [v0.7.574] - 2026-01-09

### Changes
- Merge pull request #1943 from Matchpoint-AI/feat/1705-video-cost-recorder

**Source:** project-beta-api@35b4fb50

## [v0.7.573] - 2026-01-09

### Changes
- Merge pull request #1934 from Matchpoint-AI/feat/1929-audience-demographics

**Source:** project-beta-api@a3f47fc3

## [v0.7.572] - 2026-01-09

### Changes
- Merge pull request #1949 from Matchpoint-AI/fix/1946-uvicorn-reload

**Source:** project-beta-api@c236b394

## [v0.7.571] - 2026-01-09

### Changes
- Merge pull request #1947 from Matchpoint-AI/fix/1835-remove-asserts

**Source:** project-beta-api@8fb146d2

## [v0.7.570] - 2026-01-09

### Changes
- Merge pull request #1950 from Matchpoint-AI/fix/1830-remove-firebase-auth

**Source:** project-beta-api@5eb9b5fd

## [v0.7.569] - 2026-01-09

### Changes
- fix: add additionalProperties to SceneMixPolicy object fields (#1863) (#1948)

**Source:** project-beta-api@a2b6003f

## [v0.7.568] - 2026-01-09

### Changes
- Merge pull request #1941 from Matchpoint-AI/feat/1933-scene-selection

**Source:** project-beta-api@706370cf

## [v0.7.567] - 2026-01-09

### Changes
- Merge pull request #1932 from Matchpoint-AI/fix/1930-brand-status-transition

**Source:** project-beta-api@1d52268a

## [v0.7.566] - 2026-01-08

### Changes
- fix: mask email addresses in password-related logs for security (#1935)

**Source:** project-beta-api@e299116a

## [v0.7.565] - 2026-01-08

### Changes
- Merge pull request #1936 from Matchpoint-AI/fix/1834-instagram-oauth-validation

**Source:** project-beta-api@c315b6f0

## [v0.7.564] - 2026-01-08

### Changes
- Merge pull request #1937 from Matchpoint-AI/feat/1833-magic-numbers

**Source:** project-beta-api@f3e455d4

## [v0.7.563] - 2026-01-08

### Changes
- feat: add POST /api/v2/posts/{post_id}/videos endpoint (#1927)

**Source:** project-beta-api@9344a24c

## [v0.7.562] - 2026-01-08

### Changes
- fix: replace silent exception handler with debug logging in brand_controller (#1928)

**Source:** project-beta-api@33a59f2a

## [v0.7.561] - 2026-01-08

### Changes
- Merge pull request #1926 from Matchpoint-AI/feat/1698-video-generation-publisher

**Source:** project-beta-api@df494833

## [v0.7.560] - 2026-01-08

### Changes
- Merge pull request #1925 from Matchpoint-AI/feat/1695-video-generation-jobs

**Source:** project-beta-api@a0e68380

## [v0.7.559] - 2026-01-08

### Changes
- Merge pull request #1919 from Matchpoint-AI/feat/1897-connection-pool-monitoring

**Source:** project-beta-api@076232ff

## [v0.7.558] - 2026-01-08

### Changes
- Merge pull request #1918 from Matchpoint-AI/feat/1704-video-generation-costs

**Source:** project-beta-api@315d9ba1

## [v0.7.557] - 2026-01-08

### Changes
- Merge pull request #1887 from Matchpoint-AI/fix/1886

**Source:** project-beta-api@e183bc69

## [v0.7.556] - 2026-01-08

### Changes
- Merge pull request #1885 from Matchpoint-AI/fix/1774-datetime-utcnow

**Source:** project-beta-api@0f4f4183

## [v0.7.555] - 2026-01-08

### Changes
- Merge pull request #1884 from Matchpoint-AI/fix/1816-print-statements

**Source:** project-beta-api@dd1aaf9e

## [v0.7.554] - 2026-01-08

### Changes
- fix(api): support string post IDs in content prompt endpoint (#1880)

**Source:** project-beta-api@a3f996e2

## [v0.7.553] - 2026-01-08

### Changes
- Merge pull request #1877 from Matchpoint-AI/feat/migrate-to-project-beta-runners

**Source:** project-beta-api@0626a595

## [v0.7.552] - 2026-01-07

### Changes
- Merge pull request #1861 from Matchpoint-AI/fix/1802-ssl-verification

**Source:** project-beta-api@81ccb5ad

## [v0.7.551] - 2026-01-07

### Changes
- Merge pull request #1865 from Matchpoint-AI/fix/campaign-creation-400

**Source:** project-beta-api@4bb1526c

## [v0.7.550] - 2026-01-07

### Changes
- Merge pull request #1875 from Matchpoint-AI/fix/567-temp-ubuntu-latest-runners

**Source:** project-beta-api@5f211cc3

## [v0.7.549] - 2026-01-07

### Changes
- Merge pull request #1874 from Matchpoint-AI/fix/migration-sa-text

**Source:** project-beta-api@fbf8ff60

## [v0.7.548] - 2026-01-07

### Changes
- Merge pull request #1873 from Matchpoint-AI/fix/1873-duplicate-brands

**Source:** project-beta-api@1507208e

## [v0.7.547] - 2026-01-06

### Changes
- Merge pull request #1872 from Matchpoint-AI/fix/1871-migration-enum

**Source:** project-beta-api@524a0694

## [v0.7.546] - 2026-01-06

### Changes
- Merge pull request #1870 from Matchpoint-AI/chore/remove-unused-protocols

**Source:** project-beta-api@cc4d40e2

## [v0.7.545] - 2026-01-06

### Changes
- Merge pull request #1869 from Matchpoint-AI/chore/remove-brand-attribute

**Source:** project-beta-api@fe9e909e

## [v0.7.544] - 2026-01-06

### Changes
- ci: temporarily use ubuntu-latest for release workflow (ARC down) (#1868)

**Source:** project-beta-api@221e2466

## [v0.7.543] - 2026-01-06

### Changes
- Merge pull request #1860 from Matchpoint-AI/chore/remove-stale-coveragerc-entries

**Source:** project-beta-api@d4ae9841

## [v0.7.542] - 2026-01-06

### Changes
- Merge pull request #1859 from Matchpoint-AI/chore/remove-admin-service

**Source:** project-beta-api@d9ce0556

## [v0.7.541] - 2026-01-06

### Changes
- fix: replace broad exception handlers with handle_service_exception (#1690) (#1857)

**Source:** project-beta-api@7a656f61

## [v0.7.540] - 2026-01-06

### Changes
- Merge pull request #1858 from Matchpoint-AI/chore/remove-quality-gate-service

**Source:** project-beta-api@f4196bc9

## [v0.7.539] - 2026-01-06

### Changes
- Merge pull request #1856 from Matchpoint-AI/fix/1827-client-exceptions

**Source:** project-beta-api@9fd3fe7c

## [v0.7.538] - 2026-01-06

### Changes
- Merge pull request #1855 from Matchpoint-AI/fix/1801-sanitize-exceptions

**Source:** project-beta-api@647edcea

## [v0.7.537] - 2026-01-06

### Changes
- Merge pull request #1853 from Matchpoint-AI/fix/1852-rename-test

**Source:** project-beta-api@9c332f08

## [v0.7.536] - 2026-01-06

### Changes
- Merge pull request #1849 from Matchpoint-AI/cleanup/dynamic-prompt-todos

**Source:** project-beta-api@5c2ef2f6

## [v0.7.535] - 2026-01-06

### Changes
- Merge pull request #1848 from Matchpoint-AI/fix/brand-knowledge-schema-validation

**Source:** project-beta-api@bded880e

## [v0.7.534] - 2026-01-06

### Changes
- Merge pull request #1850 from Matchpoint-AI/fix/1828-deprecated-post-service-methods

**Source:** project-beta-api@981dc60d

## [v0.7.533] - 2026-01-06

### Changes
- Merge pull request #1847 from Matchpoint-AI/fix/openapi-brand-knowledge-refs

**Source:** project-beta-api@adc0bfc2

## [v0.7.532] - 2026-01-06

### Changes
- fix: read brand knowledge from semantic_data for V2 API (#1844)

**Source:** project-beta-api@0f1087bd

## [v0.7.531] - 2026-01-06

### Changes
- fix(security): remove API key exposure in debug logs (#1843)

**Source:** project-beta-api@739b507d

## [v0.7.530] - 2026-01-06

### Changes
- Merge pull request #1846 from Matchpoint-AI/fix/1691-remove-firebase-uid

**Source:** project-beta-api@118867a9

## [v0.7.529] - 2026-01-06

### Changes
- Merge pull request #1845 from Matchpoint-AI/fix/1984-brand-knowledge-progress

**Source:** project-beta-api@dd9bce64

## [v0.7.528] - 2026-01-06

### Changes
- Merge pull request #1836 from Matchpoint-AI/fix/1800-api-key-exposure

**Source:** project-beta-api@28350f34

## [v0.7.527] - 2026-01-05

### Changes
- Merge pull request #1764 from Matchpoint-AI/fix/1735-dlq-phase2

**Source:** project-beta-api@95f9c610

## [v0.7.526] - 2026-01-05

### Changes
- Merge pull request #1765 from Matchpoint-AI/fix/1734-unbounded-queries

**Source:** project-beta-api@dddd918c

## [v0.7.525] - 2026-01-05

### Changes
- fix(#1735): wire DeadLetterQueueService into DirectHttpPostGenerationPublisher (#1763)

**Source:** project-beta-api@86b95f1b

## [v0.7.524] - 2026-01-05

### Changes
- fix: use job.schedule_time for correct scheduled_time in CloudSchedulerService (#1762)

**Source:** project-beta-api@f03af6ea

## [v0.7.523] - 2026-01-05

### Changes
- Merge pull request #1760 from Matchpoint-AI/fix/ci-xfail-markers

**Source:** project-beta-api@31ef86db

## [v0.7.522] - 2026-01-05

### Changes
- Merge pull request #1761 from Matchpoint-AI/fix/1732-instagram-id-validation

**Source:** project-beta-api@7d6d59e9

## [v0.7.521] - 2026-01-05

### Changes
- fix: add session.refresh() after commit in create_or_update() (#1759)

**Source:** project-beta-api@e566b703

## [v0.7.520] - 2026-01-05

### Changes
- Merge pull request #1757 from Matchpoint-AI/fix/1737-content-authorization

**Source:** project-beta-api@3826a8b7

## [v0.7.519] - 2026-01-05

### Changes
- Merge pull request #1749 from Matchpoint-AI/fix/1736-campaign-authorization

**Source:** project-beta-api@124a133d

## [v0.7.518] - 2026-01-05

### Changes
- Merge pull request #1758 from Matchpoint-AI/fix/1728-instagram-timezone

**Source:** project-beta-api@0922f527

## [v0.7.517] - 2026-01-05

### Changes
- Merge pull request #1742 from Matchpoint-AI/fix/1689-jwt-secret-key-validation

**Source:** project-beta-api@2ab587fa

## [v0.7.516] - 2026-01-05

### Changes
- Merge pull request #1741 from Matchpoint-AI/fix/1725-user-registration-race-condition

**Source:** project-beta-api@6af36872

## [v0.7.515] - 2026-01-05

### Changes
- Merge pull request #1740 from Matchpoint-AI/fix/1726-timezone-aware-blacklist

**Source:** project-beta-api@89188bbb

## [v0.7.514] - 2026-01-05

### Changes
- Merge pull request #1739 from Matchpoint-AI/fix/1727-token-blacklist-fail-closed

**Source:** project-beta-api@d2f68ab3

## [v0.7.513] - 2026-01-05

### Changes
- Merge pull request #1714 from Matchpoint-AI/fix/1668-token-expiration

**Source:** project-beta-api@bfb15294

## [v0.7.512] - 2026-01-05

### Changes
- Merge pull request #1686 from Matchpoint-AI/fix/1684

**Source:** project-beta-api@2d0021a2

## [v0.7.511] - 2026-01-05

### Changes
- Merge pull request #1687 from Matchpoint-AI/fix/1776

**Source:** project-beta-api@01dae7ec

## [v0.7.510] - 2026-01-05

### Changes
- Merge pull request #1682 from Matchpoint-AI/fix/1664

**Source:** project-beta-api@63030f64

## [v0.7.509] - 2026-01-05

### Changes
- Merge pull request #1683 from Matchpoint-AI/fix/1658

**Source:** project-beta-api@cac49691

## [v0.7.508] - 2026-01-05

### Changes
- Merge pull request #1681 from Matchpoint-AI/fix/1662

**Source:** project-beta-api@51a70acc

## [v0.7.507] - 2026-01-05

### Changes
- Merge pull request #1680 from Matchpoint-AI/fix/1615

**Source:** project-beta-api@abdad286

## [v0.7.506] - 2026-01-05

### Changes
- Merge pull request #1677 from Matchpoint-AI/fix/1655-brand-auth

**Source:** project-beta-api@4203edce

## [v0.7.505] - 2026-01-05

### Changes
- Merge pull request #1679 from Matchpoint-AI/fix/1614

**Source:** project-beta-api@0252d14c

## [v0.7.504] - 2026-01-05

### Changes
- Merge pull request #1678 from Matchpoint-AI/fix/1654-pubsub-emulator-auth

**Source:** project-beta-api@1c7654ec

## [v0.7.503] - 2026-01-05

### Changes
- Merge pull request #1652 from Matchpoint-AI/fix/1613

**Source:** project-beta-api@5ac93ad5

## [v0.7.502] - 2026-01-05

### Changes
- Merge pull request #1653 from Matchpoint-AI/fix/audience-suggestions-parsing

**Source:** project-beta-api@8d8a784b

## [v0.7.501] - 2026-01-05

### Changes
- Merge pull request #1651 from Matchpoint-AI/fix/1612

**Source:** project-beta-api@63aff8b1

## [v0.7.500] - 2026-01-05

### Changes
- Merge pull request #1650 from Matchpoint-AI/fix/1611

**Source:** project-beta-api@1a0579e8

## [v0.7.499] - 2026-01-05

### Changes
- Merge pull request #1649 from Matchpoint-AI/fix/1610

**Source:** project-beta-api@62d80c6f

## [v0.7.498] - 2026-01-04

### Changes
- Merge pull request #1648 from Matchpoint-AI/fix/1609

**Source:** project-beta-api@7452b464

## [v0.7.497] - 2026-01-04

### Changes
- Merge pull request #1647 from Matchpoint-AI/fix/1608

**Source:** project-beta-api@60785333

## [v0.7.496] - 2026-01-04

### Changes
- Merge pull request #1646 from Matchpoint-AI/fix/1607

**Source:** project-beta-api@63415d84

## [v0.7.495] - 2026-01-04

### Changes
- Merge pull request #1645 from Matchpoint-AI/fix/1606

**Source:** project-beta-api@ea584541

## [v0.7.494] - 2026-01-04

### Changes
- Merge pull request #1644 from Matchpoint-AI/fix/1605

**Source:** project-beta-api@32ea8cb8

## [v0.7.493] - 2026-01-04

### Changes
- Merge pull request #1643 from Matchpoint-AI/fix/1603-v2

**Source:** project-beta-api@dffde05d

## [v0.7.492] - 2026-01-04

### Changes
- Merge pull request #1642 from Matchpoint-AI/fix/1604

**Source:** project-beta-api@cdae875e

## [v0.7.491] - 2026-01-04

### Changes
- Merge pull request #1640 from Matchpoint-AI/fix/1602

**Source:** project-beta-api@6be629ee

## [v0.7.490] - 2026-01-04

### Changes
- Merge pull request #1639 from Matchpoint-AI/fix/1601

**Source:** project-beta-api@0c781778

## [v0.7.489] - 2026-01-04

### Changes
- Merge pull request #1637 from Matchpoint-AI/fix/1600

**Source:** project-beta-api@323b8128

## [v0.7.488] - 2026-01-04

### Changes
- Merge pull request #1636 from Matchpoint-AI/fix/1633-audience-suggestions-error-handling

**Source:** project-beta-api@bf677bf8

## [v0.7.487] - 2026-01-04

### Changes
- Merge pull request #1635 from Matchpoint-AI/fix/1597-schema-mismatch

**Source:** project-beta-api@f030979a

## [v0.7.486] - 2026-01-04

### Changes
- Merge pull request #1594 from Matchpoint-AI/fix/adr-fal-video

**Source:** project-beta-api@6358ceb6

## [v0.7.485] - 2026-01-04

### Changes
- docs: add ADR for Instagram Reels video generation architecture (#1593)

**Source:** project-beta-api@a2336110

## [v0.7.484] - 2026-01-04

### Changes
- Merge pull request #1592 from Matchpoint-AI/fix/1589-approval-empty-text

**Source:** project-beta-api@1cd95f5d

## [v0.7.483] - 2026-01-04

### Changes
- Merge pull request #1591 from Matchpoint-AI/fix/1586-injector-binding

**Source:** project-beta-api@434360de

## [v0.7.482] - 2026-01-04

### Changes
- Merge pull request #1590 from Matchpoint-AI/fix/1588-approval-persistence

**Source:** project-beta-api@41ebe89c

## [v0.7.481] - 2026-01-04

### Changes
- Merge pull request #1587 from Matchpoint-AI/fix/1586-runtime-checkable

**Source:** project-beta-api@6515bfb4

## [v0.7.480] - 2026-01-03

### Changes
- Merge pull request #1585 from Matchpoint-AI/fix/1712-content-weeks-field

**Source:** project-beta-api@6f9dd190

## [v0.7.479] - 2026-01-03

### Changes
- Merge pull request #1577 from Matchpoint-AI/fix/1576-brand-knowledge-404

**Source:** project-beta-api@78bedb6a

## [v0.7.478] - 2026-01-03

### Changes
- Merge pull request #1575 from Matchpoint-AI/fix/1571-brand-knowledge-stubs

**Source:** project-beta-api@096b23db

## [v0.7.477] - 2026-01-03

### Changes
- Merge pull request #1574 from Matchpoint-AI/fix/1570-sendgrid-logging

**Source:** project-beta-api@3a2b8daa

## [v0.7.476] - 2026-01-03

### Changes
- fix(security): require auth for text versions endpoint (#1569) (#1573)

**Source:** project-beta-api@27c5432b

## [v0.7.475] - 2026-01-03

### Changes
- refactor: remove deprecated content_workflow_controller (#1568)

**Source:** project-beta-api@cfafd5e6

## [v0.7.474] - 2026-01-03

### Changes
- Merge pull request #1567 from Matchpoint-AI/fix/1566-export-typeerror

**Source:** project-beta-api@171d94dd

## [v0.7.473] - 2026-01-03

### Changes
- Merge pull request #1562 from Matchpoint-AI/fix/1543-remove-audience-suggestions

**Source:** project-beta-api@bfd39fdf

## [v0.7.472] - 2026-01-03

### Changes
- Merge pull request #1564 from Matchpoint-AI/fix/2002-workflow-status

**Source:** project-beta-api@716707e3

## [v0.7.471] - 2026-01-03

### Changes
- Merge pull request #1558 from Matchpoint-AI/fix/1547-async-plan

**Source:** project-beta-api@913ee8bf

## [v0.7.470] - 2026-01-03

### Changes
- Merge pull request #1563 from Matchpoint-AI/fix/1545-remove-diversity-endpoints

**Source:** project-beta-api@e37c7e8e

## [v0.7.469] - 2026-01-03

### Changes
- Merge pull request #1559 from Matchpoint-AI/fix/1495-video-generation

**Source:** project-beta-api@3a90d89c

## [v0.7.468] - 2026-01-03

### Changes
- Merge pull request #1557 from Matchpoint-AI/fix/1549-async-specifications

**Source:** project-beta-api@8b2424d7

## [v0.7.467] - 2026-01-03

### Changes
- Merge pull request #1554 from Matchpoint-AI/fix/1538-delete-plans-endpoint

**Source:** project-beta-api@34fd6cd8

## [v0.7.466] - 2026-01-03

### Changes
- Merge pull request #1556 from Matchpoint-AI/fix/1553-e2e-content-tests

**Source:** project-beta-api@06e65778

## [v0.7.465] - 2026-01-03

### Changes
- Merge pull request #1555 from Matchpoint-AI/fix/1551-scene-mix-auth

**Source:** project-beta-api@e704a30f

## [v0.7.464] - 2026-01-03

### Changes
- Merge pull request #1536 from Matchpoint-AI/fix/1484-async-polling

**Source:** project-beta-api@dece1c0e

## [v0.7.463] - 2026-01-03

### Changes
- Merge pull request #1535 from Matchpoint-AI/fix/1481-content-service-migration

**Source:** project-beta-api@a9eb874a

## [v0.7.462] - 2026-01-03

### Changes
- Merge pull request #1532 from Matchpoint-AI/fix/1482-llm-decouple

**Source:** project-beta-api@1285a207

## [v0.7.461] - 2026-01-03

### Changes
- Merge pull request #1534 from Matchpoint-AI/fix/1492-video-action

**Source:** project-beta-api@a9aa0eb3

## [v0.7.460] - 2026-01-02

### Changes
- Merge pull request #1533 from Matchpoint-AI/fix/1491-video-infra

**Source:** project-beta-api@d42e0a7d

## [v0.7.459] - 2026-01-02

### Changes
- Merge pull request #1523 from Matchpoint-AI/fix/1346-scheduler

**Source:** project-beta-api@b91bb546

## [v0.7.458] - 2026-01-02

### Changes
- Merge pull request #1531 from Matchpoint-AI/fix/1490-video-models

**Source:** project-beta-api@af734f90

## [v0.7.457] - 2026-01-02

### Changes
- Merge pull request #1525 from Matchpoint-AI/fix/1489-fal-video-client

**Source:** project-beta-api@55f8a2cc

## [v0.7.456] - 2026-01-02

### Changes
- Merge pull request #1529 from Matchpoint-AI/issue-1526-add-google-cloud-scheduler

**Source:** project-beta-api@0b264c43

## [v0.7.455] - 2026-01-02

### Changes
- Merge pull request #1524 from Matchpoint-AI/fix/1480-llm-decouple-content-image-service

**Source:** project-beta-api@8b32322a

## [v0.7.454] - 2026-01-02

### Changes
- Merge pull request #1522 from Matchpoint-AI/fix/1510-approval-stats

**Source:** project-beta-api@9437074f

## [v0.7.453] - 2026-01-02

### Changes
- Merge pull request #1521 from Matchpoint-AI/fix/1488-video-client-protocol

**Source:** project-beta-api@768f46ba

## [v0.7.452] - 2026-01-02

### Changes
- Merge pull request #1520 from Matchpoint-AI/fix/1507-thread-messages-cleanup

**Source:** project-beta-api@f40cbe8b

## [v0.7.451] - 2026-01-02

### Changes
- Merge pull request #1518 from Matchpoint-AI/fix/1511-dead-code

**Source:** project-beta-api@90c825f1

## [v0.7.450] - 2026-01-02

### Changes
- Merge pull request #1516 from Matchpoint-AI/fix/1509-api-mismatch

**Source:** project-beta-api@1fd97155

## [v0.7.449] - 2026-01-02

### Changes
- Merge pull request #1517 from Matchpoint-AI/fix/1478-llm-decouple-p2-2

**Source:** project-beta-api@b8c3258c

## [v0.7.448] - 2026-01-02

### Changes
- Merge pull request #1514 from Matchpoint-AI/revert/1502-generate-image

**Source:** project-beta-api@2d9d8273

## [v0.7.447] - 2026-01-02

### Changes
- Merge pull request #1498 from Matchpoint-AI/fix/1475-migrate-rag-embeddings

**Source:** project-beta-api@a1831cc4

## [v0.7.446] - 2026-01-02

### Changes
- Merge pull request #1508 from Matchpoint-AI/fix/1485-fal-video-research

**Source:** project-beta-api@b79a9dec

## [v0.7.445] - 2026-01-02

### Changes
- Merge pull request #1506 from Matchpoint-AI/fix/1476-threadmessages-eval

**Source:** project-beta-api@c38e5e4f

## [v0.7.444] - 2026-01-02

### Changes
- Merge pull request #1504 from Matchpoint-AI/fix/1486-video-quality-tiers

**Source:** project-beta-api@f830428f

## [v0.7.443] - 2026-01-02

### Changes
- Merge pull request #1503 from Matchpoint-AI/fix/1487-video-gcs-design

**Source:** project-beta-api@5f3eaa0e

## [v0.7.442] - 2026-01-02

### Changes
- Merge pull request #1502 from Matchpoint-AI/fix/1479-image-service-migration

**Source:** project-beta-api@db983887

## [v0.7.441] - 2026-01-02

### Changes
- Merge pull request #1501 from Matchpoint-AI/fix/1474-campaign-spec-v2

**Source:** project-beta-api@af1d6b43

## [v0.7.440] - 2026-01-02

### Changes
- Merge pull request #1499 from Matchpoint-AI/fix/1477-migrate-extractor

**Source:** project-beta-api@759f16a9

## [v0.7.439] - 2026-01-02

### Changes
- Merge pull request #1497 from Matchpoint-AI/fix/1473-migrate-audience-suggestion

**Source:** project-beta-api@bba6129a

## [v0.7.438] - 2026-01-02

### Changes
- Merge pull request #1496 from Matchpoint-AI/fix/allow-draft-to-approved-transition

**Source:** project-beta-api@cbe89c9a

## [v0.7.437] - 2026-01-02

### Changes
- Merge pull request #1472 from Matchpoint-AI/fix/1469-content-approval-dedup

**Source:** project-beta-api@78b1ac4a

## [v0.7.436] - 2026-01-02

### Changes
- Merge pull request #1467 from Matchpoint-AI/fix/1466-bulk-approval

**Source:** project-beta-api@6ffbd284

## [v0.7.435] - 2026-01-02

### Changes
- Merge pull request #1468 from Matchpoint-AI/feat/1153-quality-gate

**Source:** project-beta-api@f4333ad9

## [v0.7.434] - 2026-01-02

### Changes
- Merge pull request #1462 from Matchpoint-AI/fix/1659-brand-audience-suggestions

**Source:** project-beta-api@f21f5cee

## [v0.7.433] - 2026-01-02

### Changes
- Merge pull request #1465 from Matchpoint-AI/feat/1417-tiered-models

**Source:** project-beta-api@9a849da8

## [v0.7.432] - 2026-01-02

### Changes
- Merge pull request #1464 from Matchpoint-AI/fix/1724-firestore-migration

**Source:** project-beta-api@dc7e8608

## [v0.7.431] - 2026-01-02

### Changes
- Merge pull request #1454 from Matchpoint-AI/fix/1446-delete-legacy-versioning

**Source:** project-beta-api@edfd512c

## [v0.7.430] - 2026-01-02

### Changes
- feat(api): delete legacy brand endpoints (summary, extract/locations) (#1452)

**Source:** project-beta-api@1bfff96d

## [v0.7.429] - 2026-01-02

### Changes
- Merge pull request #1461 from Matchpoint-AI/fix/1459-jsonb-mismatch

**Source:** project-beta-api@94fb75ab

## [v0.7.428] - 2026-01-02

### Changes
- Merge pull request #1456 from Matchpoint-AI/fix/1445-delete-legacy-campaign

**Source:** project-beta-api@fc022e65

## [v0.7.427] - 2026-01-01

### Changes
- Merge pull request #1458 from Matchpoint-AI/fix/1443-delete-legacy-auth

**Source:** project-beta-api@6c0514e8

## [v0.7.426] - 2026-01-01

### Changes
- Merge pull request #1457 from Matchpoint-AI/fix/1448-delete-legacy-integration

**Source:** project-beta-api@e7cad75f

## [v0.7.425] - 2026-01-01

### Changes
- Merge pull request #1455 from Matchpoint-AI/chore/1385-cleanup-dead-brand-services

**Source:** project-beta-api@9a956157

## [v0.7.424] - 2026-01-01

### Changes
- Merge pull request #1453 from Matchpoint-AI/fix/1449-delete-legacy-utility

**Source:** project-beta-api@760b8c3e

## [v0.7.423] - 2026-01-01

### Changes
- Merge pull request #1451 from Matchpoint-AI/fix/1447-delete-legacy-analytics

**Source:** project-beta-api@5bcead1c

## [v0.7.422] - 2026-01-01

### Changes
- Merge pull request #1442 from Matchpoint-AI/fix/465-api-weeks-serialization

**Source:** project-beta-api@fe4cf5bd

## [v0.7.421] - 2026-01-01

### Changes
- Merge pull request #1441 from Matchpoint-AI/fix/1105

**Source:** project-beta-api@8f78208b

## [v0.7.420] - 2026-01-01

### Changes
- Merge pull request #1440 from Matchpoint-AI/fix/1107

**Source:** project-beta-api@12f1a7be

## [v0.7.419] - 2026-01-01

### Changes
- Merge pull request #1439 from Matchpoint-AI/feat/1388-llm-params

**Source:** project-beta-api@63c242f7

## [v0.7.418] - 2026-01-01

### Changes
- Merge pull request #1438 from Matchpoint-AI/feat/1030-db-assertion-plugin

**Source:** project-beta-api@6794c339

## [v0.7.417] - 2026-01-01

### Changes
- Merge pull request #1432 from Matchpoint-AI/fix/rmm-l2-medium

**Source:** project-beta-api@95311cf7

## [v0.7.416] - 2026-01-01

### Changes
- Merge pull request #1437 from Matchpoint-AI/feat/530-ci-optimization

**Source:** project-beta-api@241a4e14

## [v0.7.415] - 2026-01-01

### Changes
- Merge pull request #1435 from Matchpoint-AI/fix/1023-post-identifier

**Source:** project-beta-api@37c17011

## [v0.7.414] - 2026-01-01

### Changes
- Merge pull request #1436 from Matchpoint-AI/docs/1302-content-gen-docs

**Source:** project-beta-api@fca81166

## [v0.7.413] - 2026-01-01

### Changes
- cleanup(1326): Remove dead brand crawling code (#1434)

**Source:** project-beta-api@0669b13d

## [v0.7.412] - 2026-01-01

### Changes
- Merge pull request #1433 from Matchpoint-AI/fix/1046-request-id

**Source:** project-beta-api@100b4b28

## [v0.7.411] - 2026-01-01

### Changes
- fix(schemas): handle weeks array format in content_data (#1429) (#1430)

**Source:** project-beta-api@3c9d39b3

## [v0.7.410] - 2026-01-01

### Changes
- Merge pull request #1431 from Matchpoint-AI/feat/1422-pdf-extraction-cleanup

**Source:** project-beta-api@31fc7e7d

## [v0.7.409] - 2026-01-01

### Changes
- Merge pull request #1428 from Matchpoint-AI/feat/1102-rmm-l2

**Source:** project-beta-api@459a35b3

## [v0.7.408] - 2026-01-01

### Changes
- Merge pull request #1427 from Matchpoint-AI/feat/1424-media-snapshot-schema

**Source:** project-beta-api@e4133f77

## [v0.7.407] - 2026-01-01

### Changes
- Merge pull request #1425 from Matchpoint-AI/fix/1421-uuid-v2

**Source:** project-beta-api@e0f237b1

## [v0.7.406] - 2026-01-01

### Changes
- Merge pull request #1420 from Matchpoint-AI/docs/1410-readme-update

**Source:** project-beta-api@8e899da3

## [v0.7.405] - 2026-01-01

### Changes
- Merge pull request #1414 from Matchpoint-AI/feat/1407-repo-integration-tests

**Source:** project-beta-api@a1965595

## [v0.7.404] - 2026-01-01

### Changes
- Merge pull request #1413 from Matchpoint-AI/feat/1408-schema-validation-tests

**Source:** project-beta-api@4e30330e

## [v0.7.403] - 2026-01-01

### Changes
- Merge pull request #1412 from Matchpoint-AI/feat/1405-regen-tests

**Source:** project-beta-api@3c16eaac

## [v0.7.402] - 2026-01-01

### Changes
- Merge pull request #1411 from Matchpoint-AI/feat/1406-caption-tests

**Source:** project-beta-api@2df573b2

## [v0.7.401] - 2026-01-01

### Changes
- Merge pull request #1404 from Matchpoint-AI/feat/1345-restore-endpoints

**Source:** project-beta-api@b32bf330

## [v0.7.400] - 2026-01-01

### Changes
- Merge pull request #1402 from Matchpoint-AI/feat/1371-e2e-versioning

**Source:** project-beta-api@c64a5983

## [v0.7.399] - 2025-12-31

### Changes
- Merge pull request #1397 from Matchpoint-AI/fix/1268-remove-workflow-service

**Source:** project-beta-api@b60b22a0

## [v0.7.398] - 2025-12-31

### Changes
- Merge pull request #1403 from Matchpoint-AI/fix/1386-brand-llm-migration

**Source:** project-beta-api@703a46b0

## [v0.7.397] - 2025-12-31

### Changes
- Merge pull request #1401 from Matchpoint-AI/feat/1369-deprecate-versioning

**Source:** project-beta-api@def0af18

## [v0.7.396] - 2025-12-31

### Changes
- Merge pull request #1400 from Matchpoint-AI/fix/1301-e2e-pubsub-tests

**Source:** project-beta-api@d0d5c897

## [v0.7.395] - 2025-12-31

### Changes
- Merge pull request #1399 from Matchpoint-AI/fix/1363-content-image-media-migration

**Source:** project-beta-api@9a6bf46c

## [v0.7.394] - 2025-12-31

### Changes
- Merge pull request #1394 from Matchpoint-AI/feat/1367-post-version-publisher

**Source:** project-beta-api@7a7945c7

## [v0.7.393] - 2025-12-31

### Changes
- Merge pull request #1393 from Matchpoint-AI/feat/1360-media-table

**Source:** project-beta-api@9df3a67b

## [v0.7.392] - 2025-12-31

### Changes
- Merge pull request #1396 from Matchpoint-AI/feat/1316-brand-crawler-pubsub

**Source:** project-beta-api@bcd78360

## [v0.7.391] - 2025-12-31

### Changes
- Merge pull request #1398 from Matchpoint-AI/feat/1298-content-status

**Source:** project-beta-api@40cbe845

## [v0.7.390] - 2025-12-31

### Changes
- Merge pull request #1395 from Matchpoint-AI/feat/1364-version-endpoints

**Source:** project-beta-api@08a6fd8b

## [v0.7.389] - 2025-12-31

### Changes
- Merge pull request #1392 from Matchpoint-AI/feat/1361-post-version

**Source:** project-beta-api@31603468

## [v0.7.388] - 2025-12-31

### Changes
- Merge pull request #1391 from Matchpoint-AI/feat/1362-version-request

**Source:** project-beta-api@92260991

## [v0.7.387] - 2025-12-31

### Changes
- Merge pull request #1390 from Matchpoint-AI/feat/1297-pubsub-workflow-controller

**Source:** project-beta-api@b436ff64

## [v0.7.386] - 2025-12-31

### Changes
- Merge pull request #1387 from Matchpoint-AI/feat/1383-two-action-publisher

**Source:** project-beta-api@51099c27

## [v0.7.385] - 2025-12-31

### Changes
- Delete terraform directory (#1389)

**Source:** project-beta-api@79837527

## [v0.7.384] - 2025-12-31

### Changes
- Merge pull request #1379 from Matchpoint-AI/fix/1317-remove-workflow-brand-endpoints

**Source:** project-beta-api@9355f7c2

## [v0.7.383] - 2025-12-31

### Changes
- cleanup: Simplify WorkflowService by removing unused methods (#1378)

**Source:** project-beta-api@7497d594

## [v0.7.382] - 2025-12-31

### Changes
- Merge pull request #1381 from Matchpoint-AI/fix/1318-remove-workflow-campaign-endpoints

**Source:** project-beta-api@a7143e5b

## [v0.7.381] - 2025-12-31

### Changes
- Merge pull request #1382 from Matchpoint-AI/fix/1370-dead-llm-services

**Source:** project-beta-api@beefba08

## [v0.7.380] - 2025-12-31

### Changes
- Merge pull request #1376 from Matchpoint-AI/cleanup/1375-dead-di

**Source:** project-beta-api@17d95c52

## [v0.7.379] - 2025-12-31

### Changes
- Merge pull request #1380 from Matchpoint-AI/feat/1352-pubsub-publishing

**Source:** project-beta-api@dab5429e

## [v0.7.378] - 2025-12-31

### Changes
- Merge pull request #1374 from Matchpoint-AI/fix/issue-1357

**Source:** project-beta-api@aa661692

## [v0.7.377] - 2025-12-31

### Changes
- Merge pull request #1372 from Matchpoint-AI/refactor/1355-remove-dead-llm

**Source:** project-beta-api@8cba2023

## [v0.7.376] - 2025-12-31

### Changes
- Merge pull request #1373 from Matchpoint-AI/fix/issue-1356

**Source:** project-beta-api@cc7c0649

## [v0.7.375] - 2025-12-31

### Changes
- Merge pull request #1350 from Matchpoint-AI/test/1335-pubsub-e2e

**Source:** project-beta-api@66d2495e

## [v0.7.374] - 2025-12-31

### Changes
- Merge pull request #1351 from Matchpoint-AI/feat/1315-brand-crawler-publisher

**Source:** project-beta-api@b09c54b9

## [v0.7.373] - 2025-12-31

### Changes
- Merge pull request #1343 from Matchpoint-AI/feat/1296-create-campaign-publisher

**Source:** project-beta-api@43f24b6a

## [v0.7.372] - 2025-12-31

### Changes
- Merge pull request #1344 from Matchpoint-AI/cleanup/1334-remove-legacy-publishing

**Source:** project-beta-api@d1f9abcc

## [v0.7.371] - 2025-12-31

### Changes
- Merge pull request #1348 from Matchpoint-AI/cleanup/1328-scheduler-todos

**Source:** project-beta-api@15f5710b

## [v0.7.370] - 2025-12-31

### Changes
- Merge pull request #1342 from Matchpoint-AI/feat/1332-campaign-publisher-protocol

**Source:** project-beta-api@c55e15a0

## [v0.7.369] - 2025-12-31

### Changes
- Merge pull request #1323 from Matchpoint-AI/feat/1274-content-gen-protocol

**Source:** project-beta-api@62d02b4a

## [v0.7.368] - 2025-12-31

### Changes
- Merge pull request #1341 from Matchpoint-AI/feat/api-skills-1330-1331

**Source:** project-beta-api@af35d50e

## [v0.7.367] - 2025-12-31

### Changes
- Merge pull request #1313 from Matchpoint-AI/feat/1269-campaign-constraints

**Source:** project-beta-api@fb1e16d0

## [v0.7.366] - 2025-12-31

### Changes
- Merge pull request #1336 from Matchpoint-AI/fix/1321-datetime-utc

**Source:** project-beta-api@69961d02

## [v0.7.365] - 2025-12-31

### Changes
- Merge pull request #1338 from Matchpoint-AI/chore/1337-cleanup-stale-files

**Source:** project-beta-api@2bf4530d

## [v0.7.364] - 2025-12-31

### Changes
- Merge pull request #1314 from Matchpoint-AI/fix/1312-dead-tests

**Source:** project-beta-api@1798fa1b

## [v0.7.363] - 2025-12-31

### Changes
- Merge pull request #1322 from Matchpoint-AI/feat/1311-coverage-thresholds

**Source:** project-beta-api@6efe016a

## [v0.7.362] - 2025-12-31

### Changes
- Merge pull request #1307 from Matchpoint-AI/feat/1293-mock-publisher

**Source:** project-beta-api@2a6e70ea

## [v0.7.361] - 2025-12-31

### Changes
- Merge pull request #1309 from Matchpoint-AI/test/1286-extractor-coverage

**Source:** project-beta-api@3926c1e1

## [v0.7.360] - 2025-12-31

### Changes
- Merge pull request #1310 from Matchpoint-AI/test/1287-prompt-composer-coverage

**Source:** project-beta-api@db98420d

## [v0.7.359] - 2025-12-31

### Changes
- Merge pull request #1306 from Matchpoint-AI/test/1290-expression-evaluator-coverage

**Source:** project-beta-api@e01e6694

## [v0.7.358] - 2025-12-31

### Changes
- Merge pull request #1308 from Matchpoint-AI/test/1289-quick-extract-coverage

**Source:** project-beta-api@c00ffdbf

## [v0.7.357] - 2025-12-31

### Changes
- Merge pull request #1305 from Matchpoint-AI/test/1288-rag-coverage

**Source:** project-beta-api@02994e78

## [v0.7.356] - 2025-12-31

### Changes
- Merge pull request #1304 from Matchpoint-AI/test/1285-local-workflow-coverage

**Source:** project-beta-api@4303178d

## [v0.7.355] - 2025-12-31

### Changes
- Merge pull request #1303 from Matchpoint-AI/refactor/rename-post-worker-to-content-generator

**Source:** project-beta-api@d7a79f1c

## [v0.7.354] - 2025-12-30

### Changes
- Merge pull request #1273 from Matchpoint-AI/feat/313-content-generation-publisher

**Source:** project-beta-api@18ad0954

## [v0.7.353] - 2025-12-30

### Changes
- Merge pull request #1283 from Matchpoint-AI/fix/1257-retry-v2

**Source:** project-beta-api@ebc74a67

## [v0.7.352] - 2025-12-30

### Changes
- Merge pull request #1284 from Matchpoint-AI/feat/1279-brand-crawl-progress

**Source:** project-beta-api@60c830dc

## [v0.7.351] - 2025-12-30

### Changes
- Merge pull request #1280 from Matchpoint-AI/fix/1255-image-gen-task

**Source:** project-beta-api@fc6838b1

## [v0.7.350] - 2025-12-30

### Changes
- Merge pull request #1270 from Matchpoint-AI/feat/1263-publisher-protocol

**Source:** project-beta-api@26548fc0

## [v0.7.349] - 2025-12-30

### Changes
- Merge pull request #1259 from Matchpoint-AI/fix/1251-image-sync

**Source:** project-beta-api@a3892bbc

## [v0.7.348] - 2025-12-30

### Changes
- Merge pull request #1262 from Matchpoint-AI/feat/brand-campaign-relationships

**Source:** project-beta-api@11c965f7

## [v0.7.347] - 2025-12-30

### Changes
- Merge pull request #1245 from Matchpoint-AI/fix/1244-audience-params

**Source:** project-beta-api@a5a7c4d9

## [v0.7.346] - 2025-12-30

### Changes
- Merge pull request #1252 from Matchpoint-AI/fix/1247-feature-flag

**Source:** project-beta-api@82a46c06

## [v0.7.345] - 2025-12-30

### Changes
- Merge pull request #1243 from Matchpoint-AI/fix/1222-posts-per-day-overwrite

**Source:** project-beta-api@49e943d3

## [v0.7.344] - 2025-12-30

### Changes
- Merge pull request #1242 from Matchpoint-AI/fix/1222-posts-per-day-overwrite

**Source:** project-beta-api@38d02b90

## [v0.7.343] - 2025-12-29

### Changes
- fix: add fallback for API_BASE_URL env var reading (Issue #1236) (#1241)

**Source:** project-beta-api@794b6ebf

## [v0.7.342] - 2025-12-29

### Changes
- Merge pull request #1234 from Matchpoint-AI/feat/1227-workflow-status

**Source:** project-beta-api@a086cfea

## [v0.7.341] - 2025-12-29

### Changes
- fix: make duration_weeks and posts_per_day required in campaign schema (#1235)

**Source:** project-beta-api@b661d155

## [v0.7.340] - 2025-12-29

### Changes
- Merge pull request #1232 from Matchpoint-AI/fix/1226-posts-per-day-strict

**Source:** project-beta-api@72e263eb

## [v0.7.339] - 2025-12-29

### Changes
- Merge pull request #1229 from Matchpoint-AI/fix/1101-consolidate-auth-refresh

**Source:** project-beta-api@f0595020

## [v0.7.338] - 2025-12-29

### Changes
- Merge pull request #1228 from Matchpoint-AI/fix/1098-crawls-resource

**Source:** project-beta-api@b0162309

## [v0.7.337] - 2025-12-29

### Changes
- Merge pull request #1231 from Matchpoint-AI/fix/require-total-posts

**Source:** project-beta-api@61a5722a

## [v0.7.336] - 2025-12-29

### Changes
- Merge pull request #1230 from Matchpoint-AI/fix/1097-export-content-negotiation

**Source:** project-beta-api@1c65a2cb

## [v0.7.335] - 2025-12-29

### Changes
- fix: Support multiple posts per day with postNumber parameter (#1224)

**Source:** project-beta-api@19e1d672

## [v0.7.334] - 2025-12-29

### Changes
- Merge pull request #1221 from Matchpoint-AI/fix/284-workflow-api-base

**Source:** project-beta-api@b6c62730

## [v0.7.333] - 2025-12-29

### Changes
- fix: lower coverage threshold to 89.9% to avoid floating-point edge case (#1225)

**Source:** project-beta-api@11267438

## [v0.7.332] - 2025-12-29

### Changes
- Merge pull request #1220 from Matchpoint-AI/feat/1215-model-used

**Source:** project-beta-api@ca05ea19

## [v0.7.331] - 2025-12-29

### Changes
- fix: add GCP Workflows default() and map.get() to expression evaluator (#1219)

**Source:** project-beta-api@2bec7f8e

## [v0.7.330] - 2025-12-29

### Changes
- Merge pull request #1218 from Matchpoint-AI/fix/261-demographics

**Source:** project-beta-api@cf708763

## [v0.7.329] - 2025-12-29

### Changes
- Merge pull request #1217 from Matchpoint-AI/feat/1209-background-workflows

**Source:** project-beta-api@d2ae8dbc

## [v0.7.328] - 2025-12-29

### Changes
- Merge pull request #1216 from Matchpoint-AI/feat/1190-model-selection

**Source:** project-beta-api@4812231b

## [v0.7.327] - 2025-12-29

### Changes
- Merge pull request #1214 from Matchpoint-AI/fix/1210-posts-per-day

**Source:** project-beta-api@f906cd5a

## [v0.7.326] - 2025-12-29

### Changes
- Merge pull request #1213 from Matchpoint-AI/fix/1212-campaign-brand-context

**Source:** project-beta-api@7909bab5

## [v0.7.325] - 2025-12-29

### Changes
- Merge pull request #1208 from Matchpoint-AI/fix/rmm-l2-phase3-unused

**Source:** project-beta-api@0332df40

## [v0.7.324] - 2025-12-29

### Changes
- Merge pull request #1207 from Matchpoint-AI/fix/1205-json-serialization

**Source:** project-beta-api@9ff9fddd

## [v0.7.323] - 2025-12-29

### Changes
- Merge pull request #1204 from Matchpoint-AI/fix/267-knowledge-extraction

**Source:** project-beta-api@498998a7

## [v0.7.322] - 2025-12-29

### Changes
- Merge pull request #1206 from Matchpoint-AI/fix/268-campaign-validation

**Source:** project-beta-api@edea3070

## [v0.7.321] - 2025-12-29

### Changes
- Merge pull request #1201 from Matchpoint-AI/fix/rmm-l2-active-endpoints

**Source:** project-beta-api@841bd4b5

## [v0.7.320] - 2025-12-29

### Changes
- Merge pull request #1203 from Matchpoint-AI/fix/1198-workflow

**Source:** project-beta-api@4c41b4d5

## [v0.7.319] - 2025-12-29

### Changes
- Merge pull request #1202 from Matchpoint-AI/fix/rmm-l2-dead-code

**Source:** project-beta-api@345f3576

## [v0.7.318] - 2025-12-29

### Changes
- Merge pull request #1200 from Matchpoint-AI/fix/260-demographics-persistence

**Source:** project-beta-api@60ec0c24

## [v0.7.317] - 2025-12-29

### Changes
- Merge pull request #1197 from Matchpoint-AI/fix/1195-db-pool-exhaustion

**Source:** project-beta-api@275efec2

## [v0.7.316] - 2025-12-29

### Changes
- Merge pull request #1196 from Matchpoint-AI/fix/content-generation-persistence

**Source:** project-beta-api@bc2b5e7b

## [v0.7.315] - 2025-12-28

### Changes
- Merge pull request #1194 from Matchpoint-AI/fix/1192-brand-kb-mock

**Source:** project-beta-api@d60dae1a

## [v0.7.314] - 2025-12-28

### Changes
- Merge pull request #1193 from Matchpoint-AI/fix/256-switch-support

**Source:** project-beta-api@48e5c269

## [v0.7.313] - 2025-12-28

### Changes
- Merge pull request #1191 from Matchpoint-AI/fix/1187-startup-probe

**Source:** project-beta-api@b54fefcd

## [v0.7.312] - 2025-12-28

### Changes
- Merge pull request #1186 from Matchpoint-AI/fix/1088-content-approvals

**Source:** project-beta-api@2c991a0f

## [v0.7.311] - 2025-12-28

### Changes
- feat: add RMM L2 compliant POST /url-content-fetches endpoint (#1185)

**Source:** project-beta-api@697a88d9

## [v0.7.310] - 2025-12-28

### Changes
- Merge pull request #1182 from Matchpoint-AI/refactor/1140-instagram-integration

**Source:** project-beta-api@c65d6cfc

## [v0.7.309] - 2025-12-28

### Changes
- Merge pull request #1164 from Matchpoint-AI/feat/1149-scene-mix-policy-api

**Source:** project-beta-api@94d664ae

## [v0.7.308] - 2025-12-28

### Changes
- Update pytest.ini (#1184)

**Source:** project-beta-api@dd3cd285

## [v0.7.307] - 2025-12-28

### Changes
- Merge pull request #1181 from Matchpoint-AI/feat/1086-e2e-gate-expansion

**Source:** project-beta-api@762c1d95

## [v0.7.306] - 2025-12-28

### Changes
- fix: include campaign demographics in post generation prompt (#1183)

**Source:** project-beta-api@b9bbbe49

## [v0.7.305] - 2025-12-28

### Changes
- Merge pull request #1165 from Matchpoint-AI/feat/1152-diversity-scoring

**Source:** project-beta-api@a2e63212

## [v0.7.304] - 2025-12-28

### Changes
- Merge pull request #1180 from Matchpoint-AI/fix/1177-audience-columns

**Source:** project-beta-api@78b81bf8

## [v0.7.303] - 2025-12-28

### Changes
- Merge pull request #1179 from Matchpoint-AI/fix/225-auto-workflow

**Source:** project-beta-api@f7400cc5

## [v0.7.302] - 2025-12-28

### Changes
- Merge pull request #1178 from Matchpoint-AI/fix/1173-campaign-stats-fields

**Source:** project-beta-api@f3792373

## [v0.7.301] - 2025-12-28

### Changes
- Merge pull request #1176 from Matchpoint-AI/feat/1146-dynamic-prompt-composer

**Source:** project-beta-api@8663473a

## [v0.7.300] - 2025-12-28

### Changes
- Merge pull request #1167 from Matchpoint-AI/fix/1108-dead-brand-pages

**Source:** project-beta-api@1e00c838

## [v0.7.299] - 2025-12-28

### Changes
- Merge pull request #1170 from Matchpoint-AI/fix/1112-dead-campaign-misc

**Source:** project-beta-api@962b45cb

## [v0.7.298] - 2025-12-28

### Changes
- fix: remove unused content endpoints (Issue #1113) (#1174)

**Source:** project-beta-api@402811f6

## [v0.7.297] - 2025-12-28

### Changes
- fix: remove unused brand misc endpoints as dead code (#1172)

**Source:** project-beta-api@d7b9569b

## [v0.7.296] - 2025-12-28

### Changes
- Merge pull request #1175 from Matchpoint-AI/fix/1115-dead-crawls

**Source:** project-beta-api@fad9699c

## [v0.7.295] - 2025-12-28

### Changes
- Merge pull request #1171 from Matchpoint-AI/fix/1111-dead-workflow

**Source:** project-beta-api@7c81ed46

## [v0.7.294] - 2025-12-28

### Changes
- Merge pull request #1145 from Matchpoint-AI/fix/1117-dead-knowledge

**Source:** project-beta-api@cfe20351

## [v0.7.293] - 2025-12-28

### Changes
- Merge pull request #1168 from Matchpoint-AI/feat/1151-rag-service

**Source:** project-beta-api@2bdb547d

## [v0.7.292] - 2025-12-28

### Changes
- Merge pull request #1143 from Matchpoint-AI/fix/1119-dead-misc

**Source:** project-beta-api@03de8050

## [v0.7.291] - 2025-12-28

### Changes
- Merge pull request #1139 from Matchpoint-AI/fix/1114-dead-code-images

**Source:** project-beta-api@bc4c2095

## [v0.7.290] - 2025-12-28

### Changes
- Merge pull request #1163 from Matchpoint-AI/feat/1150-feedback-system

**Source:** project-beta-api@6a8a9a91

## [v0.7.289] - 2025-12-28

### Changes
- chore: centralize coverage threshold config and raise to 92% (#1161)

**Source:** project-beta-api@3cfc2d28

## [v0.7.288] - 2025-12-28

### Changes
- Merge pull request #1162 from Matchpoint-AI/test/auth-coverage-gaps

**Source:** project-beta-api@22b2f928

## [v0.7.287] - 2025-12-28

### Changes
- Merge pull request #1131 from Matchpoint-AI/fix/1121-prompt-composer

**Source:** project-beta-api@bab11b70

## [v0.7.286] - 2025-12-28

### Changes
- Merge pull request #1155 from Matchpoint-AI/fix/1137-audience-fallbacks

**Source:** project-beta-api@1f59a089

## [v0.7.285] - 2025-12-28

### Changes
- fix: correct Black formatting in middleware and workflow modules (#1148)

**Source:** project-beta-api@474c67f7

## [v0.7.284] - 2025-12-28

### Changes
- Merge pull request #1138 from Matchpoint-AI/fix/1109-dead-code-queue

**Source:** project-beta-api@832f4f74

## [v0.7.283] - 2025-12-28

### Changes
- Merge pull request #1141 from Matchpoint-AI/fix/1118-dead-session

**Source:** project-beta-api@3c9dc724

## [v0.7.282] - 2025-12-28

### Changes
- ci: add concurrency limits to prevent runner exhaustion (#1142)

**Source:** project-beta-api@daee6e0e

## [v0.7.281] - 2025-12-28

### Changes
- Merge pull request #1128 from Matchpoint-AI/fix/1085-caption-500

**Source:** project-beta-api@b7e6f66d

## [v0.7.280] - 2025-12-28

### Changes
- fix: rename execution_id to job_id in workflow args (#1133)

**Source:** project-beta-api@3d9f0342

## [v0.7.279] - 2025-12-27

### Changes
- Merge pull request #1124 from Matchpoint-AI/fix/1082-resend-403

**Source:** project-beta-api@39325570

## [v0.7.278] - 2025-12-27

### Changes
- Merge pull request #1125 from Matchpoint-AI/fix/1084-image-422

**Source:** project-beta-api@67e4366c

## [v0.7.277] - 2025-12-27

### Changes
- Merge pull request #1127 from Matchpoint-AI/fix/1121-prompt-campaign-data

**Source:** project-beta-api@11be8991

## [v0.7.276] - 2025-12-27

### Changes
- Merge pull request #1130 from Matchpoint-AI/docs/skill-progressive-enhancement

**Source:** project-beta-api@23f030ae

## [v0.7.275] - 2025-12-27

### Changes
- Merge pull request #1129 from Matchpoint-AI/docs/skill-idempotent-migrations

**Source:** project-beta-api@13e61ff9

## [v0.7.274] - 2025-12-27

### Changes
- Merge pull request #1126 from Matchpoint-AI/fix/1122-prompt-brand-kb

**Source:** project-beta-api@57513434

## [v0.7.273] - 2025-12-27

### Changes
- Merge pull request #1083 from Matchpoint-AI/refactor/1021-content-controller

**Source:** project-beta-api@86694da0

## [v0.7.272] - 2025-12-27

### Changes
- Merge pull request #1081 from Matchpoint-AI/fix/1045-dead-letter-queue

**Source:** project-beta-api@3b456dbf

## [v0.7.271] - 2025-12-27

### Changes
- feat: add alerting infrastructure for content generation failures (#1078)

**Source:** project-beta-api@ae16a385

## [v0.7.270] - 2025-12-27

### Changes
- Merge pull request #1080 from Matchpoint-AI/fix/1042-structured-errors

**Source:** project-beta-api@1c3b17ba

## [v0.7.269] - 2025-12-27

### Changes
- Merge pull request #1074 from Matchpoint-AI/fix/1072-quality-service

**Source:** project-beta-api@020082e8

## [v0.7.268] - 2025-12-27

### Changes
- Merge pull request #1079 from Matchpoint-AI/fix/1077-scene-mix-migration

**Source:** project-beta-api@cc1102e0

## [v0.7.267] - 2025-12-27

### Changes
- fix: use upsert pattern for content creation to prevent duplicate key errors (#1075)

**Source:** project-beta-api@d1df8cbb

## [v0.7.266] - 2025-12-27

### Changes
- feat: add /metrics endpoint for content generation success rate visibility (#1073)

**Source:** project-beta-api@141e84ea

## [v0.7.265] - 2025-12-27

### Changes
- feat: add correlation ID (trace_id) for end-to-end request tracing (#1056)

**Source:** project-beta-api@c3eb146f

## [v0.7.264] - 2025-12-27

### Changes
- Merge pull request #1069 from Matchpoint-AI/feat/1054-rate-limiting

**Source:** project-beta-api@78e62e63

## [v0.7.263] - 2025-12-26

### Changes
- Merge pull request #1070 from Matchpoint-AI/feat/1050-audit-log

**Source:** project-beta-api@851c1f8a

## [v0.7.262] - 2025-12-26

### Changes
- Merge pull request #1071 from Matchpoint-AI/fix/162-quality-scores

**Source:** project-beta-api@9d96c1b9

## [v0.7.261] - 2025-12-26

### Changes
- Merge pull request #1067 from Matchpoint-AI/fix/1065-auth-refresh

**Source:** project-beta-api@ac247f22

## [v0.7.260] - 2025-12-26

### Changes
- Merge pull request #1068 from Matchpoint-AI/test/1051-db-constraints

**Source:** project-beta-api@4f6a7b2f

## [v0.7.259] - 2025-12-26

### Changes
- Merge pull request #1058 from Matchpoint-AI/fix/1029-health-check

**Source:** project-beta-api@16fa7256

## [v0.7.258] - 2025-12-26

### Changes
- Merge pull request #1059 from Matchpoint-AI/fix/1039-timeouts

**Source:** project-beta-api@99bc5bec

## [v0.7.257] - 2025-12-26

### Changes
- Merge pull request #1057 from Matchpoint-AI/fix/1037-token-refresh

**Source:** project-beta-api@b861479b

## [v0.7.256] - 2025-12-26

### Changes
- Merge pull request #1060 from Matchpoint-AI/fix/1053-graceful-shutdown

**Source:** project-beta-api@70929582

## [v0.7.255] - 2025-12-26

### Changes
- Merge pull request #1061 from Matchpoint-AI/fix/1040-circuit-breaker

**Source:** project-beta-api@b309d2eb

## [v0.7.254] - 2025-12-26

### Changes
- Merge pull request #1062 from Matchpoint-AI/fix/1041-retry-logic

**Source:** project-beta-api@13d12032

## [v0.7.253] - 2025-12-26

### Changes
- Merge pull request #1035 from Matchpoint-AI/fix/1022-exception-handling

**Source:** project-beta-api@23ab4dae

## [v0.7.252] - 2025-12-26

### Changes
- Merge pull request #1048 from Matchpoint-AI/fix/1024-enable-e2e

**Source:** project-beta-api@b4cb71d5

## [v0.7.251] - 2025-12-26

### Changes
- Merge pull request #1036 from Matchpoint-AI/fix/1020-layering

**Source:** project-beta-api@3ae95f22

## [v0.7.250] - 2025-12-26

### Changes
- Merge pull request #1047 from Matchpoint-AI/fix/1028-posts-test

**Source:** project-beta-api@b77fc189

## [v0.7.249] - 2025-12-26

### Changes
- Merge pull request #1049 from Matchpoint-AI/fix/1026-db-logging

**Source:** project-beta-api@7e2355de

## [v0.7.248] - 2025-12-26

### Changes
- Merge pull request #1034 from Matchpoint-AI/fix/1019-image-failure

**Source:** project-beta-api@be64d453

## [v0.7.247] - 2025-12-26

### Changes
- Merge pull request #1032 from Matchpoint-AI/fix/1016-posts-persistence

**Source:** project-beta-api@b668d917

## [v0.7.246] - 2025-12-26

### Changes
- Merge pull request #1033 from Matchpoint-AI/docs/1018-deployment-skill

**Source:** project-beta-api@f8fed213

## [v0.7.245] - 2025-12-26

### Changes
- Merge pull request #1031 from Matchpoint-AI/test/1017-db-assertion

**Source:** project-beta-api@848dc248

## [v0.7.244] - 2025-12-26

### Changes
- Fix #1014: Add missing campaign plan fields (mix_goal, subtype_weights, rationale)

**Source:** project-beta-api@6687d0cf

## [v0.7.243] - 2025-12-25

### Changes
- fix(#1010): use atomic UPSERT for scene_mix_plan creation (#1011)

**Source:** project-beta-api@d54123eb

## [v0.7.242] - 2025-12-25

### Changes
- fix(#1007): add diagnostic logging for content parsing (#1008)

**Source:** project-beta-api@c5f3697f

## [v0.7.241] - 2025-12-24

### Changes
- fix: return 204 instead of 404 when campaign has no content yet (#1005)

**Source:** project-beta-api@e3ef403c

## [v0.7.240] - 2025-12-24

### Changes
- feat: remove hasBrand field from API responses (#1004)

**Source:** project-beta-api@3350cbe0

## [v0.7.239] - 2025-12-24

### Changes
- Merge pull request #1002 from Matchpoint-AI/fix/1001-email-verification

**Source:** project-beta-api@8c582a4c

## [v0.7.238] - 2025-12-24

### Changes
- Merge pull request #998 from Matchpoint-AI/fix/978-db-constraint

**Source:** project-beta-api@c178566a

## [v0.7.237] - 2025-12-24

### Changes
- Merge pull request #997 from Matchpoint-AI/fix/content-parsing-platform-posts

**Source:** project-beta-api@ee0cd11e

## [v0.7.236] - 2025-12-24

### Changes
- Merge pull request #996 from Matchpoint-AI/fix/array-expression-before-concat

**Source:** project-beta-api@a5828cc1

## [v0.7.235] - 2025-12-24

### Changes
- Merge pull request #995 from Matchpoint-AI/fix/992-content-status-patch

**Source:** project-beta-api@30fcfb6a

## [v0.7.234] - 2025-12-24

### Changes
- Merge pull request #994 from Matchpoint-AI/perf/fast-image-generation

**Source:** project-beta-api@a7980e31

## [v0.7.233] - 2025-12-24

### Changes
- Merge pull request #991 from Matchpoint-AI/fix/990-test-coverage

**Source:** project-beta-api@cf4e42f5

## [v0.7.232] - 2025-12-23

### Changes
- Merge pull request #988 from Matchpoint-AI/fix/workflow-dot-notation

**Source:** project-beta-api@9f3fbc20

## [v0.7.231] - 2025-12-23

### Changes
- Merge pull request #989 from Matchpoint-AI/feat/987-increase-test-coverage

**Source:** project-beta-api@e7c5bcd9

## [v0.7.230] - 2025-12-23

### Changes
- Merge pull request #981 from Matchpoint-AI/feat/1807-phase3-background-crawl

**Source:** project-beta-api@3e661682

## [v0.7.229] - 2025-12-23

### Changes
- Merge pull request #986 from Matchpoint-AI/fix/985-test-coverage

**Source:** project-beta-api@cebac19e

## [v0.7.228] - 2025-12-23

### Changes
- Merge pull request #984 from Matchpoint-AI/fix/982-email-verification

**Source:** project-beta-api@4ea90b06

## [v0.7.227] - 2025-12-23

### Changes
- Merge pull request #975 from Matchpoint-AI/fix/fal-model-id-format

**Source:** project-beta-api@8fd842e7

## [v0.7.226] - 2025-12-23

### Changes
- Merge pull request #974 from Matchpoint-AI/feat/local-workflow-gcp-parity

**Source:** project-beta-api@da2ccd98

## [v0.7.225] - 2025-12-22

### Changes
- Merge pull request #973 from Matchpoint-AI/fix/972-response-model-by-alias

**Source:** project-beta-api@4a2e2c6b

## [v0.7.224] - 2025-12-22

### Changes
- Merge pull request #970 from Matchpoint-AI/perf/fast-image-generation

**Source:** project-beta-api@6c1dc126

## [v0.7.223] - 2025-12-22

### Changes
- Merge pull request #968 from Matchpoint-AI/fix/962-observability

**Source:** project-beta-api@40c568da

## [v0.7.222] - 2025-12-22

### Changes
- Merge pull request #965 from Matchpoint-AI/fix/964-workflow-api-base

**Source:** project-beta-api@c63d1367

## [v0.7.221] - 2025-12-22

### Changes
- Merge pull request #963 from Matchpoint-AI/feat/961-content-integration-test

**Source:** project-beta-api@7bc7bd1b

## [v0.7.220] - 2025-12-22

### Changes
- Merge pull request #960 from Matchpoint-AI/fix/959-content-status-tracking

**Source:** project-beta-api@7b2c7c68

## [v0.7.219] - 2025-12-22

### Changes
- Merge pull request #958 from Matchpoint-AI/feat/local-workflow-gcp-parity

**Source:** project-beta-api@7182b75d

## [v0.7.218] - 2025-12-22

### Changes
- Merge pull request #957 from Matchpoint-AI/fix/1326-brand-scraping

**Source:** project-beta-api@d2d45b7c

## [v0.7.217] - 2025-12-22

### Changes
- Merge pull request #955 from Matchpoint-AI/fix/954-content-prompt-endpoint

**Source:** project-beta-api@c4c9861e

## [v0.7.216] - 2025-12-21

### Changes
- Merge pull request #953 from Matchpoint-AI/skill/api-validation-agents

**Source:** project-beta-api@a6308a75

## [v0.7.215] - 2025-12-21

### Changes
- Merge pull request #949 from Matchpoint-AI/feat/1807-progressive-brand

**Source:** project-beta-api@a7d45332

## [v0.7.214] - 2025-12-21

### Changes
- Merge pull request #950 from Matchpoint-AI/feat/1806-quick-extract

**Source:** project-beta-api@9cc181f4

## [v0.7.213] - 2025-12-21

### Changes
- Merge pull request #948 from Matchpoint-AI/fix/1805-nonblocking-workflow

**Source:** project-beta-api@fd5ff714

## [v0.7.212] - 2025-12-21

### Changes
- Merge pull request #945 from Matchpoint-AI/fix/944-brands-user-filter

**Source:** project-beta-api@6ee79ca7

## [v0.7.211] - 2025-12-21

### Changes
- Merge pull request #947 from Matchpoint-AI/refactor/consolidate-release-workflow

**Source:** project-beta-api@fa57607a

## [v0.7.210] - 2025-12-21

### Changes
- Merge pull request #939 from Matchpoint-AI/fix/937-scene-mix-constraint

**Source:** project-beta-api@93cb6940 "Merge pull request #939 from Matchpoint-AI/fix/937-scene-mix-constraint"

## [v0.7.209] - 2025-12-20

### Changes
- Merge pull request #942 from Matchpoint-AI/fix/938-post-generation

**Source:** project-beta-api@7341b34a "Merge pull request #942 from Matchpoint-AI/fix/938-post-generation"

## [v0.7.208] - 2025-12-20

### Changes
- Merge pull request #940 from Matchpoint-AI/fix/938-post-generation

**Source:** project-beta-api@c1c82ff5 "Merge pull request #940 from Matchpoint-AI/fix/938-post-generation"

## [v0.7.206] - 2025-12-20

### Changes
- Merge pull request #935 from Matchpoint-AI/fix/934-fal-image-generation-404

**Source:** project-beta-api@1aaff35a "Merge pull request #935 from Matchpoint-AI/fix/934-fal-image-generation-404"

## [v0.7.205] - 2025-12-19

### Changes
- Merge pull request #933 from Matchpoint-AI/fix/930-931-connection-pool-and-platform-bugs

**Source:** project-beta-api@268f68ec "Merge pull request #933 from Matchpoint-AI/fix/930-931-connection-pool-and-platform-bugs"

## [v0.7.204] - 2025-12-19

### Changes
- Merge pull request #932 from Matchpoint-AI/fix/931-platform-none

**Source:** project-beta-api@4fa2d63d "Merge pull request #932 from Matchpoint-AI/fix/931-platform-none"

## [v0.7.203] - 2025-12-19

### Changes
- Merge pull request #929 from Matchpoint-AI/fix/928-content-generation

**Source:** project-beta-api@e6fe2de6 "Merge pull request #929 from Matchpoint-AI/fix/928-content-generation"

## [v0.7.202] - 2025-12-18

### Changes
- Merge pull request #926 from Matchpoint-AI/fix/924-campaign-autotrigger

**Source:** project-beta-api@23314adf "Merge pull request #926 from Matchpoint-AI/fix/924-campaign-autotrigger"

## [v0.7.201] - 2025-12-18

### Changes
- Merge pull request #925 from Matchpoint-AI/fix/922-export-approval

**Source:** project-beta-api@f57cee99 "Merge pull request #925 from Matchpoint-AI/fix/922-export-approval"

## [v0.7.200] - 2025-12-18

### Changes
- Merge pull request #927 from Matchpoint-AI/fix/923-pdf-export

**Source:** project-beta-api@dc3b6b94 "Merge pull request #927 from Matchpoint-AI/fix/923-pdf-export"

## [v0.7.198] - 2025-12-18

### Changes
- Merge pull request #921 from Matchpoint-AI/fix/idempotent-generation-count-migration

**Source:** project-beta-api@35e47c94 "Merge pull request #921 from Matchpoint-AI/fix/idempotent-generation-count-migration"

## [v0.7.197] - 2025-12-18

### Changes
- Merge pull request #920 from Matchpoint-AI/fix/914-platforms-column

**Source:** project-beta-api@eec1621a "Merge pull request #920 from Matchpoint-AI/fix/914-platforms-column"

## [v0.7.195] - 2025-12-18

### Changes
- Merge pull request #919 from Matchpoint-AI/fix/docker-copy-config

**Source:** project-beta-api@2efe3097 "Merge pull request #919 from Matchpoint-AI/fix/docker-copy-config"

## [v0.7.194] - 2025-12-18

### Changes
- Merge pull request #916 from Matchpoint-AI/fix/idempotent-firebase-uid-migration

**Source:** project-beta-api@6b74bb1e "Merge pull request #916 from Matchpoint-AI/fix/idempotent-firebase-uid-migration"

## [v0.7.193] - 2025-12-18

### Changes
- Merge pull request #915 from Matchpoint-AI/fix/idempotent-migration-860

**Source:** project-beta-api@95d8ee81 "Merge pull request #915 from Matchpoint-AI/fix/idempotent-migration-860"

## [v0.7.191] - 2025-12-17

### Changes
- Merge pull request #911 from Matchpoint-AI/fix/910-docker-gcp-auth

**Source:** project-beta-api@f61877bc "Merge pull request #911 from Matchpoint-AI/fix/910-docker-gcp-auth"

## [v0.7.190] - 2025-12-17

### Changes
- Merge pull request #908 from Matchpoint-AI/fix/906-hasbrand-bug

**Source:** project-beta-api@15aa8018 "Merge pull request #908 from Matchpoint-AI/fix/906-hasbrand-bug"

## [v0.7.189] - 2025-12-17

### Changes
- Merge pull request #902 from Matchpoint-AI/fix/1721-standardize-runner-labels

**Source:** project-beta-api@397b115f "Merge pull request #902 from Matchpoint-AI/fix/1721-standardize-runner-labels"

## [v0.7.188] - 2025-12-17

### Changes
- Merge pull request #904 from Matchpoint-AI/fix/903-worktree-cleanup

**Source:** project-beta-api@4a38cd09 "Merge pull request #904 from Matchpoint-AI/fix/903-worktree-cleanup"

## [v0.7.187] - 2025-12-16

### Changes
- Merge pull request #901 from Matchpoint-AI/fix/900-remove-firebase

**Source:** project-beta-api@92dd549a "Merge pull request #901 from Matchpoint-AI/fix/900-remove-firebase"

## [v0.7.186] - 2025-12-16

### Changes
- chore: Remove orphaned cloudbuild.yaml and update docs to GitHub Actions (#899)

**Source:** project-beta-api@05da5927 "chore: Remove orphaned cloudbuild.yaml and update docs to GitHub Actions (#899)"

## [v0.7.185] - 2025-12-16

### Changes
- Merge pull request #896 from Matchpoint-AI/fix/895-brandstatus-enum

**Source:** project-beta-api@ec8b8f86 "Merge pull request #896 from Matchpoint-AI/fix/895-brandstatus-enum"

## [v0.7.184] - 2025-12-16

### Changes
- Merge pull request #894 from Matchpoint-AI/fix/893-login-token

**Source:** project-beta-api@fc0bd594 "Merge pull request #894 from Matchpoint-AI/fix/893-login-token"

## [v0.7.183] - 2025-12-16

### Changes
- Merge pull request #892 from Matchpoint-AI/feat/1009-brand-colors

**Source:** project-beta-api@14304ed6 "Merge pull request #892 from Matchpoint-AI/feat/1009-brand-colors"

## [v0.7.182] - 2025-12-16

### Changes
- Merge pull request #891 from Matchpoint-AI/fix/openapi-cleanup

**Source:** project-beta-api@8eb6f3ac "Merge pull request #891 from Matchpoint-AI/fix/openapi-cleanup"

## [v0.7.181] - 2025-12-15

### Changes
- Merge pull request #890 from Matchpoint-AI/feat/881-api-linting

**Source:** project-beta-api@7d3f9ad1 "Merge pull request #890 from Matchpoint-AI/feat/881-api-linting"

## [v0.7.180] - 2025-12-15

### Changes
- Merge pull request #889 from Matchpoint-AI/fix/888-flaky-port-test

**Source:** project-beta-api@05ef8e45 "Merge pull request #889 from Matchpoint-AI/fix/888-flaky-port-test"

## [v0.7.179] - 2025-12-15

### Changes
- Merge pull request #887 from Matchpoint-AI/skill/api-design-auditing

**Source:** project-beta-api@7dc041e5 "Merge pull request #887 from Matchpoint-AI/skill/api-design-auditing"

## [v0.7.178] - 2025-12-15

### Changes
- Merge pull request #842 from Matchpoint-AI/fix/839-openai-retry

**Source:** project-beta-api@9bbf73f6 "Merge pull request #842 from Matchpoint-AI/fix/839-openai-retry"

## [v0.7.177] - 2025-12-15

### Changes
- Merge pull request #880 from Matchpoint-AI/fix/879-color-extraction

**Source:** project-beta-api@d40e30b0 "Merge pull request #880 from Matchpoint-AI/fix/879-color-extraction"

## [v0.7.176] - 2025-12-15

### Changes
- Merge pull request #878 from Matchpoint-AI/fix/876-empty-image-url

**Source:** project-beta-api@d42e9302 "Merge pull request #878 from Matchpoint-AI/fix/876-empty-image-url"

## [v0.7.175] - 2025-12-15

### Changes
- fix: increment approval count instead of overwriting (#877)

**Source:** project-beta-api@63b46021 "fix: increment approval count instead of overwriting (#877)"

## [v0.7.174] - 2025-12-15

### Changes
- Merge pull request #851 from Matchpoint-AI/test/503-e2e-golden-path

**Source:** project-beta-api@a49dc5aa "Merge pull request #851 from Matchpoint-AI/test/503-e2e-golden-path"

## [v0.7.173] - 2025-12-14

### Changes
- Merge pull request #874 from Matchpoint-AI/feat/873-has-brand

**Source:** project-beta-api@6f10af6f "Merge pull request #874 from Matchpoint-AI/feat/873-has-brand"

## [v0.7.172] - 2025-12-14

### Changes
- Merge pull request #871 from Matchpoint-AI/fix/869-total-posts

**Source:** project-beta-api@4fd248b6 "Merge pull request #871 from Matchpoint-AI/fix/869-total-posts"

## [v0.7.171] - 2025-12-14

### Changes
- Merge pull request #836 from Matchpoint-AI/fix/471-config-validation

**Source:** project-beta-api@98ec7fb1 "Merge pull request #836 from Matchpoint-AI/fix/471-config-validation"

## [v0.7.170] - 2025-12-14

### Changes
- Merge pull request #870 from Matchpoint-AI/fix/868-single-prompt-per-post

**Source:** project-beta-api@b97ccef3 "Merge pull request #870 from Matchpoint-AI/fix/868-single-prompt-per-post"

## [v0.7.169] - 2025-12-14

### Changes
- Merge pull request #864 from Matchpoint-AI/feat/827-e2e-content-tests

**Source:** project-beta-api@9fcfe155 "Merge pull request #864 from Matchpoint-AI/feat/827-e2e-content-tests"

## [v0.7.168] - 2025-12-14

### Changes
- Merge pull request #867 from Matchpoint-AI/fix/docker-dind-race-condition

**Source:** project-beta-api@21d1cd32 "Merge pull request #867 from Matchpoint-AI/fix/docker-dind-race-condition"

## [v0.7.167] - 2025-12-14

### Changes
- Merge pull request #866 from Matchpoint-AI/test/685-thread-api

**Source:** project-beta-api@8020ef43 "Merge pull request #866 from Matchpoint-AI/test/685-thread-api"

## [v0.7.166] - 2025-12-14

### Changes
- Merge pull request #865 from Matchpoint-AI/docs/529-database-adr

**Source:** project-beta-api@92f64512 "Merge pull request #865 from Matchpoint-AI/docs/529-database-adr"

## [v0.7.165] - 2025-12-14

### Changes
- test: Add comprehensive tests for health controller endpoint (#863)

**Source:** project-beta-api@232c9e57 "test: Add comprehensive tests for health controller endpoint (#863)"

## [v0.7.164] - 2025-12-14

### Changes
- Merge pull request #859 from Matchpoint-AI/fix/856-bulk-approval-v2

**Source:** project-beta-api@12edadb9 "Merge pull request #859 from Matchpoint-AI/fix/856-bulk-approval-v2"

## [v0.7.163] - 2025-12-14

### Changes
- Merge pull request #862 from Matchpoint-AI/feat/855-calendar-reliability

**Source:** project-beta-api@0472ab3d "Merge pull request #862 from Matchpoint-AI/feat/855-calendar-reliability"

## [v0.7.162] - 2025-12-14

### Changes
- Merge pull request #858 from Matchpoint-AI/feat/468-schema-drift

**Source:** project-beta-api@9fc1de62 "Merge pull request #858 from Matchpoint-AI/feat/468-schema-drift"

## [v0.7.161] - 2025-12-14

### Changes
- Merge pull request #861 from Matchpoint-AI/fix/860-schema-drift

**Source:** project-beta-api@3df07081 "Merge pull request #861 from Matchpoint-AI/fix/860-schema-drift"

## [v0.7.160] - 2025-12-13

### Changes
- Merge pull request #854 from Matchpoint-AI/feat/649-token-refresh

**Source:** project-beta-api@3fd05d0a "Merge pull request #854 from Matchpoint-AI/feat/649-token-refresh"

## [v0.7.159] - 2025-12-13

### Changes
- Merge pull request #849 from Matchpoint-AI/fix/847-multi-platform

**Source:** project-beta-api@ac7f78b3 "Merge pull request #849 from Matchpoint-AI/fix/847-multi-platform"

## [v0.7.158] - 2025-12-13

### Changes
- Merge pull request #850 from Matchpoint-AI/fix/846-bulk-approval

**Source:** project-beta-api@4b55b60c "Merge pull request #850 from Matchpoint-AI/fix/846-bulk-approval"

## [v0.7.157] - 2025-12-13

### Changes
- fix: Add ADDITIONAL_CORS_ORIGINS environment variable for flexible CORS configuration (#853)

**Source:** project-beta-api@f6020d79 "fix: Add ADDITIONAL_CORS_ORIGINS environment variable for flexible CORS configuration (#853)"

## [v0.7.156] - 2025-12-13

### Changes
- Merge pull request #838 from Matchpoint-AI/fix/513-dynamic-prompt

**Source:** project-beta-api@49f3f691 "Merge pull request #838 from Matchpoint-AI/fix/513-dynamic-prompt"

## [v0.7.155] - 2025-12-13

### Changes
- Merge pull request #841 from Matchpoint-AI/fix/16-remove-ai-dir

**Source:** project-beta-api@c738df03 "Merge pull request #841 from Matchpoint-AI/fix/16-remove-ai-dir"

## [v0.7.154] - 2025-12-13

### Changes
- Merge pull request #832 from Matchpoint-AI/fix/736-datetime-utcnow

**Source:** project-beta-api@fc88ab31 "Merge pull request #832 from Matchpoint-AI/fix/736-datetime-utcnow"

## [v0.7.153] - 2025-12-13

### Changes
- Merge pull request #831 from Matchpoint-AI/fix/711-apiconfig-tests

**Source:** project-beta-api@d20c07d0 "Merge pull request #831 from Matchpoint-AI/fix/711-apiconfig-tests"

## [v0.7.152] - 2025-12-13

### Changes
- Merge pull request #822 from Matchpoint-AI/fix/744-apiconfig-di-injection

**Source:** project-beta-api@9a751bcd "Merge pull request #822 from Matchpoint-AI/fix/744-apiconfig-di-injection"

## [v0.7.151] - 2025-12-13

### Changes
- Merge pull request #830 from Matchpoint-AI/delete-e2e-workflow

**Source:** project-beta-api@68acbf20 "Merge pull request #830 from Matchpoint-AI/delete-e2e-workflow"

## [v0.7.150] - 2025-12-13

### Changes
- Merge pull request #829 from Matchpoint-AI/fix/remove-e2e-workflow

**Source:** project-beta-api@6fd9ab7a "Merge pull request #829 from Matchpoint-AI/fix/remove-e2e-workflow"

## [v0.7.149] - 2025-12-13

### Changes
- Merge pull request #824 from Matchpoint-AI/fix/654-e2e-content-generation

**Source:** project-beta-api@60c6b8b9 "Merge pull request #824 from Matchpoint-AI/fix/654-e2e-content-generation"

## [v0.7.148] - 2025-12-13

### Changes
- Merge pull request #826 from Matchpoint-AI/feat/1431-automated-migrations

**Source:** project-beta-api@6f854327 "Merge pull request #826 from Matchpoint-AI/feat/1431-automated-migrations"

## [v0.7.147] - 2025-12-13

### Changes
- Merge pull request #823 from Matchpoint-AI/fix/746-silent-workflow-failure

**Source:** project-beta-api@0b6b1ba1 "Merge pull request #823 from Matchpoint-AI/fix/746-silent-workflow-failure"

## [v0.7.146] - 2025-12-13

### Changes
- Merge pull request #820 from Matchpoint-AI/fix/817-bulk-approval-bug

**Source:** project-beta-api@582629a4 "Merge pull request #820 from Matchpoint-AI/fix/817-bulk-approval-bug"

## [v0.7.145] - 2025-12-12

### Changes
- Merge pull request #819 from Matchpoint-AI/fix/818-fal-image-bug

**Source:** project-beta-api@5e92e088 "Merge pull request #819 from Matchpoint-AI/fix/818-fal-image-bug"

## [v0.7.144] - 2025-12-12

### Changes
- Merge pull request #821 from Matchpoint-AI/fix/816-campaign-type-bug

**Source:** project-beta-api@75a9667b "Merge pull request #821 from Matchpoint-AI/fix/816-campaign-type-bug"

## [v0.7.143] - 2025-12-12

### Changes
- fix: Make migration 548e5a2dc7a4 idempotent with IF EXISTS check (#815)

**Source:** project-beta-api@ec3e1a57 "fix: Make migration 548e5a2dc7a4 idempotent with IF EXISTS check (#815)"

## [v0.7.142] - 2025-12-12

### Changes
- Merge pull request #811 from Matchpoint-AI/fix/678-e2e-content-workflow

**Source:** project-beta-api@ddd29192 "Merge pull request #811 from Matchpoint-AI/fix/678-e2e-content-workflow"

## [v0.7.141] - 2025-12-12

### Changes
- Remove Firebase Auth from project-beta-api (Issue #804) (#807)

**Source:** project-beta-api@27386de4 "Remove Firebase Auth from project-beta-api (Issue #804) (#807)"

## [v0.7.140] - 2025-12-12

### Changes
- Merge pull request #810 from Matchpoint-AI/fix/809

**Source:** project-beta-api@61286968 "Merge pull request #810 from Matchpoint-AI/fix/809"

## [v0.7.139] - 2025-12-12

### Changes
- Merge pull request #798 from Matchpoint-AI/fix/89-update-runner-labels

**Source:** project-beta-api@8d6e66f3 "Merge pull request #798 from Matchpoint-AI/fix/89-update-runner-labels"

## [v0.7.138] - 2025-12-12

### Changes
- Merge pull request #806 from Matchpoint-AI/fix/797

**Source:** project-beta-api@1214795f "Merge pull request #806 from Matchpoint-AI/fix/797"

## [v0.7.137] - 2025-12-12

### Changes
- Merge pull request #801 from Matchpoint-AI/fix/785-workflow-status-wrong-workflow-name

**Source:** project-beta-api@363be1ae "Merge pull request #801 from Matchpoint-AI/fix/785-workflow-status-wrong-workflow-name"

## [v0.7.136] - 2025-12-12

### Changes
- Merge pull request #802 from Matchpoint-AI/fix/774-local-dev-contentgen

**Source:** project-beta-api@177bd153 "Merge pull request #802 from Matchpoint-AI/fix/774-local-dev-contentgen"

## [v0.7.135] - 2025-12-12

### Changes
- Merge pull request #799 from Matchpoint-AI/fix/792-detect-changes

**Source:** project-beta-api@74e07265 "Merge pull request #799 from Matchpoint-AI/fix/792-detect-changes"

## [v0.7.134] - 2025-12-12

### Changes
- Merge pull request #800 from Matchpoint-AI/fix/796-db-migration

**Source:** project-beta-api@15fc054f "Merge pull request #800 from Matchpoint-AI/fix/796-db-migration"

## [v0.7.133] - 2025-12-12

### Changes
- Merge pull request #761 from Matchpoint-AI/fix/743

**Source:** project-beta-api@ff618a6f "Merge pull request #761 from Matchpoint-AI/fix/743"

## [v0.7.132] - 2025-12-12

### Changes
- feat: Implement LocalWorkflowService for local development (#787) (#788)

**Source:** project-beta-api@d1317f3a "feat: Implement LocalWorkflowService for local development (#787) (#788)"

## [v0.7.131] - 2025-12-12

### Changes
- docs: Add comprehensive local development patterns skill (#795)

**Source:** project-beta-api@22c79960 "docs: Add comprehensive local development patterns skill (#795)"

## [v0.7.130] - 2025-12-12

### Changes
- Merge pull request #793 from Matchpoint-AI/fix/791-ci-runner-docs

**Source:** project-beta-api@a0abc97c "Merge pull request #793 from Matchpoint-AI/fix/791-ci-runner-docs"

## [v0.7.129] - 2025-12-12

### Changes
- Merge pull request #778 from Matchpoint-AI/fix/772-security-brands

**Source:** project-beta-api@602b05a0 "Merge pull request #778 from Matchpoint-AI/fix/772-security-brands"

## [v0.7.128] - 2025-12-12

### Changes
- fix: Extract user_id from JWT token in POST /api/v2/content (#775)

**Source:** project-beta-api@1fc51e90 "fix: Extract user_id from JWT token in POST /api/v2/content (#775)"

## [v0.7.127] - 2025-12-12

### Changes
- Merge pull request #783 from Matchpoint-AI/fix/782

**Source:** project-beta-api@51dd4530 "Merge pull request #783 from Matchpoint-AI/fix/782"

## [v0.7.126] - 2025-12-12

### Changes
- fix: Make database migrations idempotent with IF NOT EXISTS checks (#784)

**Source:** project-beta-api@c8bef7ac "fix: Make database migrations idempotent with IF NOT EXISTS checks (#784)"

## [v0.7.125] - 2025-12-12

### Changes
- Merge pull request #777 from Matchpoint-AI/fix/771-firebase-sync

**Source:** project-beta-api@902a8667 "Merge pull request #777 from Matchpoint-AI/fix/771-firebase-sync"

## [v0.7.124] - 2025-12-12

### Changes
- Merge pull request #770 from Matchpoint-AI/fix/769-ai-skill-migration

**Source:** project-beta-api@0dc3a7fc "Merge pull request #770 from Matchpoint-AI/fix/769-ai-skill-migration"

## [v0.7.123] - 2025-12-12

### Changes
- docs: Move investigation notes from .ai to GitHub issues (#768)

**Source:** project-beta-api@f91f3737 "docs: Move investigation notes from .ai to GitHub issues (#768)"

## [v0.7.122] - 2025-12-12

### Changes
- chore: Remove redundant GITHUB_COMMENTING.md files (Issue #765) (#766)

**Source:** project-beta-api@f78d24bb "chore: Remove redundant GITHUB_COMMENTING.md files (Issue #765) (#766)"

## [v0.7.121] - 2025-12-12

### Changes
- Merge pull request #764 from Matchpoint-AI/fix/758-issue-grooming-skill

**Source:** project-beta-api@f59b0360 "Merge pull request #764 from Matchpoint-AI/fix/758-issue-grooming-skill"

## [v0.7.120] - 2025-12-12

### Changes
- Merge pull request #762 from Matchpoint-AI/fix/749

**Source:** project-beta-api@a36173d1 "Merge pull request #762 from Matchpoint-AI/fix/749"

## [v0.7.119] - 2025-12-12

### Changes
- Merge pull request #760 from Matchpoint-AI/fix/748

**Source:** project-beta-api@4d717d54 "Merge pull request #760 from Matchpoint-AI/fix/748"

## [v0.7.118] - 2025-12-11

### Changes
- docs: Add worktree-to-merge development lifecycle skill (#759)

**Source:** project-beta-api@4a326822 "docs: Add worktree-to-merge development lifecycle skill (#759)"

## [v0.7.117] - 2025-12-11

### Changes
- Merge pull request #755 from Matchpoint-AI/fix/742

**Source:** project-beta-api@bd076fab "Merge pull request #755 from Matchpoint-AI/fix/742"

## [v0.7.116] - 2025-12-11

### Changes
- feat: Add Claude Code skills for API development (#754)

**Source:** project-beta-api@40471f1c "feat: Add Claude Code skills for API development (#754)"

## [v0.7.115] - 2025-12-11

### Changes
- Merge pull request #752 from Matchpoint-AI/fix/741

**Source:** project-beta-api@52534907 "Merge pull request #752 from Matchpoint-AI/fix/741"

## [v0.7.114] - 2025-12-11

### Changes
- Merge pull request #753 from Matchpoint-AI/fix/747

**Source:** project-beta-api@5b01d053 "Merge pull request #753 from Matchpoint-AI/fix/747"

## [v0.7.113] - 2025-12-11

### Changes
- Merge pull request #745 from Matchpoint-AI/test/issue-680-integration-tests

**Source:** project-beta-api@32092c40 "Merge pull request #745 from Matchpoint-AI/test/issue-680-integration-tests"

## [v0.7.112] - 2025-12-11

### Changes
- Merge pull request #737 from Matchpoint-AI/fix/scene-mix-policies-731

**Source:** project-beta-api@86f1d9ed "Merge pull request #737 from Matchpoint-AI/fix/scene-mix-policies-731"

## [v0.7.111] - 2025-12-11

### Changes
- Merge pull request #739 from Matchpoint-AI/fix/738-workflow-status-endpoint

**Source:** project-beta-api@c497fb1e "Merge pull request #739 from Matchpoint-AI/fix/738-workflow-status-endpoint"

## [v0.7.110] - 2025-12-11

### Changes
- Merge pull request #735 from Matchpoint-AI/chore/coverage-92

**Source:** project-beta-api@18a8a91a "Merge pull request #735 from Matchpoint-AI/chore/coverage-92"

## [v0.7.109] - 2025-12-11

### Changes
- Merge pull request #733 from Matchpoint-AI/fix/brand-onboarding-status-696

**Source:** project-beta-api@31399408 "Merge pull request #733 from Matchpoint-AI/fix/brand-onboarding-status-696"

## [v0.7.108] - 2025-12-11

### Changes
- Merge pull request #732 from Matchpoint-AI/fix/651-650-firebase-local-jwt

**Source:** project-beta-api@694ef804 "Merge pull request #732 from Matchpoint-AI/fix/651-650-firebase-local-jwt"

## [v0.7.107] - 2025-12-11

### Changes
- Merge pull request #728 from Matchpoint-AI/fix/694

**Source:** project-beta-api@22ba28d "Merge pull request #728 from Matchpoint-AI/fix/694"

## [v0.7.106] - 2025-12-10

### Changes
- Merge pull request #727 from Matchpoint-AI/fix/695

**Source:** project-beta-api@283f669 "Merge pull request #727 from Matchpoint-AI/fix/695"

## [v0.7.105] - 2025-12-10

### Changes
- Merge pull request #729 from Matchpoint-AI/fix/697

**Source:** project-beta-api@190da9d "Merge pull request #729 from Matchpoint-AI/fix/697"

## [v0.7.104] - 2025-12-10

### Changes
- Merge pull request #730 from Matchpoint-AI/fix/696

**Source:** project-beta-api@3176100 "Merge pull request #730 from Matchpoint-AI/fix/696"

## [v0.7.103] - 2025-12-10

### Changes
- Merge pull request #725 from Matchpoint-AI/fix/715-content-version

**Source:** project-beta-api@da77e5c "Merge pull request #725 from Matchpoint-AI/fix/715-content-version"

## [v0.7.102] - 2025-12-10

### Changes
- Merge pull request #726 from Matchpoint-AI/fix/api-715-content-version-service-di

**Source:** project-beta-api@0308790 "Merge pull request #726 from Matchpoint-AI/fix/api-715-content-version-service-di"

## [v0.7.101] - 2025-12-10

### Changes
- Merge pull request #724 from Matchpoint-AI/fix/716-image-tier

**Source:** project-beta-api@6912941 "Merge pull request #724 from Matchpoint-AI/fix/716-image-tier"

## [v0.7.100] - 2025-12-10

### Changes
- Merge pull request #723 from Matchpoint-AI/fix/698-brand-user-id

**Source:** project-beta-api@67f5aef "Merge pull request #723 from Matchpoint-AI/fix/698-brand-user-id"

## [v0.7.99] - 2025-12-10

### Changes
- Merge pull request #722 from Matchpoint-AI/fix/720-brand-id

**Source:** project-beta-api@da8ae93 "Merge pull request #722 from Matchpoint-AI/fix/720-brand-id"

## [v0.7.98] - 2025-12-10

### Changes
- fix: correct workflow name computation in start_campaign_content_workflow (#721)

**Source:** project-beta-api@a3fd776 "fix: correct workflow name computation in start_campaign_content_workflow (#721)"

## [v0.7.97] - 2025-12-10

### Changes
- Merge pull request #719 from Matchpoint-AI/fix/714-bulk-approve

**Source:** project-beta-api@2a2db20 "Merge pull request #719 from Matchpoint-AI/fix/714-bulk-approve"

## [v0.7.96] - 2025-12-10

### Changes
- Merge pull request #717 from Matchpoint-AI/fix/713

**Source:** project-beta-api@947dc1c "Merge pull request #717 from Matchpoint-AI/fix/713"

## [v0.7.95] - 2025-12-10

### Changes
- fix: Add ApiConfig DI binding for campaign creation endpoint (#712)

**Source:** project-beta-api@eca0ee9 "fix: Add ApiConfig DI binding for campaign creation endpoint (#712)"

## [v0.7.94] - 2025-12-10

### Changes
- feat: Auto-trigger content generation workflow on campaign creation (#707)

**Source:** project-beta-api@a7994da "feat: Auto-trigger content generation workflow on campaign creation (#707)"

## [v0.7.93] - 2025-12-10

### Changes
- fix: Remove duplicate endpoint definitions (#689) (#702)

**Source:** project-beta-api@28b8035 "fix: Remove duplicate endpoint definitions (#689) (#702)"

## [v0.7.92] - 2025-12-10

### Changes
- Merge pull request #705 from Matchpoint-AI/fix/688-thread-auth

**Source:** project-beta-api@72866f6 "Merge pull request #705 from Matchpoint-AI/fix/688-thread-auth"

## [v0.7.91] - 2025-12-10

### Changes
- fix: TokenBlacklistRepository use async_sessionmaker pattern (#701)

**Source:** project-beta-api@b19ce04 "fix: TokenBlacklistRepository use async_sessionmaker pattern (#701)"

## [v0.7.90] - 2025-12-10

### Changes
- fix: Implement stub methods in ContentServiceImpl (#704)

**Source:** project-beta-api@a2b0448 "fix: Implement stub methods in ContentServiceImpl (#704)"

## [v0.7.89] - 2025-12-10

### Changes
- Merge pull request #703 from Matchpoint-AI/fix/690-brand-update

**Source:** project-beta-api@70a0ea9 "Merge pull request #703 from Matchpoint-AI/fix/690-brand-update"

## [v0.7.88] - 2025-12-10

### Changes
- fix: Add 'from __future__ import annotations' to resolve AsyncEngine NameError (#700)

**Source:** project-beta-api@fb2ee9e "fix: Add 'from __future__ import annotations' to resolve AsyncEngine NameError (#700)"

## [v0.7.87] - 2025-12-09

### Changes
- fix: Add idempotent migration to fix reset_token state drift (#679)

**Source:** project-beta-api@192eaa5 "fix: Add idempotent migration to fix reset_token state drift (#679)"

## [v0.7.86] - 2025-12-09

### Changes
- Merge pull request #677 from Matchpoint-AI/fix/654-weeks-empty

**Source:** project-beta-api@5676572 "Merge pull request #677 from Matchpoint-AI/fix/654-weeks-empty"

## [v0.7.85] - 2025-12-09

### Changes
- fix: add stamp support to migration workflow for state drift fixes (#674)

**Source:** project-beta-api@b373988 "fix: add stamp support to migration workflow for state drift fixes (#674)"

## [v0.7.84] - 2025-12-09

### Changes
- Merge pull request #673 from Matchpoint-AI/fix/1567-wif-config-mismatch

**Source:** project-beta-api@685972d "Merge pull request #673 from Matchpoint-AI/fix/1567-wif-config-mismatch"

## [v0.7.83] - 2025-12-09

### Changes
- Merge pull request #670 from Matchpoint-AI/fix/1567-wif-auth

**Source:** project-beta-api@50107bb "Merge pull request #670 from Matchpoint-AI/fix/1567-wif-auth"

## [v0.7.82] - 2025-12-09

### Changes
- Merge pull request #667 from Matchpoint-AI/fix/662-prompt-crud

**Source:** project-beta-api@f08c2f3 "Merge pull request #667 from Matchpoint-AI/fix/662-prompt-crud"

## [v0.7.81] - 2025-12-09

### Changes
- Merge pull request #666 from Matchpoint-AI/fix/640-batch-parallel

**Source:** project-beta-api@d27096b "Merge pull request #666 from Matchpoint-AI/fix/640-batch-parallel"

## [v0.7.80] - 2025-12-08

### Changes
- Merge pull request #657 from Matchpoint-AI/fix/638-database-connection-singleton

**Source:** project-beta-api@f1a0aed "Merge pull request #657 from Matchpoint-AI/fix/638-database-connection-singleton"

## [v0.7.79] - 2025-12-08

### Changes
- fix(#655): Add dual-format parsing for content_data in GeneratedContent (#661)

**Source:** project-beta-api@faba4c6 "fix(#655): Add dual-format parsing for content_data in GeneratedContent (#661)"

## [v0.7.78] - 2025-12-08

### Changes
- Merge pull request #660 from Matchpoint-AI/fix/645-email-resend

**Source:** project-beta-api@f0cf207 "Merge pull request #660 from Matchpoint-AI/fix/645-email-resend"

## [v0.7.77] - 2025-12-08

### Changes
- Merge pull request #659 from Matchpoint-AI/fix/647-email-tracking-password-reset

**Source:** project-beta-api@094fbd5 "Merge pull request #659 from Matchpoint-AI/fix/647-email-tracking-password-reset"

## [v0.7.76] - 2025-12-08

### Changes
- Merge pull request #658 from Matchpoint-AI/fix/646-add-fal-api-key-env

**Source:** project-beta-api@e0cda11 "Merge pull request #658 from Matchpoint-AI/fix/646-add-fal-api-key-env"

## [v0.7.75] - 2025-12-08

### Changes
- feat: Add password reset flow (forgot password) (#653)

**Source:** project-beta-api@0cf2ecc "feat: Add password reset flow (forgot password) (#653)"

## [v0.7.74] - 2025-12-08

### Changes
- [P1] Add server-side session invalidation endpoint (DELETE /sessions) (#652)

**Source:** project-beta-api@5b333a6 "[P1] Add server-side session invalidation endpoint (DELETE /sessions) (#652)"

## [v0.7.73] - 2025-12-08

### Changes
- Merge pull request #644 from Matchpoint-AI/fix/642-db-singleton-proper

**Source:** project-beta-api@48a8b3f "Merge pull request #644 from Matchpoint-AI/fix/642-db-singleton-proper"

## [v0.7.72] - 2025-12-08

### Changes
- Merge pull request #643 from Matchpoint-AI/fix/639-unique-brand-names

**Source:** project-beta-api@bdbc758 "Merge pull request #643 from Matchpoint-AI/fix/639-unique-brand-names"

## [v0.7.71] - 2025-12-07

### Changes
- Merge pull request #637 from Matchpoint-AI/fix/427-has-brand-cleanup

**Source:** project-beta-api@bf43a10 "Merge pull request #637 from Matchpoint-AI/fix/427-has-brand-cleanup"

## [v0.7.70] - 2025-12-07

### Changes
- ci: Migrate Docker builds to GitHub Actions (#636)

**Source:** project-beta-api@d98dd55 "ci: Migrate Docker builds to GitHub Actions (#636)"

## [v0.7.69] - 2025-12-07

### Changes
- feat: Remove deprecated endpoints after frontend migration (#629)

**Source:** project-beta-api@dfb9e41 "feat: Remove deprecated endpoints after frontend migration (#629)"

## [v0.7.68] - 2025-12-07

### Changes
- Merge pull request #634 from Matchpoint-AI/test/ci-filtering

**Source:** project-beta-api@6983798 "Merge pull request #634 from Matchpoint-AI/test/ci-filtering"

## [v0.7.67] - 2025-12-07

### Changes
- Merge pull request #628 from Matchpoint-AI/chore/559-api-cleanup

**Source:** project-beta-api@3b0c950 "Merge pull request #628 from Matchpoint-AI/chore/559-api-cleanup"

## [v0.7.66] - 2025-12-07

### Changes
- Merge pull request #626 from Matchpoint-AI/feat/617-threads-schema

**Source:** project-beta-api@4a67dd3 "Merge pull request #626 from Matchpoint-AI/feat/617-threads-schema"

## [v0.7.65] - 2025-12-07

### Changes
- Merge pull request #627 from Matchpoint-AI/docs/549-md-audit

**Source:** project-beta-api@58d07c7 "Merge pull request #627 from Matchpoint-AI/docs/549-md-audit"

## [v0.7.64] - 2025-12-07

### Changes
- Merge pull request #623 from Matchpoint-AI/docs/537-ci-filtering-patterns

**Source:** project-beta-api@5edfd31 "Merge pull request #623 from Matchpoint-AI/docs/537-ci-filtering-patterns"

## [v0.7.63] - 2025-12-06

### Changes
- Merge pull request #622 from Matchpoint-AI/fix/614-docs-cleanup

**Source:** project-beta-api@e4ab754 "Merge pull request #622 from Matchpoint-AI/fix/614-docs-cleanup"

## [v0.7.62] - 2025-12-06

### Changes
- Merge pull request #619 from Matchpoint-AI/chore/615-ai-docs-update

**Source:** project-beta-api@4d97bd0 "Merge pull request #619 from Matchpoint-AI/chore/615-ai-docs-update"

## [v0.7.61] - 2025-12-06

### Changes
- Merge pull request #612 from Matchpoint-AI/docs/ai-guidelines

**Source:** project-beta-api@2dcb137 "Merge pull request #612 from Matchpoint-AI/docs/ai-guidelines"

## [v0.7.60] - 2025-12-06

### Changes
- Merge pull request #607 from Matchpoint-AI/refactor/574-split-controller

**Source:** project-beta-api@0cab4f8 "Merge pull request #607 from Matchpoint-AI/refactor/574-split-controller"

## [v0.7.59] - 2025-12-06

### Changes
- Merge pull request #613 from Matchpoint-AI/audit/559-api-surface

**Source:** project-beta-api@b58c530 "Merge pull request #613 from Matchpoint-AI/audit/559-api-surface"

## [v0.7.58] - 2025-12-06

### Changes
- Merge pull request #611 from Matchpoint-AI/docs/602-repo-history

**Source:** project-beta-api@dfa8460 "Merge pull request #611 from Matchpoint-AI/docs/602-repo-history"

## [v0.7.56] - 2025-12-06

### Changes
- fix: Prevent SQL error leak on large campaign IDs (#609)

**Source:** project-beta-api@81540c6 "fix: Prevent SQL error leak on large campaign IDs (#609)"

## [v0.7.55] - 2025-12-06

### Changes
- Merge pull request #604 from Matchpoint-AI/feat/543-image-tiers

**Source:** project-beta-api@cff2dd9 "Merge pull request #604 from Matchpoint-AI/feat/543-image-tiers"

## [v0.7.52] - 2025-12-06

### Changes
- Merge pull request #599 from Matchpoint-AI/fix/527-duplicate-endpoint

**Source:** project-beta-api@387b790 "Merge pull request #599 from Matchpoint-AI/fix/527-duplicate-endpoint"

## [v0.7.51] - 2025-12-06

### Changes
- fix: Remove forward reference from AuthService in UserService provider (#555) (#594)

**Source:** project-beta-api@44d5df6 "fix: Remove forward reference from AuthService in UserService provider (#555) (#594)"

## [v0.7.50] - 2025-12-06

### Changes
- fix(content): make user_id optional in ContentCreate schema (#597)

**Source:** project-beta-api@4ebf1e1 "fix(content): make user_id optional in ContentCreate schema (#597)"

## [v0.7.49] - 2025-12-06

### Changes
- feat: Improve test coverage to 90% threshold (#592)

**Source:** project-beta-api@51bad5b "feat: Improve test coverage to 90% threshold (#592)"

## [v0.7.48] - 2025-12-06

### Changes
- Merge pull request #593 from Matchpoint-AI/docs/569-agent-comment-monitoring

**Source:** project-beta-api@e337422 "Merge pull request #593 from Matchpoint-AI/docs/569-agent-comment-monitoring"

## [v0.7.47] - 2025-12-06

### Changes
- Merge pull request #586 from Matchpoint-AI/ai/github-commenting-guidance

**Source:** project-beta-api@c2fbd98 "Merge pull request #586 from Matchpoint-AI/ai/github-commenting-guidance"

## [v0.7.46] - 2025-12-06

### Changes
- Merge pull request #589 from Matchpoint-AI/fix/588-ci-skipped-checks

**Source:** project-beta-api@62b5ade "Merge pull request #589 from Matchpoint-AI/fix/588-ci-skipped-checks"

## [v0.7.45] - 2025-12-06

### Changes
- feat: Integrate ContentService into generate_campaign_content endpoint (#582)

**Source:** project-beta-api@3ae59e2 "feat: Integrate ContentService into generate_campaign_content endpoint (#582)"

## [v0.7.44] - 2025-12-06

### Changes
- Merge pull request #584 from Matchpoint-AI/fix/583-parallel-tests

**Source:** project-beta-api@037f578 "Merge pull request #584 from Matchpoint-AI/fix/583-parallel-tests"

## [v0.7.43] - 2025-12-06

### Changes
- fix: Remove duplicate routes, dead code, and past-sunset deprecated endpoints (#577)

**Source:** project-beta-api@b030758 "fix: Remove duplicate routes, dead code, and past-sunset deprecated endpoints (#577)"

## [v0.7.42] - 2025-12-05

### Changes
- feat: Add campaign content workflow trigger endpoint (#572)

**Source:** project-beta-api@452de86 "feat: Add campaign content workflow trigger endpoint (#572)"

## [v0.7.41] - 2025-12-05

### Changes
- fix: Resolve duplicate /versions endpoints - RMM-L2 compliance (#554)

**Source:** project-beta-api@3aed8f8 "fix: Resolve duplicate /versions endpoints - RMM-L2 compliance (#554)"

## [v0.7.40] - 2025-12-05

### Changes
- Merge pull request #563 from Matchpoint-AI/feat/brand-embeddings

**Source:** project-beta-api@f3d585e "Merge pull request #563 from Matchpoint-AI/feat/brand-embeddings"

## [v0.7.39] - 2025-12-05

### Changes
- fix: Disable SendGrid click tracking for verification emails (#570)

**Source:** project-beta-api@5aa5c6e "fix: Disable SendGrid click tracking for verification emails (#570)"

## [v0.7.38] - 2025-12-05

### Changes
- Merge pull request #567 from Matchpoint-AI/perf/restore-testcontainers-issue-1522

**Source:** project-beta-api@a303634 "Merge pull request #567 from Matchpoint-AI/perf/restore-testcontainers-issue-1522"

## [v0.7.37] - 2025-12-05

### Changes
- Merge pull request #566 from Matchpoint-AI/migrate/arc-beta-runners

**Source:** project-beta-api@deab19c "Merge pull request #566 from Matchpoint-AI/migrate/arc-beta-runners"

## [v0.7.36] - 2025-12-04

### Changes
- Merge pull request #564 from Matchpoint-AI/feat/image-client-factory

**Source:** project-beta-api@08c35b4 "Merge pull request #564 from Matchpoint-AI/feat/image-client-factory"

## [v0.7.35] - 2025-12-04

### Changes
- ci: Temporarily disable OpenAPI breaking changes check (#562)

**Source:** project-beta-api@f726c94 "ci: Temporarily disable OpenAPI breaking changes check (#562)"

## [v0.7.34] - 2025-12-04

### Changes
- Merge pull request #561 from Matchpoint-AI/feat/image-tiers-endpoint

**Source:** project-beta-api@1b64bce "Merge pull request #561 from Matchpoint-AI/feat/image-tiers-endpoint"

## [v0.7.33] - 2025-12-04

### Changes
- Merge pull request #560 from Matchpoint-AI/feat/brand-guardrails-migration

**Source:** project-beta-api@fbdf478 "Merge pull request #560 from Matchpoint-AI/feat/brand-guardrails-migration"

## [v0.7.32] - 2025-12-04

### Changes
- Merge pull request #557 from Matchpoint-AI/feat/brand-attributes-migration

**Source:** project-beta-api@a7134c0 "Merge pull request #557 from Matchpoint-AI/feat/brand-attributes-migration"

## [v0.7.31] - 2025-12-04

### Changes
- Merge pull request #558 from Matchpoint-AI/feat/model-tier-service

**Source:** project-beta-api@ad17602 "Merge pull request #558 from Matchpoint-AI/feat/model-tier-service"

## [v0.7.30] - 2025-12-04

### Changes
- Merge pull request #556 from Matchpoint-AI/feat/ci-cond-tests

**Source:** project-beta-api@88a8c3d "Merge pull request #556 from Matchpoint-AI/feat/ci-cond-tests"

## [v0.7.29] - 2025-12-04

### Changes
- Merge pull request #553 from Matchpoint-AI/fix/duplicate-versions-endpoint

**Source:** project-beta-api@68db35c "Merge pull request #553 from Matchpoint-AI/fix/duplicate-versions-endpoint"

## [v0.7.28] - 2025-12-04

### Changes
- Merge pull request #551 from Matchpoint-AI/feat/ci-conditional-lint

**Source:** project-beta-api@acc829f "Merge pull request #551 from Matchpoint-AI/feat/ci-conditional-lint"

## [v0.7.27] - 2025-12-04

### Changes
- Merge pull request #550 from Matchpoint-AI/feat/ci-conditional-typecheck

**Source:** project-beta-api@e058ecd "Merge pull request #550 from Matchpoint-AI/feat/ci-conditional-typecheck"

## [v0.7.26] - 2025-12-04

### Changes
- fix: Implement lazy user sync from Firebase Auth to database (#525)

**Source:** project-beta-api@c96cb6a "fix: Implement lazy user sync from Firebase Auth to database (#525)"

## [v0.7.25] - 2025-12-04

### Changes
- Merge pull request #538 from Matchpoint-AI/feat/ci-audit

**Source:** project-beta-api@33e068b "Merge pull request #538 from Matchpoint-AI/feat/ci-audit"

## [v0.7.24] - 2025-12-04

### Changes
- Merge pull request #540 from Matchpoint-AI/feat/ci-detect-changes

**Source:** project-beta-api@2bd09b6 "Merge pull request #540 from Matchpoint-AI/feat/ci-detect-changes"

## [v0.7.23] - 2025-12-04

### Changes
- feat: Add SEMVER keyword support to breaking changes check (#539)

**Source:** project-beta-api@fd000a1 "feat: Add SEMVER keyword support to breaking changes check (#539)"

## [v0.7.22] - 2025-12-03

### Changes
- Merge pull request #526 from Matchpoint-AI/fix/515-connection-pool

**Source:** project-beta-api@f3a5707 "Merge pull request #526 from Matchpoint-AI/fix/515-connection-pool"

## [v0.7.21] - 2025-12-03

### Changes
- fix(auth): Replace placeholder user_id with Firebase auth in content regeneration (#521)

**Source:** project-beta-api@24c846c "fix(auth): Replace placeholder user_id with Firebase auth in content regeneration (#521)"

## [v0.7.20] - 2025-12-03

### Changes
- Merge pull request #522 from Matchpoint-AI/docs/update-readme-vision

**Source:** project-beta-api@2424563 "Merge pull request #522 from Matchpoint-AI/docs/update-readme-vision"

## [v0.7.19] - 2025-12-03

### Changes
- Merge pull request #516 from Matchpoint-AI/fix/472-local-email-links

**Source:** project-beta-api@e621db5 "Merge pull request #516 from Matchpoint-AI/fix/472-local-email-links"

## [v0.7.18] - 2025-12-03

### Changes
- Merge pull request #518 from Matchpoint-AI/fix/517-ai-commenting

**Source:** project-beta-api@13e4d40 "Merge pull request #518 from Matchpoint-AI/fix/517-ai-commenting"

## [v0.7.17] - 2025-12-03

### Changes
- fix(fal): Update remaining services to use flux-pro v1.1-ultra (#510)

**Source:** project-beta-api@ad928b0 "fix(fal): Update remaining services to use flux-pro v1.1-ultra (#510)"

## [v0.7.16] - 2025-12-03

### Changes
- fix(fal): Use flux-pro v1.1-ultra model from V1 implementation (#509)

**Source:** project-beta-api@f1635e9 "fix(fal): Use flux-pro v1.1-ultra model from V1 implementation (#509)"

## [v0.7.15] - 2025-12-03

### Changes
- fix: Use fal-client package instead of fal for FAL.ai API (#507)

**Source:** project-beta-api@52ca6f0 "fix: Use fal-client package instead of fal for FAL.ai API (#507)"

## [v0.7.14] - 2025-12-03

### Changes
- Merge pull request #505 from Matchpoint-AI/fix/504-fal-ai-integration

**Source:** project-beta-api@0915c2a "Merge pull request #505 from Matchpoint-AI/fix/504-fal-ai-integration"

## [v0.7.11] - 2025-12-02

### Changes
- Merge pull request #502 from Matchpoint-AI/fix/501-regenerate-di

**Source:** project-beta-api@b803251 "Merge pull request #502 from Matchpoint-AI/fix/501-regenerate-di"

## [v0.0.341] - 2025-11-29

### Changes
- Merge pull request #473 from Matchpoint-AI/fix/custom-token-auth-support

**Source:** project-beta-api@1e3e65b "Merge pull request #473 from Matchpoint-AI/fix/custom-token-auth-support"

## [v0.0.340] - 2025-11-29

### Changes
- fix: use correct GCP workflow name for brand onboarding (#470)

**Source:** project-beta-api@92f4ee8 "fix: use correct GCP workflow name for brand onboarding (#470)"

## [v0.0.339] - 2025-11-27

### Changes
- fix: add Cloud Run frontend URL to CORS allowed origins (#465)

**Source:** project-beta-api@122429b "fix: add Cloud Run frontend URL to CORS allowed origins (#465)"

## [v0.0.338] - 2025-11-27

### Changes
- test: increase test coverage from 89% to 90% and enforce threshold (#463)

**Source:** project-beta-api@c872545 "test: increase test coverage from 89% to 90% and enforce threshold (#463)"

## [v0.0.337] - 2025-11-27

### Changes
- fix: construct full verification URL in email template (#462)

**Source:** project-beta-api@0e71f99 "fix: construct full verification URL in email template (#462)"

## [v0.0.336] - 2025-11-27

### Changes
- fix: use GKE default credentials instead of WIF for migrations (#458)

**Source:** project-beta-api@3bb2b26 "fix: use GKE default credentials instead of WIF for migrations (#458)"

## [v0.0.335] - 2025-11-27

### Changes
- perf: optimize CI test run time through test cleanup and parallelization (#455)

**Source:** project-beta-api@c464863 "perf: optimize CI test run time through test cleanup and parallelization (#455)"

## [v0.0.334] - 2025-11-27

### Changes
- fix: add OIDC permissions for migration workflow (#457)

**Source:** project-beta-api@5c3b542 "fix: add OIDC permissions for migration workflow (#457)"

## [v0.0.333] - 2025-11-27

### Changes
- fix: add gcloud auth to migration workflow (#456)

**Source:** project-beta-api@d63a217 "fix: add gcloud auth to migration workflow (#456)"

## [v0.0.332] - 2025-11-27

### Changes
- Merge pull request #453 from Matchpoint-AI/fix/jwt-custom-tokens

**Source:** project-beta-api@4109ff8 "Merge pull request #453 from Matchpoint-AI/fix/jwt-custom-tokens"

## [v0.0.331] - 2025-11-27

### Changes
- Merge pull request #452 from Matchpoint-AI/ci/add-migration-workflow

**Source:** project-beta-api@7e684f8 "Merge pull request #452 from Matchpoint-AI/ci/add-migration-workflow"

## [v0.0.330] - 2025-11-27

### Changes
- chore: remove skipped and obsolete tests from CI (#450)

**Source:** project-beta-api@0d00e46 "chore: remove skipped and obsolete tests from CI (#450)"

## [v0.0.329] - 2025-11-26

### Changes
- fix: EmailService DI protocol and CORS origins for local auth testing (#448)

**Source:** project-beta-api@9f6d3c7 "fix: EmailService DI protocol and CORS origins for local auth testing (#448)"

## [v0.0.328] - 2025-11-25

### Changes
- fix: add localhost:5174 to CORS allowed origins (#445)

**Source:** project-beta-api@74d621a "fix: add localhost:5174 to CORS allowed origins (#445)"

## [v0.0.327] - 2025-11-24

### Changes
- Merge pull request #425 from Matchpoint-AI/feat/add-epic-blocking-workflow

**Source:** project-beta-api@28b4045 "Merge pull request #425 from Matchpoint-AI/feat/add-epic-blocking-workflow"

## [v0.0.326] - 2025-11-24

### Changes
- Merge pull request #444 from Matchpoint-AI/feat/v2-user-authentication

**Source:** project-beta-api@3444813 "Merge pull request #444 from Matchpoint-AI/feat/v2-user-authentication"

## [v0.0.325] - 2025-11-23

### Changes
- chore: regenerate OpenAPI spec from main branch (#442)

**Source:** project-beta-api@e0b970e "chore: regenerate OpenAPI spec from main branch (#442)"

## [v0.0.324] - 2025-11-23

### Changes
- fix: add additionalProperties to campaign_variables field in OpenAPI schema (#441)

**Source:** project-beta-api@317918d "fix: add additionalProperties to campaign_variables field in OpenAPI schema (#441)"

## [v0.0.323] - 2025-11-23

### Changes
- fix: regenerate OpenAPI spec with additionalProperties for metadata fields (#440)

**Source:** project-beta-api@c6f953b "fix: regenerate OpenAPI spec with additionalProperties for metadata fields (#440)"

## [v0.0.322] - 2025-11-23

### Changes
- fix: add json_schema_extra for metadata additionalProperties (#439)

**Source:** project-beta-api@4442f06 "fix: add json_schema_extra for metadata additionalProperties (#439)"

## [v0.0.321] - 2025-11-23

### Changes
- fix: correct OpenAPI spec generation for metadata fields (#438)

**Source:** project-beta-api@cd60f8d "fix: correct OpenAPI spec generation for metadata fields (#438)"

## [v0.0.320] - 2025-11-23

### Changes
- feat: Implement SendGrid email verification (#434)

**Source:** project-beta-api@d3ba0c0 "feat: Implement SendGrid email verification (#434)"

## [v0.0.319] - 2025-11-22

### Changes
- fix: add localhost:5173 to CORS allowed origins for Vite dev server (#430)

**Source:** project-beta-api@d8da7e2 "fix: add localhost:5173 to CORS allowed origins for Vite dev server (#430)"

## [v0.0.318] - 2025-11-20

### Changes
- 📋 Add V2 Compliance PR Template (Backend - Phase 0) (#426)

**Source:** project-beta-api@99d7d4f "📋 Add V2 Compliance PR Template (Backend - Phase 0) (#426)"

## [v0.0.317] - 2025-11-20

### Changes
- Merge pull request #429 from Matchpoint-AI/fix/424

**Source:** project-beta-api@3fb8b2c "Merge pull request #429 from Matchpoint-AI/fix/424"

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