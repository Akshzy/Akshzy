# GitHub Profile / Repository README Makeover — AI Agent Task Specification

## Objective

Act as a **GitHub README designer + developer agent**.

I want you to transform my GitHub profile README / main README into something that feels:

- polished
- visually entertaining
- modern
- personal
- developer-focused
- interactive-looking without becoming cluttered
- memorable when someone opens my GitHub profile

The inspiration is the repository:

https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub

Use that repository as a **source/catalogue for suitable GIFs, animations, stickers, banners, and visual assets**. Do not simply copy its entire README. Select assets that fit my profile and construct an original layout around them.

You have permission to inspect my repository/files, edit the relevant README and supporting files, run local checks, preview the result where possible, and iterate until the result is clean.

---

# 1. First: Inspect Before Editing

Before changing anything:

1. Inspect the repository/workspace I have given you access to.
2. Determine whether this is:
   - my GitHub profile repository, normally `<username>/<username>`, or
   - a normal project repository.
3. Locate:
   - `README.md`
   - existing images/assets
   - badges
   - links
   - existing sections
   - contribution/activity widgets
   - social/contact information
   - any existing HTML/SVG/GIF assets
4. Read the existing README completely before modifying it.
5. Preserve useful existing information unless it is clearly outdated or redundant.
6. Do not destroy the original content. If a major rewrite is necessary, create a temporary backup such as `README.backup.md` before editing.

If the repository is a profile README repository, optimize specifically for the **GitHub profile landing page**.

If it is a project repository, keep the technical/project documentation intact and only introduce the visual style where appropriate.

---

# 2. Visual Direction

The overall style should be:

**"Professional developer profile + playful internet/GitHub energy."**

I do NOT want:

- a generic template
- an overloaded wall of GIFs
- 20 different animation styles
- huge images that push important information far below the fold
- random anime/GIF spam
- excessive badges
- excessive emojis
- fake statistics
- fake claims
- broken images
- external assets that are unreliable when GitHub renders the README

The visuals should support the content.

Think of the page as a carefully designed personal landing page rather than a collection of random GIFs.

---

# 3. Core Visual Ideas I Specifically Want

Use these ideas as the starting point.

## A. Coding Vibe

Use a GIF/animation representing:

- coding
- programming
- developer workstation
- multiple monitors
- focused coding
- developer environment

The source repository contains options such as:

- `Coding Vibe`
- `Coding from Home`
- `Busy Work`
- `Girl Coding Serious`
- `Deep Thinking`
- `Pro Coder`
- `Modern Work Environment`
- `Development Time`
- `Working on Laptop Illustration`

Choose **one** that visually fits the final composition.

Do not use several similar coding GIFs.

---

## B. Life Balance

Use a visual representing:

- work/life balance
- switching between work and personal life
- maintaining balance
- developer life outside code

The source repository has a `Life balance` visual.

Use it only if it fits naturally with the page.

This can work particularly well near a small personal statement such as:

> Building things, learning continuously, and trying not to forget there's a world outside the terminal.

Do not invent personal facts. Keep the wording generic unless my existing README provides real information.

---

## C. Mario / Playful Developer Moment

I specifically liked the **Mario** visual from the source repository.

Use the Mario GIF/animation as a small personality element.

Possible placement:

- near a "Currently building..." section
- beside a playful developer quote
- near the lower half of the profile
- as a divider between serious/professional content and playful content

Do not make Mario the dominant visual.

---

## D. Busy Work

I liked the `Busy Work` visual.

Use it as a developer-life joke around a section such as:

### Current Mode

> `Building → Debugging → Deploying → Repeat`

Again, do not invent claims about my actual workload.

The visual should communicate "developer chaos / lots happening" without making the profile look unprofessional.

---

## E. A Dinosaur-Type Animation — But Different

I like the idea of the Chrome Dinosaur Game visual shown in the source repository, but I **do not want to simply copy the exact dinosaur visual as the main element**.

Find another visually interesting animation with a similar concept:

- endless progress
- keep moving
- debugging
- persistence
- developer journey
- playful pixel animation
- progress despite obstacles

The source repository includes alternatives such as:

