# Professional Profile Implementation Plan

> **For agentic workers:** Use superpowers:executing-plans in this session, working alone per the owner's preferences. Steps use checkbox tracking.

**Goal:** Replace the Sasuke presentation with the approved professional technical portfolio, verified credentials and LinkedIn.

**Architecture:** Native GitHub Markdown with one local SVG banner. Projects and credentials remain ordinary linked text; a separate Markdown catalog contains all Coursera records. No application, build system or hosted service.

**Tech Stack:** GitHub Markdown, supported HTML, self-contained SVG, unchanged PDF; PowerShell and existing Node/Python tools for one-time preparation and checks.

**Spec:** [Approved design](../specs/2026-11-01-professional-profile-design.md).

## Global Constraints

- Preserve history, existing assets and unrelated edits; publish only after concrete approval.
- English public portfolio; Russian guide and project memory; no invented roles, credentials or contacts.
- Work alone in the existing checkout. A temporary local branch separates implementation from main; no new worktree or dependencies.
- Use explicit file staging. Keep original inputs and all local previews outside the repository.
- This is documentation and static vector design: validate links, markup, XML, hashes and visual rendering rather than adding application unit tests.

## Review Focus

- At 390 px, About text and project descriptions must remain readable without floats or fixed-column layout.
- Distinguish course certificates from program certificates and professional licensing exams; preserve exact issuer names.
- Team technology and personal contribution must not be conflated; avoid production claims beyond project evidence.
- LinkedIn must use the verified `/in/` address; relative asset/catalog links must be case-correct and portable.
- Legacy anime files and temporary/local paths must not enter the displayed README or public changes accidentally.

## Task 1: Credential evidence and catalog

**Files:** Create `docs/CERTIFICATIONS.md`, `assets/certificates/hackalem-ai-participation-2026.pdf`.

**Interface:** Input is the local verified Coursera JSON (94 course records, 16 program records) and supplied HackAlem PDF. Output is a selectable-text catalog with exact public URLs and an unchanged source PDF.

- [x] Generate two separately counted certificate sections with issuer and month/year; normalize display whitespace only.
- [x] Copy the PDF without editing and compare SHA-256 against the supplied original.
- [x] Verify 110 unique credential IDs, 94/16 category counts, valid Coursera link hosts and existing PDF link.

## Task 2: Portfolio presentation

**Files:** Modify `README.md`; create `assets/professional/banner.svg`.

**Interface:** Consume the catalog and certificate paths from Task 1. Public project and LinkedIn links come from the approved spec and current evidence.

- [x] Build a quiet graphite/blue banner with a small API/data/inference diagram; render it for visual inspection.
- [x] Write native-text identity, About, four project descriptions, grouped technology text, selected credentials, HackAlem participation and LinkedIn.
- [x] Confirm FocusDuo release 0.1.0 from GitHub Releases; leave other projects' readiness accurately described.
- [x] Validate SVG/XML, alt text, relative paths and absence of float/table-based portfolio columns, scripts and custom README CSS.
- [x] Process the README through GitHub Markdown API; prepare a clearly labeled manual local preview outside Git.

## Task 3: Maintenance and review

**Files:** Modify `AGENTS.md`, `docs/PROFILE_GUIDE.md`, `docs/PROFILE_REDESIGN_STATUS.md`; update this plan's checkboxes.

**Interface:** Documentation describes the final files and only checks actually performed.

- [x] Replace outdated style/stack rules while preserving Git safety and truthful-content rules; explain catalog updates, image paths and account settings.
- [x] Review the full diff as a separate self-review pass; use explicit staged paths and run `git diff --cached --check`.
- [x] Create a local implementation commit and a concrete publication review with destination, file list and limitations. Do not push yet.
- [x] After publication approval, verify the real profile at 1280 px and 390 px and save genuine screenshots; report any unavailable theme check.

Publication: implementation `539cdf9` is in public `main`. Both widths passed in the dark theme; light theme was not separately checked. Catalog and PDF are accessible. Verification evidence is recorded in `docs/PROFILE_REDESIGN_STATUS.md`.

## Execution rulings

- Existing checkout and one agent are the owner's preference; no worktree scripts or reviewer-agent workflow are added for this small static profile update.
- The approved design and the owner's request authorize local implementation; no extra plan-approval round is needed for routine execution choices.
- Project status is the durable execution ledger. This plan adds no new product infrastructure or synthetic tests.
