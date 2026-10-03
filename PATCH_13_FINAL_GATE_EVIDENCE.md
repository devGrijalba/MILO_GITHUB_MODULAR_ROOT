# PATCH — 13_FINAL_GATE — EVIDENCE-BACKED FINAL PASS

## Purpose

Prevent self-certification and false final PASS.

Before final PASS verify:

1. seed identity has exact canonical evidence;
2. mechanical QA has computed evidence;
3. semantic QA has beat-level evidence;
4. required visible action has an actual beat;
5. actor continuity is proven by beat text and characters array;
6. duration is computed from final narration;
7. all repairs were revalidated;
8. Voice, if present, was generated only after script PASS;
9. final output corresponds exactly to the validated candidate.

Any missing evidence:
`REPAIR_REQUIRED`.

A value such as:
- PASS
- VALIDATED
- duration_target_seconds
- "had left"
- "had prepared"

is not by itself proof of compliance.
