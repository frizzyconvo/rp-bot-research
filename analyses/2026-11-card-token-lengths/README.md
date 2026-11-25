# Card length: older card collections vs Chub today

November 2026. Written for a community discussion about whether a "≤500 tokens = low effort" cutoff is a fair way to filter cards.

## Finding

Older card sets are much shorter than Chub today. Most 2023-era collections have 60–86% of cards at 500 tokens or fewer, against about 29% of Chub's live library. A ≤500-token cutoff would therefore remove most early cards while barely touching recent ones.

## Scraped and archived card sets

Mostly human-written for 2023 and earlier. Provenance of 2024+ cards is unknown.

| Set | Years | Cards | 1–500 | 501–1k | 1k–1.5k | 1.5k–2k | 2k–3k | 3k+ | Median tokens |
|---|---|---|---|---|---|---|---|---|---|
| Chub, live public library (API counts) | all | 311,120 | 29% | 27% | 20% | 11% | 8% | 5% | — |
| Chub collection, 2023–26 | 2023–26 | 6,444 | 26% | 43% | 20% | 6% | 3% | 1% | 754 |
| Chub dump, early 2023 | 2023 | 12,790 | 77% | 20% | 3% | 0% | 0% | 0% | 72\* |
| JanitorAI | 2023–24 | 188,482 | 58% | 23% | 11% | 5% | 3% | 1% | 376 |
| VenusAI | 2023 | 2,652 | 68% | 26% | 5% | 1% | 0% | 0% | 367 |
| Pygmalion Discord | 2023 | 899 | 85% | 13% | 2% | 0% | 0% | 0% | 314 |
| Single-creator collection A | 2023 | 784 | 86% | 12% | 1% | 0% | 0% | 0% | 310 |
| Roko's Basilisk (card hub) | 2023 | 932 | 80% | 19% | 2% | 0% | 0% | 0% | 113 |
| Single-creator collection B | 2023–24 | 217 | 32% | 52% | 10% | 2% | 5% | 0% | 656 |
| Perchance | 2025 | 512 | 40% | 45% | 8% | 4% | 1% | 2% | 551 |
| Perchance (NSFW) | 2025 | 337 | 40% | 42% | 11% | 1% | 5% | 1% | 569 |

\*The early-2023 Chub dump's median is probably wrong: its dated rows look truncated (median about 9 tokens), which pulls the whole set down.

## Known AI-written sets, for comparison

| Set | Cards | 1–500 | 501–1k | 1k–1.5k | 1.5k–2k | 2k–3k | 3k+ | Median tokens |
|---|---|---|---|---|---|---|---|---|
| Creator using a published AI template | 109 | 2% | 26% | 39% | 24% | 9% | 1% | 1,355 |
| Creator-stated AI set A | 100 | 0% | 17% | 49% | 19% | 11% | 4% | 1,294 |
| Mixed creator-stated AI cards | 82 | 22% | 23% | 26% | 10% | 16% | 4% | 1,077 |
| Creator-stated AI set B | 66 | 0% | 64% | 33% | 3% | 0% | 0% | 959 |
| Creator-stated AI set C | 595 | 0% | 1% | 46% | 46% | 7% | 0% | 1,516 |
| Creator-stated AI set D | 6 | 0% | 50% | 33% | 17% | 0% | 0% | 1,426 |
| Generated test cards (3 sets) | 9,260 | 60% | 30% | 7% | 2% | 0% | 0% | ~410 |

## Overlap between old archives

An exact and near-duplicate check of the early collections against each other found little overlap: about 15% of the early-2023 Chub dump, 6% of VenusAI, 3% of the Pygmalion Discord set, and almost none of the Roko's Basilisk set appeared in the other collections. The sets were checked against each other, not against any live site.

## Method and caveats

- **Token counts are estimates:** word count × 1.33, over the description and greeting fields. They likely run a little under the full-definition counts that sites report.
- **Bins match the ones used in the original discussion,** so the live Chub row lines up with the rest.
- **The live Chub row** comes from Chub API search counts by token range, posted in that discussion in November 2026. It is not computed from a card dump.
- **No card text is published here.** The underlying collections are not redistributed.
