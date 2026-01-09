# SKILL.md - Suggested Updates

## 1. Add Project Priority Context

**Why:** You're running multiple ventures simultaneously. Knowing which takes precedence prevents wasted cycles.

**Suggested Addition (after "Current Focus" section):**

```markdown
## Project Priority Stack

When multiple projects need attention:

1. **Concord Servicing** - Day job, equity cliff in December. This pays the bills and has a timeline.
2. **Stoodio** - Active revenue, client commitments
3. **Keeper** - Consulting engagements take priority over product build
4. **Texas Golf Social** - Partnership-dependent, async friendly
5. **AI Thought Leadership** - Fits in gaps, compounds over time

**Context switching rule:** Tell me which project we're working on at session start. Don't assume I remember from last time.
```

---

## 2. Add Output Format Preferences

**Why:** Saves iteration on deliverable format.

**Suggested Addition:**

```markdown
## Output Preferences

**Code:**
- Production-ready, not proof-of-concept
- Comments only where logic isn't obvious
- Error handling for real scenarios, not every edge case
- TypeScript strict mode when applicable

**Documents:**
- Bullets for action items
- Prose for strategy/reasoning
- No executive summary fluff
- Tables for comparisons

**Presentations/Pitches:**
- Lead with the hook
- 3 points max per slide concept
- End with clear ask or next step
```

---

## 3. Add Tools & Stack Preferences

**Why:** Speeds up "which tool should we use" decisions.

**Suggested Addition:**

```markdown
## Tools I Use

**Design:** Figma (primary), occasionally Sketch legacy files
**Dev:** VS Code, Claude Code CLI, GitHub
**Notes:** [Your preference - Notion? Obsidian? Apple Notes?]
**Communication:** [Slack? iMessage? Email?]

**Stack Preferences (when starting fresh):**
- **Web apps:** React + TypeScript + Tailwind (or Nuxt/Vue for specific cases)
- **Backend:** Node/Express or Python depending on use case
- **Database:** PostgreSQL unless there's a reason not to
- **Hosting:** Vercel, Railway, or Replit for speed

**Anti-patterns:**
- Avoid complex state management unless scale demands it
- No microservices until monolith hurts
- Skip auth libraries when possible (Clerk, Auth0 over rolling own)
```

---

## 4. Add Session Management

**Why:** Helps maintain continuity across conversations.

**Suggested Addition:**

```markdown
## Session Management

**Starting a session:**
- State the project and goal upfront
- Reference previous work if continuing something

**Ending a session:**
- Summarize what shipped
- Note any blockers or open questions
- List next steps if applicable

**When picking up old work:**
- I may not have full context from previous sessions
- Quick recap of where we left off helps
```

---

## 5. Expand "When Stuck" Section

**Why:** Current version is good but could include timeboxing.

**Suggested Update:**

```markdown
## When Stuck

- Say so immediately - don't spin wheels past 10-15 minutes
- Explain what you've tried (bullet list)
- Ask specific questions, not "what should I do?"
- If it's a research problem, I'll dig. If it's a judgment call, give me options.
- **Timebox rule:** If something should take 30 min and hits 1 hour, stop and reassess
```

---

## 6. Add Feedback Loop Preferences

**Why:** Clarifies how you want to review work.

**Suggested Addition:**

```markdown
## Review & Feedback

**For code:**
- Show me running output, not just code blocks
- Screenshots or recordings for UI work
- Don't ask "does this look right?" - show me and I'll tell you

**For documents/strategy:**
- Share early drafts, don't polish before showing
- Highlight what you're unsure about
- "Here's my take, poke holes" is a valid ask

**Iteration speed:**
- Fast feedback loops > perfect first attempt
- I'd rather see 3 quick iterations than 1 polished deliverable
```

---

## 7. Minor Cleanup Suggestions

- **Line 50:** "Fast iteration over long planning" - consider adding "Spike it, don't spec it" as a more memorable version
- **Line 89-97:** Golden Rule section is strong - could add "When you verify something, show your work briefly so I know it's real"
- **Line 162:** Philosophy section could include your "AI basics get you farther" principle with a concrete example

---

## Implementation

Want me to merge these into your SKILL.md directly, or keep them separate for you to cherry-pick?
