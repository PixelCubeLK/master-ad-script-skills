# Master Ad Script Writer

PixelCube's Claude plugin for writing and validating advertising scripts.

## Skills in this plugin

| Skill | Use it to |
|---|---|
| `master-ad-script-writer` | Write any ad script: strategy, five hooks, timed director's script, clean voiceover, CTA variants, test variants. Validates its own draft before delivering. |
| `ad-script-review` | Rate and validate any script: fourteen scored checks, a first-time viewer pass, a critic pass and a risk pass, then the top five fixes. |

## What's inside

```
.claude-plugin/plugin.json
skills/
  master-ad-script-writer/
    SKILL.md
    references/
      audience-psychology.md  story-frameworks.md  hooks.md
      offer-and-cta.md  voice-and-production.md  examples.md
      library/              26 scanned source skills, opened on demand
        INDEX.md
  ad-script-review/
    SKILL.md
SOURCES.md                  where everything came from, and the scan report
```

## Install

**Claude app:** download `master-ad-script-writer.plugin` from this repo, then add it as a plugin.

**Claude Code:** clone this repo and add it as a plugin, or copy the two folders under `skills/` into `~/.claude/skills/`.

**Build the plugin file:**

```
zip -r master-ad-script-writer.plugin .claude-plugin skills README.md SOURCES.md
```

## Rules the skills follow

They will not invent statistics, testimonials, discounts or deadlines. Missing proof is flagged as `[NEED: ...]`. No script is scored 10/10 while proof is unconfirmed.

## Credits

Built from five MIT-licensed repositories (ai-ads-claude, clawfu-skills, claude-vibes, motion-creative/skills, marketingskills) and lessons from videos by Fraser Cottrell, Kallaway, Youri van Hofwegen and Sabri Suby. Frameworks referenced: StoryBrand, Schwartz awareness stages, Cialdini's influence principles, Made to Stick, the value equation. Full detail in `SOURCES.md`.
