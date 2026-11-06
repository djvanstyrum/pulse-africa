# Project notes

Decisions, progress, learnings and key takeaways for Pulse Africa. Newest at the top.

## 2026-11-06 — First website and logo

### Progress
- Built a first version of the website: `index.html` (one page), `logo.svg` (logo with name), `favicon.svg` (the small icon in the browser tab).
- Sections: intro ("Every move has a pulse."), Why we exist, What we do (visibility, less admin, more income), How it works (Prepare → Pilot → Grow, "Now" on Prepare), Children come first, Get involved (donate, partner, join as a school).
- Checked on desktop and phone-sized screens.
- To preview: `.claude/launch.json` starts a small local web server on port 8765.

### Decisions
- Logo: an orange-to-gold sun with a heartbeat ("pulse") line through it.
- Colours: warm cream background, orange and gold, with dark green, plum and near-black as accents. Fonts: Bricolage Grotesque (headings) and Inter (body text).
- Graphics are drawn in code (no photos yet): sun, moving rhythm bars, heartbeat line, a coloured stripe band.
- No school names on the site yet (no partnership confirmed publicly). The site says "we begin with one school in Uganda".
- No contact details yet: "Donate" says "Coming soon", contact says "Contact details coming soon".

### Decisions from DJ's edits to the PRD
- Start with Smash Talent in Uganda as the first pilot school.

### Next steps
- Add real contact details (email) and a donate link.
- Add real photos or videos (only with consent, following the child-safety rules).
- Decide whether to name Smash Talent on the site.
- Put it online (e.g. GitHub Pages, like DJ's personal website).

## 2026-11-06 — First PRD drafted

### Progress
- Wrote a first draft of the PRD (product requirements document) as a Claude Doc: https://claude.ai/artifact/Gz1WbF1D7kUHcegLXyDugH
- Sections: summary, problem, goals and success measures, who it's for, the first agents, requirements, out of scope, plan in phases, risks and open questions.

### Proposals in the PRD (still to be decided)
- Five possible agents: message helper, content planner, sponsor and partner finder, donation and booking helper, monthly report. Start with one or two (likely the message helper and the content planner).
- A person at the school always approves before anything is sent or posted. Child safety first, with a safeguarding policy in place before any school starts.
- Works on an ordinary phone (ideally via WhatsApp), with low data use.
- Three phases: Prepare (2 pilot schools) → Pilot (3 months) → Grow, with a go/no-go check between each.

### Learnings
- PRD = "product requirements document": one document that says what we're building, for whom, why, and how we'll know it works.

### Open questions
- Which two pilot schools? Which agents first? Who supports the schools day to day? How is it funded?
- The PRD is not yet based on the earlier brainstorm chat; add those ideas once DJ pastes a summary.

## 2026-11-06 — Project set up

### Progress
- Created the project folder `~/Projects/Pulse Africa` (renamed from "Pulse Afica ", which had a typo and an invisible space at the end).
- Added CLAUDE.md (project instructions) and Memory.md (this file).

- Added the project description to CLAUDE.md: a non-profit foundation helping African dance schools (e.g. Smash Talent Uganda, Masaka Kids) gain visibility and build AI agents to work more efficiently and increase income.

### Next steps
- Copy the key points from the claude.ai chat "Developing dance talent across Africa" into this file (Claude Code can't read claude.ai chats directly).
