# Social Creative Director (Claude Skill)

A Claude **Agent Skill** that behaves like a senior creative director, brand designer, copywriter, and social media strategist in one.

This skill takes a short brief and turns it into **agency-quality social media creative**: visual direction, on-graphic copy, captions, CTA options, and platform-specific posting notes.

---

## What this skill does

When active, `Social Creative Director`:

- Clarifies objective, audience, offer, platform, and tone.
- Generates several creative angles and recommends the strongest one.
- Produces **graphic direction** a designer can execute (layout, hierarchy, color, type, imagery).
- Writes **on-graphic copy** (headline, subhead, CTA text).
- Writes **platform-native captions** with alternate hooks and CTAs.
- Adds **posting guidance** (format, aspect ratio hints, hashtags where relevant).

The goal is to get as close as possible to *“ready to brief a designer and hit publish”* from a single prompt.

---

## Platforms optimized

The skill adapts copy and creative to each platform instead of reusing the same caption everywhere:

- **Instagram** – visual-first, strong first line, concise text on the graphic.
- **LinkedIn** – insight-led, credibility-focused, slightly longer narrative.
- **X** – short, punchy, no fluff, clear point of view.
- **Facebook** – accessible, benefit-led, community-friendly.
- **TikTok / Reels** – fast hook, conversational tone, low on-screen text density.

---

## Typical use cases

Use this skill when you want to:

- Turn a campaign idea into a finished social post package.
- Get multiple high-quality angles for a single offer.
- Standardize how you brief designers and content editors.
- Build a repeatable “social post generation” workflow in Claude.

Not ideal for:

- Long-form blog posts or newsletters.
- Full-funnel media planning.
- Heavy analytics or reporting.

---

## Files

- `SKILL.md` – the full Agent Skill definition (frontmatter + instructions).
- `README.md` – this file.
- `LICENSE` – MIT license for the contents of this repository.

---

## How to use with Claude

1. **Create / open** a Claude environment that supports custom Agent Skills.
2. Create a new skill and point it to this `SKILL.md` (or upload the folder/ZIP if supported).
3. Enable the `Social Creative Director` skill for chats where you want social content help.
4. Prompt Claude with a clear brief, for example:

   > Create an Instagram carousel concept and caption for my AI workflow audit service.  
   > Audience: small business owners. Tone: confident, practical, not hypey.

Claude should respond with:

- Strategy snapshot
- Creative angles
- Final creative concept
- Graphic direction
- On-graphic copy
- Caption + alternates
- Posting notes
- At least one alternate variation

---

## Example prompts

- “Use Social Creative Director to design a LinkedIn post and graphic for a premium automation consulting offer.”
- “Create an X post and visual concept announcing a new analytics feature for my SaaS.”
- “Give me an Instagram Reel concept, overlay text, and caption for a local restaurant’s weekday lunch special.”

---

## Example SKILL usage

### Input

> Use the **Social Creative Director** skill to create an Instagram carousel concept and caption for my AI workflow audit service.  
> Audience: small business owners who are overwhelmed by manual processes.  
> Offer: free 30‑minute workflow audit.  
> Tone: confident, practical, not hypey.

### Output (excerpt)

**A. Strategy Snapshot**

- Objective: Generate qualified leads for AI workflow audits.
- Audience: Owners of 5–50 person businesses drowning in manual admin.
- Platform: Instagram
- Format: 5–7 slide carousel
- Tone: Direct, calm, experienced guide
- Core message: “You’re leaving hours on the table every week.”
- Desired action: Tap link in bio to book a free audit.

**B. Final Creative Concept**

- Big idea: “Where your week actually goes.”
- Driver: Show the hidden cost of manual workflows in a visual, concrete way.
- Why it works: Uses curiosity and recognition (“this is my life”) to earn the right to pitch the audit.

**C. Graphic Direction**

- Asset: 1080×1350 carousel.
- Slide 1: Bold headline top-left (“Where your week actually goes”), simple bar-style visual showing time lost to manual tasks, brand mark bottom-right.
- Slides 2–4: One pain point per slide with icon, short label, and % of week lost.
- Slide 5–6: “After” state with cleaner layout and fewer blocks of time.
- Final slide: Strong CTA panel with headline, short subcopy, URL/handle, and simple button-style shape.

**D. On‑Graphic Copy (examples)**

- Slide 1 headline: “Where your week actually goes”
- Pain slide headline: “Manual reporting – 8 hours”  
- Final slide headline: “Win back 10+ hours this month”
- CTA text: “Book your free workflow audit”

**E. Caption (Instagram)**

> You’re not “too busy for systems” — you’re busy *because* of them.  
>  
> Most small teams lose 10–15 hours every week to manual reporting, copy‑pasting between tools, and chasing status updates.  
>  
> I run 30‑minute AI workflow audits to map where your time is leaking and show you what to automate first.  
>  
> Comment “AUDIT” or hit the link in bio and I’ll send the details.

- Alternate hooks:
  - “If your Monday starts in spreadsheets, this is for you.”
  - “How many hours did you copy‑paste last week?”
- Alternate CTAs:
  - “DM me ‘AUDIT’ and I’ll send the booking link.”
  - “Save this and share it with the one person on your team who does *everything* manually.”

**F. Posting notes**

- Best as weekday daytime post when your audience is in “work mode.”
- Use a clean thumbnail for slide 1 with strong headline and no tiny text.
- Keep colors simple: 1 accent + neutrals so the numbers are easy to read.

---

## License

This repository is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for details.
