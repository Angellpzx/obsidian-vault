---
epoch: 1771849845403
modelKey: "gemini-2.5-flash|google"
topic: "Resumen de Criterios Preconectorizado"



tags:
  - copilot-conversation
---

**user**: Resume el contenido de la pagina
[Context: Notes: 30 Trabajo/Preconectorizado (Criterios).md]
[Timestamp: 2026/02/23 08:30:45]

**ai**: 
<errorChunk>Model request failed: API key is not provided for the model: google/gemini-2.5-flash|openrouterai.</errorChunk>
[Timestamp: 2026/02/23 08:30:45]

**user**: Resume el contenido de la pagina
[Context: Notes: 30 Trabajo/Preconectorizado (Criterios).md]
[Timestamp: 2026/02/23 08:30:56]

**ai**: La nota [[Preconectorizado (Criterios)]] detalla los criterios y la secuencia para la división de señal en cajas y el uso de equipos preconectorizados.

Aquí tienes un resumen de su contenido:

**Secuencia de división de señal en cajas:**
La secuencia recomendada para la división de señal es: FL (Fin de línea), 50/50, 70/30, 80/20 (x3), 90/10 (x2).

**Criterios a tener en consideración:**

*   **Mangas HUB:**
    *   Soportan un máximo de 24 fibras.
    *   Máximo 4 fibras por Manga HUB.
    *   Si se usa como Jumper, la distribución debe hacerse dentro de la Manga.
*   **Empalmes:**
    *   Máximo 24 empalmes por Manga HUB.
    *   Cada splitter equivale a 2 empalmes.
*   **TAP (Derivador direccional):**
    *   Máximo 6 TAP por Manga HUB.
    *   Medidas de 80, 110, 150 metros.
    *   Máximo 150 metros por TAP.
*   **Rangos de señal:**
    *   Se debe intentar mantener la señal en -16dB para futuras expansiones.
    *   Nunca se debe llegar o superar los -20dB.
*   **Atenuaciones:**
    Se especifican las pérdidas en dB para varios equipos:
    *   Splitters (1x2: -3.7dB, 1x4: -7.1dB, 1x8: -10.7dB, 1x16: -13.7dB, 1x32: -16.9dB, 1x64: -21dB).
    *   Pérdida de Fibra Óptica (λ 1310 Km: -0.35dB, λ 1550 Km: -0.25dB).
    *   Pérdida por fusión: -0.06dB.
    *   Pérdida de conector: -0.5dB.
*   **Etiquetado:**
    *   Las salidas de fibra se etiquetan como OUT y se enumeran.
    *   Los TAP se denominan D1, D2, etc.
[Timestamp: 2026/02/23 08:31:01]