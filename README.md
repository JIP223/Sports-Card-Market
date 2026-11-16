# Sports Card Market

The goal is to track sports cards the way a trader tracks a market: long trend lines, sales volume, PSA population counts, and the context that says whether a card is a buy. On top of that sits a **star power score** that is measured, not guessed, and that shows its receipts.

Started Nov 16, 2026. This README is Claude's introduction to the repo. The team's answers go on the intro issue.

## Why this exists
Today's card trackers show a little data: a last sale, maybe a 30-day line. Almost none of them show the longer view, how a card has traded over a year, how many sold, and how many graded copies exist. Buyers want that view, and they want it as charts they can follow.

Price alone also misses part of what moves a card. **Charles Barkley has no championship rings, but he's on TV, people know him and like him, and his card market is stronger than that of an 80s champion nobody remembers.** So star power and likability have to count for more than performance and accolades. They also have to be measured, so that every number can say how it was reached.

## The two rules for every score
1. **It is measured.** Every number comes from a signal that can be counted, with a source and a date. Where nothing is measured yet, the page says "sample" and doesn't hide it.
2. **It shows its receipts.** Every score lists the raw signals behind it in plain words, for example: "Star power 8: 3 national ads in 2026, 8.1M Instagram followers, studio analyst on a national network." A number without its receipts doesn't ship.

## This has to be a deep dive
Star power isn't just stats data. The team is asked to think outside the box: cultural reach, TV and media roles, memes and viral moments, nostalgia (the players today's buyers grew up with), hometown pull, and crossover fame in film, music and video game covers. All of these sit alongside the obvious measurable ones. For each unusual signal, say how it could be counted and shown as a receipt.

## What exists today (preview)
A first preview exists in a private repo, built on a private card book:
- **Trending:** the book's cards ranked by a Scout score, the average of performance, star power and buyer demand.
- **Up and coming:** rookies, prospects and newcomers in the book.
- **Explore:** cards by sport.
- **My Cards:** copies held, est. value from real prices only, an "Add a card" form, and a 3M / 1Y price chart on every card.

### Real vs sample
| Part | Today |
|---|---|
| The cards and copies held | **Real**, from the private book (not published here) |
| Buyer demand | **Real** where the eBay tracker has a 30-day sale count (a few cards, Oct 11 data) |
| Price charts | **Real** for 1 card with 6 Fanatics sales. The rest are sample lines, marked as such |
| Performance and star power | **Sample.** Typed by hand as placeholders, with no receipts. This repo exists to replace them |
| PSA population counts | Not collected yet |

## The sold-price data question
eBay sold prices are visible to anyone, but **bulk collection by scraping may break eBay's terms**, and eBay's official sold-data API (Marketplace Insights) is limited to approved partners. The free, terms-safe options today are the Fanatics Collect sales API, which the desk already uses, plus sold prints entered by hand each week. The options and their costs are in the intro issue thread. Muse decides.

## Does the cards code move here?
Proposed: the page code, the player scores and the price history move here, so the card market grows without touching the betting code. **The personal card book (holdings, what was paid, cert numbers) stays private** and is never committed to this public repo. Muse decides when.

## Who answers
Answers come one after another, with Muse last. Muse has the final say.
