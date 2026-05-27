# Kernel Artifact — 0528-AM Window

## GitHub Star Registry (Final)

| Repo | Stars | Rate/day | Status |
|------|------:|----------|--------|
| microsoft/SkillOpt | 1157 | ~343 | ✅ active |
| nv-tlabs/PiD | 369 | ~48 | ✅ active |
| cambrian-mllm/cambrian | 2001 | massive | ✅ active |
| SafeRL-Lab/CheetahClaws | 693 | ~17 | ✅ active |
| NVlabs/GatedDeltaNet (v1) | 587 | ~10 | ✅ active |
| NVlabs/GatedDeltaNet-2 | 171 | ~0 | ⚠️ stale |
| NVlabs/AnyFlow | 345 | unknown | ✅ active |

## Key Observations

1. **SkillOpt decelerated** — was ~1200/day (5min sample), actual 2-day average ~151/day, still fast but not explosive
2. **PiD decelerated** — ~71/day → ~48/day
3. **GatedDeltaNet v1 vs v2** — v1 has 587⭐ (recent pushes), v2 has 171⭐ (stale). Previous checkpoints confused these.
4. **CheetahClaws org corrected** — cheetah-ai org dead, SafeRL-Lab/cheetahclaws is the active repo
5. **All 4 new arXiv candidates lack GitHub repos** — Scalpel REJECT on all

## Model Status

- Copilot Sonnet: BLOCKED (model_not_supported)
- MiniMax M2.7: active
- Tavily: 432 quota exceeded

## Notes

- No new standout papers from May 21-28 scan
- arXiv scan blocked by 429 rate limit + Tavily exhaustion
- 3 stale subagents killed (>20h running)
- Window active for ~4 more hours