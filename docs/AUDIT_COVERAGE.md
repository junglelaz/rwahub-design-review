# Audit coverage

All findings are addressed in the **review experience**. Live business, legal and blockchain requirements remain integration work; simulated flows are labeled throughout.

| Finding | Review implementation | How to inspect |
|---|---|---|
| 01 — Hidden high-value listings | Unbounded initial price range; numeric filters; result counts and removable chips | Marketplace includes the $2.5m and $4.2m listings before filtering |
| 02 — Dead purchase, bid and swap actions | Connected preview flows with cost review, confirmation and explicit completed/pending outcomes | Watch purchase, sapphire bid, tiara exchange; quick view opens the full terms |
| 03 — Portfolio not personalized | Dedicated local-account holdings, cost and activity; market inventory never becomes personal holdings | Portfolio begins empty and changes only after a completed demo purchase |
| 04 — Trust without inspectable evidence | Openable sample documents, reviewer/scope/date, missing-evidence status, custody and token gaps; no placeholder blockchain link | Asset detail → evidence and ownership terms |
| 05 — Inaccessible mobile filters | Responsive native modal/bottom sheet with conditions, full valuation inputs, Apply/Clear, result count and dismissal | Narrow viewport → Filters |
| 06 — Filters/sorting without effect | One tested filtering function handles conditions, category, valuation, search and review status; dates are actually sorted | Change conditions and sort order |
| 07 — Wizard guardrails | Step-level validation, supported MIME types, nonempty/10 MB/5-file limits, required evidence and permission; final cost/document/network review | List an asset |
| 08 — Wallet interrupts intent | Consistent wallet entry; permissions/network/fees explained; action callback resumes the initiating purchase; form stays intact | Begin purchase while disconnected; connect demo wallet |
| 09 — Unclear fractional economics | Unit price, full valuation, minimum share, available units, fees, terms, restrictions, settlement and risk disclosures | Listing cards, detail and transaction review |
| 10 — Loading/discovery feedback | Finite six-then-two pagination; distinct list layout; separate loading, failure, empty and filtered-empty states | Marketplace and Review controls |
| 11 — Misleading sample content/KPIs | Global demo labeling, sample badges/docs/profiles, current fixture dates, valuation labeled as illustrative rather than TVL; unmeasured times omitted | Homepage, specialist pages, all transaction flows |
| 12 — Accessibility and motion | Named controls, visible focus, native modal containment/Escape/focus return, semantic labels, skip link, reduced-motion support; removed automatic carousel | Keyboard review and mobile layouts |
| UI 1 — Unavailable vs empty | Unavailable metrics use dashes; failure offers Retry rather than pretending no inventory exists | Review controls → Inventory service unavailable |
| UI 2 — Wallet language/style | One copper primary action system and consistent wallet language; clear demo account/network explanation | Header, wallet dialog and trade review |
| UI 3 — Competing hero CTAs | One marketplace primary and a secondary asset-owner path; portfolio stays in navigation | Homepage |
| UI 4 — Hero image composition | Stable image/caption composition; no large decorative circles, auto-advance or controls on a photo edge | Homepage |
| UI 5 — Cramped filter inputs/state | Fully readable values, USD/full-asset explanation, no default maximum, active chips outside the dialog | Filters and marketplace toolbar |
| UI 6 — Inconsistent visual language | Shared ink/warm-white/copper/slate tokens, Lucide line icons, control radii, spacing, typography and semantic statuses | Across marketplace, account and forms |
| UI 7 — Unnamed controls | Explicit search, layout toggle, dialog close, condition and file input names; associated form labels | Browser accessibility tree and keyboard inspection |

Supporting material also appears as working product content: investor and owner journeys, fictional review-specialist profiles, evidence boundaries, missing evidence, pending review and network-mismatch guidance. No live eligibility, custody or settlement is implied.
