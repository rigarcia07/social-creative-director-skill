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

## License

This repository is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for details.
