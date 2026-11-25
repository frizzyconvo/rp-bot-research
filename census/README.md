# Census of character-chat platforms and card hubs

Two tables, last updated November 25, 2026.

- [`platforms.csv`](platforms.csv): 74 character-chat and AI-companion platforms, current and defunct.
- [`card-hubs.csv`](card-hubs.csv): 16 sites for sharing, mirroring, or preserving character cards.

The lists aim to be broad, not complete. Small companion sites appear and disappear faster than they can be tracked.

## Columns

| Column | Meaning |
|---|---|
| `status` | `Active`, `Active – troubled` (running but with recent app-store removals, bankruptcy, or feature withdrawals), `Shut down`, `Merged`, `Static dump`, `Unclear`, `Not checked` (exists, but status was not verified), `Not verified` (existence not confirmed) |
| `web_visits_per_month_m` | Monthly web visits in millions, from the source in `source_date`. Mobile-first apps are heavily undercounted. Visits are not users. |
| `est_cards` | Estimated number of public characters or cards. See `cards_and_definitions_basis` for the source. Blank means no reliable figure was found. |
| `definitions` | Whether a character's full definition (the prompt text behind it) is visible to other users. See below. |
| `cards_and_definitions_basis` | Where the card count and the definitions rating come from |
| `source_date` | Source and date of the traffic or user figure |

### Definitions

| Value | Meaning |
|---|---|
| `Open` | Definitions are public and cards can be downloaded (for example, as Tavern-format PNG or JSON) |
| `Semi-closed` | Each creator chooses whether to show or hide the definition |
| `Closed` | Definitions are hidden from other users |
| `Private` | Personal companion apps with no public character library |
| `n/a` | Single built-in personas, front-ends without a library, or non-card products |
| `Not checked` | Not yet determined |

## Caveats

- **Traffic trackers disagree,** often by 2x or more. Where they do, the `notes` column gives the range.
- **Company figures are self-reported** and unaudited. Registered-account totals are not active users.
- **Card counts mix methods:** some are live API counts, some are site counters, some come from reviews. The basis column says which.

## Sources

Main sources, in order of how often they are used:

- AICPB AI Character website rankings, June 2026: https://www.aicpb.com/ai-rankings/products/websites
- D17 AI companion traffic report (Similarweb data), February 2026: https://pdf.dfcfw.com/pdf/H3_AP202604011820946612_1.pdf
- "The Million Club" character-platform traffic rankings, early 2026: https://kearai.com/chat/ai-characters-roleplay-million-club-traffic-rankings
- Semrush website overviews (crushon.ai, chub.ai, replika.com, pygmalion.chat), 2026
- AI companion app shutdowns and store removals, 2023–2026: https://companionhunt.com/data/ai-companion-app-shutdowns/
- AI companion statistics 2026 (Similarweb Jun–Aug 2026): https://aicompanionlibrary.com/guides/ai-companion-statistics-2026/
- Janitor AI user figures (Forbes, May 2026), via https://www.implicator.ai/janitor-ai-draws-2-5-million-daily-users-to-adult-roleplay-app/
- Janitor AI public character count, September 2026: https://arcanumrpgs.com/blog/janitor-ai-bot-creation/
- Talkie and Xingye MAU, August 2026 (36Kr): https://eu.36kr.com/en/p/4052600729294468
- Character.AI Chapter 11 filing: https://techcrunch.com/2026/10/13/just-5-years-in-interactive-chatbot-platform-character-ai-files-for-bankruptcy/
- Card hub and archive sites, read directly: https://datacat.run, https://charavault.net, https://char-archive.evulid.cc, https://app.wyvern.chat
- SillyTavern card sources and import behavior: https://www.roborhythms.com/sillytavern-character-cards/
- Saucepan definition visibility: https://aisofting.com/saucepan-ai-review-verified-facts-safety-laws/
- Janitor AI definition visibility: https://guglytech.com/how-to-make-a-character-private-on-janitor-ai/
- Character.AI definition visibility: https://rentry.org/reverseCAI
- SpicyChat definition visibility: https://www.aigirlfriendscout.com/reviews/spicychat-ai

Rows marked "Unsourced (background knowledge)" were not re-verified against a current source.
