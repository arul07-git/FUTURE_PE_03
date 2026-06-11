# Prompt Templates — SEO Blog & Content Cluster Generator

> **Purpose:** Reusable AI prompt templates for generating SEO content packs for local health and service businesses.
> All prompts were used with Claude (claude.ai) and ChatGPT to generate the content in this repository.
> Variables are marked with `[SQUARE BRACKETS]` — replace before running.

---

## Prompt 1 — Keyword Research & Intent Map

Use this prompt to generate your keyword strategy before writing any content.

```
You are an expert SEO strategist specialising in local business content for Indian cities.

Business: [BUSINESS TYPE] in [CITY]
Example: Health diagnostic centre in Chennai

Generate a keyword research plan that includes:
1. One primary (pillar) keyword — high commercial or navigational intent
2. Four cluster keywords — one per supporting blog topic
3. Eight long-tail variations for use across all blogs
4. Five "People Also Ask" questions Google shows for this business type
5. For each keyword, state: search intent (informational / commercial / transactional / navigational)

Format as a markdown table. Be specific to [CITY] — include local search patterns.
Do not use generic global keywords. All keywords must reflect how a local patient or customer in [CITY] actually searches.
```

---

## Prompt 2 — Content Cluster Plan

Use after completing keyword research to map out your hub-and-spoke content structure.

```
You are an SEO content strategist. Based on the following keyword research, design a content cluster plan.

Primary keyword: [PRIMARY KEYWORD]
Cluster keywords: [LIST 4 CLUSTER KEYWORDS]
Business: [BUSINESS TYPE] in [CITY]

Create a content cluster plan with:
1. One pillar blog title targeting the primary keyword
2. Four supporting blog titles (one per cluster keyword)
3. A hub-and-spoke diagram showing how the blogs link to each other
4. For each blog: search intent, target reader, and the core question it answers
5. Internal linking rules — which blogs link to which

The goal is to build topical authority for [BUSINESS TYPE] in [CITY] on Google.
```

---

## Prompt 3 — Pillar Blog Generation

The most important prompt. Use this to generate your long-form authority article.

```
You are an expert SEO content writer specialising in health and local service businesses in India.

Write a long-form SEO blog post with the following specifications:

Business: [BUSINESS NAME], a [BUSINESS TYPE] in [CITY]
Primary keyword: [PRIMARY KEYWORD]
Secondary keywords: [LIST 3–4 SECONDARY KEYWORDS]
Word count: 1,500–2,000 words
Target reader: Local residents in [CITY] searching for [SERVICE]
Search intent: [COMMERCIAL / NAVIGATIONAL]

Structure requirements:
- H1: Must contain the primary keyword naturally
- H2 sections: Why [SERVICE] matters, Our services, Locations in [CITY], How to book, FAQ (5 questions), CTA
- H3 sub-sections under services and FAQ
- Meta description: Under 155 characters, includes primary keyword
- Tone: Helpful, trustworthy, clear — like a knowledgeable friend explaining a service

Local SEO requirements:
- Mention [CITY] naturally at least 5 times
- Include at least 3 neighbourhood names within [CITY]
- Use location + service phrases like "[SERVICE] in [CITY]" and "[CITY] [SERVICE] centre"
- Include a local CTA: "Book your [SERVICE] in [CITY] today"

Content requirements:
- Include a table (services with prices, or comparison)
- Answer the People Also Ask questions for this topic
- Write helpful, accurate content — no fluff or repetition
- Do NOT use generic filler phrases like "In today's fast-paced world..."

Internal linking placeholders:
Include 4–5 internal link suggestions in the format: [Read more: BLOG TITLE](link)
These will link to the supporting blogs in our content cluster.
```

---

## Prompt 4 — Supporting Blog Generation

Run this prompt once per supporting blog. Change the keyword and intent each time.

```
You are an expert SEO content writer for local health businesses in India.

Write a supporting blog post with the following specifications:

Business: [BUSINESS NAME], a [BUSINESS TYPE] in [CITY]
Primary keyword: [CLUSTER KEYWORD]
Secondary keywords: [2–3 RELATED KEYWORDS]
Word count: 700–1,000 words
Search intent: [INFORMATIONAL / TRANSACTIONAL / COMMERCIAL]
Target reader: [DESCRIBE WHO IS SEARCHING THIS — e.g. "a 35-year-old in Chennai who wants to book a thyroid test and wants to know the cost"]

Structure:
- H1: Contains the primary keyword
- Introduction: 60–80 words answering the search intent immediately
- H2 sections: [CUSTOMISE BASED ON TOPIC — e.g. for a cost article: What's included, Price table, How to book, FAQ]
- H3 sub-sections where needed
- Meta description: Under 155 characters

Local SEO:
- Mention [CITY] naturally at least 3 times
- Include 2 neighbourhood references
- End with a local CTA

Internal links:
- Link BACK to the pillar blog at least once
- Link to one other supporting blog that is topically related
- Use natural anchor text (not "click here")

Tone: Practical, clear, helpful. The reader wants information, not marketing speak.
```

