# Schema: how the per-tool files are structured

Every file in `tools/` describes one of the 22 demos from the Anonymous GTM Tech Demo Day (The Signal, June 10, 2026) using the same fields in the same order. If a field has no data, it says **"not captured"** or **"not found"**; nothing is silently omitted.

## Provenance tags

Every factual field carries a tag telling you where the information comes from:

- **[demo]**: said or shown on stage during the live demo (from the event transcript and screen captures)
- **[site]**: stated on the vendor's public website as of **2026-06-10** (a snapshot; websites change)
- **[chat]**: from the event chat, always anonymized; vendor-side statements are marked as such
- **[screenshot]**: visible on screen during a demo (used in the design notes)
- **[public-web]**: other public sources (press coverage, company blog posts) found in same-day search; lighter-confidence than [site]

A handful of names and domains were verified through a third channel (vendor employees self-identifying in the event chat); where that mattered, the file says so in plain language. No chat participant is named anywhere in this pack.

## Fields, in order

1. **Header line**: demo slot (#N of 22, with running-order notes where AV issues reshuffled things); presenter and customer company **as publicly stated on stage**; verified domain.
2. **Positioning as stated [demo]**: how the presenter framed the tool, quoting where the transcript is clean.
3. **Website says (as of 2026-06-10) [site]**: homepage headline, subhead, primary CTAs, and notable taglines, as captured that day.
4. **Category language [demo][site]**: the vocabulary each source uses ("context layer," "signal layer," "AI GTM engineer," coined terms). Useful for mapping how this market talks about itself.
5. **Claimed proof / metrics [demo]**: numbers and outcome claims exactly as stated on stage, with caveats where a claim is small-n, uncontrolled, or a weak proxy. These are customer assertions, not audited results.
6. **Demo narrative (compressed) [demo]**: what actually happened in the ~3 minutes.
7. **Pricing model [site]**: pricing structure from the website (no presenter mentioned pricing on stage; pricing is 100% website-sourced).
8. **MCP / integration posture [demo][site]**: Model Context Protocol support, Claude usage, and named integrations from both sources.
9. **Funding [site]**: only what could be verified or clearly sourced; "not found" otherwise.
10. **Demo vs website**: where what was said on stage and what the website says diverge, noted neutrally. The consistency gap is itself information.

## Accuracy conventions

- **Hedged means hedged.** Names that couldn't be verified stay marked unverified (e.g., one presenter's company, one customer name). Nothing uncertain is asserted as fact.
- **Speech-to-text caution.** The transcript had no speaker labels and garbled many proper nouns. Garble is never presented as a quote; corrections appear in brackets.
- **Redactions.** Prospect individuals and live-outreach targets visible during demos are redacted (e.g., "[prospect company]", "[a contact]"). Attendees are never named.
- **Source excerpts** (`source-excerpts/`) contain the cleaned presenter-only speech per demo, same redactions applied, for anyone who wants the source under the summary.

No rankings, no scores, no editorial verdicts. The files are descriptive only.
