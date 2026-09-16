# Algoritmo de Atención Veterinaria y Flujo Conceptual

## 1. Algoritmo de Atención (Paso a Paso)

1. **Recepción:** Llega el animal a la veterinaria con su dueño o tutor.
2. **Identificación:** Se identifican los datos básicos del animal (nombre, especie, edad, si es mascota o animal salvaje).
3. **Comprensión de la Necesidad:** Se consulta el motivo de la consulta (chequeo de rutina, vacunación, síntoma o emergencia).
4. **Evaluación / Triaje:** Se evalúa el nivel de urgencia y el estado de salud inicial.
5. **Atención Médica:** El veterinario aplica el procedimiento, examen o tratamiento correspondiente según el tipo de animal.
6. **Informe de Resultados:** Se le entrega al dueño/tutor el diagnóstico, indicaciones médicas o receta.

---

## 2. Entradas, Salidas y Decisiones del Negocio

* **Información de Entrada (Inputs):**
  - Datos del animal (nombre, especie, edad).
  - Tipo de animal (Mascota doméstica o Animal Salvaje).
  - Motivo de consulta / Síntomas reportados.

* **Resultados Esperados (Outputs):**
  - Diagnóstico médico veterinario.
  - Plan de tratamiento o receta prescrita.
  - Estado de la atención (Atendido / Derivado / En observación).

* **Decisiones del Negocio (Reglas conceptuales):**
  - **¿Es emergencia?** *(Decisión del negocio)*: Si la vida del animal corre riesgo, se atiende de inmediato sobreponiéndose a la fila de espera.
  - **¿Es mascota o animal salvaje?** *(Decisión del negocio)*: Los animales salvajes requieren medidas de contención o protocolos de seguridad especiales antes de proceder a la revisión.
  - **¿Requiere examen especializado?** *(Decisión del negocio)*: Determina si la atención termina con la consulta o si se deriva a exámenes complementarios (ej. radiografías, exámenes de sangre).