---

## Prompt 5 — Local SEO Adaptation

Use this to take any existing blog and add stronger local SEO signals.

```
You are a local SEO specialist. I have written a blog about [TOPIC] for a [BUSINESS TYPE].
I need you to adapt it to rank better for local searches in [CITY].

Here is the blog: [PASTE BLOG CONTENT]

Make the following changes:
1. Naturally insert [CITY] in the H1 if not already present
2. Add [CITY] to the meta description
3. Add 2–3 neighbourhood names from [CITY] in relevant sections (do NOT force them in unnaturally)
4. Add a sentence in the introduction that references [CITY] specifically
5. Change the CTA to reference [CITY] explicitly
6. Add a small section (3–4 lines) titled "Serving Patients Across [CITY]" listing the areas covered
7. Ensure the keyword "[SERVICE] in [CITY]" appears at least once in H1 or H2

Do not change the core content, structure, or tone of the blog. Only make local SEO additions.
```

---

## Prompt 6 — FAQ Section Generator

Use this to generate a high-quality FAQ section for any blog or webpage.

```
You are an SEO content writer. Generate a FAQ section for a [BUSINESS TYPE] in [CITY].

Topic: [BLOG TOPIC OR SERVICE PAGE TOPIC]
Business name: [BUSINESS NAME]

Instructions:
- Generate 6–8 FAQ questions and answers
- Questions should match real "People Also Ask" patterns on Google for this topic in India
- Answers should be 40–80 words each — concise but complete
- At least 2 questions should be local — specific to [CITY]
- Write in plain, helpful language. No jargon.
- Format as H3 questions with paragraph answers

Example question styles to use:
- "Do I need a prescription to book a [SERVICE] in [CITY]?"
- "How long does a [SERVICE] take?"
- "What is the cost of [SERVICE] in [CITY]?"
- "Is [SERVICE] available on Sundays in [CITY]?"
- "How do I get my reports after a [SERVICE]?"
```

---

## Prompt 7 — Meta Description Batch Generator

Use to generate meta descriptions for all blogs at once.

```
Write SEO-optimised meta descriptions for the following blog posts for [BUSINESS NAME], a [BUSINESS TYPE] in [CITY].

Rules:
- Each meta description must be under 155 characters
- Must include the primary keyword naturally
- Must include a call to action or benefit statement
- Must mention [CITY] in at least 3 of the 5 descriptions

Blogs:
1. Title: [PILLAR BLOG TITLE] | Primary keyword: [KEYWORD]
2. Title: [SUPPORTING BLOG 1 TITLE] | Primary keyword: [KEYWORD]
3. Title: [SUPPORTING BLOG 2 TITLE] | Primary keyword: [KEYWORD]
4. Title: [SUPPORTING BLOG 3 TITLE] | Primary keyword: [KEYWORD]
5. Title: [SUPPORTING BLOG 4 TITLE] | Primary keyword: [KEYWORD]

Output as a table: Blog Title | Meta Description | Character Count
```

---

## How to Use These Prompts Effectively

### Tips for Better AI Output

1. **Always fill in ALL variables** before running a prompt — vague inputs produce vague outputs
2. **Run Prompt 1 (Keyword Research) first** — everything else depends on it
3. **Review AI output before publishing** — check facts, prices, and local details
4. **Use prompts as starting points** — add your client's actual USPs, real prices, and specific branch details
5. **Run Prompt 5 (Local SEO Adaptation) last** — after all content is drafted

### Adapting for a New City

Replace every instance of `Chennai` in the prompts and blog templates with the new city name. Also update:
- Neighbourhood names (use the new city's well-known areas)
- Price references (research local market rates)
- Any regulatory references specific to Tamil Nadu → replace with the new state

### Adapting for a Different Business Type

The same prompt structure works for:
- Dental clinics → change SERVICE to "dental checkup", "teeth whitening", "dental implant"
- Physiotherapy centres → "physiotherapy session", "back pain treatment", "sports injury rehab"
- Eye care clinics → "eye test", "cataract surgery", "contact lens fitting"
- Coaching institutes → "JEE coaching", "NEET preparation", "MBA entrance coaching"
