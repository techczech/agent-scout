# Agent Scout

Agent Scout is a Mac app for researching work done with coding agents. Browse live conversations, collect related threads into named projects, then explore the saved material together.

**Public preview: 0.2.0-provisional.7.** The Mac app is Developer ID signed and notarised by Apple. Requires an Apple Silicon Mac running macOS 13 or later.

[Download the Mac preview](https://github.com/techczech/agent-scout/releases/tag/v0.2.0-provisional.7) · [About Agent Scout](https://dominiklukes.net/apps/agent-scout)

## Collect a project

Open **Live conversations** to discover supported Claude Code, Codex, T3 Code and Antigravity histories. Filter by folder, project reference, text, tool activity or date. Create a research project, then choose **Add selected** or **Add all matching**. Saving shows progress and opens the saved version when complete.

Selected original records are copied into retained project versions, including available tool records, native metadata and attachments. Earlier versions remain available. Back up projects into a portable folder and restore them with integrity checks. Unsupported or opaque records stay preserved even when no text decoder is available.

## Explore the collected work

**Overview** shows thread, message, word and tool-call counts, daily activity and recorded model tokens. The token graphic separates cache read, cache creation, uncached input and output without counting cache twice. Missing counters are labelled rather than treated as zero. Dates, models and source apps lead to the corresponding saved threads.

**Content** provides local concordances, repeated phrases, collocations and comparisons through ArchiveScout, with links to saved source passages. **Threads** retains conversation and transcript views. Optional **Summaries** and **Project questions** save content analysis with source links.

Browsing and local statistics do not run a model. Paid summaries and project questions require a supported provider key and an explicit run; they send the disclosed archived text to that provider. No API key is included.

## Install

Download the mac-arm64 ZIP from the release, expand it and drag **Agent Scout.app** into Applications. Keep existing research projects in place when updating. This repository distributes the application and release information; it does not publish the private development checkout or any conversation history.

Screenshots use synthetic conversations. This is an early public preview.
