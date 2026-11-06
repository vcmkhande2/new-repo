# The consulting slides skill

A Claude skill that teaches Claude how consultants actually build slides:
action titles, the right chart for the comparison, labelled sources, and a
review pass that checks the title against the exhibit.

Free to use and modify. No sign-up, no email.

## What is in here

```
consulting-slides/
  SKILL.md                      the skill itself — 18 rules, plus a review pass
  references/chart-picker.md    which chart for which comparison
  references/deck-skeletons.md  storyline starting points for six deck types
```

## Install it

**Claude web and desktop**

1. Go to Settings → Capabilities → Skills.
2. Choose "Upload skill" and select the `consulting-slides` folder (or the
   zip, without unpacking it).
3. Start a new chat. Claude will use the skill whenever you ask for slides.

**Claude Code**

Copy the folder into your skills directory:

```bash
cp -r consulting-slides ~/.claude/skills/
```

Then run `/skills` to confirm it is loaded.

## Use it

Ask for a deck the way you would ask a colleague:

> I need a board paper on why Q3 missed plan. The data is in the attached
> model. The board decides on the revised forecast on the 14th.

Claude will agree the storyline with you before it builds anything.

## Make the slides editable

On its own, this skill improves what Claude writes. Connect the **Riplo
Slides** connector and Claude builds the deck directly in your firm's
template, with charts that stay native and editable after a PowerPoint
export.

Add `https://os.riplo.ai/api/mcp/slides` as a custom connector in Claude,
then sign in with your Riplo account. Setup steps for web, desktop and
Claude Code: https://slides.riplo.ai/faq#mcp
