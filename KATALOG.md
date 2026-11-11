# Full Catalog — Raihan's Curated Skills & Repos

This list is the full index from the curation notes (reviewed 11 Nov 2026).
Every skill from those notes that could be found is installable through this
repo's `marketplace.json` (marked "Via this marketplace") — either because the
repo is a native plugin, or because the entry wraps the exact skill folder
inside the upstream repo. The remaining entries are apps, frameworks, or
libraries: not skills, so they live here as references with usage notes.

Legend: ⭐ = GitHub stars as of 11 Nov 2026 (approximate).

---

## Already owned (no need to install again)

| Name | Repo | Notes |
| --- | --- | --- |
| REA (Reverse Engineer Anything) | morluto/rea | Installed in Claude Code (gateway profile) |
| Karpathy skills | andrej-karpathy-skills | Installed (plugin) |
| UI UX Pro Max | nextlevelbuilder/ui-ux-pro-max | Installed (plugin, design cluster) |
| last30days | mvanhorn/last30days-skill | Installed |
| scrapling | web scraping research | Installed |
| ponytail | — | Installed, including in the official profile |
| Agent-Reach | Panniantong/Agent-Reach | Reviewed — decided against for the official profile |
| voice box (local voice/TTS) | — | Checked off in the notes — already set up locally |

## Agent & Engineering

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| Addy Osmani agent-skills | addyosmani/agent-skills | 115.7k | Via this marketplace: `agent-skills` |
| Cloudflare skills (official) | cloudflare/skills | 3.3k | Via this marketplace: `cloudflare` |
| OpenHands (autonomous agent platform — an app, not a skill) | OpenHands/OpenHands | 93.2k | Run as an application |

