# TizWildin Ecosystem Cluster Submission Route

This file is the operating plan for completing the public-facing TizWildin audio / producer / creator-tool ecosystem across LibHunt first, then indexed discovery platforms.

## Current Locked State

- **FreeEQ8** is already started on LibHunt.
- **FreeEQ8 → TizWildinEntertainmentHUB** has been added as the first alternative route.
- **TizWildinEntertainmentHUB** is already started on LibHunt.
- The next step is to finish the whole internal audio graph before moving to the next platform.

## Core TizWildin Cluster

| Project | Role | Current Wave | LibHunt Role | Public Positioning |
|---|---|---:|---|---|
| FreeEQ8 | Flagship free EQ plugin | 1 | Primary product page | Free open-source JUCE/C++ EQ plugin for VST3/AU workflows. |
| TizWildinEntertainmentHUB | Main ecosystem hub | 1 | Alternative + website hub | Discovery dashboard for plugins, sample packs, visualizers, downloads, and updates. |
| FreeVox8 | Free vocoder/spectral plugin | 1 | Alternative to FreeEQ8/HUB | Creative spectral voice-processing and vocoder plugin. |
| awesome-audio-plugins-dev | Curated audio resource list | 1 | Alternative/resource list | Open-source audio/plugin/sample-pack discovery list. |
| TizWildin-IO | Sample-pack router | 2 | Supporting ecosystem page | Deconstructed packs, creator assets, and sample-pack routing. |
| Voxel_Audio | RGB visualizer/export tool | 2 | Supporting creator tool | Music visualizer and creator export workflow. |
| Free-808-Producer-Kit | Producer sample pack | 2 | Supporting sample pack | Free 808 kit for producers. |
| TizWildin-Chime | Producer sample pack | 2 | Supporting sample pack | Free chime/sparkle sound pack. |
| PaintMask | Experimental plugin concept | 2 | Supporting plugin concept | Visual masking and creative DSP workflow. |

## LibHunt Cross-Link Graph

Finish these alternatives in this exact order.

```text
FreeEQ8
→ TizWildinEntertainmentHUB [DONE]
→ FreeVox8
→ awesome-audio-plugins-dev
→ TizWildin-IO
→ Voxel_Audio

TizWildinEntertainmentHUB
→ FreeEQ8 [DONE/STARTED]
→ FreeVox8
→ awesome-audio-plugins-dev
→ TizWildin-IO
→ Voxel_Audio

FreeVox8
→ FreeEQ8
→ TizWildinEntertainmentHUB
→ awesome-audio-plugins-dev
→ PaintMask

awesome-audio-plugins-dev
→ FreeEQ8
→ FreeVox8
→ TizWildinEntertainmentHUB
→ TizWildin-IO

TizWildin-IO
→ TizWildinEntertainmentHUB
→ Free-808-Producer-Kit
→ TizWildin-Chime
→ Voxel_Audio

Voxel_Audio
→ TizWildinEntertainmentHUB
→ TizWildin-IO
→ FreeEQ8

Free-808-Producer-Kit
→ TizWildin-IO
→ TizWildinEntertainmentHUB
→ TizWildin-Chime

TizWildin-Chime
→ TizWildin-IO
→ TizWildinEntertainmentHUB
→ Free-808-Producer-Kit

PaintMask
→ FreeEQ8
→ FreeVox8
→ TizWildinEntertainmentHUB
```

## LibHunt Submission Copy

### FreeVox8 Alternative Comment

```text
FreeVox8 is a related free audio-plugin project focused on vocoder and spectral voice-processing workflows. It complements FreeEQ8 as another JUCE/C++ music-production tool in the TizWildin ecosystem, expanding from EQ and mixing into creative spectral processing.
```

### awesome-audio-plugins-dev Alternative Comment

```text
awesome-audio-plugins-dev is a curated audio-plugin and music-production development resource list. It complements FreeEQ8 and FreeVox8 by helping producers, developers, and open-source audio users discover free plugins, DSP tools, sample packs, JUCE projects, and music-production resources.
```

### TizWildin-IO Alternative Comment

```text
TizWildin-IO is a sample-pack and creator-resource router for the TizWildin ecosystem. It complements the plugin projects by connecting FreeEQ8, FreeVox8, producer packs, and deconstructed music resources into one creator-facing distribution layer.
```

### Voxel_Audio Alternative Comment

```text
Voxel_Audio is a music visualizer and export workflow tool for creators. It complements the TizWildin plugin ecosystem by helping artists create RGB waveform visuals, promotional videos, and release-ready visual content around music made with the tools and packs.
```

## Finish Criteria

The TizWildin LibHunt cluster is considered complete when:

- FreeEQ8 has at least HUB, FreeVox8, and awesome-audio-plugins-dev listed as alternatives.
- HUB has FreeEQ8, FreeVox8, and awesome-audio-plugins-dev listed as alternatives.
- FreeVox8 has FreeEQ8, HUB, and awesome-audio-plugins-dev listed as alternatives.
- awesome-audio-plugins-dev links back to FreeEQ8, FreeVox8, and HUB.
- Wave 2 supporting projects are logged even if not all are submitted immediately.
