## Research Prompt (Perplexity Research - Computer Mode)

Research contemporary science fiction publishing and reading-market niches as of 2024-2026.

Goal: produce AI-usable market intelligence for fiction planning. Focus on modern genre niches, how they overlap, where they diverge, common character/plot/theme tropes, durable market mainstays, and underserved niches where reader demand appears higher than available supply.

Rules:
- Every factual claim must be tagged with one or more evidence tags.
- Use recent sources where possible: 2024-2026 preferred, 2022+ acceptable for trend context.
- Distinguish evidence from inference.
- Do not give generic genre history unless it explains a current market pattern.
- Favor actionable specificity over broad commentary.
- Include citations/links for all source-backed claims.

Evidence tags:
[SRC] directly source-supported
[RECENT] 2024-2026 source
[SALES] sales/ranking/bestseller/platform evidence
[READER] reader-review, BookTok, Goodreads, Reddit, forum, newsletter, or community evidence
[PUBLISHER] agent/editor/publisher/submissions/MSWL evidence
[AWARD] award/shortlist/critical-recognition evidence
[INFER] reasoned inference from multiple facts
[LOW_CONF] weak, limited, or conflicting evidence
[GAP] potential demand/supply gap

Output format:

1. Executive Map
Create a table with columns:
- niche
- one-line definition
- audience promise
- demand signal
- supply signal
- competition level: low/medium/high
- opportunity level: low/medium/high
- evidence tags
- source links

2. Contemporary Sci-Fi Niches
Cover at least:
- space opera
- military sci-fi
- first-contact
- climate fiction / eco-SF
- dystopian / post-collapse
- solarpunk / hopepunk SF
- cyberpunk / post-cyberpunk
- AI / machine consciousness
- biotech / body modification
- near-future techno-thriller SF
- literary/speculative SF
- cozy / slice-of-life SF
- romantasy-adjacent or romance-forward SF
- YA/crossover SF
- Afrofuturism, Indigenous futurism, and other culturally specific futurisms
Add other active niches if evidence supports them.

For each niche, provide:
- core reader expectation
- common character tropes
- common plot tropes
- common theme tropes
- tonal range
- adjacent niches
- key divergence points from adjacent niches
- recent market examples
- demand vs supply assessment
- evidence tags

3. Trope Matrix
Create three tables:
A. Character Tropes
B. Plot Tropes
C. Theme Tropes

Each row:
- trope
- niches where common
- reader appeal
- freshness risk
- current saturation: low/medium/high
- useful twist angles
- evidence tags

4. Similarities and Divergences
Create a comparison table:
- niche A
- niche B
- shared appeal
- major divergence
- audience overlap
- risk of confusing the market
- positioning advice
- evidence tags

5. Mainstays
List the durable market mainstays in contemporary sci-fi:
- niche/trope/theme
- why it persists
- current examples
- how to use it without feeling stale
- evidence tags

6. Underserved Opportunities
Rank 10-15 underserved or under-supplied opportunities.
For each:
- opportunity
- target reader
- demand evidence
- supply-gap evidence
- why traditional/current market may underserve it
- execution risk
- positioning angle
- comparable titles/media
- confidence: low/medium/high
- evidence tags

7. AI Extraction Block
Return a compact JSON object with:
{
  "niches": [],
  "mainstays": [],
  "underserved_opportunities": [],
  "trope_clusters": {
    "character": [],
    "plot": [],
    "theme": []
  },
  "market_signals": [],
  "positioning_rules": [],
  "avoid_or_handle_carefully": []
}

Keep prose concise. Prefer tables, bullets, and structured fields. Every row must include evidence tags.
