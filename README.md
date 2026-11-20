# Master Ad Script Skills

PixelCube's skill for writing advertising scripts with Claude.

## What's here

| Folder | What it is |
|---|---|
| `master-ad-script-writer/` | A universal storytelling ad script skill: strategy, story, hook, retention, trust, offer and call to action, delivered as a director-ready script. |

## What the skill does

Given a brief (product, audience, offer, platform, length), it produces:

1. A strategy snapshot
2. Five hook options with a pick
3. A timed director's script (visual, on-screen text, voiceover, sound)
4. A clean voiceover script with word count
5. Soft, medium and strong CTA variants
6. Director's notes and A/B test variants
7. A list of proof the client still needs to supply

It works for video ads, Reels, Shorts, TikTok, YouTube, TV, radio, UGC and brand films, for business or consumer audiences.

## How to use it

**In the Claude app:** add `master-ad-script-writer/SKILL.md` as a skill in your account, then ask for an ad script.

**In Claude Code:** copy the `master-ad-script-writer` folder into `~/.claude/skills/` (or a project's `.claude/skills/`).

## Rules the skill follows

It will not invent statistics, testimonials, discounts or deadlines. Missing proof is flagged as `[NEED: ...]` for the client to supply.

## Credits

Synthesised and re-expressed from five MIT-licensed skills:

- [ai-ads-claude](https://github.com/zubair-trabzada/ai-ads-claude) by Zubair Trabzada
- [clawfu-skills](https://github.com/guia-matthieu/clawfu-skills) by Guia
- [claude-vibes](https://github.com/mike-coulbourn/claude-vibes) by Mike Coulbourn
- [motion-creative/skills](https://github.com/motion-creative/skills) by Motion
- [marketingskills](https://github.com/coreyhaines31/marketingskills) by Corey Haines

The story spine follows Donald Miller's StoryBrand framework. The expert add-ons distil lessons from videos by Fraser Cottrell, Kallaway, Youri van Hofwegen and Sabri Suby.
