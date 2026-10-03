# SCRIPT_PACKAGE — EXACT SCHEMA

## ROOT

Obligatorias:

- `episode_id`: string
- `seed_id`: string
- `bank_version`: string
- `seed_hash`: string
- `title`: string
- `central_conflict`: string
- `payoff`: string
- `share_recipient`: string
- `novelty_justification`: string
- `selected_hook_id`: string
- `seed_snapshot`: object
- `hooks`: array[object]
- `music`: boolean
- `sfx`: boolean
- `beats`: array[object]

Reglas:
- `music == false`
- `sfx == false`
- `hooks.length == 3`
- `beats.length >= 4`

## HOOK

Cada hook:

- `id`: string
- `text`: string
- `reason`: string

IDs:
- H1
- H2
- H3

`selected_hook.text == beats[0].narration`

## BEAT

Exactamente estas claves funcionales:

- `beat_id`: string
- `function`: string
- `narration`: string
- `new_information`: string
- `visual_action`: string
- `narration_visual_link`: string
- `characters`: array[string]
- `world_id`: enum[string]
- `voice_intention`: string
- `pause_after_s`: number
- `text_emphasis`: string
- `shot`: object
- `transition`: object
- `director_direction`: object
- `director_voice_text`: string

`text_emphasis` DEBE ser string.

## SHOT

- `scale`: enum[string]
- `motion`: enum[string]
- `motion_reason`: string
- `continuity`: string
- `subtitle_safe_top`: boolean

scale:
- establishing
- medium
- close_up
- insert
- extreme_close_up
- emotional_wide

motion:
- push_in
- pull_out
- pan
- still
- reveal
- parallax

`subtitle_safe_top == true`

## TRANSITION

- `type`: enum[string]
- `duration_s`: number
- `reason`: string

type:
- cut
- match_cut
- dissolve
- motivated_blur

Reglas:
- `0 <= duration_s <= 0.6`
- `cut => duration_s == 0`

## DIRECTOR_DIRECTION

Todos string:
- viewer_emotion
- narrator_intention
- emotional_entry
- emotional_exit
- emphasis
- pause_reason
- visual_sync
- forbidden_delivery

## PROHIBIDO

- transition_to_next
- medium_shot
- medium_close_up
- static
- pan_right
- kitchen_detail
