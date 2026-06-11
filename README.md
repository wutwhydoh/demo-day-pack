# The Demo Day Context Pack

**A portable context layer for the Anonymous GTM Tech Demo Day, hosted by Brendan Short of [The Signal](https://www.thesignal.club) on June 10, 2026. 22 tools demoed by their customers, 3 minutes each. This folder is the event, structured so your AI can answer questions about it.**

## What this is

This is not a write-up. It is a **context pack**: a folder of structured, provenance-tagged files covering every demo, every vendor's public website, the cross-demo patterns, and an anonymized read on the audience. You don't read it cover to cover. You drop the folder (or the zip) into Claude, ChatGPT, Cursor, or any AI tool that reads files, and ask it questions.

The event moved fast: 22 demos in two hours, names misheard, domains guessed, two unrelated companies that sound identical. During the event, attendees asked the host for exactly this: a tool list with correct names and domains, and help keeping up and evaluating. This pack is that, plus the structure to query it. Ask it to triage the 22 against *your* stack, compare what a vendor demoed against what their website claims, or map who complements whom.

It also doubles as a small demonstration: when an event's source material is structured into plain files, any AI tool can act as an analyst on it. The format itself is part of the point.

## How to use it (3 steps)

1. **Load it.** Point your AI tool at this folder, or attach the zip. (Claude Projects, a Claude Code/Cursor working directory, or file upload in any chat tool all work.)
2. **Pick a prompt.** Two ready-made menus, copy-paste with blanks to fill:
   - [`prompts/for-attendees.md`](prompts/for-attendees.md): stack-fit triage across the 22, evaluation-criteria builder, category orientation, name/domain verification.
   - [`prompts/for-founders.md`](prompts/for-founders.md): homepage check against the patterns that landed, demo-said vs. website-says consistency, adjacency/partner scan, proof-frame borrowing.
3. **Go off-menu.** The pack answers anything its files contain. Ask "which of the 22 can I start self-serve under $200/mo?" or "what did the audience actually react to?" The answers will cite specific files.

## What's inside

```
README.md                      ← you are here
SCHEMA.md                      ← the per-tool schema, documented (every field provenance-tagged)
tools/INDEX.md                 ← one-page triage table: cluster, pricing, MCP, per tool
tools/{slug}.md                ← 22 files, identical structure: positioning as stated on
                                  stage, website copy as of Jun 10, category language,
                                  claimed proof, demo narrative, pricing model, MCP posture,
                                  funding (best-effort); full field list in SCHEMA.md
patterns/
  macro-patterns.md            ← the 5 cross-demo patterns, with evidence counts
  vocabulary-map.md            ← who says "context" vs "signals" vs "GTM brain"; demo-vs-site gaps
  adjacency-map.md             ← complementary vs overlapping, by job-to-be-done (no rankings)
signals/
  audience-signals.md          ← the event chat, distilled and anonymized
design/
  craft-notes.md               ← brand + product craft lenses; standouts named, anti-patterns anonymous
prompts/
  for-founders.md              ← copy-paste prompt menu
  for-attendees.md             ← copy-paste prompt menu
source-excerpts/               ← cleaned per-tool demo excerpts (presenter speech only)
```

Every factual claim carries a provenance tag: `[demo]` (said on stage), `[site]` (vendor's public website as of 2026-06-10), `[chat]` (event chat, anonymized), `[screenshot]` (visible on screen during a demo), `[public-web]` (other public sources).

## Data sources & honesty notes

This pack was built from a **live transcript of the event** and the **vendors' public websites as captured on June 10, 2026**, plus the event's public pages. Some things you should know before trusting it:

- **Demos were 3 minutes long.** Every tool here can do more than its file shows. Treat each `tools/` file as "what was demonstrated and publicly claimed," never as a full product assessment.
- **The transcript was machine-generated.** Names were systematically misheard ("Taret," "Skip AI," "knock.io," "helloruby.ai"). Canonical names and domains were reconciled against vendors' own self-identifications and websites. That reconciliation is one of this pack's main jobs, but residual errors are possible. A few facts remain explicitly hedged in the files rather than guessed (e.g., two customer-company names we could not verify).
- **On the count:** pre-event materials variously said 20 and 27 companies; **22 demoed on the day**, and the pack covers those 22.
- **Claimed metrics are presenter-stated and uncontrolled.** The pack reports them with attribution; it does not verify them.
- **All pricing is website-sourced.** No presenter mentioned pricing on stage. Pricing pages change; check before deciding.
- **Corrections are welcome and wanted.** If you presented, built, or bought one of these tools and something here is wrong, email **hi@derrickhicks.me** and it will be fixed and noted. If you recognize your own anonymized words in `signals/` and want them removed or reworded, write to the same address, no questions asked.

## Privacy

The event promised attendees anonymity, and this pack keeps that promise: **no attendee names appear anywhere**, and the chat ships only as an anonymized distillation. The pack includes no full event transcript, no chat transcript, and no screenshots. Presenter speech appears only as cleaned, redacted excerpts in `source-excerpts/`. Presenters and the customers who demoed spoke publicly at a public event and are named as they identified themselves on stage or in their own public materials.

## Snapshot disclaimer

This is a **point-in-time artifact**: the event as it happened on June 10, 2026, and the public web as it stood that day. Products will keep shipping, pricing will change, and the vocabulary will keep moving. There is no maintenance commitment. The pack will not be updated as the field moves. If you're reading this six months later, treat it as a structured record of that day. (Corrections of *fact*, like a misheard name or a wrong domain, are the one exception and are always honored. That's different from keeping pace with the field.)

## License & attribution

Licensed **CC-BY-4.0** (see [LICENSE](LICENSE)). You can use it, quote it, and build on it, with attribution.

Assembled by Derrick Hicks ([Memory Engine](https://getmemoryengine.ai)), using the same structured-files approach the pack demonstrates.

Event by Brendan Short / [The Signal](https://www.thesignal.club), shared here with his blessing. The demos, the format, and the room are his work.
