# Daniel Iles' case-study presentations: a step-by-step guide

I went through all 11 cases, reading each transcript alongside its screenshots (32 frames in total).

Colors, positions and type sizes below were measured from the frames, not guessed. Video compression blurs things slightly, so treat the numbers as close approximations.

Three things in the screenshots are not part of his design: the "www.viralcoach.com – to exit full screen" banner, the player controls, and the small scrub-preview thumbnail in the bottom-right corner.

---

## Part 1: The thesis

> **Daniel doesn't make slides.** Each presentation is a single plain, pageless Google Doc. He scrolls through it on screen while delivering a spoken case study of about 2 minutes.
>
> The doc compresses the script into four layers, top to bottom, in the same order he speaks them:
> 1. **Who:** `First name - Profession`
> 2. **Result:** a one-line headline with the gains in green, then a "Results:" list of plain numbers
> 3. **Proof:** real screenshots only:
>    - before/after video thumbnails showing their view counts
>    - rows of the best-performing videos
>    - profile, analytics or Slack screenshots with red marks on the key number
> 4. **How:** "What we did", which is always exactly three lines in the form `Label: Problem → Solution`, with the outcome in green
>
> He scrolls down once per beat of the script and points at numbers with the mouse cursor. Color is the only design:
> - **green** = what the client gained
> - **black** = context
> - **dark gray** = a section heading
> - **red** = look here
>
> Everything else is deliberately absent: no slides, no logo, no call-to-action slide, no animation.

**Rules that hold in all 11 cases:**
1. One continuous doc, scrolled downward only. Each video uses 2–5 screens.
2. The first screen is always the title, the green headline, the "Results:" bullets and a row of images.
3. A "What we did" section has exactly 3 items in the form `Label: before → after`. The outcome is green in 10 of 11.
4. All proof is real platform screenshots. Thumbnails keep their own view counts.
5. The Results bullets are never colored. The headline always is.
6. The doc has no CTA, logo, slide numbers or decoration. The CTA is spoken over the last screen.

**Tie-breaker for anything this guide doesn't cover:** ask what the smallest piece of real evidence is that makes the sentence being spoken *right now* believable at a glance. Put that on screen, in script order, and color only the gain green.

**Terms used below:**
- **Screen:** what's visible in the doc at one scroll position, about 30 lines of 12pt text. Every section is built to fit on one screen, with a text block on top and an image row below.
- **Image row:** one horizontal row (or a 2-row grid) of screenshots under a text block.
- **Thumbnail (tile):** a 9:16 screenshot of one video's cover as it appears in the client's TikTok or Instagram grid, including the platform's own view counter.
- **Top performer:** a video posted after the work started, ranked by views.
- **Pillar:** one tactic Daniel introduces with "First / Second / Third, we…".
- **Mechanism vs. outcome:** the mechanism is what was done (black). The outcome is the result the client cares about: views, time, leads or sales (green).
- **Connector:** the joining words in a headline: "&", "in", "in just", "in less than", "with", "From", "to", "→".

---

## Part 2: The physical format

### 2.1 The document
- **Tool:** Google Docs in pageless mode, on a white canvas. The evidence:
  - Google Docs' default color palette
  - the "→" that Docs creates automatically when you type "->"
  - "●" bullets and numbered lists with hanging indents
  - other viewers' Docs cursors visible in the Daryoosh and Dr. Richard frames
- **Font:** Arial throughout. Greg's title uses a different bold font; that's a one-off, so ignore it.
- **Line length:** about 90 characters of 12pt text per line.
- **Alignment:** everything left-aligned. There are no headers, footers or design elements.
- **Length:** the doc ends right after the last image. Expect 2–5 screens of content.

### 2.2 The video layout
Positions are percentages of the visible frame, with equivalents for a 1920×1080 frame.

| Layer | Spec |
|---|---|
| Background | Near-black, with a faint pattern of gray dots forming soft diagonal waves (strongest along the top) |
| Doc panel | White rounded rectangle.<br>• Left edge at 22% (≈428 px), top at 7.4% (≈80 px), bottom at 97% (≈1050 px).<br>• Runs to the right edge of the frame; only its top-right corner curve shows.<br>• Corner radius about 2.3% of frame width (≈44 px), with a soft shadow.<br>• Over the bottom ~8–10% the content fades to white, which tells the viewer there's more below. |
| Camera box | Rounded rectangle layered on top of the doc panel.<br>• Starts at the left frame edge (its left side is cut off) and ends at 31% (≈600 px).<br>• Top at 14% (≈151 px), bottom at 91% (≈978 px), so it's portrait, roughly 2:3.<br>• Same corner radius as the panel; casts a soft shadow onto it. |
| Clear zone | The camera box covers the panel's first ~9% of frame width, so the doc text must start at about 37% of frame width (≈715 px). It runs to about 92%. |
| Presenter | Framed from the chest up in front of a dark ribbed acoustic panel. A black broadcast microphone (SM7B-style) sits in the lower center of the box. Neutral cream overshirt over a white tee. Talks to the lens and uses his hands. |
| Pointer | The mouse cursor is visible. He parks it next to whichever number he's saying. |
| Absent | Captions, name banners, logo or watermark, zooms, cut transitions |

