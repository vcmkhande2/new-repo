---
name: consulting-slides
description: "Build, review and fix consulting-style slides — the MBB conventions for action titles, chart choice, labelling and sourcing. Use whenever the user asks for a deck, a slide, an exhibit, a chart for a presentation, or asks you to review or tidy an existing deck. Works on its own, and works with the Riplo Slides connector when one is installed."
---

# Consulting slides

Most AI-generated slides fail for the same three reasons: the title says the
topic instead of the conclusion, the chart does not match the comparison being
made, and nobody can tell where a number came from. This skill fixes those.

Apply it whenever you are producing or reviewing slides. If a Riplo Slides
connector is available, build the deck there so the charts stay native and
editable. If not, these rules still apply to whatever tool you are using.

---

## Step 1 — Get the brief before you make a slide

Never start from "make me a deck about X". Establish three things first, and
ask the user if any are missing:

1. **Who reads it.** A board, an investment committee, a client working team
   and an internal review each want a different level of detail.
2. **What they must decide.** A deck exists to move a decision. Write the
   decision down in one sentence.
3. **What evidence exists.** Which files, models or notes you may draw on. If
   there are none, say so rather than inventing figures.

Then write the **storyline**: the list of slide titles, in order, before any
slide exists. Read them top to bottom. They should make the argument on their
own, without the charts underneath. Get the user to approve the storyline
before you build anything.

---

## Step 2 — The rules

### Titles

1. **Every slide gets an action title.** The title states the conclusion, not
   the topic. "Revenue grew 23% on volume, not price" — not "Revenue
   analysis". If you cannot write a conclusion, you do not yet know what the
   slide is for.
2. **One idea per slide.** If the title needs an "and", you have two slides.
3. **Put a number in the title when you have one.** Specific beats vague.
   "Churn doubled in the SMB cohort" is weaker than "SMB churn doubled to 14%".
4. **The title must be true of the exhibit below it.** Before finishing a
   slide, read the figure in the title back off the chart data. If they
   disagree, the title is wrong, not the chart.

### Charts

5. **Pick the comparison first, then the chart.** Change over time → line or
   column. Contribution to a change → waterfall/bridge. Part of a whole →
   stacked bar, almost never a pie. Two dimensions at once → Mekko. Ranking →
   horizontal bar, sorted.
6. **The chart title sits above the chart,** and it is a sentence, not a
   label. The axis labels carry the "what"; the title carries the "so what".
7. **Label the data, drop the furniture.** Direct data labels beat a legend.
   Remove gridlines, chart borders, and any axis a reader does not need.
8. **Never start a bar chart's axis above zero.** Truncating the axis to make
   a difference look bigger is the fastest way to lose a room.
9. **Sort by value, not alphabetically,** unless the category order carries
   meaning (months, stages of a funnel).

### Numbers and sources

10. **Every figure traces to a file.** Keep the source, the date and the units
    beside the data. Put the source in a footnote on the slide.
11. **Never invent a number to complete a series.** A gap in the data is a
    finding. Show the gap.
12. **Label anything you inferred as an estimate** on the slide itself, not
    only in your message to the user.
13. **Keep units and periods consistent** from the title through the axis to
    the footnote. FY vs CY and £m vs £k mismatches are the most common error
    in a draft deck.

### Text and layout

14. **Two levels of text, maximum** — the action title and the body. A title,
    a subtitle, a kicker, a bullet and a sub-bullet is four levels and reads
    as clutter.
15. **No ALL CAPS.** Not for titles, not for labels, not for emphasis. Use
    weight or colour.
16. **Six bullets maximum, one line each.** A bullet that wraps to three lines
    is a paragraph wearing a bullet.
17. **Align to a grid and keep it.** Consistent margins and a consistent
    left edge across slides do more for perceived quality than any graphic.
18. **One accent colour, used sparingly.** Colour should mean something —
    the series being discussed, the number that matters. Decorative colour
    reads as a template, not an argument.

---

## Step 3 — Review before you hand it over

Run this pass on every deck, including ones you did not build:

- **Read the titles alone.** Do they tell the story in order? Is there a
  slide whose title does not advance the argument? Cut it.
- **Check each title against its exhibit.** Read the claimed figure off the
  underlying data.
- **Check every number has a source** on the slide.
- **Check units and periods** match from title to footnote.
- **Count the text levels** on the busiest slide. More than two, flatten it.
- **Say what you could not verify.** List it for the user rather than
  quietly leaving it in.

Report the review as a list of specific fixes, each naming the slide. Do not
make silent corrections to someone else's deck.

---

## Working with Riplo Slides

If the Riplo Slides connector is installed, build there rather than
generating a file. You get:

- charts that stay native and editable after a PowerPoint export
- the user's own firm template applied as each slide is built
- a per-slide version history, so the user can see what you changed

Ask the user which template to use before you start. If they have not set one
up, build on their default and tell them the deck is not yet in their house
style.
