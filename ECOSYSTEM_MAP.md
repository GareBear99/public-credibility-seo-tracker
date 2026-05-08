# Ecosystem Map

## ARC Local AI / AGI Infrastructure Cluster

This cluster should be cross-linked internally on LibHunt and future directory platforms.

| Project | Role | Repository |
|---|---|---|
| ARC-Neuron-LLMBuilder | Local cognition-core builder / GGUF-focused LLM workshop | https://github.com/GareBear99/ARC-Neuron-LLMBuilder |
| ARC-Core | Authority, receipts, governance, runtime-control console | https://github.com/GareBear99/ARC-Core |
| arc-lucifer-cleanroom-runtime | Local cleanroom AI execution/runtime layer | https://github.com/GareBear99/arc-lucifer-cleanroom-runtime |
| arc-language-module | Language, NLP, lineage, transliteration, cognition data layer | https://github.com/GareBear99/arc-language-module |
| Arc-RAR | Archival, reproducibility, receipts, packaging/restore layer | https://github.com/GareBear99/Arc-RAR |

### ARC LibHunt Cross-Link Map

- ARC-Neuron-LLMBuilder → ARC-Core, arc-lucifer-cleanroom-runtime, arc-language-module, Arc-RAR
- ARC-Core → ARC-Neuron-LLMBuilder, arc-lucifer-cleanroom-runtime, arc-language-module, Arc-RAR
- arc-lucifer-cleanroom-runtime → ARC-Neuron-LLMBuilder, ARC-Core, arc-language-module, Arc-RAR
- arc-language-module → ARC-Neuron-LLMBuilder, ARC-Core, arc-lucifer-cleanroom-runtime, Arc-RAR
- Arc-RAR → ARC-Core, ARC-Neuron-LLMBuilder, arc-lucifer-cleanroom-runtime, arc-language-module

## TizWildin Audio / Creator Tools Cluster

This cluster should be cross-linked internally on LibHunt and future directory platforms.

| Project | Role | Repository |
|---|---|---|
| FreeEQ8 | Free open-source JUCE/C++ EQ plugin | https://github.com/GareBear99/FreeEQ8 |
| TizWildinEntertainmentHUB | Public ecosystem hub for plugins, sample packs, downloads, updates | https://github.com/GareBear99/TizWildinEntertainmentHUB |
| FreeVox8 | Free open-source JUCE/C++ vocoder / spectral voice plugin | https://github.com/GareBear99/FreeVox8 |
| awesome-audio-plugins-dev | Curated audio plugin and music-production resource list | https://github.com/GareBear99/awesome-audio-plugins-dev |

### Audio LibHunt Cross-Link Map

- FreeEQ8 → TizWildinEntertainmentHUB, FreeVox8, awesome-audio-plugins-dev
- TizWildinEntertainmentHUB → FreeEQ8, FreeVox8, awesome-audio-plugins-dev
- FreeVox8 → FreeEQ8, TizWildinEntertainmentHUB, awesome-audio-plugins-dev
- awesome-audio-plugins-dev → FreeEQ8, FreeVox8, TizWildinEntertainmentHUB
