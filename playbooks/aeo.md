# AEO (Answer Engine Optimization) Playbook

> Optimizing content to be cited by ChatGPT, Perplexity, Google AI Overviews, Claude, and other LLMs.

## What AEO is

Traditional SEO optimizes for *ranking* (position in blue links). AEO optimizes for *citation* (being the source an LLM quotes when answering a question). Different rules, sometimes overlapping.

## Where AI answers come from

| Source | How to optimize |
|--------|----------------|
| **Google AI Overviews** | Top of SERP, draws from top 10 + structured data |
| **Perplexity** | Real-time web search + ranked citations |
| **ChatGPT search** | Bing index + curated sources |
| **Claude (with search)** | Anthropic's web search (limited) |
| **Gemini** | Google's Knowledge Graph + AI Overviews |

## Tactics

### 1. Question-format content
LLMs are trained to match questions with answers. Every blog post should have a clearly-answered question.

Bad: "Our thoughts on email marketing"
Good: "What is the best email marketing frequency for B2B SaaS in 2025?"

### 2. FAQ blocks
Every blog gets an FAQ section. 4-6 questions, each answered in 40-80 words. These get cited directly by AI.

### 3. Schema.org FAQPage markup
Mark up FAQs with structured data so AI engines parse them reliably.

### 4. Clear, extractable answers
The first sentence of any section should answer the implied question. Then expand.

Bad: "Email frequency is a topic that many marketers struggle with. There are many factors to consider, including your audience and industry."
Good: "The optimal email frequency for B2B SaaS is 2-4 emails per week. Below this, you lose engagement; above, you see unsubscribes spike."

### 5. Statistics with sources
LLMs heavily prefer citing statistics. Every claim with a number needs a primary source (research paper, government data, original study).

### 6. Authoritative bylines + About pages
LLMs favor content with clear authorship. Add author bio with credentials. Link to a real LinkedIn profile.

### 7. Entity-first writing
LLMs work in entities (people, companies, products). Mention the entity by name, link to its Wikipedia or official page if it exists.

### 8. Comparison tables
"X vs Y" content gets cited heavily. Use HTML tables (LLMs parse them well) with clear headers.

### 9. List format
Numbered and bulleted lists are easier for LLMs to extract. Use them for steps, rankings, options.

### 10. Recency signals
LLMs prefer fresh content. Always include "Last updated: YYYY-MM-DD" at the top. Update quarterly.

## Anti-patterns

- ❌ Burying the answer 3 paragraphs down
- ❌ Vague statements ("Many experts believe…")
- ❌ Content without author attribution
- ❌ Marketing fluff that doesn't actually answer the question
- ❌ Old content with no "Last updated" date
- ❌ Walls of text with no structure (no headers, no lists)

## Measuring AEO success

Track these manually each month:
1. Search your top 10 questions on Perplexity, ChatGPT, Google AI Overviews
2. Is your content cited? If yes, on what position?
3. Note which pages get cited, which don't
4. Iterate on the structure of pages that don't get cited