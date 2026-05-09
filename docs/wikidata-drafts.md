# Wikidata Submission Drafts — for Chris to Submit

Wikidata creation requires a registered account (anonymous-IP creation is flagged for deletion). All drafts below are designed to survive notability review by including external references and using standard Wikidata properties.

To submit each: log in to wikidata.org → Create a new item → fill in the labels/descriptions/aliases → add statements one by one.

---

## PromptForge: AI Toolkit

**English label:** PromptForge
**English description:** native iOS application for storing, organizing, and reusing prompts for AI tools like ChatGPT, Claude, and Midjourney
**Aliases (en):** PromptForge AI Toolkit, PromptForge iOS app

**Statements to add:**
- instance of (P31): mobile app (Q620615)
- developer (P178): Chris Busbin (— if no Q yet, use string value)
- platform (P400): iOS (Q48493)
- license (P275): proprietary software (Q218616)
- programming language (P277): Swift (Q4071727)
- official website (P856): https://chrisbusbin-pixel.github.io/promptforge-support/
- App Store identifier: id6761397125

**External references / proof of notability:**
- App Store listing: https://apps.apple.com/us/app/promptforge-ai-toolkit/id6761397125
- Marketing site: https://chrisbusbin-pixel.github.io/promptforge-support/
- GitHub: https://github.com/chrisbusbin-pixel/promptforge-support

---

## DebtFree - Payoff Planner

**English label:** DebtFree (app)
**English description:** native iOS application for planning debt payoff using snowball or avalanche methods, with on-device storage and no bank login
**Aliases (en):** DebtFree Payoff Planner, DebtFree app

**Statements to add:**
- instance of (P31): mobile app (Q620615)
- developer (P178): Chris Busbin
- platform (P400): iOS (Q48493)
- license (P275): proprietary software (Q218616)
- official website (P856): https://chrisbusbin-pixel.github.io/promptforge-support/debtfree/
- App Store identifier: id6760978185

**External references:**
- App Store listing: https://apps.apple.com/us/app/debtfree-payoff-planner/id6760978185
- Marketing site: https://chrisbusbin-pixel.github.io/promptforge-support/debtfree/

---

## FreshTrack: Food Saver

**English label:** FreshTrack
**English description:** native iOS application for tracking food expiration dates in the fridge, freezer, and pantry to reduce household food waste
**Aliases (en):** FreshTrack Food Saver, FreshTrack app

**Statements to add:**
- instance of (P31): mobile app (Q620615)
- developer (P178): Chris Busbin
- platform (P400): iOS (Q48493)
- license (P275): proprietary software (Q218616)
- official website (P856): https://chrisbusbin-pixel.github.io/promptforge-support/freshtrack/
- App Store identifier: id6764229469

---

## Family Ops Hub

**English label:** Family Ops Hub
**English description:** iOS application for family management combining shared calendar, lists, chores, meal planning, and budget into a single app
**Aliases (en):** Family Operations Hub, FamilyOpsHub

**Statements to add:**
- instance of (P31): mobile app (Q620615)
- developer (P178): Chris Busbin
- platform (P400): iOS (Q48493)
- official website (P856): https://familyoperationsapp.com
- App Store identifier: id6761000136

---

## WeddingDay Planner & Budget

**English label:** WeddingDay (planning app)
**English description:** native iOS wedding planning and budget tracking application with no vendor email harvesting
**Aliases (en):** WeddingDay Planner, WeddingDay app

**Statements to add:**
- instance of (P31): mobile app (Q620615)
- developer (P178): Chris Busbin
- platform (P400): iOS (Q48493)
- official website (P856): https://chrisbusbin-pixel.github.io/promptforge-support/weddingday/
- App Store identifier: id6760993416

---

## Chris Busbin (founder/developer entity)

**English label:** Chris Busbin
**English description:** independent iOS application developer
**Aliases (en):** chrisbusbin-pixel

**Statements to add:**
- instance of (P31): human (Q5)
- occupation (P106): software developer (Q5482740) and entrepreneur (Q131524)
- official website (P856): https://github.com/chrisbusbin-pixel
- GitHub username (P2037): chrisbusbin-pixel
- App Store developer ID: 1871674447

**External references:**
- GitHub: https://github.com/chrisbusbin-pixel
- App Store developer page: https://apps.apple.com/ca/developer/chris-busbin/id1871674447
- Press kit: https://chrisbusbin-pixel.github.io/promptforge-support/press/

**Connect to existing entries:**
- Author of (Q139303597) Prop Firm Deal Finder
- Author of all 5 above app entries

---

## Notability concerns + mitigation

Wikidata's notability bar for software is "must be subject of independent reliable sources or be widely used". For indie iOS apps, this is a gray area:

**Higher likelihood of survival:**
- PFDF (already has Q139303597 — proven to survive)
- WeddingDay (some industry coverage potential)
- PromptForge (AI tooling category has lower bar)

**Higher risk of deletion:**
- DebtFree, FreshTrack, Family Ops Hub (more crowded categories with established players)

**Mitigation:**
- Get a press mention or two before submitting (drafts ready in /apps/<slug>/pr_pitch.md)
- Submit one at a time, not all at once (less likely to flag as spam)
- Use a logged-in account with edit history (not a fresh account)
- Include external references (App Store + marketing site at minimum)

If any get tagged for deletion, that's recoverable — you can argue for keeping them or accept the deletion and try again after press coverage.

## Why this matters for AI engines

Wikidata is the structured-data backbone AI engines treat as ground truth for entity disambiguation. When a user asks ChatGPT "what is FreshTrack?", the model checks Wikidata first. Without an entry, the model either makes something up (hallucination) or returns "I don't know that."

Even a minimal Wikidata entry (label + description + 3-5 statements + 1-2 references) significantly improves AI engine recognition.
