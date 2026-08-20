# Weekly operating cadence, send ops, and kill criteria

## Weekly cadence

| Day | Work |
|-----|------|
| **Mon** | ICP refresh (any new disqualifier patterns from last week's replies?) + source 25 new accounts, 2–3× candidates researched down to 25. Every account gets trigger + trigger URL + confidence. |
| **Tue** | Verify every contact email (Hunter/Apollo/Truelist — **must be connected before the first send; nothing in this repo is verified yet**). Map missing contact names (FriskAI, Genera, Takt, Sophiie AI first). Write 10 custom first-lines for the P1 accounts. |
| **Wed** | Send: new email-1s (≤20/day while the domain warms) + due follow-ups. Prospect-local morning, Tue–Thu only. |
| **Thu** | LinkedIn touches per `copy/linkedin-scripts.md` + reply handling per `copy/reply-snippets.md`. |
| **Fri** | Metrics review: sent, bounced, replied, positive, meetings booked, show rate. Log in `ops/metrics.csv` (create on first send week). Paste numbers back into the assistant with `why no replies` if below the healthy band. |

## Send ops (non-negotiable)

- Domain mailbox only, never Gmail; warm the domain ≥2 weeks before hitting the daily cap.
- Start ≤20 new emails/day, cap 30; mix new sends and follow-ups.
- No invalid or unverified address ever enters the sequencer. Catch-all → LinkedIn-first.
- One link maximum per email; zero links in email 1; no images; no fake `Re:`/`Fwd:`.
- Signature carries: real name and title, company, physical mailing address, working unsubscribe. CASL/PECR note for CA/UK/EU recipients.
- A reply — any reply — pauses the thread instantly; a human takes over.
- Every contact row keeps `source_url`, `source_date`, and lawful-basis note (B2B legitimate interest / published business contact).

## North-star metrics (healthy ranges)

| Metric | Target |
|--------|--------|
| Verify rate before send | ≥ 90% |
| Bounce rate | < 2% |
| Reply rate | 4–12% |
| Positive reply rate | 1.5–4% |
| Meetings per 100 contacts | 1–3 |
| Show rate | ≥ 60% |

"Emails sent" is not a metric anyone reports proudly here.

## Kill criteria — stop and rewrite, do not push through

Pause all sequences immediately if any of:

- Bounce rate > 3% (list quality has failed — re-verify everything)
- Any spam complaint (deliverability risk compounds; audit copy + targeting same day)
- Reply rate < 1.5% after 100 sends (diagnose in this order: **list → copy → offer → deliverability**)

After a pause: rewrite ICP or copy, test on the next 50 sends max, only then scale again.

## Current blockers (as of 2026-08-19)

1. **No email verification tool connected** — nothing can be sent. Connect Hunter/Apollo/Truelist, verify the 11 P1 contacts, promote verified rows to Hot.
2. **Offer snapshot placeholders** — booking link, sender name/title, and send-from mailbox are UNVERIFIED in `icp/icp-one-pager.md`. Fill before first send.
3. **4 P1 accounts lack contact names** (FriskAI, Genera, Takt, Sophiie AI) — manual LinkedIn research, Tuesday.