---

## Part 3: Step 1 — Break down the transcript

### 3.1 The structure of the script
Daniel's scripts follow the same 10 beats in almost every case:

| # | Beat | How it typically opens | Extract | Where it goes in the doc |
|---|---|---|---|---|
| 1 | Hook | "Here's how we took/helped our client [Name]…" (10/11)<br>"Before coming to us, our client…" (1/11) | Name, starting state, 1–3 headline metrics, time frame | Title, Headline |
| 2 | Who + before | "So [Name] is a…", "When [Name] came to us…", "Before working with us…" | Profession; credibility; old content style; old numbers (followers, views per video, posts, hours, ad spend) | Title, left side of Results arrows, Before images, Before side of the items |
| 3 | Now | "But now he has…", "Now [Name] has…", "Since working with us…" | Followers (per platform or "across platforms"), total views, monthly views, leads, revenue, hires, ad spend replaced, status | Results bullets, Proof section |
| 4 | Transition | "So here's (exactly) how we…", "the exact strategy…", "the full strategy and breakdown…" | — | Scroll to "What we did" |
| 5–7 | Three pillars | "First…" / "Second" or "Next…" / "Third", "And lastly", "And finally" or "And then…" | Tactic, the problem it fixed, how it was done, the resulting number | The 3 items |
| 8 | Payoff | "And now [Name] has a system / is fully independent / dominates her niche", "he trusted us…" | The new state | NOW section (only if it runs 2+ sentences) |
| 9 | Scale | "We do this for hundreds of business owners every single day…" | — | Nothing |
| 10 | CTA | "Click the link down below (and) see if you qualify / to apply" | — | Nothing: stay on the last screen |

### 3.2 What to pull out of the transcript
Fill these in before building anything:

- **F1. Display name:** the client's first name, spelled correctly ("Dr. " + first name for doctors).
- **F2. Profession:** the most specific credible label for what they do.
- **F3 and F4. Before and after numbers:** followers, views per post, monthly views, posting volume, hours per month, ad spend, revenue source.
- **F5. Time frame**, plus any speed words used in the hook ("in just", "less than", "first 30 days").
- **F6. Old content style:** what their content looked like before, and the worst typical old video with its view count.
- **F7. New videos:** the biggest new hit with its views, and the top 3–8 new videos ranked by views.
- **F8. The three pillars:** for each, the tactic, the problem it fixed, how it was done, and the outcome.
- **F9. Business result:** leads, sales, hires, return on ad spend (ROAS), ad spend replaced.
- **F10. Status claim:** a ranking, "most followed", "leader in her niche".
- **F11. Proof on hand:** profile screenshots per platform, analytics report, Slack updates, ranking widget, ad dashboard.
- **F12. Closing-state sentences** from the payoff beat.

**Clean-up rules:**
- Correct transcription errors before using anything. Real examples from these transcripts:
  - "Chelsea" is Chelcie, "Caven/Kevin" is Kavin, and "Jared" is Jered.
  - "Ants Bend" and "Addspin" both mean ad spend.
  - "office plates" means "off his plate".
  - "His every ticker client" means "Here's how we took our client".
- The doc carries the precise numbers from analytics; the spoken script rounds them. For example, 6.21M impressions became "6.2 million", and +289% engagement became "290%".
- If the doc and the script disagree, the proof screenshot wins.

---

## Part 4: Step 2 — Build the doc, section by section

**Notation used below:**
- `**text**` = bold black
- `{G: text}` = bold dark green #38761D
- `{g: text}` = bold light green #6AA84F
- `{GRAY: text}` = bold dark gray #434343
- `__text__` = underlined
- `[IMG …]` = an image

**Order of sections:**
1. **A. Opening screen** (required)
2. **B. Stacked before/after section** (optional)
3. **C. Proof section** (optional)
4. **D. "What we did"** (required)
5. **E. Success grid** (optional)
6. **F. "NOW:" section** (optional)

This matches the script order: hook → before → now → how → payoff.

### A. Opening screen

