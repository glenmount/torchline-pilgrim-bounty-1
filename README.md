# torchline-pilgrim-bounty-1
Privacy‑first fall‑risk bounty: labels‑in → cited action‑out. No cameras/mics. Deterministic, fast, fair. ≤2 citations shown; top‑3 logged with hashes.
Torchline Pilgrim Quest — Build a Fall‑Risk Loop (No Cameras. All Receipts.)

Who this is for
Young, hungry builders (<30). Solo or teams up to 3.

The one‑paragraph story (ELI5)
People in care deserve calm nights and fast help without being watched. Your job: build a tiny decision loop that reads simple signals (e.g., “bed‑exit”, motion bursts), suggests the next best 1–3 actions, and proves each suggestion with short citations (page numbers & timestamps)—not video/audio. We measure progress with Dignity Minutes (DM%)—time that is safe, comfortable, connected.

Non‑Negotiable Rails (you must follow all)

Surveillance‑Zero: no cameras, no microphones, no raw A/V. Only object‑level events (e.g., bed/seat mats, mmWave motion counts, door/beam crossings, prior‑incident flag, room/zone tokens).

Determinism: same inputs → byte‑identical outputs across 5 runs (including the same citations).

Speed: p95 < 1.0 s on the provided doc pack.

Proofs over footage: show ≤2 citations in the message; log top‑3 with doc_id, page, retrieval score, plus block_hash and index_version.

Fairness: equal‑risk → equal‑action. If weekly gap ≥ 1.0 pp, freeze learning/policy changes until fixed (safety alerts still allowed).

Reversibility (Churn‑Last): any suggested move must be reversible within 72h.

Personal clocks: start only when you hit Declare Start (PM 72h, Math 5d, Code 10d).

Prize governance: if <3 pass all gates, we may award Top‑2 or Top‑1 only; remainder goes to mentorship/round‑two.

Gates to Win (hard pass/fail)

DM% +15% uplift (simulated Thin Slice)

p95 < 1.0 s

Fairness gap < 1.0 pp (or freeze applied)

Byte‑identical outputs (5×)

Privacy incidents = 0 (no A/V, no PII leaks)
Fail any gate ⇒ not prize‑eligible.

Tracks (choose one; teams can compose)

PM One‑Pager (72h): one page + “Monday Stress Report” with 2–3 costed fixes and predicted minutes returned; all moves reversible within 72h.

Math/Algorithms (5d): traffic‑light rules (LOW/MED/HIGH), Fairness Watchdog (gap <1.0 pp; freeze if ≥1.0 pp), simple ZK‑lite explanation.

Code/Prototype (10d): Next‑Best‑3 with ≤2 shown / top‑3 logged; bias‑checked wording; p95 <1.0 s; byte‑identical; small DM% simulator.

Prizes & Path (recommended pool: $15,000)

$8,000 Code • $3,000 Math • $2,000 PM • $1,000 Composability • $500 Radar‑Sim • $500 Churn‑Last

Top‑3 also get a paid micro‑sprint + mentor time + fast‑track interview. #4/#5 get mentor time + interview.

What to Submit

Public repo (MIT/Apache‑2.0) with this README, the Receipts‑Only Rider, and a Hash‑Chained Manifest (artifact → SHA‑256).

Audit bundle: tiny input → output + logs demonstrating the gates.

Public thread link (X/GitHub/LinkedIn) + hunger story (≤150 words).

Important Links (replace with your real URLs)

Bounty Brief: [https://docs.google.com/document/d/1-0Y0KGknQlIq0KMxy8w5tAJekx7UbMC7Z9cNMV9MWgU/edit?usp=sharing]

Public FAQ: [https://docs.google.com/document/d/1iDIrh6h5yUUydCScjxzl7MKI_Lgvef4k8APmTU9oft8/edit?usp=sharing]

Entry Form: []

Community (Slack/Discord): [link]

Repo Layout

/litmus_pack/ — Locked (you’ll get a private link after Declare Start).

/acceptance/ — Locked (acceptance/golden tests used by judges; released only when relevant).

/docs/ — public text (non‑sensitive).

/samples/ — tiny public examples (no real inputs).

License

This repository is published under the Apache-2.0 License.

Entrants should license their own bounty repos under MIT or Apache-2.0.

Ethos

Fast help, no spying. Labels‑in → cited action‑out. Prove what you did with receipts any auditor can replay.
