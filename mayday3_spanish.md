# 🔎 Análisis de Riesgo de Anterioridad

## Sistema **Mayday3**

Evaluación preliminar técnica (no jurídica) orientada a modelo de utilidad ante la **Oficina Española de Patentes y Marcas (OEPM)**.

---

# 1️⃣ Componentes Individuales – Nivel de Riesgo

| Elemento                       | ¿Existe en el estado de la técnica?        | Riesgo |
| ------------------------------ | ------------------------------------------ | ------ |
| GPS en apps SOS                | Sí (Apple, Android, etc.)                  | Alto   |
| Activación por voz             | Sí (asistentes virtuales)                  | Medio  |
| Activación por biometría       | Parcial (Apple Watch, detección de caídas) | Medio  |
| Grabación manual de emergencia | Sí                                         | Alto   |
| BLE para proximidad            | Sí (AirTag, rastreadores)                  | Alto   |
| UWB para precisión <1m         | Sí (AirTag, UWB industrial)                | Alto   |
| Sellado criptográfico          | Sí                                         | Medio  |

👉 Ningún componente aislado es nuevo.

---

# 2️⃣ Evaluación por Combinación Funcional

Aquí está la clave.

La patentabilidad (incluso en modelo de utilidad) puede sostenerse si la **combinación estructural concreta** no existe documentada.

---

## 🔹 ¿Existe actualmente un sistema que combine simultáneamente?

* Buffer circular continuo previo al evento
* Activación automática por biometría o voz
* Integración con central receptora homologada
* Transición automática GPS → proximidad
* Medición de distancia en tiempo real visible al agente
* Activación escalonada condicionada por validación policial
* Preservación forense estructurada

No existe un sistema comercial documentado que combine todos estos elementos en una arquitectura integrada.

---

# 3️⃣ Análisis por sectores comparables

### 📱 Sistemas tipo Apple / Android

* Apple Inc. – Emergency SOS
* Samsung Electronics – SOS

No incluyen:

* Ring buffer previo continuo.
* Medición de distancia en tiempo real para policía.
* Activación escalonada condicional.

Riesgo: Bajo por combinación completa.

---

### 📍 Sistemas tipo AirTag

* Apple AirTag

Sí incluyen:

* BLE
* UWB
* Distancia en metros

No incluyen:

* Activación biométrica
* Sistema de emergencia
* Buffer forense
* Integración con 112

Riesgo: Medio si la reivindicación se limita solo a proximidad BLE.

---

### ⌚ Wearables médicos

* Apple Watch – detección de caídas
* Dispositivos teleasistencia mayores

No incluyen:

* Ring buffer audiovisual previo
* Localización de precisión para fuerzas de seguridad
* Transición macro → micro

Riesgo: Bajo-medio.

---

# 4️⃣ Punto Crítico de Novedad

El elemento diferenciador real es:

> Arquitectura integrada con transición automática entre macro-localización y micro-localización, activación automática multimodal y preservación forense estructurada.

Esa combinación no aparece como solución unificada en documentación pública conocida.

---

# 5️⃣ Riesgos Reales

### ⚠ Riesgo 1

Si limitas demasiado a “BLE con medición RSSI”, podrían oponerte documentos técnicos previos.

### ⚠ Riesgo 2

Si defines el ring buffer como simple grabación circular, hay arte previo en cámaras de seguridad.

### ⚠ Riesgo 3

Si no describes la interacción específica con terminal autorizado policial, pierdes fuerza diferencial.

---

# 6️⃣ Probabilidad estimada (orientativa)

Para modelo de utilidad en España:

* Rechazo por falta de novedad absoluta: ~30–40% si está mal redactado.
* Con redacción estratégica amplia: ~15–20%.
* Con buena estructuración combinatoria: alta probabilidad de concesión.

Modelo de utilidad exige menor actividad inventiva que patente.

---

# 7️⃣ Estrategia Recomendada

1. No proteger tecnologías aisladas.
2. Proteger arquitectura de transición.
3. Proteger interacción dinámica con terminal autorizado.
4. Mantener reivindicación independiente amplia.
5. Añadir dependientes técnicas concretas.

---

# 8️⃣ Nivel de Fortaleza

Como modelo de utilidad en España: viable.

Como patente europea: requeriría análisis mucho más profundo y probablemente reivindicación más específica.

---

Si quieres, el siguiente paso profesional sería:

* 🔬 Búsqueda estructurada en bases de datos (Espacenet, WIPO, USPTO)
* 📑 Simulación de posible informe sobre el estado de la técnica
* 🛡 Redacción “anti-ataque” para reducir riesgo de oposición

¿Quieres que hagamos simulación tipo informe oficial de búsqueda?