**A1. Title**
- Template: `{Name} - {Profession}`, in Arial Bold 18pt black, with a space on each side of the hyphen.
- **Name:** first name only, or "Dr. " + first name. Never a surname or a business name.
- **Profession:** the most specific credible label, 1–4 words, Title Case, even when the script is vaguer. Observed mappings:

  | Script says | Title says |
  |---|---|
  | "health and wellness… kids getting braces" | Myofunctional Therapist |
  | "health and wellness" (Dr. Richard) | Holistic Medicine Practitioner |
  | "mental health professional" | Mental Health Practitioner |
  | "sells tiny homes" | Home Contractor |
  | "lead generation expert" | B2B Lead Generation Agency |
  | "fertility expert" | Fertility & Hormone Specialist |
  | "ecom brand" | eCommerce |
  | "celebrity fitness coach" | Celebrity Fitness Coach |

- Two docs (Adam, Jered) have no title and open straight on the headline. That's the older style; don't copy it.

**A2. Headline**

First, pick a template:

| Use when | Template | Seen in |
|---|---|---|
| The hook gives 2+ audience numbers (views, followers) and a time frame (default) | `{G: views} & {G: followers} in [just / less than] {G: time}` | Ashley, Chelcie, Dr. Richard, Jay, Kavin, Stephanie |
| The impressive part is a condition, not the speed | `{G: metric} & {G: metric} with **{condition}**` | David ("with $0 in adspend") |
| The starting state is qualitative, or the win is authority or ROAS | `**From {start} → to** {G: new state}` | Adam, Daryoosh |
| The numbers lead to a status, or there's one key result | `**{start} →** {G: result}` or `{G: a} & {G: b} → __status__` | Greg, Jered |

Then apply these rules:
- **Order:** views first, followers second (5 of the 7 headlines with two numbers). A status can replace the second number, as in "2.38M views & biggest in her niche in 90 days".
- **Speed word:** copy the hook's own wording: "in just", "in less than", or plain "in".
- **Colors:**
  - Every outcome phrase (number + unit, or the new state) is bold dark green.
  - Every connector and the starting state is bold black.
  - The time-frame number and unit are green. (His docs are split 3–3 between green and black; green is the stronger, newer look.)
- **Underline:** at most one element. Either the time frame if it's 90 days or less (Chelcie, Stephanie; Kavin also underlined his 6 months), or a superlative status (Jered's "most followed plumber").
- **Size and position:** 6–12 words, Arial Bold 15pt, directly under the title with no blank line, then a blank line after.
- **Number style:** one decimal place for millions (13.4M), lowercase k for thousands (90k), and "+" when the true number is higher (10M+).

Calibration examples (spoken hook → headline):
- "13.4 million views and gain 90,000 followers in less than six months" → `{G: 13.4M views} & {G: 90k followers} in less than {G: 6 months}`
- "50 million views… with zero ad spend" → `{G: 50 million views} & {G: 1.8M followers} with **$0 in adspend**`
- "from solely relying on word of mouth to generating a 21x return" → `**Relying solely on word of mouth →** {G: 21x ROAS}`
- "finding random trends… positioning himself as an actual industry expert" → `**From chasing trends → to** {G: reaching millions as an authority}`

**A3. "Results:" heading**
- `Results:` in Arial Bold 15pt black.
- Variant: `Results in first {N} days:` when every bullet comes from one short launch window (Greg).

**A4. Results bullets**
- **Count:** 4 by default (3–6 seen; 4 in 7 of 11 cases).
- **Format:** "●" bullets, Arial 12pt regular black, 1.5 line spacing (1.15 also seen).
- **Never green.** Bold at most one key word in at most two bullets (e.g., "**230k+**", "**top 4%**", "**most-followed**").
- **Phrasing:** short fragments, not sentences. The last bullet can be a short sentence.

Fill these slots in order, skipping any slot with no data:

| Slot | Content | Wording taken from his docs |
|---|---|---|
| 1 | Audience growth | `344 → 230k+ followers across platforms (668% increase)` · `80,000 → 170,000+ followers` · `12K → 118K followers` · `35k new Instagram followers` · `+1.8M followers across platforms` · `10x follower growth` |
| 2 | Total views | `39.1M views total` · `13.4 million views in 6 months` · `21.6M views since working with us` · `200M+ views total` |
| 3 | Lift or efficiency (1–2 bullets) | `Less than 2,000 views per post → 47,000 views per post on average` · `Average views 100x from 2K → 200K per video` · `Views: thousands on avg → hundreds of thousands on avg` · `92% fewer posts, exponentially better results (1 per day vs. 5 per day)` · `From 40 hours/month → 4 hours/month time commitment (90% time saved)` · `+110% increase in engagement` · `First viral video hit 1M views in 6 weeks` |
| 4 (last) | Business result or status | `She is now getting so many leads she had to hire sales staff for the first time` · `High-ticket program now backed by predictable traffic` · `Replaced $60k per month ad spend` · `+1,000 leads per month` · `Now the clear leader in her niche` · `Reached top 4% of lawyer creators worldwide` · `"funny office content" → industry expert` |