- `Keep Moving Forward`
- `Infinite Loop`
- `Error 404`
- `Fixing a bug in production`
- `Mission Bug Termination`
- `Pro Level Debugging`
- `How my code works?`
- `Why my code works?`
- `It's Not a bug! It's a Feature!!`

Select **one** alternative that fits better than the dinosaur.

The goal is:

**same playful developer feeling, but not a direct repetition of the Chrome Dino.**

---

# 4. Animated Hello

I want an **Animated Hello** element near the beginning of the profile.

The source repository has an `Animated Hello` section.

Use an appropriate animated greeting if it looks good with the rest of the page.

Possible structure:

```text
[Animated Hello]

Hi, I'm Akshay 👋
Computer Science Engineer | AI / Automation | ...
```

However:

- do not invent my role
- do not invent companies
- do not invent technologies
- use information already present in my README/repository
- if my existing profile contains the relevant information, preserve it accurately

The greeting should act as an entry point rather than consuming half the screen.

---

# 5. Octodex / Octocat Element

I also want a **quality Octocat / Octodex visual**.

The source repository points to:

https://octodex.github.com/

Use the Octodex as inspiration/source for a suitable GitHub-themed visual.

Select something that feels:

- developer-related
- clean
- high quality
- visually compatible with the profile

Possible placement:

- beside an "About Me" section
- beside "What I'm working on"
- near the bottom as a signature
- in a two-column HTML table if GitHub rendering permits it

Do NOT make the Octocat compete with the main hero.

---


## Special Octodex Interaction Requirement

I specifically want the **awesome Octodex / Octocat visual from the reference repository** where the character appears to be watching or reacting to a butterfly.

Use that idea as the visual inspiration for the Octocat section.

### Desired effect

I want the Octocat to feel as if it is:

- watching the visitor's mouse/cursor
- following the cursor with its eyes/head
- reacting to movement in the same playful way that it appears to watch the butterfly
- feeling alive rather than being a completely static decorative image

### Important GitHub limitation

A normal GitHub README does **not** allow arbitrary JavaScript, mouse-position tracking, or custom interactive scripts.

Therefore:

1. **Do not attempt to inject JavaScript into `README.md`.**
2. If the exact Octodex asset already contains an animation where the Octocat tracks a butterfly/object, use that animated asset directly.
3. Prefer an animated GIF/SVG that creates the *illusion* that the Octocat is following something.
4. If true cursor-follow interaction is impossible inside the GitHub README, preserve the visual concept using the best animated Octodex asset available.
5. Do not add broken or unsupported HTML/JS simply to fake cursor tracking.

### Optional enhanced version

If this repository also contains or can host a separate webpage (for example GitHub Pages), you may optionally create a **separate interactive version** where the Octocat's eyes/head genuinely follow the user's mouse using HTML/CSS/JavaScript.

If you do this:

- keep the GitHub README version fully compatible and self-contained
- do not make the README depend on the interactive page
- keep the interactive page lightweight
- link to it subtly from the README, for example:
  `🐙 Play with the Octocat`
- only implement this if it genuinely improves the profile and does not create unnecessary complexity

### Visual placement

The preferred placement is near the bottom of the profile or beside the closing/about section, where the Octocat can act like a playful "profile mascot".

The animation should be medium-sized and should not overpower the main profile content.


# 6. Suggested Page Architecture

Use this as a starting structure, but improve it if the existing content suggests a better arrangement.

## Hero

Animated greeting / subtle visual

```text
Hi, I'm Akshay 👋
[short existing accurate tagline]
```

Then a compact introduction.

---

## About Me

A concise, human description based on my actual README information.

Avoid a giant paragraph.

Prefer:

- what I build
- what I am learning
- areas of interest
- current focus

---

## Current Focus / What I'm Building

Use a small developer-related GIF, potentially:

- Coding Vibe
- Busy Work
- Deep Thinking
- Development Time

Keep this section factual.

---

## Tech Stack

Show technologies in a clean way.

Do not add technologies merely because a GIF repository mentions them.

Only use technologies already supported by my repository/profile information.

---

## Projects

Keep the projects useful and easy to scan.

If project cards/badges already exist, improve their visual consistency rather than replacing everything unnecessarily.

---

## Developer Life / Personality Section

This is where the playful assets can appear.

Potential composition:

```text
[Busy Work GIF]     [short developer joke / statement]

[Life Balance GIF]  [short statement]

[Mario GIF]         [small playful message]
```

