# Sources

The upstream skills the master skill was built from. These are unmodified copies, kept for reference and credit. The master skill opens them on demand through `references/library/INDEX.md`.

Every copied skill was scanned with NVIDIA SkillSpector v2.12.0 (static mode) on 2026-11-20 and returned SAFE, 0/100 risk, no findings.

## Copied into the master skill's library (26 skills)

Location: `skills/master-ad-script-writer/references/library/`. Each skill's main file is saved as `<skill>.md` and its supporting files as `<skill>--<file>.md`.

| Folder | Upstream | Commit | Licence | Skills |
|---|---|---|---|---|
| `library/ai-ads-claude/` | https://github.com/zubair-trabzada/ai-ads-claude | d1df3f5 | MIT | ads-hooks, ads-copy, ads-creative, ads-video, ads-funnel, ads-landing, ads-testing, ads-audience, ads-strategy |
| `library/motion-creative/` | https://github.com/motion-creative/skills | 5d03170 | MIT | hook-writing, hook-tactics, hook-voice-patterns, ad-concept-generator, ugc-scriptwriter |
| `library/claude-vibes/` | https://github.com/mike-coulbourn/claude-vibes | 1f8b508 | MIT | scriptwriting-methodology, conversion-psychology, natural-writing, platform-optimization, elevator-pitch-techniques, tagline-creation-strategies, jtbd-psychographic-research |
| `library/marketingskills/` | https://github.com/coreyhaines31/marketingskills | 5b2b400 | MIT | copywriting, marketing-psychology, offers, customer-research, copy-editing |

Each folder carries the upstream LICENSE file.

## Linked, not copied (21 skills)

From https://github.com/guia-matthieu/clawfu-skills at commit 4108f5c (MIT). All 21 scanned SAFE. They are linked rather than copied because many of them quote passages from published books, which the repository's MIT licence does not cover.

Under `skills/content/`: persuasion-principles, storytelling-storybrand, cta-writing, copy-frameworks, copywriting-awareness, headline-formulas, made-to-stick, copywriting-classic, dan-kennedy-copy, boron-letters, conversion-copywriting, expert-secrets

Under `skills/strategy/`: grand-slam-offers, cognitive-biases, audience-research, buyer-personas, value-proposition-canvas

Under `skills/validation/`: objection-mapping

Under `skills/video/`: ai-video-concept

Under `skills/audio/`: voiceover-direction, video-testimonial

## Left out after scanning (3 skills)

From coreyhaines31/marketingskills:

| Skill | Scan result | Why it was left out |
|---|---|---|
| ad-creative | DO NOT INSTALL, 100/100 | Flags were on an HTML template and a tools file with unpinned install commands. On reading, the flagged lines look like false alarms (words such as "arsenic" in a sample ad), but one file could not be fully inspected, so the rule was kept. |
| ads | DO NOT INSTALL, 58/100 | Flags in media-buying reference files. Also off-topic for script writing. |
| video | SAFE, 20/100, 6 findings | Runs unpinned install commands for video tooling. Off-topic for script writing. |

## Not reviewed

The rest of the five repositories (about 220 other skills and 166 code scripts) was not scanned or copied.
