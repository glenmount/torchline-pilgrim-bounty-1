Receipts‑Only Rider (Must‑Follow Rules)

We ship receipts, not streams. To participate, you agree to:

Surveillance‑Zero
No cameras, no microphones, no raw A/V. Only object‑level events. Any A/V at ingress must be rejected and logged with a signed receipt.

Determinism & Speed
Same inputs must produce byte‑identical outputs across 5 runs. p95 < 1.0 s on the provided doc pack.

Citations Discipline
Show ≤2 citations in your message. In logs, keep the top‑3 with doc_id, page, retrieval score, plus block_hash and index_version.

Fairness Watchdog
Equal‑risk → equal‑action. If weekly cohort gap ≥ 1.0 percentage point, you must freeze learning/policy changes until fixed (alerts still allowed). Include freeze_flag and fairness_gap_pp in your logs.

Reversibility (Churn‑Last)
Any suggested change must be reversible within 72 hours.

Receipts, Hashes, Versioning
Every nudge must log: timestamp, risk_level, nudge, reason, citations_shown (≤2), citations_top3 (doc/page/score), index_version, block_hash (hash‑chain), output_hash, fairness_gap_pp, freeze_flag. Target ≥99% proof coverage.

Prize Governance
If <3 pass all gates, prizes may be awarded to Top‑2 or Top‑1 only; unawarded funds move to mentorship/round‑two.

Disallowed (DQ immediately): any A/V or identity reconstruction; showing >2 citations; non‑deterministic outputs; missing receipts; violating Declare‑Start clocks or 48h inactivity pledge.

Signing your final commit implies acceptance of this Rider.
