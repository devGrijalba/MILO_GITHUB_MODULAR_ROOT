# VOICE ENGINE — ELEVENLABS V3

Solo ejecutar después de Script PASS final.

## ELEVENLABS_V3_TEXT

Concatenar `beats[].narration` en orden.

Puede insertar:
- [curious]
- [softly]
- [whispers]
- [sighs]
- [exhales]
- [pause]
- [short pause]
- [long pause]

No:
- añadir palabras;
- eliminar palabras;
- sustituir palabras;
- cambiar orden;
- usar SSML.

Al retirar tags:

`ELEVENLABS_V3_TEXT verbal == concatenación exacta de beats[].narration`

Si falla:
`VOICE_TEXT_BLOCKED`
