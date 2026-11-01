# Daniyar's Lab Implementation Plan

> **For agentic workers:** Use superpowers:executing-plans, one agent in the existing checkout, with checkbox tracking.

**Goal:** Give the verified portfolio the approved playful night-lab identity.

**Architecture:** Native Markdown, local GIF/SVG assets and supported HTML details/picture. All content is static and stored in Git; no running service or application framework.

**Tech Stack:** Markdown, SVG, GIF; existing Node/Sharp and bundled Python/Pillow for local asset preparation only.

**Spec:** [Daniyar's Lab design](../specs/2026-11-01-daniyars-lab-design.md).

## Global Constraints

- Preserve all confirmed profile facts, source certificates, public URLs, history and existing assets.
- One short-loop animation only; no flashing or fake activity indicators.
- Use a local branch in the existing checkout, one agent, no dependency installation.
- Source inputs, frame PNGs, scripts and screenshots stay outside the public repository.
- Validate these static artifacts directly; do not introduce application tests or infrastructure.

## Review Focus

- GIF opens as an actual multi-frame animation and has a useful static first frame.
- Important identity/content remains readable text when graphics are small or motion is reduced.
- New icon files are original licensed copies, with accurate sources and accessible names.
- Project covers remain decorative; text and roles stay accurate and clickable.
- New relative paths and native details blocks work without floats or fixed columns at narrow widths.

## Task 1: Art and motion

**Files:** `assets/lab/room.svg`, `assets/lab/hero.gif`, four `assets/lab/project-*.svg`, eight additions under `assets/icons/`, `assets/icons/SOURCES.md`.

- [x] Draw an original night lab and generate a 6–8 second GIF; retain a static SVG and inspect key frames.
- [x] Create four distinct project covers without made-up metrics or screenshots.
- [x] Fetch only pinned Devicon originals, preserve MIT and document the new files.
- [x] Verify image metadata, animation frames/duration/loop, file sizes and SVG safety.

## Task 2: README and memory

**Files:** `README.md`, `AGENTS.md`, `docs/PROFILE_GUIDE.md`, `docs/PROFILE_REDESIGN_STATUS.md`.

- [x] Assemble hero, native-text identity/links, JSON About, project covers, icon toolkit, `open /lab`, credentials and HackAlem.
- [x] Keep all 110 credential links and the source PDF unchanged.
- [x] Align maintenance rules, guide and project status with the selected Lab direction.

## Task 3: Verify and prepare publication

- [x] Validate relative paths, XML, sources, catalog/PDF invariance, Markdown API output and real details/picture retention.
- [x] Prepare clearly labeled manual previews outside Git; do a separate self-review of the staged diff.
- [ ] Create local commit and concrete publication manifest; ask for publication approval once.
- [ ] After approval, publish to `main` and verify the actual profile at 1280 and 390 px with genuine screenshots.