Do not use all three if that makes the page too long.

---

## Progress / Developer Journey

Use the alternative to the dinosaur here.

Possible concept:

```text
Still building.
Still learning.
Still debugging.
Still moving forward.
```

Pair it with:

- Keep Moving Forward
- Infinite Loop
- debugging animation
- another suitable visual

---

## GitHub Stats / Activity

If my README already has GitHub stats:

- preserve useful stats
- avoid duplicated stats
- avoid visually overwhelming the page
- use a clean arrangement
- ensure image links are valid

Do not fabricate statistics.

---

## Contact / Social Links

Keep these at the bottom.

Use existing links only.

---

## Closing Visual

A small Octodex / Octocat or animated farewell can work here.

Avoid another huge GIF.

---

# 7. Asset Selection Process

Do NOT guess asset URLs.

Instead:

1. Open the source repository:
   https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub
2. Inspect its README and/or repository files.
3. Identify the exact asset associated with the desired category.
4. Prefer stable URLs that GitHub can render reliably.
5. Verify that the asset actually loads.
6. Prefer a direct image/GIF URL or a reliable GitHub-hosted/raw asset where appropriate.
7. Avoid hotlinking questionable third-party hosts when a stable source is available.
8. If an asset is broken, select another asset instead of leaving a broken image.
9. Keep track of the selected asset URLs in a small internal notes section or comments while developing.

Useful source categories include:

- Animated Hello
- Work Culture
- Coding Vibe
- Coding from Home
- Busy Work
- Girl Coding Serious
- Life balance
- Mario
- Extra Value Added
- Keep Moving Forward
- Infinite Loop
- Error 404
- Fixing a bug in production
- Deep Focus
- GitHub Star
- Hello Wave
- Pro Level Debugging

Do not blindly use every category.

---

# 8. GitHub Markdown Compatibility

This is important.

The final result must render correctly on GitHub.

Prefer:

- Markdown
- GitHub-supported HTML
- `<img>`
- `<picture>` only when appropriate
- simple tables when useful
- aligned HTML layouts only where GitHub reliably supports them

Avoid depending on:

- JavaScript
- CSS files
- external scripts
- unsupported HTML
- interactive components that GitHub strips
- local file paths
- localhost URLs

Remember:

**GitHub README rendering is not the same as a normal web page.**

Everything must work inside GitHub's README renderer.

---

# 9. Responsive / Visual Quality

The README will be viewed on:

- desktop
- laptop
- mobile
- GitHub dark mode
- GitHub light mode

Therefore:

- do not use enormous fixed-width images
- use sensible image widths
- avoid layouts that break badly on narrow screens
- avoid tiny unreadable text
- maintain reasonable whitespace
- make the first viewport visually strong

Use image widths intentionally, for example:

```html
<img src="..." width="..." />
```

but choose the actual dimensions based on the asset.

---

# 10. Design Rules

Follow these rules strictly.

### Rule 1 — Visual hierarchy

The page should have an obvious hierarchy:

1. identity
2. professional focus
3. projects/skills
4. personality
5. GitHub activity
6. contact

### Rule 2 — One visual should have one purpose

Do not place three coding GIFs next to each other.

### Rule 3 — Quality over quantity

Approximately **4–7 carefully selected animated/static visual assets** is preferable to 15+ random GIFs.

### Rule 4 — Avoid visual noise

If a GIF makes the page look childish, replace it.

### Rule 5 — Don't let GIFs dominate

The profile is still a developer portfolio.

### Rule 6 — Don't invent facts

Never create:

- fake experience
- fake projects
- fake statistics
- fake certifications
- fake job titles
- fake GitHub numbers

### Rule 7 — Preserve authenticity

The final page should look like **my profile**, not like a copied template.

---

# 11. Implementation Workflow

Follow this exact workflow.

## Phase 1 — Audit

Inspect the repository and existing README.

Output internally:

- current README structure
- current visual assets
- useful existing sections
- redundant sections
- missing sections
- potential places for animations

Do not start randomly editing.

---

## Phase 2 — Asset Research

Inspect:

https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub

Find candidates for:

1. Animated Hello
2. Coding Vibe
3. Life Balance
4. Mario
5. Busy Work
6. Dinosaur alternative
7. Octodex visual

