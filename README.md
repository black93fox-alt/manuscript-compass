# Manuscript Compass — Manuscript Review Plugin for Grok Bot

![Manuscript Compass logo](assets/logo.png)

Interactive universal manuscript review plugin. Guides authors and editors through structured editorial passes from first full draft through final publication file.

Covers:
- Core editorial principles and priority system (P0–P3)
- Stage-by-stage review (Intake → Structure → Genre → Accuracy → Line edit → Voice → Proofread → Author review → Production QA → Maintenance)
- Genre-specific checks (fiction/narrative, practical nonfiction, reference/illustrated)
- Living Strengths-to-Preserve list
- Actionable issue tracking
- Full Editorial Review Report generation

## Installation (local / testing)

Copy the plugin folder into your Grok skills or plugins directory, or install from a public GitHub repository once published.

Example (user-level skills):
```bash
cp -R skills/manuscript-review ~/.grok/skills/
```

Or place the whole plugin directory under `~/.grok/plugins/` or a marketplace source.

After installation, invoke with `/manuscript-review` or by asking the bot to review a manuscript.

## Testing Instructions

1. Install the plugin (local copy or from the public repo).
2. Start a new Grok Bot conversation.
3. Run `/manuscript-review` or say “Start a manuscript review for my nonfiction book.”
4. Provide sample baseline info when prompted (title, genre, audience, purpose, word count).
5. Confirm the bot:
   - Creates a Strengths to Preserve list
   - Walks through Stage A (Intake) interactively
   - Asks clarifying questions instead of dumping the full checklist
   - Records issues with Priority, Location, Issue, Reader impact, Recommendation
   - Can generate the Editorial Review Report template on request
6. Paste a short sample chapter or section and verify it analyzes against the relevant stage (structure, clarity, or accuracy).
7. Ask for a full report and confirm it follows the template structure.
8. Test a focused pass: “Run only the natural-voice pass on this paragraph.”

No external credentials or network services are required. The plugin is pure instructional skills.

## Submission Notes

- Organization handle: choose a unique lowercase handle with no spaces — `manuscriptcompass`.
- Logotype: provide a 1:1 SVG or PNG with a background plate.
- Description (suggested): Interactive universal manuscript review plugin. Guides authors and editors through structured editorial passes covering structure, accuracy, voice, proofreading, and production QA from first draft to publication-ready file.
- Testing instructions: paste the section above.
- Confirm you have tested locally and in-app.

Repository: https://github.com/black93fox-alt/manuscript-compass

## License

MIT