## Creative & Design

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| garden-skills (6 skills: beautiful-article, gpt-image-2, kb-retriever, motion-showreel, web-design-engineer, web-video-presentation) | ConardLi/garden-skills | 14.9k | Via this marketplace: `garden-skills` (all 6 wrapped) |
| anatomy (interactive isometric illustrations) | wheresryan22/anatomy | 26.7k | Via this marketplace: `anatomy` |
| OpenDesign (open-source Claude Design alternative) | nexu-io/open-design | 107k | Local-first desktop app (BYOK) |
| astryx (Meta's official design system, agent-ready) | meta/astryx | 24.5k | React library — `npm` in a project |

## Video

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| HyperFrames (+ reverse-any-video skill; reverse feature is Pro) | heygen-com/hyperframes | 82.7k | Via this marketplace: `hyperframes` |
| brag (launch video from the project folder) | latent-spaces/brag | 21k | Via this marketplace: `brag` |
| hypit (dissect & recreate viral reels) | hypit-ai/hypit | 29.3k | Via this marketplace: `hypit` |
| video-use (edit video by conversation, by the browser-use team) | browser-use/video-use | ±31k | Via this marketplace: `video-use` (needs an ElevenLabs API key + ffmpeg) |
| Remotion skills (official) | remotion-dev/skills | 6.8k | Via this marketplace: `remotion-skills` |
| Remotion (React video framework — not a skill) | remotion-dev/remotion | 72.4k | `npm i remotion` in a project (special Remotion license) |
| motion-graphics-skills (from Charlie Hills' list) | charlie947/motion-graphics-skills | 644 | Via this marketplace: `motion-graphics-skills` |
| claude-motion | whaleyxbt/claude-motion | 944 | Via this marketplace: `claude-motion` (very early) |
| motionmaxxing | Tejashmakwana/motionmaxxing | 1.5k | Via this marketplace: `motionmaxxing` (early release) |
| auto-editor (auto-remove silent parts) | WyattBlue/auto-editor | 5.8k | `npx skills add WyattBlue/auto-editor` or app.auto-editor.com |
| OpenCut (web video editor, CapCut alternative) | OpenCut-app/OpenCut | 98.1k | Web app — open & use |
| LosslessCut (lossless video trimming) | mifi/lossless-cut | 45.9k | Desktop app — download the official binary |
| OpenShorts (auto-clip into 9:16 shorts) | mutonby/openshorts | 7.7k | openshorts.app (free tier) or self-host with Docker |
| OpenMotion (agentic video studio, by the OpenDesign team) | nexu-io/openmotion | 9.5k | Local web app (BYOA + BYOK) |
| Brism (faceless video director) | — | — | NOT open-source: paid product via Whop ($49/mo) |

## Business & Marketing

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| Sellbird (formerly "Harvey") — customer-finding & cold outreach agent | ethanplusai/sellbird | 5.1k | Local app; rides on your Claude/Codex subscription |

## SEO

One repo covers four entries at once:

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| OpenSEO — skills `ai-visibility-audit`, `local-seo`, `competitor-analysis`, `keyword-research`, and more | every-app/open-seo | 27k | Via this marketplace: `open-seo` |
| open-seo-mcp-skills (alternative, MCP + SEO/GEO skills) | Ryze-AI-Adgent/open-seo-mcp-skills | 9.2k | Via this marketplace: `open-seo-mcp-skills` |

Note: open-source SEO tools of this kind usually pull data from inexpensive
paid APIs (DataForSEO/SerpApi) — the software is free, the data is pay-per-call.

## Security

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| BLA — Blind LLM Agents (anti reverse-engineering) | qybaihe/bla | 5.3k | Via this marketplace: `bla` (skill wrap); full CLI/MCP: `npm i -g bla-agents` |

## Writing & Fiction

| Name | Repo | ⭐ | Install |
| --- | --- | --- | --- |
| awesome-novel (novel-writing skill) | modoojunko/awesome-novel-agent | — | Via this marketplace: `awesome-novel` (AGPL-3.0) |
| MuMuAINovel (AI novel-writing web app) | xiamuceer-j/MuMuAINovel | 3.3k | Self-host (Docker), GPL-3.0 |

## Free Tokens / Routers

| Name | Repo | ⭐ | Notes |
| --- | --- | --- | --- |
| FreeLLMAPI (free-tier aggregator across 34 providers, BYOK) | tashfeenahmed/freellmapi | 50.6k | Your own keys, NOT a shared pool. Free tiers are usually dev-only under provider ToS — do not build a resale business on them |
| OmniRouter (self-hosted router software) | omnilabs-ai/OmniRouter | 129 | Not a token source; same pattern as RouterReceh but self-hosted |

## Trading

| Name | Repo | ⭐ | Notes |
| --- | --- | --- | --- |
| day-trader-skill (11 day-trading skills, paper by default) | Jakeschincariol/day-trader-skill | 6.9k | Via this marketplace: `day-trader-skill` |
| TradingAgents (multi-agent trading research) | TauricResearch/TradingAgents | 122k | Research/simulation framework, needs an LLM API key |
| ai-hedge-fund | virattt/ai-hedge-fund | 64.6k | Education/PoC project, has a backtester |
| NautilusTrader (production engine, Rust+Python) | NautechSystems/nautilus_trader | 31.5k | Heavy — for experienced quants, LGPL-3.0 |
| awesome-systematic-trading (curated list + paper replications) | paperswithbacktest/awesome-systematic-trading | 15.3k | Best starting point for mapping the ecosystem |

## Caution

| Name | Repo | Why be careful |
| --- | --- | --- |
| jailbreaks | togg53192-cmd/jailbreaks | A collection of jailbreak prompts, no license. Fine as prompt-injection study material only — using them to bypass model safeguards violates provider ToS. Do NOT put this in a product pipeline |
| MiroFish (swarm simulation) | 666ghj/MiroFish | AGPL-3.0 license — strong copyleft, risky for closed commercial products |

## Curation references

- Charlie Hills' "Top 30 Claude plugins/repos" list (LinkedIn/Substack,
  Oct 2026) — the original discovery source for many entries in this catalog.

---

# From the office repo catalog (kantor.raihann.me/katalog)

The office maintains its own evaluated repo catalog (57 repos, with install
statuses and verdicts). Every repo there was probed for this marketplace
(plugin manifest present? SKILL.md folders? or not a skill at all?).
**49 of the 57 are now installable through this marketplace** — find them in
`marketplace.json` under their categories (engineering, creative, video,
research, marketing, documents, productivity, writing, security,
infrastructure). Two were already in this bag from the notes list
(`hyperframes`, `agent-skills`).

Three repos the office had marked **rejected** are included at the owner's
direction — the rejections were for the Hermes office context, not for this
bag: `headroom` (productivity), `hermes-jev-skills` and `claude-x-jev`
(engineering). Their entries carry the office's reasoning.

## Reference only — cannot be installed as skills

| Name | Repo | Why |
| --- | --- | --- |
| Graphify | Graphify-Labs/graphify | The repo itself ships no SKILL.md or plugin manifest (the office's copy is office-packaged for Hermes) — it is a tool, installed separately |
| Web Interface Guidelines | vercel-labs/web-interface-guidelines | A rules document (MUST/SHOULD/NEVER lists) with no SKILL.md anywhere in the repo |
| GSD (get-shit-done) | gsd-build/get-shit-done | A command/agent system installed via its own installer; zero SKILL.md files |
| React Bits | DavidHDev/react-bits | A React component library (copy-paste components), not an agent skill; MIT + Commons Clause — components may not be resold |
| SkillUI | amaancoderx/npxskillui | A CLI design-system generator; zero SKILL.md files |

## Withheld

| Name | Repo | Why |
| --- | --- | --- |
| Archify | tt-a1i/archify | Technically wrappable (skills exist under `.agents/skills/`), but the office's security scanner returned a **dangerous** verdict on 28 Oct 2026 (agent_config_mod, encoded_exfil, oversized_file findings). Withheld from a public marketplace until the owner explicitly decides otherwise. The office uses the installed Diagram Design for the same job |
