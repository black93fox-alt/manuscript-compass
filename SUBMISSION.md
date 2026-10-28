# Manuscript Compass — marketplace form values
(x.ai/bot/marketplace/submit-a-plugin — Keith submits himself)

- **Organization name:** Manuscript Compass
- **Organization handle:** manuscriptcompass
- **Website URL:** https://github.com/black93fox-alt
- **Logotype:** /workspace/manuscript-compass/assets/logo.png (1024x1024 PNG, solid navy plate); SVG: assets/logo.svg
- **MCP server URL or public GitHub repository:** https://github.com/black93fox-alt/manuscript-compass

## Plugin description
Interactive universal manuscript review plugin. Guides authors and editors through structured editorial passes covering structure, accuracy, voice, proofreading, and production QA from first draft to publication-ready file.

## Testing instructions
1. Install the plugin from the public repo (https://github.com/black93fox-alt/manuscript-compass).
2. Start a new Grok Bot conversation.
3. Run `/manuscript-review` or say "Start a manuscript review for my nonfiction book."
4. Provide sample baseline info when prompted (title, genre, audience, purpose, word count).
5. Confirm the bot: creates a Strengths to Preserve list; walks through Stage A (Intake) interactively; asks clarifying questions instead of dumping the full checklist; records issues with Priority, Location, Issue, Reader impact, Recommendation; can generate the Editorial Review Report on request.
6. Paste a short sample chapter or section and verify it analyzes it against the relevant stage (structure, clarity, or accuracy).
7. Ask for a full report and confirm it follows the template structure (`/manuscript-review-report`).
8. Test a focused pass: "Run only the natural-voice pass on this paragraph."

No external credentials or network services are required. The plugin is pure instructional skills.
