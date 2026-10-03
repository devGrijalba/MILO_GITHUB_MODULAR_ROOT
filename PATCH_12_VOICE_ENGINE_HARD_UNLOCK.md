# PATCH — 12_VOICE_ENGINE — HARD UNLOCK

## Purpose

Prevent Voice generation before a valid script exists.

Voice generation is prohibited unless:

```yaml
seed_identity: PASS
mechanical_qa: PASS
semantic_qa: PASS
script_final_gate: PASS
```

All four must be evidence-backed results from the current candidate.

If any gate is missing, unresolved, REPAIR_REQUIRED or FAIL_CRITICAL:
- do not generate `ELEVENLABS_V3_TEXT`;
- return to repair flow.

Do not treat presence of a candidate as PASS.
Do not treat a self-declared PASS label as evidence.
