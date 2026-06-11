# Craft Notes — Where Design Was Doing Real Work

Two lenses: **brand** (public websites, as of 2026-06-10 [site]) and **product** (what was on screen during demos [screenshot]). Named call-outs are praise only; weaknesses are described as anonymous field-wide observations, never attributed. Caveat: demo observations come from mid-demo Zoom captures — compression limits typography-level certainty. These lenses are also narrow by construction: only a minority of the 22 demos yielded clean visual captures, so absence from these notes is a sampling limit, not a judgment.

## Standouts (named, by evidence)

**Clearskies — brand lens.** The most intentional marketing surface of the set: cream background, large serif display type, the key line set in two colors ("Connectors give AI access. Clearskies gives it complete context."), a dark inset panel illustrating the context layer connecting to Claude/ChatGPT/"Any AI" nodes. Editorial and anti-SaaS-gradient in a field of template gradients — the visual restraint *is* the trust argument for a product whose pitch is reliability.

**Terret — brand lens.** A coherent slide system: near-black teal-tinted ground with a woven texture, mirrored wordmark, monospace-flavored display headlines, a single red accent reserved for questions. Numbered 1-2-3 layouts with thin rules. Reads as a designed identity, not a deck template — notable because most 3-minute demos leaned on raw product screens.

**Swan — product lens.** Two things worth studying. First, copywriting-as-personality: a chat-first home whose warmth comes entirely from language (a time-aware greeting, quick actions like "Find hidden revenue") on an almost chrome-free white canvas with one accent color. Second, the clearest agent anatomy of the day: the agent's configuration is a plain-language instruction document on the left, with a right rail of legible cards — trigger, run activity, referenced knowledge docs, available context, granted tools. A non-technical operator can see exactly what the agent is, knows, and may touch. (We describe this structurally and deliberately don't reproduce any instruction text visible on screen.)

**Cedar — product lens.** The standout interaction pattern of the event: after drafting an email, the agent reports back as a short changelog — what it did, why it made each choice, and the single remaining task for the human — ending with an offer to do that too. It converts "AI did something" into "AI accounts for itself," which is the actual trust problem in agent UX. The warm cream palette and soft chips give it a personal-software feel distinct from dashboard SaaS.

*Honorable mention — demo craft:* The Swarm's before/after stack slide (old tools with red price pills struck through against green replacements) and WhiteWhale's whiteboard storyboard both solved the real constraint — legibility at Zoom resolution — better than live UI would have.

## Common tells across the field (anonymous, aggregate)

- **The product is increasingly text, and the text is unart-directed.** Several demos put long-form generated prose in the primary surface with no formatting layer — no cards, tables, or hierarchy. The information quality was often high; the consumability at screen-share resolution was near zero. Writing quality varied more across products than chrome quality did.
- **AI-built surfaces have a recognizable accent:** stat-card grids, eyebrow caps, default component-library spacing — competent and interchangeable. Where brand craft existed, it usually lived in slides and marketing sites, not in the product.
- **Demo-data hygiene failures undercut otherwise good pitches:** gamification screens with every metric at zero, a reply column still sitting at zero, visible on screen during a results walkthrough, a trial-expiry countdown banner on stage, and an internal metric inconsistency a designer would have caught.
- **Color discipline was rare.** "Green as everything" — progress, success, CTA, chat bubble — was common; few products reserved color for meaning.
- **A dark-mode split:** revenue-intelligence tools trended dark and dense; outreach/workflow tools trended light and airy. Marketing sites were consistently more polished than the apps behind them — a brand-promise/product-polish gap visible across the field.

## The pattern under the patterns

The best moments rendered **human-in-the-loop as UI structure, not policy**: a send button that stays disabled until review (visible in Syft AI's review→approve→send flow), draft-then-confirm loops, a human teammate visibly able to jump into an AI conversation. The chat confirmed this is what the room wants — final control, legible agents, AI that shows its work. In this field, trust is currently a design problem more than a model problem.
