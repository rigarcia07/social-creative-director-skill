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

- ---

### Example: LinkedIn post

#### Input (LinkedIn)

> Use the Social Creative Director skill to create a LinkedIn post and visual concept promoting my AI workflow audit service.  
> Audience: founders and ops leaders at service businesses (agencies, studios, consultancies).  
> Offer: free 30‑minute audit.  
> Tone: expert, calm, no hype.

#### Output (excerpt)

**Strategy Snapshot**

- Objective: Start DM conversations that lead to audit bookings.
- Platform: LinkedIn
- Format: Single image post
- Tone: Expert, practical, slightly contrarian
- Core message: “Your team doesn’t need more hours, it needs fewer manual workflows.”

**Graphic Direction**

- Asset: 1200×627 LinkedIn image.
- Layout: Split layout — left 60% text, right 40% simple visual.
- Headline block: “Your ‘busy’ team might just have a workflow problem.”
- Right side: Minimal flow diagram showing manual steps vs automated steps.
- Colors: Muted neutral background, one bold accent for key words and connectors.

**On‑Graphic Copy**

- Headline: “Your ‘busy’ team might just have a workflow problem.”
- Subline: “Map, automate, and give them 10 hours back.”
- CTA: “Free 30‑min AI workflow audit”

**Caption**

> Most teams don’t have a capacity problem.  
>  
> They have a workflow problem:  
> - 4 tools that don’t talk to each other  
> - Status checks that should be dashboards  
> - Reports built from copy‑paste  
>  
> I run 30‑minute AI workflow audits to:  
> - Map where time is being burned  
> - Identify 2–3 processes that should be automated first  
> - Outline a realistic automation roadmap (no “rip everything out” required)  
>  
> Comment “AUDIT” or DM me “audit” and I’ll send over the details and booking link.

**Posting notes**

- Use a short, text-based first line that stands on its own in the feed.
- Encourage comments/DMs, not just link clicks.
- Re-share from personal profile to company page with a shorter caption.

---

### Example: X (Twitter) post

#### Input (X)

> Use the Social Creative Director skill to create an X post and visual concept announcing a new analytics feature in my SaaS.  
> Audience: product managers and founders using spreadsheet-based reporting.  
> Tone: sharp, confident, no fluff.

#### Output (excerpt)

**Strategy Snapshot**

- Objective: Drive curiosity and clicks to the feature page.
- Platform: X
- Format: Single image + short post
- Tone: Direct, slightly provocative
- Core message: “Stop building dashboards by hand.”

**Graphic Direction**

- Asset: 1600×900 image.
- Layout: Dark background, bright data panel in center.
- Visual: Before/after — left side messy spreadsheet snapshot, right side clean auto-updating chart.
- Text: One clear headline, no more than 6–7 words.

**On‑Graphic Copy**

- Headline: “Stop building dashboards by hand.”
- Subline (optional): “Your product metrics should update themselves.”

**Post copy**

> If you still rebuild the same product dashboard every week… you don’t have a “data” problem.  
>  
> You have a workflow problem.  
>  
> Our new **Auto Boards** feature plugs into your existing stack and keeps your key metrics live without spreadsheets.  
>  
> 👇 See it in action

(Include link preview.)

**Posting notes**

- Keep the text to a few short paragraphs for scannability.
- Use 0–2 relevant hashtags; avoid hashtag stuffing.
- Pin this post for launch week.

---

### Example: TikTok / Reels

#### Input (Reels / TikTok)

> Use the Social Creative Director skill to create a short-form video concept, overlay text, and caption for a Reel promoting my AI workflow audit service.  
> Audience: solo and small-team service providers.  
> Tone: conversational, grounded, no “guru” energy.

#### Output (excerpt)

**Strategy Snapshot**

- Objective: Get viewers to DM or click through to book an audit.
- Platform: Instagram Reels / TikTok
- Format: 20–30 second talking-head + simple b-roll
- Tone: Friendly, “builder in the trenches”, practical
- Core message: “You’re losing whole days to tasks you shouldn’t be touching.”

**Video concept**

- Hook shot: You at a desk, staring at a messy calendar or overflowing inbox.
- Beat 1 (0–3s): Pattern interrupt — quick zoom + overlay text.
- Beat 2 (3–10s): Call out the 2–3 biggest time leaks.
- Beat 3 (10–20s): Show the “after” state with short examples of automation.
- Beat 4 (20–30s): Clear CTA to book the audit.

**On‑screen text**

- Frame 1: “If your week looks like THIS…”
- Frame 2: “You don’t need more hours.”  
- Frame 3: “You need fewer manual workflows.”
- Frame 4: “Free 30‑min AI workflow audit → link in bio”

**Script outline (spoken)**

- Hook: “If you’re working late every week just to keep up, this is for you.”
- Pain: Briefly describe common manual tasks (reporting, intake, follow-ups).
- Shift: “Most of this can be automated with simple AI workflows.”
- Offer: “I run 30‑minute audits to map where your time is leaking and what to automate first.”
- CTA: “Tap the link in my bio and book an audit. Let’s win you back 10+ hours a month.”

**Caption**

> You don’t need another productivity hack.  
>  
> You need fewer manual workflows.  
>  
> In a 30‑minute AI workflow audit, I’ll:  
> - Map where your time is actually going  
> - Show you what to automate first  
> - Give you a simple plan you can execute  
>  
> Tap the link in my bio and book “Workflow Audit” in my calendar.

**Posting notes**

- Use a clear cover frame with the “If your week looks like THIS…” text.
- Add 3–5 relevant hashtags (e.g., `#smallbusiness`, `#automation`, `#solopreneur`).
- Keep cuts fast; remove dead time and long pauses.

---

## Installation in Claude

There are two common ways to install this skill, depending on how you use Claude.

### Option 1 – Upload as a custom Skill (Claude app / desktop)

1. Zip this skill folder so the archive contains:
   - `social-creative-director/`
     - `SKILL.md`
2. In Claude, go to **Customize → Skills** (or **Settings → Capabilities → Skills**, depending on your UI).
3. Click the **+** button, then choose **Create skill** → **Upload a skill**.
4. Select the ZIP file you created and upload it.
5. Once it appears in your Skills list, toggle **Social Creative Director** **on** so Claude can use it in chats. [web:20][web:38]

After that, you can either:
- Call it explicitly in your prompt (e.g., “Use the Social Creative Director skill to…”), or
- Just describe the task and let Claude load it automatically when relevant. [web:2][web:20]

### Option 2 – Install manually for Claude Code (local skills folder)

If you’re using Claude Code with local skills support:

1. Clone or download this repository.
2. Copy the `social-creative-director` folder into your skills directory, e.g.:

   ```bash
   mkdir -p ~/.claude/skills
   cp -r social-creative-director ~/.claude/skills/
   ```

   By convention, Claude looks for skills in `~/.claude/skills/` (for personal skills) or in a `.claude/skills/` folder at the project root. [web:17][web:199]

3. Restart or reload Claude Code so it picks up new skills.
4. In Claude Code, mention the skill by name or use whatever slash-command / invocation style your environment supports.

Once installed either way, the skill behaves like any other Claude Skill: you can toggle it in your Skills list, and Claude will follow its `SKILL.md` instructions whenever you ask for social post creative. [web:17][web:20]

---

## License

This repository is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for details.
