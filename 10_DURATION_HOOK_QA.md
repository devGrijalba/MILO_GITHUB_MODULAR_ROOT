# QA — DURATION + HOOK

## DURACIÓN

Contar solo `beats[].narration`.

Fórmula:

`duracion_estimada_s = total_palabras_narration / 2`

PASS FINAL:
- 48–53 palabras

REPAIR_REQUIRED:
- 54–64 palabras

FAIL_CRITICAL:
- <48
- >64

54–64 obliga compresión antes de aprobación.

## HOOK

Exactamente 3 hooks.

`selected_hook_id` válido.

Texto seleccionado:
`selected_hook.text == beats[0].narration`

No revelar payoff.

No clickbait falso.
