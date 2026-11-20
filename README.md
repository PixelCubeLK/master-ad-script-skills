# Master Ad Script Skills

PixelCube's skill for writing advertising scripts with Claude.

## What's here

```
master-ad-script-writer/      the skill
  SKILL.md                    main instructions (works alone)
  references/
    audience-psychology.md    awareness stages, emotions, influence, objections
    story-frameworks.md       beat maps for eleven ad formats
    hooks.md                  triggers, tactic library, openers, visual hooks
    offer-and-cta.md          offer anatomy, price framing, risk reversal, CTAs
    voice-and-production.md   writing for the ear, word budgets, platforms, variants
    examples.md               two complete worked outputs
sources/                      upstream skills it was built from (reference only)
```

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

**In Claude Code:** copy the `master-ad-script-writer` folder into `~/.claude/skills/` (or a project's `.claude/skills/`). The reference files load when the skill needs them.

**In the Claude app:** add `master-ad-script-writer/SKILL.md` as a skill. The app version runs from the main file alone.

## Rules the skill follows

It will not invent statistics, testimonials, discounts or deadlines. Missing proof is flagged as `[NEED: ...]` for the client to supply.

## How it was built

- 50 script-related skills were selected from five public MIT-licensed repositories and scanned with NVIDIA SkillSpector. 47 passed; 3 were left out. See `sources/README.md`.
- Lessons were distilled from five expert videos (transcripts only).
- Everything in `master-ad-script-writer/` is re-expressed in this skill's own words.

## Credits

- [ai-ads-claude](https://github.com/zubair-trabzada/ai-ads-claude) by Zubair Trabzada
- [clawfu-skills](https://github.com/guia-matthieu/clawfu-skills) by Guia
- [claude-vibes](https://github.com/mike-coulbourn/claude-vibes) by Mike Coulbourn
- [motion-creative/skills](https://github.com/motion-creative/skills) by Motion
- [marketingskills](https://github.com/coreyhaines31/marketingskills) by Corey Haines

Frameworks referenced: StoryBrand (Donald Miller), awareness stages (Eugene Schwartz), influence principles (Robert Cialdini), Made to Stick (Chip and Dan Heath), the value equation (Alex Hormozi). Video lessons from Fraser Cottrell, Kallaway, Youri van Hofwegen and Sabri Suby.
