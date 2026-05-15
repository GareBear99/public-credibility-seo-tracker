# Next Steps

## Current Phase: Finish LibHunt First

Do not jump platforms until both internal graphs are complete enough to compound.

## 1. Finish ARC LibHunt Graph

```text
ARC-Neuron-LLMBuilder ↔ ARC-Core ↔ arc-lucifer-cleanroom-runtime ↔ arc-language-module ↔ Arc-RAR
```

Minimum finish state:

- ARC-Neuron has ARC-Core, Lucifer Runtime, language module, and Arc-RAR alternatives.
- ARC-Core has ARC-Neuron, Lucifer Runtime, language module, and Arc-RAR alternatives.
- Lucifer Runtime is submitted and linked to ARC-Neuron + ARC-Core.
- arc-language-module is submitted and linked to ARC-Neuron + ARC-Core.
- Arc-RAR is submitted and linked to ARC-Core + ARC-Neuron.

## 2. Finish TizWildin LibHunt Graph

```text
FreeEQ8 ↔ TizWildinEntertainmentHUB ↔ FreeVox8 ↔ awesome-audio-plugins-dev
```

Minimum finish state:

- FreeEQ8 has HUB, FreeVox8, and awesome-audio-plugins-dev alternatives.
- HUB has FreeEQ8, FreeVox8, and awesome-audio-plugins-dev alternatives.
- FreeVox8 is submitted and cross-linked.
- awesome-audio-plugins-dev is submitted and cross-linked.

Wave-2 support after core graph:

```text
TizWildin-IO → HUB, Free-808-Producer-Kit, TizWildin-Chime, Voxel_Audio
Voxel_Audio → HUB, TizWildin-IO, FreeEQ8
PaintMask → FreeEQ8, FreeVox8, HUB
```

## 3. Clean GitHub Topics

Apply `platforms/github-topics.md` and `platforms/tizwildin-github-topics.md` topic sets.

## 4. Move to Public Indexes

Next route order:

```text
Open Hub
SourceForge
KVR Audio
Audio Plugins for Free
awesome-juce / OpenAudio / awesome-audio-dsp
OpenAlternative / OpenSourceAlternative.to
AlternativeTo
Editorial/community launches
```

## 5. Evidence Discipline

For every submission:

- save screenshot under `evidence/screenshots/<project>/`
- save confirmation under `evidence/confirmations/<project>/`
- write quick note under `evidence/notes/<project>/`
- update `STATUS_BOARD.md`
- update project record


## TizWildin-IO Website Capture Update

- Added `platforms/tizwildin-io-website-capture.md`.
- Updated `projects/TizWildin-IO.md` with public-facing descriptions, topics, pack catalog, cross-links, and LibHunt submission routing.
- Added evidence notes under `evidence/notes/tizwildin-io/`.
- Current rule: finish the primary LibHunt audio graph first, then submit TizWildin-IO as the sample-pack / producer-resource router.

## Corrected TizWildin `.io` next step

The next LibHunt and directory work should point the audio cluster back to:

https://garebear99.github.io/TizWildinEntertainmentHUB/

Use this as the main public ecosystem front door, then route out to individual repos, packs, release vault, visualizers, and awesome lists.

## DEV.to Next Steps

1. Publish the Start Here ecosystem hub post.
2. Add final public DEV.to URLs to `dev.to-post-tracker`.
3. Cross-link the best DEV.to article from each project README where appropriate.
4. Use DEV.to URLs as hub links for KVR, JUCE, Gearspace, Facebook, Reddit, and directory submissions.
5. Keep this tracker and `dev.to-post-tracker` linked both ways.
