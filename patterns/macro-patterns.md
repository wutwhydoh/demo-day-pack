# Macro Patterns — What 22 Demos Said, Taken Together

Cross-demo patterns from the event. Provenance: [demo] = said on stage, [site] = public website as of 2026-06-10, [chat] = event chat (anonymized). Per-tool evidence: `tools/{slug}.md`.

## 1. Claude/MCP is the assumed runtime — nobody differentiated on the model

Six of the 22 demos used Claude or MCP **on stage** as load-bearing infrastructure: Octave (prompt → Claude → MCP push into MixMax), Deepline (CLI/MCP, "the Claude Code form factor"), Clearskies (Claude on a context graph for reporting), The Swarm (a two-step Claude + Swarm-MCP workflow *was* the demo), Saber (reps working in Claude Code with slash commands), and Syft Data (their Claude MCP adding context to captured visitors) [demo]. (A seventh, Swan, uses agent "skills" vocabulary that echoes the Claude ecosystem, but showed no Claude/MCP usage on stage.) On websites, roughly 9 of 22 carry explicit MCP/Claude product surface — Octave, Clearskies, Deepline, Saber, Skyp, The Swarm, WhiteWhale, FirstTouch, Alfa — plus Smoke Signals, which draws Claude Code inside its homepage architecture diagram [site]. No other model vendor was named on stage all day [demo]. Even the lone counter-positioner defined itself against Claude: Ruby's demo distinguished the product from "just the Claude MCP to extract information from your database" [demo].

**What this means for you:** the model layer is settled in this room; nobody differentiated on which AI they use. What they competed on instead: data quality, workflow fit, and — by their own vocabulary — context (see pattern #2). If you're evaluating tools, MCP availability is now a standard question worth asking — 10 of the 22 expose it somewhere, 12 don't (see `tools/INDEX.md`).

## 2. "Signals" vs. "context": a vocabulary fault line ran through the lineup — and some vendors are visibly switching sides

The day opened with Octave's customer reporting his reps' demand: "stop giving me a bunch of signals and just give me context so I can actually go and take action" [demo]. Syft Data's presenter called signal capture "table stakes" and sold the contextualize step [demo]. Clearskies is "The Context Layer for Revenue AI" with a "context graph" [site]; Ruby's site declares "Context is Everything" [site]. Meanwhile signals vocabulary was very much in the room: WhiteWhale sells "Custom Sales Signals," Smoke Signals brands its product "Alpha Signals" [site] — and the host's own brand, The Signal, uses the same vocabulary as roughly half the lineup. This isn't a settled shift — it's a fault line running through the lineup. (Full map: `patterns/vocabulary-map.md`.)

**For founders:** check which side of the line your homepage is on, on purpose. **For attendees:** two tools using opposite vocabulary may be selling adjacent things; the words are moving faster than the products.

## 3. Customers are doing the vendors' category creation

The format — customer demos, not founder pitches — produced the day's most memorable positioning, and it came from the customers' mouths: "Octave is basically the GitHub of our ICP" [demo], the "three C's: capture, contextualize, connect" framework [demo], "you miss 100% of the revenue you're not aware of" [demo], "AI GTM engineer" delivered by a customer as a job description [demo]. Practitioner language consistently beat homepage language for stickiness — the chat reacted to the customer phrases, not the taglines [chat].

**For founders:** your best category language is probably already in your customers' Gong calls. The customer-demo format is a positioning-research engine, not just social proof.

## 4. The proof-frames that landed had a common anatomy

The claims the room reacted to shared a shape: one baseline, one after, stated in the owner's own units. Avarra's customer: average new-hire first-year run rate "$22,000 → $96,000 ARR" across 70–80 reps — the headline number of the event, and the chat reacted in those exact units [demo][chat]. Knock's customer: "barely got a chat a day [before] — today I'm getting probably seven or eight conversations a day" [demo]. First-week activation framing also landed: Alfa's customer — reps "outbounding possibly in under a week since signing" [demo]. So did let-the-buyer-do-the-math framing: Clearskies' customer — "20 to 25 minutes per intake call… about 150 intake calls a month. You can start to think 20 minutes times 150" [demo]. **Hedge:** all of these are presenter-stated, uncontrolled, and unverified — the pattern is about what *persuades*, not what's proven.

## 5. The same category vocabulary spans wildly different business models

Of the 22, by website pricing posture as of June 10 [site]: **8 PLG self-serve** (Deepline, Swan, WhiteWhale, Alfa, The Swarm, Saber, Syft Data, FirstTouch), **4 hybrid** — self-serve entry with sales-led scale (Octave, Clearskies, Ruby, Skyp), **10 sales-led/demo-gated** (Terret, Docket, 1mind, Syft AI, Avarra, Exportly, Centralize, Smoke Signals, Knock, Cedar). Entry points run from $0/free tiers to a $14,999/mo productized service. Notably, **zero of the 22 demos mentioned pricing on stage** [demo] — every pricing fact in this pack is website-sourced.

**For attendees:** vocabulary won't tell you the motion. Two "context" tools can differ by 100x in commitment. Check the pricing field in `tools/` before you fall in love with a demo.
