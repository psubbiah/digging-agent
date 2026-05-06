# Source list

> This file is your editorial position on whose work to trust, whose to read sceptically, and whose to treat as noise. The agent uses it to weight what it surfaces and to flag confidence levels.
>
> The richer this file, the better the agent's triage. Add to it as you build your beat.

---

## Tier 1 — Trusted

*Sources you treat as reliable on first read. The agent can cite them without strong caveats. Specialist publications, peer-reviewed journals, named beat reporters whose work you respect, primary sources (government data, official reports).*

**Example:**

**General publications**
- Times of Israel
- The Times
- Politico London
- BBC
- The Telegraph
- The Guardian
- Private Eye

**Beat reporters (any outlet)**
- Lee Harpin (Jewish News) — Jewish political news
- Joshi Herrmann (Mill Media) — Northern independent journalist
- Judith Moritz (BBC) — general reporter who sometimes covers Jewish stories 
- Lucy Manning (BBC) — general reporter who sometimes covers Jewish stories
- Harriet Sherwood (Guardian) - reporter who sometimes covers Jewish stories (she is biased against Israel)
- Camilla Turner (Telegraph) - political editor

**Primary sources**
- Hansard (record of Commons and Lords debates)
- British Board of Deputies 
- Institute for Jewish Policy Research (JPR)
- Daily court listing (look out for Jewish names and Israel-related issues)

**Think tanks I trust on Jewish issues**
- Henry Jackson Society
- More in Common
- Stop the Hate
- Tony Blair Institute (TBI)

---

## Tier 2 — Read with care

*Sources worth reading but where you check claims independently. Could be partisan, agenda-driven, or just inconsistent. Useful for tip-offs, not for direct citation.*

**Example:**
- Jewish trade press (Jewish News, JNS, Forward) — useful for signals, but read for framing
- Any press releases — reliable but always advocating
- Jewish advocacy groups (Campaign Against Antisemitism, UK Lawyers for Israel) — useful for case studies, but check sources
- Social media (X / Twitter / Facebook / Bluesky) - useful for leads, but ensure posts are not AI 

---

## Tier 3 — Noise / sceptical

*Sources to discount or ignore. The agent should not surface stories from these unless multiple Tier 1 sources have picked them up.*

**Example:**
- Anti-Israel far-left publications (Novara Media, The Canary, and Double Down News) 
- Jewish influencers on social media
- Partisan think tanks running campaigns rather than analysis
- AI-generated content farms

---

## Sources I want monitored daily

*A short list of URLs, RSS feeds, or named writers the agent should always check, in priority order. The daily prompt will use this.*

**Example:**
1. https://hansard.parliament.uk/ (primary)
2. https://www.jpr.org.uk/topics/antisemitism (primary)
3. https://henryjacksonsociety.org/publication/ (think tank)
4. https://www.uklfi.com/blog (tier two)
5. https://x.com/home (tier three)

---

## How I want sources flagged in output

*A note for the agent on attribution style. The agent will follow this.*

**Example:**
- Tier 1 sources: cite by name without caveat. *"Hansard reporter reports..."* 
- Tier 2 sources: cite with attribution context. *"According to a Politico London item (which is well-sourced but typically rumour-heavy)..."*
- Tier 3 sources: do not cite. If a Tier 3 source is the only one carrying a story, flag it as: *"Currently only reported by [source], not yet picked up by trusted outlets — monitor."*