- A status claim moves up to slot 1 when the hook is built on it (Jered).
- Put calculated lifts in parentheses and check the math. Adam's "668%" is actually about a 670x increase.
- Bullets can include numbers from analytics that are never spoken.

**A5. Image row on the opening screen** (one blank line below the last bullet)

Decide which kind of row to use:
1. **The client had never posted before (an ads case):** show the ad videos side by side, without view counts (Greg).
2. **Otherwise, if the script gives a low "before" number or names a breakout video** (e.g., "averaging under 2,000 views", "never cracked 5,000 views", "his 17th video got 5.1 million"): use a **Before/After pair**.
3. **Otherwise:** use a **top-performer row**.

**Before/After pair:**
- Two 9:16 tiles side by side with about a 6 px gap.
- Each tile is about ⅓ of the text width, so the pair takes about ⅔, aligned left.
- "Before" and "After" labels in Arial Bold 16pt (15–17 seen), centered above each tile.
- **Before:** a typical old-style video with low views (360 to 4,014 in his docs).
- **After:** the biggest new hit (millions).
- Circle both view counts in red.

**Top-performer row:**
- 4 tiles by default; 3; or 2 if there are only two big hits.
- Use a 4×2 grid if there are 8 or more videos near 1M views (David).
- Highest views first, left to right, then the next row. View counts must be visible.

**Add-on:** if the script reads analytics aloud right after the hook ("these right here are her first 30-day stats"), put the analytics dashboard screenshot directly under the row, with its total circled in red (Chelcie).

### B. Stacked before/after section (optional; Daryoosh, Stephanie)

**Use it when** both are true:
- the script spends 2 or more sentences describing the old content style (office trend skits, Facebook Live clips), and
- the opening screen used a top-performer row rather than a Before/After pair.

Place it directly after the opening screen:
```
Before        ← bold 14pt, light-yellow highlight #FFF2CC (or plain "Before:")
[IMG row of 3 old tiles — hundreds to low thousands of views]
After         ← bold 14pt, light-green highlight #D9EAD3 (or plain "After:")
[IMG row of 3 new tiles, same size — 100K+ views]
```

### C. Proof section (optional; used in 6 of 11)

| What the script claims | Screenshot to use | Red mark | Heading line above it? |
|---|---|---|---|
| "N followers across platforms" | Profile headers stacked, one per platform (TikTok, Facebook, YouTube, Instagram) | Ellipse around each follower count | Yes |
| "X million views a month" | 4×2 grid of top tiles | None | Yes |
| Percentage increases or "first 30 days" stats | Cross-channel analytics report | Ellipse around the claimed total | No |
| Revenue, ROAS or a team update | Slack message(s) from the account manager | Underline the 1–4 key figures | No |
| A ranking ("top 4% worldwide") | The ranking widget | Rectangle around it | No |

- **Heading-line format:** `{GRAY: {old} views → {new} views monthly} {g: ({x}x increase)}`, optionally followed by `{g: & {N} followers}`, in Arial Bold 14–15pt.
- His exact wording: "5k views → 20M views monthly (4,000x increase) & 1.8M followers" and "500k views monthly → 6M to 12M views monthly (24x increase)".
- **Placement:** after sections A and B, before D. Exception: a Slack screenshot proving one pillar's business result goes under the "What we did" items instead (Greg, Stephanie).
- **Privacy:** cover handles and URLs with light-gray boxes when needed. This was done for Adam, the attorney, and not for the others.

### D. "What we did" (required)

