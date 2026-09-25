# ax-skills

Skills that help Claude with digital accessibility (AX) work, built by Carmen Krol.

A skill is a set of instructions Claude loads when a task calls for it. These skills turn the research and judgment I use in accessibility work into something Claude can apply consistently, and that other people can reuse.

## Skills

| Skill | What it does |
| --- | --- |
| [ax-link-library](plugins/ax-link-library) | Searches my curated library of 160+ accessibility resources (articles, standards, tools and lived-experience stories). Each link has my own comments plus a summary of the page, and Claude answers questions from it with citations. |

## Installing

### Claude Code

Add this repo as a plugin marketplace, then install the skill you want:

```
/plugin marketplace add carmenvkrol/ax-skills
/plugin install ax-link-library@ax-skills
```

When I update a skill, `/plugin marketplace update ax-skills` pulls the new version.

### Claude apps (desktop, web)

1. Download the skill's folder, for example `plugins/ax-link-library/skills/ax-link-library`, and zip it. The zip should contain the `ax-link-library` folder with `SKILL.md` inside.
2. In Claude, open Settings and upload the zip in the Skills section.

### Copying by hand

Copy the skill folder (the one containing `SKILL.md`) into `~/.claude/skills/`.

## Repo layout

```
ax-skills/
├── .claude-plugin/marketplace.json   the list of skills in this repo
└── plugins/
    └── <skill-name>/
        ├── .claude-plugin/plugin.json
        ├── skills/<skill-name>/SKILL.md
        └── README.md
```

To add a skill: create its folder under `plugins/` following the layout above, add an entry to the `plugins` list in `.claude-plugin/marketplace.json`, and add a row to the table above.
