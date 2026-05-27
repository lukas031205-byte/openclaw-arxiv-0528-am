# Checkpoint #38b — 0528-AM Window | 05:52 CST (21:52 UTC)

**Last updated:** 2026-05-28 05:52 CST (21:52 UTC)
**Window:** 0528-AM autonomous research window
**Workflow:** rwr_mpojxq58_0e69d112

---

## ✅ Actions Taken

1. **Killed 3 stale subagents** (>20h running):
   - e8d19f54 (Scout, 20h37m) — old arXiv scan
   - f95ba800 (Scalpel, 23h4m) — old paper review
   - 701bf4c8 (Scout, 3d23h) — scout-0524-am zombie
2. **Killed 1 zombie Scout** (923dd9a5, 5m timeout) doing arXiv candidate verification
3. **Spawned new Scalpel** (932f886e) to review 4 new May 21-28 papers
4. **Verified all 7 confirmed standouts** via direct gh API

---

## GitHub Stars (21:52 UTC) — Verified

| Repo | Stars | vs Checkpoint #37 (12:30 UTC) | Rate |
|------|------:|-------------------------------|------|
| **SkillOpt** | **1157** | +129 (was 1028) | **~343/day** (decelerated from ~1200) |
| **PiD** | **369** | +18 (was 351) | **~48/day** (decelerated from ~71) |
| **Cambrian** | **2001** | large stable | massive |
| **CheetahClaws** | **693** | +2 (was 691, org corrected) | ~17/day |
| **GatedDeltaNet (v1)** | **587** | +3 (was 584? earlier count) | ~10/day |
| **GatedDeltaNet-2** | **171** | 0 (stale) | near-zero |
| **AnyFlow** | **345** | first measurement | unknown |

**Rate corrections:**
- SkillOpt: was estimated 1200/day based on 5min sample, real 2-day average ~151/day
- PiD: decelerated from ~71/day to ~48/day
- GatedDeltaNet-2 is essentially stale at 171⭐, last push May 25

---

## arXiv May 21-28 Candidates Status

| Paper | arXiv ID | GitHub | Scalpel Status |
|-------|----------|--------|----------------|
| SIA | 2605.27276 | ❌ NOT_FOUND | ⏳ running |
| MUSE-AutoSkill | 2605.27366 | ❌ NOT_FOUND | ⏳ running |
| Maat | 2605.27331 | ❌ NOT_FOUND (prev reported confirmed — wrong) | ⏳ running |
| MobileMoE | 2605.27358 | ❌ NOT_FOUND | ⏳ running |
| SAERL | 2605.27354 | ❌ NOT_FOUND | pending |
| BASIS | 2605.27293 | ❌ NOT_FOUND | pending |
| NoisyAgent | 2605.27209 | ❌ NOT_FOUND | pending |

**All 7 lack GitHub repos at submission time.** Scalpel review in progress.

---

## Copilot Model Status

- **Copilot Sonnet:** BLOCKED (model_not_supported) — recorded in workflow
- **MiniMax M2.7:** active, used for all subagents
- **Tavily:** 432 quota exceeded

---

## Window Info

- **Start:** 05:03 CST (21:03 UTC)
- **Timeout:** ~10:03 CST (02:03 UTC next day)
- **5h quota:** ~4h remaining
- **Scalpel subagent:** running (932f886e, ~2m so far)

---

## Workflow Status

- trigger: pass
- recall: pass
- scout_source_verified: pass (verified 7 confirmed standouts via direct gh API)
- scalpel_review: ⏳ in progress (4 papers, subagent running)
- kernel_artifact: pending
- github_publish: pending
- memory_candidate: pending
- domain_final: pending

*Next checkpoint after Scalpel completes or next Feishu report (~5:55 CST).*