**D1. Heading**
- `What we did` by default (5 of 11).
- Variants: `What we did:` (3), `What We Did:` (2), or a phrase echoing the spoken transition (Ashley's "That strategy that blew her up:").
- Arial Bold 14pt, dark gray #434343, then a blank line.

**D2. Intro line (optional)**
- `We implemented a simple system for busy professionals:` in regular black.
- Use it for time-poor licensed professionals (attorneys, doctors) when the script stresses limited time. Both attorney docs have it.

**D3. The three items** (exactly 3, in all 11 cases)

1. **Take the pillars in the order they're spoken.** If only two tactics are explicit, build the third from the outcome claim ("Predictable traffic", "Predictable revenue") or from "our team handled everything else" ("Full execution").
2. **Write each item as:** `**{Label}:** {Before} → {mechanism} {G: outcome}.`
   - **Label:** 2–5 words naming the tactic, sentence case, bold (including the colon). Make it a noun phrase from the spoken verb, or take one from the phrase bank in D4:
     - "we set up batch production" → "Batch production"
     - "we optimized his production" → "Production optimization"
     - "we leveraged his visual storytelling" → "Leveraged visual storytelling"
   - **Before:** 2–8 words, regular black: the specific problem this pillar removed, taken from the "before" beat (e.g., "Doing everything herself", "Low-quality Facebook Live clips", "No tracking or planning"). If the script names no problem, state the absence of the solution ("No conversion system").
   - **After:** an optional black mechanism, then a bold green outcome: a level of views, a time figure, leads, sales, "every post had a purpose". If the whole after-state is an outcome, make all of it green. Put the client's own numbers in, e.g., "(0 → 733 posts in 6 months)" or "$10K/month from $50/day ad spend".
   - **Length:** 12–25 words, ending with a period.
3. **Formatting:** automatically numbered "1." list with hanging indent, Arial 12pt, 1.15 line spacing, one blank line between items. (Variants seen: bold manual "1." numbers, or no numbers.)

When the script doesn't set an order, the typical sequence is: #1 format or content change (7 of 11) → #2 production, studio or funnel → #3 systems or revenue.

**D4. Phrase bank** (wording taken directly from his docs; adapt the numbers)

**Format and content** (8 of the 33 items)
- Labels: Reaction video strategy · Format variety · Leveraged visual storytelling · Quality > Quantity · Stopped posting bad content · Structured ideation · Market research and content planning · Complete SMM strategy
- Before: No winning format · Low-quality Facebook Live clips · Stopped posting 5x/day · Stopped posting videos with poor editing and no strategy · No clear direction on what to post · No variety or expert positioning
- After:
  - `{G: Consistently hitting hundreds of thousands to millions of views.}`
  - `Scripted direct-to-camera product demos getting {G: hundreds of thousands of views per post.}`
  - `Highlighted visual details with {G: hooks that convert.}`
  - `Fewer, strategically crafted posts that {G: actually performed.}`
  - `{G: New studio, new editor, new approach.}`
  - `{G: Library of proven formats to pull from.}`
  - `Identified trending topics and planned {G: dozens of successful content angles.}`

**Production handled for them / time saved** (7)
- Labels: Minimal lift · Full production · Content production team · Full execution · Batch production · Batch filming system · Scaled production with limited time
- Before: Time-consuming filming sessions · Doing everything herself · Time-consuming daily filming · Filming was time-consuming and inefficient · 10 posts per month
- After:
  - `{Name} records once a month, we handle ideation, scripting, editing, and distribution.`
  - `{G: Ideation, scripting, editing all handled by our team.}`
  - `{G: Sitting once or twice a month to film}`
  - `Our team handles everything post-filming {G: (0 → 733 posts in 6 months).}`
  - `Weeks of content filmed in {G: one session.}`
  - `Improved studio so {Name} films a month's worth of content in {G: under an hour.}`
  - `{G: 50+ posts in just a few hours per month}`

**Positioning and studio** (5)
- Labels: Expert positioning · Professional studio setup · 30-minute studio setup · Production optimization
- Before: Lacked authority and credibility · Looked like a local practitioner · No professional camera experience · No structure or editing standards
- After:
  - `{G: Professional studio and clear messaging positioned him as the go-to expert.}`
  - `Complete studio setup positioned him as wellness authority while {G: driving local bookings.}`
  - `{G: Built a studio from scratch in under an hour}`
  - `Strategic pre- and post-production process with {G: proper editing techniques.}`

**Funnel and conversion** (5). TOF, MOF and BOF are top-, middle- and bottom-of-funnel content.
- Labels: Scripted funnel content · Strategic direction · Full-funnel content system · Full-funnel social media strategy · Automated DM funnel
- Before: Content that didn't convert · Random posting with no purpose · Posting with no strategy · No conversion system
- After:
  - `Middle and bottom-of-funnel scripts that turned views into {G: qualified leads and paying clients.}`
  - `Every post serves the funnel {G: (awareness → authority → conversion).}`
  - `TOF for reach, MOF for trust, BOF for {G: leads and customers.}`
  - `TOF for views, MOF for authority, BOF for conversions → {G: Every post had a purpose.}`
  - `ManyChat automation turning viral posts into sales, {G: driving 10K+ website visits in months.}`

**Systems and data** (5)
- Labels: Strategic overhaul · Strategic social media system · Built internal systems · Data-driven refinement
- Before: Random posting with no results · No tracking or planning · Guessing what to post
- After:
  - `Strategic social media system that consistently performs.`
  - `{G: Built a system for organizing clips, planning ahead, and tracking what works.}`
  - `Built a library for organizing clips, tracking performance, and planning ahead → {G: No more guessing.}`
  - `Used analytics to identify winners and {G: doubled down on successful formats.}`

**Volume and revenue** (3)
- Labels: Predictable traffic · Predictable revenue · Massive volume increase
- Before: Inconsistent results · Hoping the calendar fills up · Posting once every other day
- After:
  - `{G: Millions of views driving high-ticket sales.}`
  - `{G: $10K/month from $50/day ad spend}`
  - `Multiple posts daily across platforms {G: (163% increase) with no extra lift from her.}`

**D5. Image row under the items**

Use whichever kind of row the opening screen didn't use:
- **Opening screen had a Before/After pair:** put a row of 3–4 top performers, or a 4×2 grid, here.
- **Opening screen had a top-performer row:** put the Before/After pair here.
- **A pillar's result is proven by a team update:** use the Slack screenshot(s) with red underlines instead (Greg, Stephanie).
- Variant: a second, smaller Before/After pair (Kavin).

### E. Success grid (optional; Adam)
- **Use it when**, after the pillars, the script says something like "this is what success looks like" or "consistently getting videos with hundreds of thousands, if not millions of views".
- **Layout:** 3 columns by 2–3 rows, highest views first, directly below D5. Scroll slowly through it while talking.

### F. "NOW:" section (optional; Jered)
- **Use it when** the payoff beat runs 2+ sentences about a new state, such as independence or dominating the niche.
- **Format:** `{GRAY: NOW:}`, then 1–2 paragraphs in Arial 12pt black that rephrase those sentences almost word for word. Capitalize one word for emphasis ("ANY agency").

**Never in the doc:** the "why he succeeded / he trusted us" story, the "we do this for hundreds" line, the CTA, a logo or prices.

---

## Part 5: Image rules
1. **Source:** screenshots of the client's own profile grid (TikTok, Instagram, YouTube Shorts). Each is a 9:16 cover with the platform's view counter (eye or ▶ icon) in the bottom-left. Leave pin icons and captions as they are, and add nothing except red marks.
2. **Sorting:** highest views first, left to right, then top to bottom.
3. **Choosing Before:** the most typical old-style video with low views (car selfie, office skit, hotel-room selfie, Zoom/podcast clip).
4. **Choosing After:** the single biggest hit. Ideally it's the same person, now in a clean studio, with a large on-screen hook caption.
5. **Red marks:**
   - A stroke of about 3 px in pure red. It looks roughly like #B43C3B after video compression.
   - What to mark: view counts on Before/After tiles, follower counts on profiles, the claimed total in a dashboard, and key figures in Slack (underlined). Ranking widgets get a rectangle.
   - One mark per image, except Slack, which can take up to 4 underlines.
6. **Sizes, as a share of the text width:**

   | Image type | Width |
   |---|---|
   | Before/After tiles | ≈33% each |
   | 3 in a row | 27–30% each |
   | 4 in a row | 23–25% each |
   | 4×2 grid | 17–21% each |
   | Profile, Slack and dashboard screenshots | 55–100% |

   - Gaps of 0–8 px between tiles. Pasting one screenshot of a whole grid row is fine.
   - An image row takes about 40–52% of the visible doc height.
7. **Alignment:** the left edge of the text, occasionally lined up with the bullet-text indent instead.
8. **Slack screenshots:** dark or light theme are both fine. Keep the author, timestamp and emoji reactions, since they're part of the proof.

---

## Part 6: Font and color spec
Body text is 12pt; the multipliers show the measured size relative to body text.

| Element | Font and size | Color | Spacing |
|---|---|---|---|
| Title `Name - Profession` | Arial Bold 18pt (≈1.5×) | #000000 | — |
| Headline | Arial Bold 15pt (≈1.25×) | Gains #38761D (Docs "dark green 2"); connectors #000000 | Directly under the title; blank line after |
| `Results:` | Arial Bold 15pt | #000000 | — |
| Results bullets | Arial 12pt regular, "●" | #000000 | 1.5 line spacing; blank line after the list |
| Before/After labels (pair) | Arial Bold 16pt, centered over each tile | #000000 | — |
| Section headings ("What we did", "NOW:", stacked Before/After) | Arial Bold 14pt (≈1.15×) | #434343 (Docs "dark gray 4") | Blank line after |
| Proof heading line | Arial Bold 14–15pt | #434343, with the "(Nx increase)" part in #6AA84F (Docs "dark green 1") | — |
| "What we did" items | Arial 12pt; label bold; outcome bold | Label black; outcome #38761D | 1.15 line spacing; blank line between items |
| Stacked-label highlights | — | #FFF2CC behind Before / #D9EAD3 behind After | — |
| Arrows | → (Unicode U+2192) | Inherits | One space on each side |

**Google Docs setup:**
- File → Page setup → **Pageless**.
- Normal text: Arial 12pt.
- Tools → Preferences → turn on automatic substitution, so "->" becomes "→".
- Insert images "In line".
- For a labeled Before/After pair, use a 2×2 table with 0pt borders and center the labels in the top row.
- Record with the browser in full screen and the Docs menus hidden, so only the white page shows.

---

## Part 7: Scrolling and timing

| When the script says… | Do this |
|---|---|
| The hook (0:00) | Doc at the very top, with the title about one line below the top edge. Stay here through the hook and the before-state. |
| Any number in the hook or the "now" beat | Park the cursor next to that bullet or number |
| The first sentence describing the old content | Scroll to the stacked before/after section, if there is one |
| "But now he has… / now he's generating X a month…" | Scroll to the proof section, if there is one |
| The transition ("So here's exactly how we…"), or "First, we…" if there's no transition | Scroll so "What we did" sits about one line from the top |
| "This is what success looks like" | Scroll into the success grid and keep drifting down slowly |
| The payoff ("And now [Name] is…") | Scroll to "NOW:" and center it |
| The scale line and the CTA | Don't move; end on the last screen |

**Timing benchmarks** (from the 11 videos):
- Runtime 1:13–2:47 (median about 1:52), 244–577 words, at about 3.2–3.7 words per second.
- "What we did" appears at 25–46% of the runtime (median about 35%).
- The opening screen stays up for 18–50 seconds.
- Screens per video = 2 (opening + "What we did") + 1 for each optional section used.
- Scrolls are smooth manual mouse-wheel scrolls of about 1 second, with no cuts or zooms.

---

## Part 8: Decision table

| If the transcript… | Then the doc gets… |
|---|---|
| Gives views + followers + a time frame in the hook | The first headline template |
| Brags about a condition ($0 ads) | The "with {condition}" headline |
| Describes a qualitative change, or the win is ROAS or status | The "From… → to…" or "… → …" headline |
| Gives a low old per-video number or names a breakout video | A Before/After pair on the opening screen (otherwise a top-performer row) |
| Describes the old content style in 2+ sentences | A stacked 3 vs. 3 before/after section (if the opening screen has no pair) |
| Says "followers across platforms" | Profile screenshots plus a proof heading line |
| States monthly views | A proof heading line plus a 4×2 grid |
| Reads out stats or percentage increases | A dashboard screenshot under the opening row |
| Reports revenue, ROAS or a team win | A Slack screenshot under the "What we did" items |
| Claims a ranking | The ranking widget with a red rectangle |
| Is about a busy attorney or doctor and stresses their time | The intro line under "What we did" |
| Has only two clear tactics | A third item built from the outcome |
| Says "this is what success looks like" | A success grid |
| Ends with 2+ sentences about the new state | A "NOW:" section |
| Is an ads case, or the client never posted before | No Before/After; the ad videos instead; "Results in first N days:" |

---

## Part 9: Final checklist (every item must pass)
- [ ] Title is `Name - Profession`: first name only, spelled correctly.
- [ ] Headline is 6–12 words, with green outcomes, black connectors and at most one underline.
- [ ] `Results:` has 3–6 black bullets (default 4), no green, follows the slot order, and every number matches a proof screenshot.
- [ ] The first screen shows everything from the title down to the images without scrolling.
- [ ] Every organic thumbnail shows its view count, and rows run from highest to lowest views.
- [ ] A Before/After is present, unless the client had no earlier content.
- [ ] Gray "What we did" heading with exactly 3 items, each `Label: Before → After` with a green outcome, 12–25 words, in the order spoken.
- [ ] Each section fits on one screen, and sections follow the script order.
- [ ] Red marks only on the numbers being claimed. No logo, CTA, emoji, extra colors or slide styling.
- [ ] Scroll plan has 2–5 screens, with "What we did" landing at 25–46% of the runtime.

---

## Part 10: Worked example (a new transcript)

**The transcript (made up, about 243 words, about 1:11):**
> Here's how we helped our client Marcus go from 1,200 followers to over 85,000 followers and 9.4 million views in just four months. So Marcus is a family dentist, and when he came to us his practice was already doing great, but his social media was just before-and-after photos and the occasional office birthday video. He was averaging around 300 views per post, and none of it was bringing in new patients. But now he has over 85,000 followers across platforms, 9.4 million views, and his front desk is booking over 40 new-patient consults a month straight from social media. So here's exactly how we did it. First, we completely changed his format to myth-busting videos, things your dentist won't tell you, and his very first one hit 2.1 million views. Second, we set up a professional studio in an empty operatory, so now he films for two hours once a month and our team handles the scripting, editing, and posting. And third, we built out a full funnel: top of funnel for views, middle of funnel for trust, and bottom of funnel with a comment-keyword DM that books consults automatically. And now Marcus has a system that brings in new patients every single week. We do this for hundreds of business owners every single day. If you're ready to see if this can work for your business, click the link down below and see if you qualify.

**The resulting doc:**
```
**Marcus - Family Dentist**
{G: 9.4M views} & {G: 85k followers} in just {G: 4 months}      ← no underline (more than 90 days)

**Results:**
●  1,200 → 85k+ followers across platforms (70x increase)
●  9.4M views total
●  ~300 views per post → first new video hit 2.1M views
●  40+ new-patient consults booked per month from social media

        **Before**                    **After**
[IMG old before/after-photo post, red ○ "312"]  [IMG myth-busting video, red ○ "2.1M"]

────────── (Proof — triggered by "85,000 followers across platforms")
{GRAY: 1.2k → 85k followers across platforms} {g: (70x increase)}
[IMG Instagram profile, red ○ on followers]
[IMG TikTok profile, red ○]   [IMG YouTube, red ○]   [IMG Facebook, red ○]

────────── (What we did — triggered by "So here's exactly how we did it")
{GRAY: What we did}

1. **Myth-busting format:** Before-and-after photos and office videos → Scripted
   "things your dentist won't tell you" videos, {G: first one hit 2.1M views.}

2. **Minimal lift:** No time to create content → Studio built in an empty operatory;
   Marcus films 2 hours a month, {G: we handle everything else.}

3. **Full-funnel content system:** Views that never became patients → TOF for reach,
   MOF for trust, BOF keyword DMs that {G: book 40+ consults a month.}

[IMG row of the top 3 new videos, highest views first: 2.1M · … · …]
```

**Why each choice was made:**
- **Before/After on the opening screen:** the script gives a low "before" number (300 views) and a breakout video (2.1M).
- **Proof section:** the script says "across platforms".
- **Top-performer row under the items:** the opening screen already used the pair.
- **No "NOW:" section:** the payoff is only one sentence.

**Scroll plan** (at 3.4 words per second):

| Time | Script | Screen |
|---|---|---|
| 0:00 | Hook | Opening screen; cursor moves to each bullet as its number is spoken |
| ≈0:22 | "But now he has over 85,000…" | Proof section |
| ≈0:30 | "So here's exactly how we did it" (42% of runtime) | "What we did" |
| 0:30–1:11 | Pillars and CTA | Hold on "What we did" |

---

## Part 11: Evidence — the 11 cases at a glance

| Case | Length | Screens in order | Headline template | Bullets | Opening-screen images | Heading | Images under the items |
|---|---|---|---|---|---|---|---|
| Adam | 1:56 | Opening → Proof (profiles, Slack, ranking) → What we did → Success grid | From → to | 4 | Before/After, circled | What we did + intro line | Row of 3, then a 3×3 grid |
| Ashley | 1:52 | Opening → What we did | A & B in less than T | 4 | Row of 4 | That strategy that blew her up: | Before/After |
| Chelcie | 1:27 | Opening (+dashboard, scrolled) → What we did | A & B in just __T__ | 4 | 2 circled tiles + dashboard | What we did | Row of 4, circled |
| Daryoosh | 2:47 | Opening → Stacked 3 vs. 3 → What we did | From → to | 4 | 1 standout tile | What we did + intro line | Row of 3 |
| David | 1:39 | Opening → Proof (heading line + 4 profiles) → What we did | A & B with $0 | 5 | 4×2 grid | What we did: | Before/After, circled |
| Dr. Richard | 2:07 | Opening → What we did | A & B in T | 4 | Before/After | What We Did: (no numbers) | 4×2 grid |
| Greg | 2:04 | Opening → What we did | X → Y | 3 ("in first 14 days") | 2 ad videos | What we did: | Slack, underlined |
| Jay | 1:51 | Opening → What we did | A & B in less than T | 6 | Row of 4 | What we did | Before/After |
| Jered | 2:34 | Opening → Proof (grid) → What we did → NOW | A & B → __status__ | 5 | Before/After, circled | What We Did: | Row of 4 |
| Kavin | 1:13 | Opening → What we did | A & B in __T__ | 4 | Before/After, circled | What we did: | Second Before/After |
| Stephanie | 1:50 | Opening → Stacked 3 vs. 3 → Proof (Slack) → What we did | A & B in __T__ | 4 | Row of 3 | What we did | 2 Slack messages, underlined |

---

## Appendix: Inconsistencies in his own docs (don't copy them)
- **Numbers that don't match:**
  - Adam: "Top 5%" in the headline but "top 4%" in the bullets, and "668%" for what is really about a 670x increase.
  - Jay: the doc says "under an hour"; he says "half a day".
  - Daryoosh: +400% vs. "10 → 50+ posts" vs. the spoken "400 posts".
- **Typos and missing words:**
  - "That strategy" (should be "The")
  - "acros"
  - "Relying solely word of mouth" (missing "on")
  - "5x/dy"
- **Inconsistent formatting:** colons sometimes bold and sometimes not; the time-frame color varies.

The lesson: the docs are fast rather than polished, and that plain look is part of the style. Your words and numbers should still be correct and should match your screenshots.
