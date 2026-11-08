# LibHunt Submission Tracker

LibHunt is the first public credibility and SEO submission platform tracked for this ecosystem.

## Purpose

LibHunt helps establish:

- Public project listings
- Categorized discovery
- Alternative/project relationship mapping
- Search-indexable project descriptions
- Topic/tag reinforcement
- Cross-linking between ecosystem projects

## Current Seed State

### FreeEQ8

- Status: submitted / details complete — LIVE at https://libhunt.com/GareBear99/FreeEQ8 (21 alternatives, 6 mentions, 21 stars; details verified complete 2026-11-08, see Live status below; evidence screenshot still pending)
- Current alternative: TizWildinEntertainmentHUB
- Next: add FreeVox8 (Gary's call — list as-is or wait until shippable). awesome-audio-plugins-dev is LIVE at https://libhunt.com/GareBear99/awesome-audio-plugins-dev (21 alternatives, 1 mention, 10 stars) but its details are INCOMPLETE — no website URL, no Docs URL, no self-hosted status (see Live status below).

### ARC-Neuron-LLMBuilder

- Status: submitted / details complete — LIVE at https://libhunt.com/GareBear99/ARC-Neuron-LLMBuilder (11 alternatives, 6 mentions, 14 stars; details verified complete 2026-11-08, see Live status below)
- Current alternative: ARC-Core
- Next: ARC graph complete as alternatives — arc-lucifer-cleanroom-runtime, arc-language-module, and Arc-RAR all appear as alternatives on the LLMBuilder and ARC-Core pages (verified 2026-11-08). Details verified complete 2026-11-08 (see Live status below); remaining is the evidence screenshot only.

## First Wave Project List

### ARC Local AI Cluster

1. ARC-Neuron-LLMBuilder
2. ARC-Core
3. arc-lucifer-cleanroom-runtime
4. arc-language-module
5. Arc-RAR

### TizWildin Audio / Creator Tools Cluster

1. FreeEQ8
2. TizWildinEntertainmentHUB
3. FreeVox8
4. awesome-audio-plugins-dev

## Cross-Linking Logic

ARC projects are submitted as alternatives to other ARC projects.

Audio projects are submitted as alternatives to other TizWildin audio / creator ecosystem projects.

The goal is not to compete internally. The goal is to create a public graph showing that each repo is part of a larger open-source ecosystem.

## Completion Criteria

A LibHunt project is considered complete when:

- Project name is correct
- Description is public-facing and SEO-friendly
- Topics are entered
- Website URL is entered
- Docs URL is entered
- Language is correct
- License is correct
- Self-hosted status is recorded
- Internal alternatives are linked
- Public listing URL is saved
- Evidence screenshot is saved

## Live status — verified 2026-11-08 (full sweep)

LibHunt pages LIVE (36) — checked 2026-11-08 by curl title-marker sweep
plus browser spot-checks (FreeEQ8, ARC-Neuron-LLMBuilder,
arc-language-module). The graph is far bigger than the 5 pages recorded
before this sweep: every Maid/plugin repo and most ARC repos already
have a page. Details — per-page verdicts, verified 2026-11-08 ~06:11 PST by live HTML fetch
of each of the five first-wave pages (all HTTP 200; description, topics,
website/docs links, language, license, self-hosted statement checked
field by field against the completion criteria above):

- COMPLETE (4): FreeEQ8, TizWildinEntertainmentHUB, ARC-Neuron-LLMBuilder,
  ARC-Core. Each shows a public-facing description, topics (FreeEQ8 26,
  HUB 34, LLMBuilder 26, ARC-Core 30), a website link (FreeEQ8 →
  github.com/.../releases; HUB → garebear99.github.io; LLMBuilder and
  ARC-Core → their github.com repo URL), a Docs link (repo #readme),
  correct language (C++, HTML, Python, Python), correct license
  (GPL-3.0 only, MIT, MIT, MIT), a "marked as self-hosted" statement,
  and linked internal alternatives. This is why STATUS_BOARD.md shows
  Details Added ✅ for these four — the board was right, and the round-1
  claim in this file that details were "unfinished on all five" was wrong
  for these four; corrected here.
- INCOMPLETE (1): awesome-audio-plugins-dev. Description, 15 topics,
  language (Python), license (GPL-3.0 or later), and alternatives are
  present — but the links row is Source Code only: NO website URL and
  NO Docs URL, and the about block has NO "marked as self-hosted"
  statement. Matches STATUS_BOARD.md's Details Added: Pending. Filling
  those three fields needs an "Edit details" pass (browser form, no API).
  **CORRECTED 2026-11-08 (see "2026-11-08 submissions" below):** an
  "Edit details" submission filled the website and Docs URLs, corrected
  the language Python → Markdown, and corrected the license GPL-3.0 →
  **CC0 1.0 Universal** (the repo LICENSE file is CC0 — the tracker
  record saying MIT was WRONG; corrected here). Submitted, awaiting
  LibHunt moderator approval; until approval the live page still shows
  the old GitHub-synced values.
- Evidence screenshots are a tracker-side artifact, not a LibHunt field,
  and are still pending for all five — STATUS_BOARD.md's
  "Evidence Saved: Pending" stands. (Evidence PDFs of the seven NEW
  pages created 2026-11-08 were saved by the browser task; see
  "2026-11-08 submissions" below.)

The newly found pages beyond the first wave were checked for existence
only, not details.

First-wave live (5, numbers verified): FreeEQ8 (21 alternatives,
6 mentions, 21 stars — mentions rose 5 → 6 on 2026-11-08 from the
cross-link suggestions, see "2026-11-08 submissions" below),
ARC-Neuron-LLMBuilder (11 alternatives,
6 mentions, 14 stars), TizWildinEntertainmentHUB,
ARC-Core, awesome-audio-plugins-dev (21 alternatives, 1 mention,
10 stars). All five show "Last Commit, 6 months ago" — LibHunt's data
is a May 2026 snapshot and refreshes when the repos move and LibHunt
recrawls. The four refreshed pages (LLMBuilder, ARC-Core, HUB,
plugins-dev) STILL show "Last Commit, 6 months ago" after the
2026-11-08 refreshes — that is LibHunt's GitHub-sync timestamp, which
no edit can change; it updates when LibHunt next syncs.

ARC cluster, also live: arc-language-module (18 alternatives, 5 mentions,
2 stars), Arc-RAR, arc-lucifer-cleanroom-runtime, ARC-StreamMemory,
ARC-Turbo-OS, omnibinary-runtime, arc-neuron-llmbuilder-v1.0.0.

Audio / creator tools, also live: Instrudio, XyloCore, Therum_JUCE-Plugin,
AETHER_Choir-Atmosphere-Designer, BassMaid, SpaceMaid, GlueMaid, MixMaid,
MultiMaid, MeterMaid, ChainMaid, WhisperGate_Free-JUCE-Plugin,
PaintMask_Free-JUCE-Plugin, RiftWaveSuite_RiftSynth_WaveForm_Lite,
WURP_Toxic-Motion-Engine_JUCE, FreeSampler_v0.3, VF-PlexLab,
PAP-Forge-Audio.

Other ecosystem repos, also live: ai-desk-meter, Proto-Synth_Grid_Engine,
LuciferAI_Local, Neo-VECTR_Solar_Sim_NASA_Standard, Synth-Grid-Engine,
TT-101_Handbook.

LibHunt pages MISSING (5, checked 2026-11-08; was 12 — 7 were created
live on 2026-11-08, see "2026-11-08 submissions" below):

- FreeVox8 — Gary's call: list as-is with an honest description, or wait until shippable.
- PaintMask — NOT missing: already live under its full name
  PaintMask_Free-JUCE-Plugin (the "missing" was a short-name artifact;
  verified 2026-11-08, seen in FreeEQ8's alternatives list).
- juce-tutorial, QKV-Core, SpectrumAnalyzer — NOT Gary's: the existing
  LibHunt pages for those names belong to other authors (wyan's
  juce-tutorial, sylwekkominek's SpectrumAnalyzer). Do not submit as Gary's.

How a missing project gets on LibHunt: LibHunt pages are created from GitHub
mentions/posts, or by suggesting the project as an alternative on an existing
related page ("Suggest an alternative" link — browser form, no API). There is
no API submission. Suggestions prepared 2026-11-08 (see lists-finish report):
awesome-audio-lists, awesome-music-platforms, and awesome-python-audio-science
as alternatives to awesome-audio-plugins-dev / FreeEQ8.

## 2026-11-08 submissions — 7 new pages LIVE + 4 refreshes submitted

Browser task ran 2026-11-08 06:45–07:28 PST (LibHunt "Suggest an
alternative" form for the new pages, "Edit details" form for the
refreshes). Nothing was paid, no sign-in was needed anywhere. Form
email used: neovectr.inc@gmail.com (the public contact email published
in the TizWildin-IO README — verification/notification for the
submissions goes to that address).

### 7 NEW pages — LIVE (verified loading at canonical URLs)

LibHunt suggestions create the page immediately — the live pages already
show fresh GitHub-synced data (e.g. recent last-commit dates). The
curated detail edits submitted with each page go to LibHunt moderator
approval (each edit showed "Your suggested changes will be applied as
soon as they are approved"); until approval a page displays its
GitHub-synced description/topics/license/language. Evidence PDFs of all
seven live pages were saved by the browser task.

| Project | Live URL | LibHunt repo ID | Suggested on | Stars | License / Language (confirmed from repo) |
|---|---|---|---|---|---|
| awesome-audio-lists | https://libhunt.com/GareBear99/awesome-audio-lists | 3911411 | awesome-audio-plugins-dev | 7 | CC0 1.0 Universal, Markdown |
| awesome-music-platforms | https://libhunt.com/GareBear99/awesome-music-platforms | 3911412 | awesome-audio-plugins-dev | 2 | CC0 1.0 Universal, Markdown |
| awesome-python-audio-science | https://libhunt.com/GareBear99/awesome-python-audio-science | 3911413 | awesome-audio-plugins-dev | 7 | CC0 1.0 Universal, Markdown |
| Free-808-Producer-Kit | https://libhunt.com/GareBear99/Free-808-Producer-Kit | 3911414 | TizWildinEntertainmentHUB | 7 | No LICENSE file (license field left blank on purpose); Python 100% |
| TizWildin-Chime | https://libhunt.com/GareBear99/TizWildin-Chime | 3911415 | TizWildinEntertainmentHUB | 2 | No LICENSE file (license field left blank on purpose); Python 100% |
| Voxel_Audio | https://libhunt.com/GareBear99/Voxel_Audio | 3911416 | TizWildinEntertainmentHUB | 3 | MIT, HTML 99.5%, self-hosted Yes |
| TizWildin-IO | https://libhunt.com/GareBear99/TizWildin-IO | 3911417 | TizWildinEntertainmentHUB | 2 | No LICENSE file (license field left blank on purpose); Python 100%, self-hosted No |

License/language notes (confirmed from the repos at submit time, no
guessing): the three lists are CC0 1.0 Universal, Markdown (the
awesome-audio-lists LICENSE file was read directly — it is the CC0 1.0
Universal legal code). Free-808's README License section, quoted
exactly: "Free to use in commercial and non-commercial productions. No
credit required. Do not redistribute the raw samples as a sample pack."
Chime's README says "$1 USD on paid platforms · free on GitHub" /
"free forever from official channels". Voxel_Audio is MIT (README: "MIT
License. See LICENSE."; LICENSE file present) and self-hosted Yes
(local-first tool — runs entirely locally, no server). TizWildin-IO is
the sample-pack lane, not the HUB itself, and FreeVox8 was NOT linked as
an alternative because it is not shippable yet. Topics were added as
chips per page (17, 14, 17, 11, 9, 13, 15 respectively), plus website,
docs, language, license, self-hosted, and an edit note.

LibHunt's own sync currently MIS-DETECTS licenses on several repos (it
shows GPL-3.0 for the three CC0 lists and for Voxel_Audio, and MIT for
the HUB); the submitted edits correct these.

### 4 REFRESHES — detail edits submitted, awaiting moderator approval

| Project | Live URL | What changed |
|---|---|---|
| ARC-Neuron-LLMBuilder | https://libhunt.com/GareBear99/ARC-Neuron-LLMBuilder | Description corrected (removed the "trains small brains" claim; dataset section done, model NOT trained). Website, docs, Python, MIT, self-hosted already correct, unchanged. |
| ARC-Core | https://libhunt.com/GareBear99/ARC-Core | Description corrected. Website, docs, Python, MIT, self-hosted already correct, unchanged. ARC alternative graph still linked. |
| TizWildinEntertainmentHUB | https://libhunt.com/GareBear99/TizWildinEntertainmentHUB | Description corrected. Website/docs already correct. License: repo has no LICENSE file, GitHub detects no license, README badge reads "License: Free" — LibHunt's "MIT" label is unsupported, but the form would not accept clearing it, so flagged in the edit note for moderators. Language: GitHub primary Python 51.6% (HTML 38.8%), flagged in the note. |
| awesome-audio-plugins-dev | https://libhunt.com/GareBear99/awesome-audio-plugins-dev | FULLY corrected: description updated with the 113-entry count; website and Docs URLs filled (both were blank); language corrected Python → Markdown; license corrected GPL-3.0 → CC0 1.0 Universal (repo LICENSE is CC0; the tracker record saying MIT was WRONG — corrected in this file). Self-hosted left as No. |

All four still show "Last Commit, 6 months ago" — LibHunt's GitHub-sync
timestamp, which no edit can change; it updates when LibHunt next syncs.

### Cross-links (2026-11-08)

7 further suggestions, all accepted (the existing-project ones were
auto-approved with "Thanks for your suggestion! It's been approved
automatically"): awesome-audio-lists, Free-808-Producer-Kit,
Voxel_Audio and TizWildin-IO on FreeEQ8; awesome-music-platforms on
awesome-audio-lists; awesome-python-audio-science on
ARC-Neuron-LLMBuilder (ML-audio angle); TizWildin-Chime on
Free-808-Producer-Kit. FreeEQ8's mention count rose from 5 to 6 as a
result.

### HELD — not done (2026-11-08)

- FreeEQ8 refresh NOT done — gated on ProEQ8 payments being live.
- FreeVox8 NOT submitted.
- No PaintMask duplicate — already live as PaintMask_Free-JUCE-Plugin.
- juce-tutorial, QKV-Core, SpectrumAnalyzer NOT submitted as Gary's —
  existing pages belong to other authors (wyan's juce-tutorial,
  sylwekkominek's SpectrumAnalyzer).

### Limitations (recorded in the submitted edit notes for moderators)

1. On the 4 refresh pages, topics are UNCHANGED — LibHunt's topic
   remove buttons and Enter/comma topic-add did not respond to browser
   input, so extra topics were not trimmed and missing payload topics
   were not added; each edit note lists the intended payload topic set
   for moderators to apply. (On the 7 new pages all payload topics were
   still added one by one — paste, then clicking away to commit each chip.)
2. On the HUB refresh, the language combobox would not accept a change
   through the form's usual input methods, so its language stays HTML
   until a moderator applies the note's Python 51.6% finding; likewise
   its MIT license could not be cleared.
3. All detail edits (7 new + 4 refresh) await LibHunt moderator approval
   before the curated payload values replace the GitHub-synced values
   currently displayed.

### Tracker corrections made with this update (2026-11-08)

- plugins-dev license: MIT → **CC0 1.0 Universal** (repo LICENSE file
  is authoritative; the MIT record was wrong).
- Missing list: 12 → 5 (7 created live; PaintMask was never missing —
  live under its full name; juce-tutorial / QKV-Core / SpectrumAnalyzer
  are not Gary's).
- FreeEQ8 mentions: 5 → 6 (cross-link suggestions).
- plugins-dev details: INCOMPLETE → corrected via Edit details,
  awaiting moderator approval.
- Refresh pages: "Last Commit, 6 months ago" persists after the
  refreshes (sync timestamp, not an edit failure).