For each candidate verify:

- visual quality
- relevance
- URL
- GitHub compatibility

---

## Phase 3 — Design

Create a rough structure before implementation.

The target should resemble:

```text
┌───────────────────────────────────────┐
│             ANIMATED HELLO            │
│                                       │
│              AKSHAY                   │
│       short professional intro        │
├───────────────────────────────────────┤
│              ABOUT ME                 │
├───────────────────────────────────────┤
│         CURRENTLY BUILDING            │
│       text + small coding GIF         │
├───────────────────────────────────────┤
│             TECH STACK                │
├───────────────────────────────────────┤
│              PROJECTS                 │
├───────────────────────────────────────┤
│         DEVELOPER LIFE                │
│                                       │
│  Busy Work     Life Balance     Mario │
├───────────────────────────────────────┤
│          KEEP MOVING / DEBUGGING      │
├───────────────────────────────────────┤
│          GITHUB ACTIVITY              │
├───────────────────────────────────────┤
│        OCTOCAT / CLOSING              │
└───────────────────────────────────────┘
```

This is conceptual. Improve it if the actual repository content suggests a better layout.

---

# 12. Implement

Edit the relevant README.

If necessary, create an assets directory only when there is a strong reason to locally host assets.

Prefer reliable external assets when appropriate.

Do not add unnecessary files.

---

# 13. Test

After implementation:

### Check Markdown

Verify:

- headings
- links
- HTML
- tables
- image tags
- image URLs
- alignment
- spacing

### Check every image

For every image/GIF:

- URL resolves
- content is actually an image/GIF
- no 404
- no empty embed
- no broken GitHub rendering

### Check Git status

Ensure you know exactly what files changed.

### Check for accidental content

Make sure no:

- debug text
- temporary links
- placeholder images
- TODOs
- local paths
- localhost URLs
- API keys
- secrets

remain.

---

# 14. Preview / Iterate

If your environment allows you to preview Markdown or render the README:

1. render it
2. inspect the visual hierarchy
3. fix oversized images
4. fix awkward whitespace
5. fix alignment
6. fix broken embeds
7. reduce unnecessary GIFs
8. render again

Repeat until the result looks intentional.

If you have access to a browser or GitHub preview, use it.

---

# 15. Important: Do Not Stop After Editing

Your task is not:

> "Modify README.md."

Your task is:

> **Create a polished, working GitHub profile experience and verify it.**

Therefore, after editing, actually inspect the resulting README and test the asset URLs.

---

# 16. Final Report

After completing the work, report:

### Changed

List the files changed.

### Visuals Added

List each visual and its purpose, for example:

- Animated Hello — hero
- Coding Vibe — current focus
- Busy Work — developer-life section
- Mario — personality element
- Keep Moving Forward — progress section
- Octodex — closing visual

### Removed / Replaced

Explain anything removed and why.

### Validation

Confirm:

- README renders
- image URLs checked
- no broken assets found
- no secrets added
- no fake information added

### Optional Improvements

Give me 3–5 improvements that could be made later, but do not leave obvious unfinished work in the README.

---

# 17. Quality Bar

Before considering the task complete, ask yourself:

> If a recruiter, developer, or engineer opens this GitHub profile for the first time, does it immediately feel like a real developer's profile rather than a copied GIF collection?

The answer should be yes.

The page should communicate:

**technical → clean → modern → personal → slightly playful**

not:

**random → overloaded → childish → template-like**

---

# 18. Primary Reference

Main GIF source:

https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub

Octodex:

https://octodex.github.com/

Animated Hello / related resources may be discovered through the main GIF repository.

---

# 19. User's Initial Visual Preferences

These are the assets/concepts I explicitly liked from the reference:

- Coding Vibe
- Life balance
- Mario
- Busy Work
- Dinosaur-style developer animation, but **use a different concept/asset rather than the exact dinosaur**
- Animated Hello
- Quality Octodex / Octocat visual

Use these preferences as the foundation, but make the final design coherent rather than forcing every element into the page.

## Final instruction

**Inspect → research assets → design → implement → test → preview → refine → report.**

Do not ask me to manually find GIF URLs unless access to the source repository genuinely fails. You are expected to research and select the assets yourself.
