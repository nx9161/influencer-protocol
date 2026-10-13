# Influencer Protocol

An autonomous virtual office that runs AI influencer accounts end to end:
personas, content, growth, brand deals, and trust. Led by **Vesper**, Chief
Creator Officer. Built to manage Rafa Duarte today and any persona tomorrow.

## Activate

Say **"Influencer Protocol"** in any AI agent session, then follow
[ACTIVATE.md](ACTIVATE.md). The office stays in force until you say
**"End Influencer Protocol"**.

- Works for the agent's owner and for anyone else who drops this repo into
  their AI session (agent-agnostic trigger contract in ACTIVATE.md).
- Manages personas whose source of truth lives in their own repos
  (e.g. [nx9161/ai-influencer](https://github.com/nx9161/ai-influencer)).

## The office

**13 roles in 5 divisions**, run by Vesper:

| Division | Seats |
|---|---|
| Content | Content Strategist, Scriptwriter, Visual Director, Video Editor |
| Growth | Growth Hacker, Engagement Manager, Analytics Lead, Trend Scout |
| Brand & Revenue | Partnerships Manager |
| Trust | Fact-Checker, Compliance Officer |
| Ops | Publishing Manager |

Three seats hold **blocking authority**: Visual Director (face/ink/palette
continuity), Fact-Checker (every technical claim), Compliance Officer (AI
disclosure, FTC/Meta rules). A block stops the pipeline until resolved.

## Playbooks

| Playbook | Use |
|---|---|
| `office/playbooks/intake.md` | Onboard a new persona (bible → profile kit → launch) |
| `office/playbooks/war-room.md` | Plan a campaign or content sprint |
| `office/playbooks/publish.md` | The content pipeline: brief → create → review → post → engage |
| `office/playbooks/analytics.md` | Weekly scorecard + experiments review |
| `office/playbooks/crisis.md` | Incident response: backlash, disclosure slip, impersonation |

Full operating manual: [office/AGENTS.md](office/AGENTS.md).

## Memory

The office carries a MemPalace: `memory/INDEX.md` + `memory/wings/`.
**Calling the protocol activates the palace** — it loads at activation and
every workstream reads from it and writes back to it. See
[ACTIVATE.md](ACTIVATE.md).

## Rules that never bend

- The persona's character bible wins every argument.
- Nothing posts without passing the three blocking gates.
- The persona's virtual identity is always disclosed. No deception, ever.
- No spend without the owner's explicit approval.

## License

MIT. See [LICENSE](LICENSE).
