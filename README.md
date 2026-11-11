# bag-of-skills — A Personal Curation Marketplace

A Claude Code marketplace of hand-picked plugins & skills, curated from GitHub
(starting from a personal notes list, then reviewed one by one: stars, license,
activity, and usefulness).

**Index model:** this repo does NOT copy anyone's code. The marketplace only
points to each plugin's original repository — when someone installs, Claude
Code fetches it directly from the original author's repo. Always fresh from
upstream, and clean from a licensing standpoint.

## Usage

Add this marketplace to Claude Code:

```
/plugin marketplace add <your-github-username>/bag-of-skills
```

The marketplace currently holds **66 plugins** in 12 categories:
engineering (16), creative (19), video (9), productivity (6), writing (4),
infrastructure (2), security (2), research (2), SEO (2), documents (2),
marketing (1), trading (1). It merges two curation sources: the curator's
personal notes list, and the office repo catalog
(kantor.raihann.me/katalog), whose 57 evaluated repos were each probed for
plugin/skill installability before inclusion.

Install any of them the same way:

```
/plugin install <plugin-name>@bag-of-skills
```

```
/plugin install hypit@bag-of-skills
```

Two kinds of entries live in `marketplace.json`:

1. **Native plugins** — repos that ship their own `.claude-plugin/plugin.json`
   (e.g. `agent-skills`, `hyperframes`, `cloudflare`).
2. **Wrapped skill folders** — repos that are plain skill collections. The
   entry points at the exact folder holding the `SKILL.md` files inside the
   upstream repo (`strict: false` + a `skills` list). Still no copied code:
   Claude Code clones the upstream repo at install time and reads the skills
   from there.

Entries that are **apps, frameworks, or libraries** (Remotion the framework,
OpenCut, NautilusTrader, FreeLLMAPI, and friends) cannot be installed as
skills at all — they are reference entries in [CATALOG.md](CATALOG.md) with
their own usage notes.

## Public or private?

- **Public:** anyone can `marketplace add` this repo and install the curated
  picks. What they install still comes from the original authors' repos.
- **Private:** only you (signed in to the GitHub account that owns the repo)
  can add it. Good for a purely personal collection across your own
  machines/profiles.

You can start private and flip the repo to public anytime in GitHub Settings.

## Adding new entries

1. Make sure the candidate repo is actually a Claude Code plugin (it has
   `.claude-plugin/plugin.json` at its root) before adding it to
   `marketplace.json`.
2. Append an entry to the `plugins` array: `name`, `description`, `category`,
   and `source: {"source": "github", "repo": "owner/repo"}`.
3. If it is not a plugin (skill collection / app / framework), log it in
   `CATALOG.md` under the right category, with its install command.
4. Curation principles: popular (high stars), clear license, still active,
   one slot one owner (no duplicate functions).

## License

The catalog and descriptions in this repo belong to the curator. Every plugin
or skill it points to remains under the license of its original repository.
