# Playbook: Viral Briefing

Runs at every protocol activation (after the palace loads) and on demand
("brief me", "what's viral"). The office never plans content blind.

## Seats
Trend Scout (lead), Content Strategist, Analytics Lead.

## Inputs
- `config/niche.md` — the owner's content preferences and tracked accounts.
- The active persona's bible, pillars, and hook playbook.

## Steps

### 1. Load preferences
Read `config/niche.md` plus the persona's content docs (pillars, hook
playbook, calendar). The briefing is filtered through these — viral content
outside the niche is noise.

### 2. Pull what's viral
- Social search with engagement ranking on 2–4 niche queries (AI tools,
  build in public, tech explainers, plus persona-specific topics).
- For each tracked account in `config/niche.md`: fetch recent posts, rank
  by likes and comments.
- Time window: the last 7–14 days matters most. Older viral is reference,
  not signal.

### 3. Analyze
For the top 5–10 hits, extract: format (screen recording? talking head?
decode?), hook (first line), CTA mechanic, topic, why it worked.
A pattern appearing twice is a signal. Three times is an order.

### 4. Plan
Produce 3–5 concrete recommendations for this week, each mapped to a
content pillar:
- The idea in one line
- Format + hook + CTA
- Which viral reference it riffs on

### 5. Report and log
Vesper delivers the briefing as the activation report (or standalone when
requested). Patterns go into the office memory wing.
