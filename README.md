# Torchline Pilgrim Bounty 1 — Public Repo (Skeleton)

**North Star:** fast help, no spying. Labels‑in → cited action‑out — with receipts that any auditor can replay, every time.

## Quick links
- **Brief (read first)** → <ADD LINK>
- **Public FAQ** → <ADD LINK>
- **Entry Form (Registration + Effort Gate)** → <ADD LINK>

> ⚠️ **Entrants:** Do **not** submit here. Create **your own public repo** for your entry (MIT/Apache‑2.0) and link it in your public thread. This repo only publishes the public skeleton + rules.

---

## Who this is for
Builders under 30; solo or teams up to 3. Choose one track (PM / Math / Code), or compose across tracks.

## Tracks & clocks (start at **Declare Start**)
- **PM One‑Pager:** 72 hours
- **Math / Algorithms:** 5 days
- **Code / Prototype:** 10 days

Your personal clock starts **only** when you hit **Declare Start** in the form. We then email you the private pack and a countdown; timestamps are shown in **Australia/Brisbane**. 

## Non‑negotiable rails
- **Surveillance‑Zero:** no cameras/mics/raw A/V; object‑level events only.  
- **Determinism:** same inputs → **byte‑identical** outputs (including citations) across **5×** runs.  
- **Speed:** **p95 < 1.0 s** end‑to‑end on the provided doc pack.  
- **Proofs over footage:** show **≤2** citations in the message; **log top‑3** with `doc_id, page, score` + `index_version` + `block_hash`.  
- **Fairness:** equal-risk → equal-action; weekly gap **< 1.0 pp**, else **freeze** learning/changes (safety alerts allowed).  
  *Fairness is computed across cohorts (risk_band ∈ {LOW, MED, HIGH} × time_of_day ∈ {Day, Night}), with ≥30 decisions/week per cohort. Weekly gap must be <1.0 pp or you must freeze learning/policy changes until fixed. See Rails §5 for the full formula.*


- **Reversibility (Churn‑Last):** every suggested action must be reversible within **72h**.  
- **Language:** wording must be respectful and neutral; avoid blaming/stigmatizing terms. 

**Retrieval & tie‑breakers:** BM25 (or equivalent), **top‑k=3**; ties by **score → doc_id → page**.  
**Output caps:** **Nudge ≤80 chars**, **Reason ≤160**; show ≤2; log top‑3. 

## Gates to win (must pass all)
- **DM% +15% uplift** on the fixed **Thin Slice** (deterministic).  
- **p95 < 1.0 s**.  
- **Fairness gap < 1.0 pp** (or freeze applied).  
- **Byte‑identical 5×**.  
- **Privacy incidents = 0**. 

## Prize pool (AUD 15,000)
-## Prize pool (AUD 15,000)
- **Track awards:** Code **A$8,000** • Math **A$3,000** • PM **A$2,000**.  
- **Stackable bonuses:**  
  - **Composability A$1,000** — clear interfaces: swap docs/policy or replace retrieval without breaking logic.  
  - **Radar-Sim A$500** — mmWave-style motion burst simulator/adapter with deterministic seeds + reproducible bursts.  
  - **Churn-Last A$500** — lowest policy churn over a week: minimal action changes on similar inputs while still meeting gates.  
- **Extras:** Top-3 eligible entries overall → paid micro-sprint + mentor time + fast-track interview; overall **#4/#5** → mentor + interview.  
- **If <3 pass:** we may award Top-2 or Top-1 only; unawarded funds → mentorship/round-two.


## Entry steps (high‑level)
1) **Effort Gate:** one‑pager + 5‑Q basics quiz (DM%, p95, ≤2 vs top‑3, fairness freeze, SZ). One structured retake if needed.  
2) **Litmus** (15–30 min): return same **Next‑Best‑3** with same citations **5×** (p95<1s), compute a toy fairness gap & freeze at ≥1.0pp, accept object event & reject A/V at ingress; output a **signed receipt**. One retry within **48h** (100‑word reflection).  
3) **Declare Start:** starts your personal clock; you receive the **private pack** + **countdown** (A/Brisbane timestamps).  
4) **Public thread:** link your repo + short hunger story. 

## Submission pack (what judges expect)
- **Public repo (MIT/Apache‑2.0)** with README, **Receipts‑Only Rider**, and **Hash‑Chained Manifest**; **sign your final commit**.  
- **Audit bundle:** small input → output + logs demonstrating the gates.  
- **Public thread link + hunger story**.  
- **Litmus output:** captured in the Entry Form in the required field order (no repo copy needed). 

## Leaderboard (gates-only)
**Update cadence:** the leaderboard is **updated within 48 hours** of each submission.  
IDs are anonymised until judging; identity reveal is opt-in.  
Columns: **DM% P/F, p95 P/F, Fairness P/F (+Freeze), Determinism P/F, Privacy P/F, Bonuses, Last update**.

## Disallowed (instant DQ)
Any camera or microphone data; any attempt to reconstruct identity.  
Showing **>2** citations in the message (keep top‑3 only in logs).  
Non‑deterministic outputs or missing receipts. Ignoring Declare‑Start clocks / 48h inactivity pledge. 
