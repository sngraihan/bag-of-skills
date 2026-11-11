# bag-of-skills

A Claude Code marketplace of hand-picked plugins & skills, curated from
GitHub. Every repo was checked one by one: stars, license, activity, and
whether it actually installs as a plugin or skill.

**Index model:** this repo does NOT copy anyone's code. The marketplace only
points to each plugin's original repository — when someone installs, Claude
Code fetches it directly from the original author's repo. Always fresh from
upstream, and clean from a licensing standpoint.

## Usage

Add this marketplace to Claude Code:

```
/plugin marketplace add sngraihan/bag-of-skills
```

Then install any of the **66 plugins** (12 categories: engineering 16,
creative 19, video 9, productivity 6, writing 4, infrastructure 2,
security 2, research 2, SEO 2, documents 2, marketing 1, trading 1):

```
/plugin install <plugin-name>@bag-of-skills
```

```
/plugin install hypit@bag-of-skills
```

The full list — including apps, frameworks, and libraries that cannot be
installed as skills and live here as references — is in
[CATALOG.md](CATALOG.md).

## How entries work

Two kinds of entries live in `marketplace.json`:

1. **Native plugins** — repos that ship their own `.claude-plugin/plugin.json`
   (e.g. `agent-skills`, `hyperframes`, `cloudflare`).
2. **Wrapped skill folders** — repos that are plain skill collections. The
   entry points at the exact folder holding the `SKILL.md` files inside the
   upstream repo (`strict: false` + a `skills` list). Still no copied code:
   Claude Code clones the upstream repo at install time and reads the skills
   from there.

## Adding new entries

1. Make sure the candidate repo is actually a Claude Code plugin (it has
   `.claude-plugin/plugin.json` at its root) before adding it to
   `marketplace.json`.
2. Append an entry to the `plugins` array: `name`, `description`, `category`,
   and `source: {"source": "github", "repo": "owner/repo"}`.
3. If it is not a plugin (skill collection / app / framework), log it in
   `CATALOG.md` under the right category, with its install command.
4. Curation principles: popular (high stars), clear license, still active,
   one slot one function (no duplicates).

## License

The catalog and descriptions in this repo are the curator's own writing.
Every plugin or skill it points to remains under the license of its original
repository.
