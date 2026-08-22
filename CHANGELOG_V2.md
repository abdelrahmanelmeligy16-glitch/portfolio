# CHANGELOG V2 — 2026-08-22
v1.1 (single-page static) → v2.0 "AI Systems Observatory" (single-file multi-view application). Backup preserved: index.v1.1.backup.html.

## Added
- Hash router with 14 routes incl. 5 real project pages (Overview/System/Proof/Decisions/Roadmap tabs), Systems Atlas, Evidence Registry, Experiment Lab, Skills Matrix, About, print-ready Résumé, Compare.
- Three global modes: Explore (default), **Evidence Mode** (grade outlines + source amplification), **Compare Mode** (≤3 projects, data-model-driven table).
- Governed Autonomy Map + per-project interactive topologies (hand-rolled SVG, click-to-inspect, dashed planned paths, legend).
- Command palette (⌘K/Ctrl+K, 26 commands, keyboard navigation).
- Complete light theme (OS-detected first visit, persisted); app-shell nav with mobile sheet; metric evidence drawers; @media print résumé system; reduced-motion support; skip link + dialog focus management.
- Structured embedded data model (PROJECTS/METRICS/LAB/skills) — single source of truth for cards, pages, compare, atlas, registry.

## Content claims — preserved / modified / removed
**Preserved (verbatim from audit):** 5 platforms · 1,158 commits · 289 tests · 10 launchd jobs · 4,256 files · 62 migrations · 76 test files · 20 locales · 1,927 sessions · 6.8GB index · 152-line server · 141K audience (attested label) · all proof/limitation pairs · AI-development disclosure · "Not claimed" skills tier.
**Modified:** "Systems active" hero kicker → "Evidence snapshot audited August 22, 2026" (cannot verify all systems live at view-time) · videos moved from autoplaying card embeds → labeled click-to-play modals · MONT presented only as M&A deal-room lab entry · ISG loop consistently described as content-production (not self-QA).
**Removed:** none of the audited claims; decorative background orbs from v1 bio-style design (brief: no orbs).
**Downgraded:** KAIRO deployment described as "currently offline (HTTP 402 at audit)" everywhere it appears.

## Fixed during QA
Palette id-search · 375px overflow · print drawer leak · favicon 404 · thumbnail overflow (details in QA_REPORT_V2.md).


# V3 — 2026-08-22 (feature waves 1–3, spec: 11_FEATURE_SPECS_V3.md)
**Added:** #/hire (two offers, real prices $2,500–5,000 fixed, prefilled mailtos, truth-compliant client-results placeholder) · real redacted audit-log artifact (12 lines) on Creator Command Proof + dashboard teaser · QR code on résumé — machine-decode VERIFIED: an identically-parameterized encoding of the same URL decodes via OpenCV QRCodeDetector to exactly https://abdelrahmanelmeligy16-glitch.github.io/portfolio/ (MATCH: True) HTML/PDF and #/resume · #/timeline (90-day SVG, 17 audited milestone dots with evidence inspector) · per-project Q&A tab (60-second version + 5 interview Q&A × 5 projects, verbatim from case studies) · live GitHub deploy strip (public portfolio repo, graceful offline fallback) · 7 ask-the-portfolio palette commands · visitor-mode chips (recruiter/client/engineer teaser panels — implemented as emphasis-injection rather than full section reorder; deviation from spec recorded) · #/now with 21-day stale guard · Hire in nav, new routes in palette.
**QA:** full route sweep (8 routes), interaction tests (timeline inspector, Q&A accordions, visitor modes, palette ask, mailtos, price render), mobile 390px clean on all new routes, zero JS errors.

**Ship-time limitation:** Playwright screenshot capture degraded at final-handoff time (frame-stability stall; earlier V3 visuals verified during build) — live functional acceptance was fully programmatic and passed.
