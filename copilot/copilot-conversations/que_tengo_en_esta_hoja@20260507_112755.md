---
epoch: 1778167675342
modelKey: "gemini-2.5-flash|google"
topic: "Criterios de Preconectorizado"



tags:
  - copilot-conversation
---

**user**: que tengo en esta hoja?
[Context: Notes: 30 Trabajo/Preconectorizado (Criterios).md]
[Timestamp: 2026/05/07 11:27:55]

**ai**: 
<errorChunk>Model request failed: API key is not provided for the model: google/gemini-2.5-flash|openrouterai.</errorChunk>
[Timestamp: 2026/05/07 11:27:55]

**user**: hola
[Context: Notes: 30 Trabajo/Preconectorizado (Criterios).md]
[Timestamp: 2026/05/07 11:28:07]

**ai**: ¡Hola! ¿En qué puedo ayudarte hoy?
[Timestamp: 2026/05/07 11:28:09]

**user**: que tengo en eseta hoja?
[Context: Notes: 30 Trabajo/Preconectorizado (Criterios).md]
[Timestamp: 2026/05/07 11:28:24]

**ai**: En la nota [[Preconectorizado (Criterios)]] tienes la siguiente información:

-   **Secuencia de división de señal en cajas**: Describe el orden de los divisores de señal (FL, 50/50, 70/30, 80/20, 90/10).
-   **Criterios a tener en consideración**:
    -   **Mangas HUB**: Soportan hasta 24H de fibra, máximo 4 fibras por manga, y la distribución debe hacerse dentro de la manga si se usa como Jumper.
    -   **Empalmes**: Máximo 24 por Manga HUB, y cada splitter equivale a 2 empalmes.
    -   **TAP (Derivador direccional)**: Máximo 6 por Manga HUB, con medidas de 80, 110, 150m y un máximo de 150 metros por TAP.
    -   **Rangos de señal**: Se recomienda mantenerlos en -16db y nunca llegar o superar los -20db.
    -   **Atenuaciones**: Una tabla detallando las pérdidas en dB para diferentes equipos como splitters (1x2, 1x4, 1x8, 1x16, 1x32, 1x64), pérdida de fibra óptica (λ 1310 Km, λ 1550 Km), pérdida por fusión y pérdida de conector.
    -   **Etiquetado**: Las salidas de fibra se etiquetan como OUT y se enumeran, mientras que los TAP llevan la denominación D1, D2, etc.
[Timestamp: 2026/05/07 11:28:28]