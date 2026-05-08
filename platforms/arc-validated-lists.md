# ARC Validated List Targets

This file tracks community-vetted public lists, directories, and launch routes for the ARC Local AI ecosystem.

## Current ARC rule

Finish the LibHunt internal graph before moving to broader list submissions.

Current LibHunt state:

- ARC-Neuron-LLMBuilder has ARC-Core as the first alternative.
- ARC-Core is started as the first internal alternative.
- Next LibHunt targets: arc-lucifer-cleanroom-runtime, arc-language-module, Arc-RAR.

## Tier 1: Validated / Community-Vetted Targets

| Target | URL | Best ARC Fit | Submission Type | Priority | Status | Notes |
|---|---|---|---|---|---|---|
| LibHunt | https://www.libhunt.com/ | All five ARC repos | Manual project + alternatives | A+ | Active | First platform route. Finish internal ARC graph first. |
| GitHub Topics | https://github.com/topics | All ARC repos | Repo settings / GitHub API | A+ | Pending | Native GitHub discovery layer. |
| awesome-local-llm | https://github.com/rafska/awesome-local-llm | ARC-Neuron, Lucifer Runtime | PR / issue | A | Pending | Curated local LLM platforms, tools, practices, and resources. |
| awesome-local-ai | https://github.com/msb-msb/awesome-local-ai | ARC-Neuron, ARC-Core, Lucifer Runtime | PR / issue | A | Pending | Local AI resources for consumer hardware. |
| janhq/awesome-local-ai | https://github.com/janhq/awesome-local-ai | ARC-Neuron, Lucifer Runtime | PR / issue | A- | Pending | Local AI tools list; good fit after README polish. |
| awesome-llm-services | https://github.com/av/awesome-llm-services | ARC-Neuron, Lucifer Runtime, ARC-Core | PR / issue | A- | Pending | Self-hostable LLM services/tools/infrastructure. |
| awesome-ai-agents | https://github.com/e2b-dev/awesome-ai-agents | ARC-Core, ARC-Neuron | PR / issue | A- | Pending | Agent list; strongest if ARC-Core has a clear local runtime/control demo. |
| Open Hub | https://www.openhub.net/ | All ARC repos | Add project | A- | Pending | Open-source credibility / repo activity indexing. |

## Tier 2: Public Directory / Alternative Graph Targets

| Target | URL | Best ARC Fit | Submission Type | Priority | Status | Notes |
|---|---|---|---|---|---|---|
| OpenAlternative | https://openalternative.co/ | ARC-Core, ARC-Neuron | Manual / project submission | B+ | Pending | Needs clear alternative-to-cloud-AI framing. |
| OpenSourceAlternative.to | https://www.opensourcealternative.to/ | ARC-Core, ARC-Neuron | Manual submission | B+ | Pending | Good after screenshots, features, and install path are clean. |
| AlternativeTo | https://alternativeto.net/ | ARC-Neuron, ARC-Core | Manual submission | B | Pending | Consumer-facing alternatives graph. |
| SourceForge | https://sourceforge.net/ | ARC-Core, ARC-Neuron | Project import/create | B | Pending | Useful mirror/listing route after GitHub cleanup. |

## Tier 3: Launch / Community Routes

| Target | Best ARC Fit | Submission Type | Priority | Status | Notes |
|---|---|---|---|---|---|
| Show HN | ARC-Neuron or ARC-Core | Manual post | B | Pending | Use only after demo/install/screenshot polish. |
| r/LocalLLaMA | ARC-Neuron, Lucifer Runtime | Manual post | B | Pending | Use a demo story, not a cold repo link. |
| r/selfhosted | ARC-Core, ARC-Neuron | Manual post | B | Pending | Needs a self-host/local dashboard angle. |
| r/opensource | Whole tracker / ARC ecosystem | Manual post | B- | Pending | Best after tracker repo is public and polished. |

## Repo-to-Target Map

### ARC-Neuron-LLMBuilder

- LibHunt
- GitHub Topics
- awesome-local-llm
- awesome-local-ai
- janhq/awesome-local-ai
- awesome-llm-services
- Open Hub
- OpenAlternative / OpenSourceAlternative.to

### ARC-Core

- LibHunt
- GitHub Topics
- awesome-ai-agents
- awesome-local-ai
- awesome-llm-services
- Open Hub
- r/selfhosted after demo polish

### arc-lucifer-cleanroom-runtime

- LibHunt
- GitHub Topics
- awesome-local-llm
- awesome-local-ai
- awesome-llm-services
- Open Hub
- r/LocalLLaMA after model-running demo exists

### arc-language-module

- LibHunt
- GitHub Topics
- awesome-nlp
- awesome-linguistics
- awesome-python
- Open Hub

### Arc-RAR

- LibHunt
- GitHub Topics
- awesome-cli-apps
- awesome-rust or awesome-python depending actual language
- awesome-backup
- Open Hub

## PR / Issue Message: ARC-Neuron-LLMBuilder

```text
Hi, I’d like to suggest adding ARC-Neuron-LLMBuilder to this list.

ARC-Neuron-LLMBuilder is an open-source, local-first LLM/cognition-core builder for the ARC ecosystem. It focuses on offline AI workflows, dataset preparation, reproducible model-building experiments, GGUF-oriented local LLM direction, receipts, and deterministic build/run records.

Repository:
https://github.com/GareBear99/ARC-Neuron-LLMBuilder

Suggested category:
Local LLM tools / local AI frameworks / AI second brain / developer tools

Why it may fit:
- Local-first and offline-oriented
- Open-source
- Built around reproducible AI experiments and local cognition workflows
- Designed to connect with ARC-Core for governance, receipts, and runtime tracking

I’m happy to adjust the description or category if another section fits better.
```

## PR / Issue Message: ARC-Core

```text
Hi, I’d like to suggest adding ARC-Core to this list.

ARC-Core is an open-source, local-first AI governance and runtime-control console. It focuses on deterministic routing, receipts, calibration, incident tracking, replayable evidence, and orchestration for local AI systems.

Repository:
https://github.com/GareBear99/ARC-Core

Suggested category:
Local AI infrastructure / AI agents / self-hosted AI tools / developer tools

Why it may fit:
- Local-first and self-hostable
- Open-source
- Provides a runtime-control and governance layer for AI workflows
- Designed for receipts, replayability, and deterministic system tracking

I’m happy to adjust the description or category if another section fits better.
```
