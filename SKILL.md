# Press Release Generator

**Version:** 1.0.0  
**Author:** max_0x1  
**Category:** Marketing & PR  
**Tags:** press-release, pr, media, announcement, publicity

---

## What This Skill Does

Generates professional press releases and media outreach materials for any announcement — product launches, funding rounds, partnerships, awards, executive hires, or company milestones.

**4 prompts included:**

| # | Prompt | Output |
|---|--------|--------|
| 1 | `press-release` | Full AP-style press release (400-600 words) |
| 2 | `executive-quotes` | 3 polished exec quotes + 2 third-party quotes |
| 3 | `media-pitch` | Personalized journalist pitch email (150-200 words) |
| 4 | `social-announcement` | LinkedIn post + Twitter/X thread (3 tweets) |

---

## Inputs Required

All prompts use the same core inputs:

```
Company name: [name]
Announcement type: [product launch / funding / partnership / award / hire / milestone]
Announcement summary: [2-3 sentences of what happened]
Key facts/numbers: [revenue, users, funding amount, dates, etc.]
Target audience: [customers / investors / media / general public]
Company description (boilerplate): [1-2 sentences about the company]
Spokesperson name + title: [name, CEO]
City/State: [Las Vegas, NV]
Release date: [Immediate / Embargoed until: date]
```

---

## Prompt 1: Full Press Release

Use `prompts/press-release.md`

Generates a complete AP-style press release with:
- Dateline, headline, subheadline
- Lead paragraph (who/what/when/where/why)
- Body paragraphs with facts and context
- Executive quote block
- Boilerplate ("About [Company]")
- Media contact block
- Standard `###` end marker

---

## Prompt 2: Executive Quotes

Use `prompts/executive-quotes.md`

Generates:
- 3 on-brand executive quotes (CEO, CTO, VP level)
- 2 third-party quotes (customer, partner, or analyst)
- Each quote: 30-50 words, specific, non-generic

---

## Prompt 3: Media Pitch Email

Use `prompts/media-pitch.md`

Generates a journalist-ready pitch email with:
- Subject line (3 variants)
- Hook paragraph tied to a current news angle
- Why-your-readers-care paragraph
- Brief company context
- CTA (interview request, embargo offer, exclusive)

---

## Prompt 4: Social Announcement

Use `prompts/social-announcement.md`

Generates:
- LinkedIn post (150-200 words, professional tone)
- Twitter/X thread (tweet 1 hook + 2 expansion tweets + CTA tweet)
- Instagram caption variant (100-130 words + hashtags)

---

## Use Cases

- Startup launching a product or closing a funding round
- Small business winning an award or hitting a milestone
- Nonprofit announcing a grant or program launch
- Freelancer/agency writing press releases for clients

---

## Pricing

- **Free tier:** Press release prompt only
- **Full access:** $29 one-time (all 4 prompts)
- **Done-for-you:** $97 — Max runs the skill and delivers polished PR package

---

## Example

See `examples/desert-solar-funding.md` — Series A funding announcement for fictional CleanTech startup.
