# MILO SEEDS — PARTE 03

Banco: `2.0.0`
Registros: `0201–0300`

## REGLAS

- Datos canónicos.
- No inventar campos.
- No recalcular seed_hash.
- El seed_id puede normalizarse desde el encabezado lógico/registro según `18_SEED_HEADER_NORMALIZATION.md`.

# MILO-S0201 — Puerta: la primera vez

```json
{
  "seed_id": "MILO-S0201",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "primera_vez",
  "titulo": "Puerta: la primera vez",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo no sabe si acercarse. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "Milo no sabe si acercarse",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión",
  "objeto_emocional": "puerta",
  "giro_posible": "una pregunta sencilla inicia la reparación",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "hermano"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo no sabe si acercarse",
      "conflicto": "Milo no sabe si acercarse",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "una pregunta sencilla inicia la reparación",
      "visual": "el hermano deja entreabierta la puerta tras una discusión",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión",
      "objeto": "puerta",
      "reinterpretacion": "una pregunta sencilla inicia la reparación",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo no sabe si acercarse"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0202 — Puerta: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0202",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_2",
  "titulo": "Puerta: la copia que no funcionó",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "puerta",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0202",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "puerta",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0203 — Puerta: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0203",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_3",
  "titulo": "Puerta: el favor convertido en deuda",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "puerta",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0203",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "puerta",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0204 — Puerta: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0204",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_4",
  "titulo": "Puerta: dos personas, dos necesidades",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "puerta",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0204",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "puerta",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0205 — Puerta: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0205",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_5",
  "titulo": "Puerta: el acuerdo que nadie había entendido",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "puerta",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0205",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "puerta",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0206 — Puerta: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0206",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_6",
  "titulo": "Puerta: la ayuda que cambió algo querido",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "puerta",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0206",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "puerta",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0207 — Puerta: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0207",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_7",
  "titulo": "Puerta: la pregunta que no quería hacer",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "puerta",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0207",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "puerta",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0208 — Puerta: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0208",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_8",
  "titulo": "Puerta: el recuerdo que tenían distinto",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "puerta",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0208",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "puerta",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0209 — Puerta: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0209",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_9",
  "titulo": "Puerta: el agradecimiento dicho demasiado tarde",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "puerta",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0209",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "puerta",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0210 — Puerta: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0210",
  "family_id": "F021",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_10",
  "titulo": "Puerta: el cuidado que necesitó permiso",
  "semilla": "El hermano deja entreabierta la puerta tras una discusión. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "el hermano deja entreabierta la puerta tras una discusión. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "puerta",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0210",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "una pregunta sencilla inicia la reparación",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde puerta y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "el hermano deja entreabierta la puerta tras una discusión. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano deja entreabierta la puerta tras una discusión. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "puerta",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0211 — Control remoto: la primera vez

```json
{
  "seed_id": "MILO-S0211",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "primera_vez",
  "titulo": "Control remoto: la primera vez",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo siente que nunca lo escuchan. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "Milo siente que nunca lo escuchan",
  "accion_visible": "dos hermanos pelean por elegir qué ver",
  "objeto_emocional": "control remoto",
  "giro_posible": "acordar turnos vuelve visible a ambos",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "hermano"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo siente que nunca lo escuchan",
      "conflicto": "Milo siente que nunca lo escuchan",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "acordar turnos vuelve visible a ambos",
      "visual": "dos hermanos pelean por elegir qué ver",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver",
      "objeto": "control remoto",
      "reinterpretacion": "acordar turnos vuelve visible a ambos",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo siente que nunca lo escuchan"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0212 — Control remoto: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0212",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_2",
  "titulo": "Control remoto: la copia que no funcionó",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0212",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "control remoto",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0213 — Control remoto: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0213",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_3",
  "titulo": "Control remoto: el favor convertido en deuda",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0213",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "control remoto",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0214 — Control remoto: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0214",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_4",
  "titulo": "Control remoto: dos personas, dos necesidades",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0214",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "control remoto",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0215 — Control remoto: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0215",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_5",
  "titulo": "Control remoto: el acuerdo que nadie había entendido",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0215",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "control remoto",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0216 — Control remoto: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0216",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_6",
  "titulo": "Control remoto: la ayuda que cambió algo querido",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0216",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "control remoto",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0217 — Control remoto: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0217",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_7",
  "titulo": "Control remoto: la pregunta que no quería hacer",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0217",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "control remoto",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0218 — Control remoto: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0218",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_8",
  "titulo": "Control remoto: el recuerdo que tenían distinto",
  "semilla": "Dos hermanos pelean por elegir qué ver. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0218",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "dos hermanos pelean por elegir qué ver. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "control remoto",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0219 — Control remoto: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0219",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_9",
  "titulo": "Control remoto: el agradecimiento dicho demasiado tarde",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0219",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "control remoto",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0220 — Control remoto: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0220",
  "family_id": "F022",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_10",
  "titulo": "Control remoto: el cuidado que necesitó permiso",
  "semilla": "Dos hermanos pelean por elegir qué ver. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "dos hermanos pelean por elegir qué ver. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "control remoto",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0220",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "acordar turnos vuelve visible a ambos",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde control remoto y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "dos hermanos pelean por elegir qué ver. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "dos hermanos pelean por elegir qué ver. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "control remoto",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0221 — Juguete compartido: la primera vez

```json
{
  "seed_id": "MILO-S0221",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "primera_vez",
  "titulo": "Juguete compartido: la primera vez",
  "semilla": "Milo encuentra un juguete que usaban juntos. Cree que su hermano olvidó aquella época. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "cree que su hermano olvidó aquella época",
  "accion_visible": "Milo encuentra un juguete que usaban juntos",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "el hermano conserva la pieza que falta",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "cree que su hermano olvidó aquella época",
      "conflicto": "cree que su hermano olvidó aquella época",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "el hermano conserva la pieza que falta",
      "visual": "Milo encuentra un juguete que usaban juntos",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos",
      "objeto": "juguete compartido",
      "reinterpretacion": "el hermano conserva la pieza que falta",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "cree que su hermano olvidó aquella época"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0222 — Juguete compartido: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0222",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_2",
  "titulo": "Juguete compartido: la copia que no funcionó",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0222",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0223 — Juguete compartido: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0223",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_3",
  "titulo": "Juguete compartido: el favor convertido en deuda",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0223",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0224 — Juguete compartido: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0224",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_4",
  "titulo": "Juguete compartido: dos personas, dos necesidades",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0224",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0225 — Juguete compartido: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0225",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_5",
  "titulo": "Juguete compartido: el acuerdo que nadie había entendido",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0225",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0226 — Juguete compartido: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0226",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_6",
  "titulo": "Juguete compartido: la ayuda que cambió algo querido",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0226",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0227 — Juguete compartido: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0227",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_7",
  "titulo": "Juguete compartido: la pregunta que no quería hacer",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0227",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0228 — Juguete compartido: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0228",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_8",
  "titulo": "Juguete compartido: el recuerdo que tenían distinto",
  "semilla": "Milo encuentra un juguete que usaban juntos. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0228",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo encuentra un juguete que usaban juntos. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0229 — Juguete compartido: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0229",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_9",
  "titulo": "Juguete compartido: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0229",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0230 — Juguete compartido: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0230",
  "family_id": "F023",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_10",
  "titulo": "Juguete compartido: el cuidado que necesitó permiso",
  "semilla": "Milo encuentra un juguete que usaban juntos. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo encuentra un juguete que usaban juntos. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "juguete compartido",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0230",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "el hermano conserva la pieza que falta",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde juguete compartido y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo encuentra un juguete que usaban juntos. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo encuentra un juguete que usaban juntos. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "juguete compartido",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0231 — Dos tazas: la primera vez

```json
{
  "seed_id": "MILO-S0231",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "primera_vez",
  "titulo": "Dos tazas: la primera vez",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo interpreta el retraso como rechazo. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "Milo interpreta el retraso como rechazo",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado",
  "objeto_emocional": "dos tazas",
  "giro_posible": "pueden fijar un momento que sí cumplan",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "hermano"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo interpreta el retraso como rechazo",
      "conflicto": "Milo interpreta el retraso como rechazo",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "pueden fijar un momento que sí cumplan",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado",
      "objeto": "dos tazas",
      "reinterpretacion": "pueden fijar un momento que sí cumplan",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo interpreta el retraso como rechazo"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0232 — Dos tazas: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0232",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_2",
  "titulo": "Dos tazas: la copia que no funcionó",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0232",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "dos tazas",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0233 — Dos tazas: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0233",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_3",
  "titulo": "Dos tazas: el favor convertido en deuda",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0233",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "dos tazas",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0234 — Dos tazas: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0234",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_4",
  "titulo": "Dos tazas: dos personas, dos necesidades",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0234",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "dos tazas",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0235 — Dos tazas: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0235",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_5",
  "titulo": "Dos tazas: el acuerdo que nadie había entendido",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0235",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "dos tazas",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0236 — Dos tazas: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0236",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_6",
  "titulo": "Dos tazas: la ayuda que cambió algo querido",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0236",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "dos tazas",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0237 — Dos tazas: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0237",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_7",
  "titulo": "Dos tazas: la pregunta que no quería hacer",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0237",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "dos tazas",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0238 — Dos tazas: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0238",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_8",
  "titulo": "Dos tazas: el recuerdo que tenían distinto",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0238",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "dos tazas",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0239 — Dos tazas: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0239",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_9",
  "titulo": "Dos tazas: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0239",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "dos tazas",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0240 — Dos tazas: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0240",
  "family_id": "F024",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_10",
  "titulo": "Dos tazas: el cuidado que necesitó permiso",
  "semilla": "Milo prepara dos bebidas pero el hermano está ocupado. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo prepara dos bebidas pero el hermano está ocupado. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "dos tazas",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0240",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "pueden fijar un momento que sí cumplan",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde dos tazas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo prepara dos bebidas pero el hermano está ocupado. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "Milo prepara dos bebidas pero el hermano está ocupado. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "dos tazas",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0241 — Caja de mudanza: la primera vez

```json
{
  "seed_id": "MILO-S0241",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "primera_vez",
  "titulo": "Caja de mudanza: la primera vez",
  "semilla": "El hermano retira sus objetos de la habitación. Milo siente que también retira el vínculo. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "Milo siente que también retira el vínculo",
  "accion_visible": "el hermano retira sus objetos de la habitación",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "una visita acordada mantiene una puerta real",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "hermano"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo siente que también retira el vínculo",
      "conflicto": "Milo siente que también retira el vínculo",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "una visita acordada mantiene una puerta real",
      "visual": "el hermano retira sus objetos de la habitación",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación",
      "objeto": "caja de mudanza",
      "reinterpretacion": "una visita acordada mantiene una puerta real",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo siente que también retira el vínculo"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0242 — Caja de mudanza: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0242",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_2",
  "titulo": "Caja de mudanza: la copia que no funcionó",
  "semilla": "El hermano retira sus objetos de la habitación. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0242",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "el hermano retira sus objetos de la habitación. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0243 — Caja de mudanza: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0243",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_3",
  "titulo": "Caja de mudanza: el favor convertido en deuda",
  "semilla": "El hermano retira sus objetos de la habitación. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0243",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "el hermano retira sus objetos de la habitación. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0244 — Caja de mudanza: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0244",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_4",
  "titulo": "Caja de mudanza: dos personas, dos necesidades",
  "semilla": "El hermano retira sus objetos de la habitación. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0244",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "el hermano retira sus objetos de la habitación. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0245 — Caja de mudanza: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0245",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_5",
  "titulo": "Caja de mudanza: el acuerdo que nadie había entendido",
  "semilla": "El hermano retira sus objetos de la habitación. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0245",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "el hermano retira sus objetos de la habitación. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0246 — Caja de mudanza: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0246",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_6",
  "titulo": "Caja de mudanza: la ayuda que cambió algo querido",
  "semilla": "El hermano retira sus objetos de la habitación. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0246",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "el hermano retira sus objetos de la habitación. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0247 — Caja de mudanza: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0247",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_7",
  "titulo": "Caja de mudanza: la pregunta que no quería hacer",
  "semilla": "El hermano retira sus objetos de la habitación. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0247",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "el hermano retira sus objetos de la habitación. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0248 — Caja de mudanza: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0248",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_8",
  "titulo": "Caja de mudanza: el recuerdo que tenían distinto",
  "semilla": "El hermano retira sus objetos de la habitación. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "el hermano retira sus objetos de la habitación. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0248",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "el hermano retira sus objetos de la habitación. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0249 — Caja de mudanza: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0249",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_9",
  "titulo": "Caja de mudanza: el agradecimiento dicho demasiado tarde",
  "semilla": "El hermano retira sus objetos de la habitación. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0249",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "el hermano retira sus objetos de la habitación. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0250 — Caja de mudanza: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0250",
  "family_id": "F025",
  "territorio": "Hermanos y distancia",
  "angulo": "arco_causal_10",
  "titulo": "Caja de mudanza: el cuidado que necesitó permiso",
  "semilla": "El hermano retira sus objetos de la habitación. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "el hermano retira sus objetos de la habitación. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "caja de mudanza",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "adulto; recuerdo infantil solo si el guion lo justifica",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "OMS"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0250",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "una visita acordada mantiene una puerta real",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde caja de mudanza y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "el hermano retira sus objetos de la habitación. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Hermanos y distancia; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Hermanos y distancia",
      "conducta": "el hermano retira sus objetos de la habitación. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "caja de mudanza",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0251 — Dibujo: la primera vez

```json
{
  "seed_id": "MILO-S0251",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "primera_vez",
  "titulo": "Dibujo: la primera vez",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Cree que lo vieron porque dijeron bonito. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "cree que lo vieron porque dijeron bonito",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina",
  "objeto_emocional": "dibujo",
  "giro_posible": "el adulto vuelve para preguntar por un detalle",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "cree que lo vieron porque dijeron bonito",
      "conflicto": "cree que lo vieron porque dijeron bonito",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "el adulto vuelve para preguntar por un detalle",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina",
      "objeto": "dibujo",
      "reinterpretacion": "el adulto vuelve para preguntar por un detalle",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "cree que lo vieron porque dijeron bonito"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0252 — Dibujo: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0252",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_2",
  "titulo": "Dibujo: la copia que no funcionó",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0252",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "dibujo",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0253 — Dibujo: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0253",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_3",
  "titulo": "Dibujo: el favor convertido en deuda",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0253",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "dibujo",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0254 — Dibujo: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0254",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_4",
  "titulo": "Dibujo: dos personas, dos necesidades",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0254",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "dibujo",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0255 — Dibujo: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0255",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_5",
  "titulo": "Dibujo: el acuerdo que nadie había entendido",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0255",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "dibujo",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0256 — Dibujo: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0256",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_6",
  "titulo": "Dibujo: la ayuda que cambió algo querido",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0256",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "dibujo",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0257 — Dibujo: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0257",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_7",
  "titulo": "Dibujo: la pregunta que no quería hacer",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0257",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "dibujo",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0258 — Dibujo: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0258",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_8",
  "titulo": "Dibujo: el recuerdo que tenían distinto",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0258",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "dibujo",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0259 — Dibujo: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0259",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_9",
  "titulo": "Dibujo: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0259",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "dibujo",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0260 — Dibujo: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0260",
  "family_id": "F026",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_10",
  "titulo": "Dibujo: el cuidado que necesitó permiso",
  "semilla": "Milo niño enseña un dibujo mientras un adulto cocina. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo niño enseña un dibujo mientras un adulto cocina. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "dibujo",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0260",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "el adulto vuelve para preguntar por un detalle",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde dibujo y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo niño enseña un dibujo mientras un adulto cocina. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño enseña un dibujo mientras un adulto cocina. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "dibujo",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0261 — Torre de bloques: la primera vez

```json
{
  "seed_id": "MILO-S0261",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "primera_vez",
  "titulo": "Torre de bloques: la primera vez",
  "semilla": "Una torre se cae y Milo niño se enfada. Un adulto quiere arreglarla de inmediato. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "un adulto quiere arreglarla de inmediato",
  "accion_visible": "una torre se cae y Milo niño se enfada",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "acompañar su frustración precede a reconstruir",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "un adulto quiere arreglarla de inmediato",
      "conflicto": "un adulto quiere arreglarla de inmediato",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "acompañar su frustración precede a reconstruir",
      "visual": "una torre se cae y Milo niño se enfada",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "una torre se cae y Milo niño se enfada",
      "objeto": "torre de bloques",
      "reinterpretacion": "acompañar su frustración precede a reconstruir",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "un adulto quiere arreglarla de inmediato"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0262 — Torre de bloques: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0262",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_2",
  "titulo": "Torre de bloques: la copia que no funcionó",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0262",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0263 — Torre de bloques: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0263",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_3",
  "titulo": "Torre de bloques: el favor convertido en deuda",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0263",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0264 — Torre de bloques: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0264",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_4",
  "titulo": "Torre de bloques: dos personas, dos necesidades",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0264",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0265 — Torre de bloques: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0265",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_5",
  "titulo": "Torre de bloques: el acuerdo que nadie había entendido",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0265",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0266 — Torre de bloques: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0266",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_6",
  "titulo": "Torre de bloques: la ayuda que cambió algo querido",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0266",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0267 — Torre de bloques: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0267",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_7",
  "titulo": "Torre de bloques: la pregunta que no quería hacer",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0267",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0268 — Torre de bloques: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0268",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_8",
  "titulo": "Torre de bloques: el recuerdo que tenían distinto",
  "semilla": "Una torre se cae y Milo niño se enfada. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0268",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Una torre se cae y Milo niño se enfada. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0269 — Torre de bloques: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0269",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_9",
  "titulo": "Torre de bloques: el agradecimiento dicho demasiado tarde",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0269",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0270 — Torre de bloques: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0270",
  "family_id": "F027",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_10",
  "titulo": "Torre de bloques: el cuidado que necesitó permiso",
  "semilla": "Una torre se cae y Milo niño se enfada. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Una torre se cae y Milo niño se enfada. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "torre de bloques",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0270",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "acompañar su frustración precede a reconstruir",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde torre de bloques y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Una torre se cae y Milo niño se enfada. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Una torre se cae y Milo niño se enfada. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "torre de bloques",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0271 — Peluche: el gesto que llegó a la persona equivocada

```json
{
  "seed_id": "MILO-R0271",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_1",
  "titulo": "Peluche: el gesto que llegó a la persona equivocada",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
  "conflicto": "Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
  "objeto_emocional": "peluche",
  "giro_posible": "El reconocimiento puede incluir a quien quedó fuera de la primera explicación.",
  "desarrollo_requerido": "Atribución equivocada → agradecimiento mal dirigido → reacción visible → pregunta → reconocimiento corregido.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0271",
  "cambio_causal": "Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC01",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
      "conflicto": "Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Atribución equivocada → agradecimiento mal dirigido → reacción visible → pregunta → reconocimiento corregido.",
      "revelacion": "El reconocimiento puede incluir a quien quedó fuera de la primera explicación.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión.",
      "objeto": "peluche",
      "reinterpretacion": "El reconocimiento puede incluir a quien quedó fuera de la primera explicación.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo atribuye la acción a la persona equivocada y le agradece delante de quien realmente la realizó. Al ver la reacción, pregunta quién participó en lugar de insistir en su versión."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0272 — Peluche: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0272",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_2",
  "titulo": "Peluche: la copia que no funcionó",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "peluche",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0272",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "peluche",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0273 — Peluche: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0273",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_3",
  "titulo": "Peluche: el favor convertido en deuda",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "peluche",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0273",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "peluche",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0274 — Peluche: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0274",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_4",
  "titulo": "Peluche: dos personas, dos necesidades",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "peluche",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0274",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "peluche",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0275 — Peluche: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0275",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_5",
  "titulo": "Peluche: el acuerdo que nadie había entendido",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "peluche",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0275",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "peluche",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0276 — Peluche: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0276",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_6",
  "titulo": "Peluche: la ayuda que cambió algo querido",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "peluche",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0276",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "peluche",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0277 — Peluche: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0277",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_7",
  "titulo": "Peluche: la pregunta que no quería hacer",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "peluche",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0277",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "peluche",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0278 — Peluche: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0278",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_8",
  "titulo": "Peluche: el recuerdo que tenían distinto",
  "semilla": "Milo niño sienta un peluche lejos de los demás. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "peluche",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0278",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo niño sienta un peluche lejos de los demás. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "peluche",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0279 — Peluche: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0279",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_9",
  "titulo": "Peluche: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "peluche",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0279",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "peluche",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0280 — Peluche: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0280",
  "family_id": "F028",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_10",
  "titulo": "Peluche: el cuidado que necesitó permiso",
  "semilla": "Milo niño sienta un peluche lejos de los demás. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo niño sienta un peluche lejos de los demás. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "peluche",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0280",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "preguntarle permite escuchar sin adivinar",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde peluche y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo niño sienta un peluche lejos de los demás. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño sienta un peluche lejos de los demás. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "peluche",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0281 — Linterna: la primera vez

```json
{
  "seed_id": "MILO-S0281",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "primera_vez",
  "titulo": "Linterna: la primera vez",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Teme parecer cobarde. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "teme parecer cobarde",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo",
  "objeto_emocional": "linterna",
  "giro_posible": "hacer el recorrido juntos convierte miedo en conversación",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "teme parecer cobarde",
      "conflicto": "teme parecer cobarde",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "hacer el recorrido juntos convierte miedo en conversación",
      "visual": "Milo niño pide compañía para recorrer el pasillo",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo",
      "objeto": "linterna",
      "reinterpretacion": "hacer el recorrido juntos convierte miedo en conversación",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "teme parecer cobarde"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0282 — Linterna: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0282",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_2",
  "titulo": "Linterna: la copia que no funcionó",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "linterna",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0282",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "linterna",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0283 — Linterna: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0283",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_3",
  "titulo": "Linterna: el favor convertido en deuda",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "linterna",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0283",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "linterna",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0284 — Linterna: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0284",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_4",
  "titulo": "Linterna: dos personas, dos necesidades",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "linterna",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0284",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "linterna",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0285 — Linterna: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0285",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_5",
  "titulo": "Linterna: el acuerdo que nadie había entendido",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "linterna",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0285",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "linterna",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0286 — Linterna: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0286",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_6",
  "titulo": "Linterna: la ayuda que cambió algo querido",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "linterna",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0286",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "linterna",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0287 — Linterna: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0287",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_7",
  "titulo": "Linterna: la pregunta que no quería hacer",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "linterna",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0287",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "linterna",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0288 — Linterna: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0288",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_8",
  "titulo": "Linterna: el recuerdo que tenían distinto",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "linterna",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0288",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "linterna",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0289 — Linterna: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0289",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_9",
  "titulo": "Linterna: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "linterna",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0289",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "linterna",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0290 — Linterna: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0290",
  "family_id": "F029",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_10",
  "titulo": "Linterna: el cuidado que necesitó permiso",
  "semilla": "Milo niño pide compañía para recorrer el pasillo. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo niño pide compañía para recorrer el pasillo. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "linterna",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0290",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "hacer el recorrido juntos convierte miedo en conversación",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde linterna y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo niño pide compañía para recorrer el pasillo. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño pide compañía para recorrer el pasillo. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "linterna",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-S0291 — Rompecabezas: la primera vez

```json
{
  "seed_id": "MILO-S0291",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "primera_vez",
  "titulo": "Rompecabezas: la primera vez",
  "semilla": "Milo niño oculta una pieza que no encaja. Cree que equivocarse decepciona. Tratamiento: Milo observa por primera vez la situación y debe comprobar su interpretación antes de actuar.",
  "conflicto": "cree que equivocarse decepciona",
  "accion_visible": "Milo niño oculta una pieza que no encaja",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "un adulto comparte su propio intento fallido",
  "desarrollo_requerido": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo"
  ],
  "personajes_secundarios": "Resolver identidad y disponibilidad de referencias desde canon antes de producir; no inventar anclas aprobadas.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PENDING_SCRIPT_REVIEW",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 85,
    "compuesto": 88.75,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "cree que equivocarse decepciona",
      "conflicto": "cree que equivocarse decepciona",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Mostrar situación → lectura inicial → detalle que contradice → pregunta o gesto concreto.",
      "revelacion": "un adulto comparte su propio intento fallido",
      "visual": "Milo niño oculta una pieza que no encaja",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja",
      "objeto": "rompecabezas",
      "reinterpretacion": "un adulto comparte su propio intento fallido",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "cree que equivocarse decepciona"
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0292 — Rompecabezas: la copia que no funcionó

```json
{
  "seed_id": "MILO-R0292",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_2",
  "titulo": "Rompecabezas: la copia que no funcionó",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
  "desarrollo_requerido": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0292",
  "cambio_causal": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC02",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "conflicto": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Modelo observado → intento imperfecto → ocultamiento breve → petición de ayuda → tarea compartida.",
      "revelacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Comprender el gesto incluye poder aprender sin fingir que ya sabe hacerlo.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo intenta repetir la acción para demostrar que ya entendió, pero su intento falla. Esconde el resultado un momento y después lo muestra para pedir ayuda."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0293 — Rompecabezas: el favor convertido en deuda

```json
{
  "seed_id": "MILO-R0293",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_3",
  "titulo": "Rompecabezas: el favor convertido en deuda",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
  "desarrollo_requerido": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0293",
  "cambio_causal": "Milo recibe el gesto y comienza a aceptar encargos que no puede sostener por sentirse en deuda. Cuando deja una tarea a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC03",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "conflicto": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Gesto recibido → promesa excesiva → tarea sin terminar → conversación → acuerdo limitado y concreto.",
      "revelacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Agradecer un gesto no exige prometer una disponibilidad que no puede cumplir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo recibe el gesto y comienza a aceptar turnos de juego que no quiere aceptar por sentirse en deuda. Cuando deja una juego a medias, reconoce lo ocurrido y acuerda qué puede ofrecer."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0294 — Rompecabezas: dos personas, dos necesidades

```json
{
  "seed_id": "MILO-R0294",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_4",
  "titulo": "Rompecabezas: dos personas, dos necesidades",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Una misma intención puede requerir dos formas distintas de cuidado.",
  "desarrollo_requerido": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0294",
  "cambio_causal": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC04",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "conflicto": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Respuesta uniforme → aceptación y rechazo → incomodidad → pedidos diferentes → dos acciones ajustadas.",
      "revelacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Una misma intención puede requerir dos formas distintas de cuidado.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara la misma respuesta para dos familiares presentes; uno la acepta y el otro dice que necesita algo distinto. Milo se siente rechazado y luego escucha ambos pedidos antes de actuar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0295 — Rompecabezas: el acuerdo que nadie había entendido

```json
{
  "seed_id": "MILO-R0295",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_5",
  "titulo": "Rompecabezas: el acuerdo que nadie había entendido",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
  "desarrollo_requerido": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0295",
  "cambio_causal": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC05",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "conflicto": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Acuerdo ambiguo → espera mutua → objeto pendiente → versiones contradictorias → nuevo acuerdo visible.",
      "revelacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Decir cuándo y quién hará cada parte evita convertir un malentendido en desinterés.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo cree que el familiar entendió un acuerdo relacionado con la escena, pero ambos esperan que el otro actúe. Ante el objeto sin atender, repiten lo acordado y descubren dos versiones diferentes."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0296 — Rompecabezas: la ayuda que cambió algo querido

```json
{
  "seed_id": "MILO-R0296",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_6",
  "titulo": "Rompecabezas: la ayuda que cambió algo querido",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Mejorar un espacio también requiere escuchar a quien lo usa.",
  "desarrollo_requerido": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0296",
  "cambio_causal": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC06",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "conflicto": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Intervención bien intencionada → detalle desplazado → desacuerdo → explicación → decisión compartida.",
      "revelacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Mejorar un espacio también requiere escuchar a quien lo usa.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo reorganiza el espacio alrededor del objeto para ayudar sin consultar. El familiar busca un detalle que ya no está en su lugar. Milo reconoce su intervención y ambos eligen qué devolver y qué cambiar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0297 — Rompecabezas: la pregunta que no quería hacer

```json
{
  "seed_id": "MILO-R0297",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_7",
  "titulo": "Rompecabezas: la pregunta que no quería hacer",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
  "desarrollo_requerido": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0297",
  "cambio_causal": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC07",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "conflicto": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Observación parcial → explicación anticipada → pregunta sobre objeto → hecho nuevo → ayuda concreta.",
      "revelacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Una pregunta verificable permite sustituir una suposición por una acción útil.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo observa la escena desde el pasillo y ensaya una explicación. Al entrar, pregunta por un detalle concreto; el familiar responde con un hecho que Milo no había visto y le muestra la parte pendiente."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0298 — Rompecabezas: el recuerdo que tenían distinto

```json
{
  "seed_id": "MILO-R0298",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_8",
  "titulo": "Rompecabezas: el recuerdo que tenían distinto",
  "semilla": "Milo niño oculta una pieza que no encaja. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
  "desarrollo_requerido": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "descubrimiento",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0298",
  "cambio_causal": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC08",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "conflicto": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Objeto presente → recuerdos diferentes → desacuerdo → evidencia disponible → reconocimiento de incertidumbre.",
      "revelacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "visual": "Milo niño oculta una pieza que no encaja. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Compartir recuerdos no obliga a imponer una única versión ni a inventar certezas.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "El objeto abre una conversación sobre una escena anterior. Milo y un familiar recuerdan decisiones distintas; buscan una foto o una marca material disponible y admiten lo que no pueden comprobar."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0299 — Rompecabezas: el agradecimiento dicho demasiado tarde

```json
{
  "seed_id": "MILO-R0299",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_9",
  "titulo": "Rompecabezas: el agradecimiento dicho demasiado tarde",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
  "desarrollo_requerido": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "representacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0299",
  "cambio_causal": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC09",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "conflicto": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Preparación de discurso → aplazamiento → visita termina → agradecimiento específico → respuesta contenida.",
      "revelacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la encuentro familiar; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Una frase concreta durante el encuentro puede acercar más que un discurso siempre pendiente.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo prepara una frase larga sobre el gesto pero sigue posponiendo decirla. El familiar comienza a recoger para terminar la visita; Milo deja el discurso a un lado y nombra una ayuda específica antes de despedirse."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```

# MILO-R0300 — Rompecabezas: el cuidado que necesitó permiso

```json
{
  "seed_id": "MILO-R0300",
  "family_id": "F030",
  "territorio": "Infancia y escucha",
  "angulo": "arco_causal_10",
  "titulo": "Rompecabezas: el cuidado que necesitó permiso",
  "semilla": "Milo niño oculta una pieza que no encaja. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "accion_visible": "Milo niño oculta una pieza que no encaja. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "objeto_emocional": "rompecabezas",
  "giro_posible": "Detenerse a preguntar puede cuidar tanto como intervenir.",
  "desarrollo_requerido": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
  "milo_role": "niño",
  "personajes_requeridos": [
    "Milo",
    "familiar presente por resolver desde canon"
  ],
  "personajes_secundarios": "En ausencia/duelo, el interlocutor es un familiar presente: no hacer hablar a alguien fallecido. En infancia, conservar rol infantil y adulto responsable. Identidad visual por resolver.",
  "world_candidates": [
    "kitchen_day",
    "living_room_day",
    "bedroom_day",
    "home_entrance_day",
    "hallway_day",
    "patio_day"
  ],
  "motor_editorial": "identificacion",
  "destinatario_emocional": "Alguien que reconoce esta tensión doméstica; concretarlo durante estrategia, sin CTA obligatorio.",
  "fuentes_tematicas": [
    "BASE_MINERIA",
    "CANON",
    "UNICEF"
  ],
  "procedencia": "ficcion_original_inspirada_en_temas; no historia extraída de la fuente",
  "estado": "EDITORIAL_ELIGIBLE",
  "qc_editorial": "PROVISIONAL_SEED_PASS_NOT_SCRIPT_APPROVAL",
  "duracion": "Estimar desde guion y pausas; ajustar al audio real.",
  "restricciones": [
    "No convertir cuidado en justificación de daño.",
    "No presentar pensamientos o diagnósticos como hechos.",
    "No repetir la misma familia en episodios consecutivos.",
    "Subtítulos superiores; imagen sin texto incrustado.",
    "Música y SFX desactivados."
  ],
  "replaces_seed_id": "MILO-S0300",
  "cambio_causal": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
  "giro_base_descartado": "un adulto comparte su propio intento fallido",
  "narrative_cluster_id": "ARC10",
  "revision": {
    "quality_notes": {
      "reconocimiento": 4.5,
      "conflicto": 4.5,
      "hook": 4.5,
      "progresion": 4.5,
      "revelacion": 4.5,
      "visual": 4.5,
      "compartibilidad": 4
    },
    "affinity_notes": {
      "territorio": 4.5,
      "conducta": 4.5,
      "objeto": 4.5,
      "reinterpretacion": 4.5,
      "tono": 4.5,
      "visual": 4.5,
      "representacion": 4.5
    },
    "calidad": 89.0,
    "afinidad": 90.0,
    "novedad": 80,
    "compuesto": 88.0,
    "nivel": "PRIORITARIA",
    "elegible": true,
    "bloqueos": [],
    "evidencia_calidad": {
      "reconocimiento": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "conflicto": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "hook": "Entrada posible desde rompecabezas y el desacuerdo descrito; hook aún no escrito.",
      "progresion": "Impulso de resolver → señal de incomodidad → detención → permiso o alternativa → acción respetuosa.",
      "revelacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "visual": "Milo niño oculta una pieza que no encaja. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "compartibilidad": "Reconocimiento de Infancia y escucha; destinatario todavía debe concretarse en guion."
    },
    "evidencia_afinidad": {
      "territorio": "Infancia y escucha",
      "conducta": "Milo niño oculta una pieza que no encaja. Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción.",
      "objeto": "rompecabezas",
      "reinterpretacion": "Detenerse a preguntar puede cuidar tanto como intervenir.",
      "tono": "Relación cotidiana y gesto contenido; no promesa clínica.",
      "visual": "Situación doméstica compatible con estilo ilustrado; referencias individuales pendientes.",
      "representacion": "Milo decide resolver la escena por su cuenta. Antes de tocar el objeto nota que el familiar retira la mano y se detiene para preguntar; recibe una preferencia concreta y ajusta su acción."
    },
    "comparacion_novedad": "Comparación de estructura causal con familia y banco; no embeddings ni corpus audiovisual bruto.",
    "confianza": "media",
    "metodo": "Juicio editorial asistido por modelo a nivel de familia y estructura; aritmética programática. No evaluación independiente ni predicción estadística."
  }
}
```
