# Entrega Práctica UD01 · Auditoría y fortificación Clínica Dental Sonrisas

- **Nombre y apellidos del alumno/a:** Enrique Navarro Velasco
- **Grupo:** 2º SMR
- **Fecha de realización:** 24/11/2026

---

### Actividad 1 · Mecanismos y objetivos de la seguridad informática

| ID | Mecanismo | Objetivo principal (C, I, D, NR) | Física / Lógica | Activa / Pasiva | Justificación |
|:---|:---|:---:|:---:|:---:|:---|
| 1.1 | SAI servidor |D|Física|Pasiva|Creo que es Disponibilidad porque está constantemente suministrando energía al servidor para que siga funcionando sin parar.|
| 1.2 | Cifrado BitLocker |C|Lógica|Activa|Creo que es confidencialidad porque sin la contraseña de ese cifrado.|
| 1.3 | Cortafuegos perimetral |D|Física|Activa|Pienso que es Disponibilidad porque controla las conexionas y dice quién puede entrar o no.|
| 1.4 | Copias de seguridad NAS |I|Lógica|Pasiva|Creo que es integridad porque permite recuperar la información en caso de que se modifique o se pierda.|
| 1.5 | Antivirus corporativo |C|Lógica|Activa|Creo que es confidencialidad porque no deja que el virus lea mis mensajes, vea mis archivos, etc.|

---

### Actividad 2 · Cadena del incidente de seguridad

1. **Activos afectados:**
   - Activo 1: Los datos de las citas de los clientes.
   - Activo 2: Tratamientos pagados cancelados perdiendo dinero.
2. **Amenaza:** El atacante.
3. **Vulnerabilidad y clasificación:** Un servicio de acceso remoto que no se actualizaba desde hace 1 año, conocida sobre software instalado porque sabían que esa actualización no la tenían y aún así seguían sin actualizarla..
4. **Riesgo previo:** Que el atacante pudiera acceder a la base de datos con una autorización instalando esa versión.
5. **Ataque:** Un script (Exploit).
6. **Impacto:**
   - Impacto cuantitativo: Pierde dinero por cancelar cosas pagadas.
   - Impacto cualitativo: Pierde reputación porque los clientes se quejan y ya más gente sabe que tiene problemas de vulnerabilidades.

---

### Actividad 3 · Plan de contingencia

1. **Clasificación de medidas:**
   - Medida A: Emergencia, porque el módem de respaldo 4G/5G se activa justo en el momento que se interrumpe la fibra óptica principal.
   - Medida B: Respaldo, porque hacen la copia antes de que pase nada, para no perderlo.
   - Medida C: Recuperación, porque reinstala el sistema operativo después de que haya una avería irreparable en el disco duro.
   - Medida D: Emergencia, porque aisla toda la red local en el momento en caso de que suene la alarma.
   - Medida E: Recuperación, porque usa un local alternativo para reanudar la facturación después del problema en la recepción.
   - Medida F: Respaldo, porque tienen contratado al servicio de soporte antes de que ocurra nada, para, en caso de que ocurra algo tener reparación rápida.
2. **Diferencia entre plan de respaldo y plan de recuperación:** Que el plan de respaldo se hace antes de que pase nada, para tener algo de seguridad en caso de que pase algo, y el plan de recuperación de ejecuta después de que pase cualquier cosa para poder volver a la normalidad.

---

### Actividad 4 · Software malicioso y test de intrusión

#### 4.1. Diagnóstico de malware
- **Caso 1:**
  - Tipo de malware: Troyano
  - Justificación (archivo anfitrión e intervención usuario): Yo pienso que es un troyano porque necesita un archivo anfitrión, porque si no, no se ejecuta, y necesita intervención del usuario porque si no lo descarga o abre, el troyano no serviría.
- **Caso 2:**
  - Tipo de malware: Gusano
  - Justificación (archivo anfitrión e intervención usuario): Requiere un archivo anfitrión pero no requiere intervención activa.
- **Medida preventiva para Caso 2:** Un antivirus.

#### 4.2. Secuenciación de test de intrusión
- Secuencia ordenada cronológicamente (letras):
- Fases correspondientes:
  - Acción ...: Fase ...
  - Acción ...: Fase ...
  - Acción ...: Fase ...
  - Acción ...: Fase ...

---

### Actividad 5 · Contraseñas e identificación digital

#### 5.1. Contraseñas
1. **Comparativa de seguridad frente a fuerza bruta:** La segunda es más fuerte porque tiene más variación de carácteres que la primera.
2. **Política de contraseñas (3 reglas):**
   - Regla 1:
   - Regla 2:
   - Regla 3:

#### 5.2. Identificación digital
3. **Mecanismos aplicados:**
   - Trámite A:
   - Trámite B:
4. **Objetivo de seguridad garantizado y diferencia con usuario/contraseña:**