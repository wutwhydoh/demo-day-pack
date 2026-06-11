# Adjacency Map — Complementary vs. Overlapping, by Job-to-be-Done

A neutral map of which of the 22 do adjacent jobs (stackable) and which do the same job (choose-between). No rankings — clusters only. Sources: [demo] and [site] as of 2026-06-10; details per tool in `tools/`.

## Clusters by job

**Data & enrichment infrastructure** (feeds everything else): Deepline (GTM API/CLI for agents, 97+ integrations), Saber (programmatic deep research, API/MCP/CLI), The Swarm (relationship/network data + API), Exportly (last-mile delivery of Clay workflows to reps).

**Signal & intent capture** (who to talk to, when): WhiteWhale (custom account signals), Syft Data (website-visitor identification), Syft AI (value-match prospecting from public signals), Alfa (conversational stream prospecting), FirstTouch (LinkedIn social signals), Centralize (relationship/stakeholder signals inside accounts).

**Context platforms** (what the AI should know): Octave (ICP/GTM context graph + MCP), Clearskies (revenue context graph under Claude/ChatGPT), Ruby (deal-scoped context + coaching), Cedar (email/meeting-centered company context).

**Execution & conversation surfaces** (the touch itself): Skyp (sending infrastructure + MCP campaign control), Knock (inbound chat routed to Slack/WhatsApp/LinkedIn), Docket (AI sales engineer answering on site and in CRM), 1mind (customer-facing AI personas on calls and sites), Terret (revenue graph + agents that write back to Salesforce), Swan (agentic GTM workflows: visitor triggers → drafted outreach → CRM updates, all surfaced in Slack — straddles signal capture and execution).

**Team capability** (making humans better): Avarra (AI-avatar sales simulations), Ruby (deal coaching — straddles this and context), Smoke Signals (productized service that builds a GTM system around you — the only services entry).

## Stacking observed *within the lineup itself* [demo][chat]

- Octave's customer runs **Deepline for enrichment → Octave for context → MCP push into their sequencer** — two of the 22 already in one production stack [demo].
- Swan's customer is also a **Syft Data** customer [chat]; Skyp's team described feeding **Syft Data** signals into Skyp outbound, "even via MCP" [chat — vendor statement].
- Three different relationships to Clay coexist: **Exportly** distributes Clay tables to reps, **WhiteWhale** syncs signals through Clay, **Deepline** positions as Clay-behind-a-CLI (its FAQ addresses the comparison head-on) [site].

The practical read: at least three multi-tool stacks already run inside this lineup itself, and in two of them MCP is the interface — several of these tools are easier to combine than their category labels suggest.

## Where jobs genuinely overlap (choose-between, not stack)

- **Octave ↔ Clearskies** — both sell a context layer under your AI; Octave leans ICP/messaging context, Clearskies leans revenue-operations context and reporting [site]. Closest pair in the lineup.
- **Syft AI ↔ WhiteWhale ↔ Alfa** — all answer "which accounts, and why now," with different inputs (public-web value signals vs. custom-written signals vs. conversational stream building) [demo][site].
- **The Swarm ↔ Centralize** — both relationship intelligence; network-scoped (whole-company graph for intro paths) vs. deal-scoped (stakeholder coverage inside active accounts) [demo][site].
- **Knock ↔ Docket** — both convert inbound interest conversationally; chat-routed-to-your-channels vs. an answering AI sales engineer [demo][site].
- **1mind ↔ Avarra** — both anthropomorphized AI people, pointed in opposite directions: at your *buyers* (1mind) vs. at your *reps* in training sims (Avarra) [demo].
- **The two Syfts do not overlap** — Syft AI (outbound) and Syft Data (inbound) are unrelated companies that happen to share a phoneme [demo][site].

## Partnership-spotting heuristic

The cleanest complement pairs cross cluster boundaries with a shared interface: signal tools → execution tools (visitor intent into outbound), data infrastructure → context platforms (enrichment into graphs), context platforms → any MCP-speaking surface. Where both sides already expose MCP [site: Octave, Clearskies, Deepline, Saber, Skyp, The Swarm, WhiteWhale, FirstTouch, and Alfa on its top tier], the integration may be a configuration, not a roadmap item.
