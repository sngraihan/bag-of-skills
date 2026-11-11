# bag-of-skills

A Claude Code marketplace of plugins & skills, grouped by category.

**Index model:** this repo does NOT copy anyone's code. The marketplace only
points to each plugin's original repository — installs fetch directly from
the original author's repo, always fresh from upstream.

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

The full list by category — including apps, frameworks, and libraries that
cannot be installed as skills and live here as references — is in
[CATALOG.md](CATALOG.md).

Two kinds of entries live in `marketplace.json`: **native plugins** (repos
that ship their own `.claude-plugin/plugin.json`) and **wrapped skill
folders** (the entry points at the exact folder holding the `SKILL.md`
files inside the upstream repo, via `strict: false` + a `skills` list).

## License

The catalog and descriptions in this repo are the curator's own writing.
Every plugin or skill it points to remains under the license of its original
repository.
