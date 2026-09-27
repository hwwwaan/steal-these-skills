# steal-these-skills 🥷

**Four AI skills for college students. Go ahead — steal them.**

Made by two Korean college students at *Shoocream Village* (슈크림마을). The skills are written in Korean
and work in Notion AI, Claude (web, app and Claude Code), ChatGPT projects, Codex, Cursor and Gemini CLI.

![Before and after using the skills](assets/before-after.png)

| Skill | What it does |
|---|---|
| [STAR Card](skills/star-card/) | Turns club, part-time and team-project experiences into reusable STAR cards for résumés |
| [Cram Plan](skills/cram-plan/) | Builds a realistic day-by-day exam study plan from the time you actually have |
| [Lunch Pick](skills/lunch-pick/) | Picks exactly one lunch menu based on what you ate yesterday and today's budget |
| [Polite Rewrite](skills/polite-rewrite/) | Rewrites an angry message into one you can actually send, without dropping your point |

## Each skill says what it won't do

Most AI helpers go wrong on scope, so every skill states its limits as plainly as its job.

- **STAR Card** won't write your cover letter. It stops at structuring the experience
- **Cram Plan** won't hide missing hours. If the time isn't enough, the plan says so
- **Lunch Pick** won't search restaurants or prices. It picks one menu, that's all
- **Polite Rewrite** won't add deadlines, apologies or promises that weren't in your message

## Install

**Claude Code · Codex · Cursor · Gemini CLI**

```bash
npx skills add hwwwaan/steal-these-skills
```

Add `--skill cram-plan` (or `star-card`, `lunch-pick`, `polite-rewrite`) to install just one.

**Claude Code plugin**

```
/plugin marketplace add hwwwaan/steal-these-skills
/plugin install steal-these-skills@shoocream
```

**Claude (web / app)** — download a skill ZIP from the [latest release](https://github.com/hwwwaan/steal-these-skills/releases/latest)
and upload it in [Customize → Skills](https://claude.ai/customize/skills) → **+** → **Create skill** → **Upload a skill**.

**Notion AI** — duplicate the [Notion template](https://pretty-cement-6c1.notion.site/3e84605a116d8055973edf4fdb40aa86),
then `···` → *Use with AI* → *Use as AI skill*.

**ChatGPT / Claude projects** — upload the skill's `SKILL.md` and tell the project to follow it.

## License

[MIT](LICENSE)
