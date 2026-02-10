# GPE — Proyecto Final: Rediseño del Proceso de Asistencia Técnica

**Universidad de Guayaquil — Facultad de Ingeniería Industrial**

---

## ✨ Resumen
Proyecto de reingeniería del proceso de **Gestión de Asistencia Técnica** del Hospital General Isidro Ayora, con la propuesta de pasar de un modelo reactivo y manual a uno **automatizado y predictivo** mediante la integración de agentes (OpenClaw) para soportar AITSM.

## 📌 Tabla de contenido
- [Descripción](#descripción)
- [Problemática y solución](#problemática-y-solución)
- [Resultados de la simulación](#resultados-de-la-simulación)
- [Integrantes](#integrantes)
- [Recursos](#recursos)

---

## Descripción
Este repositorio contiene la documentación, modelos BPMN y recursos del proyecto. La propuesta central es automatizar la recepción, clasificación y resolución L1 de incidentes, reduciendo latencias y carga manual.

## Problemática y solución
### Problemática (AS-IS)
- **Alta Latencia:** Tiempo promedio de respuesta ~4h 58m (procesos manuales)[cite: 43].
- **Informalidad:** 52.14% de reportes presenciales, pérdida de trazabilidad[cite: 34, 153].
- **Cuellos de botella:** Dependencia de analista humano para asignación[cite: 141].

### Solución (TO-BE)
- **AITSM + OpenClaw:** Orquestador de agentes para clasificación automática y ejecución de scripts.
- **Omnicanalidad:** Recepción automática vía WhatsApp/Telegram.
- **Resolución L1 automática:** Auto-reparación para incidentes recurrentes.

---

## Resultados de la simulación
Escenario: 1,000 solicitudes.

| Indicador | AS-IS | TO-BE | Mejora |
| :--- | :---: | :---: | :--- |
| Resolución Automática | 0% | **27.1% (271)** | Automatización L1 |
| Carga Manual Técnico | 100% | **25.1%** | -75% carga operativa |
| Digitalización | 48% | **100%** | Trazabilidad total |

*Datos basados en el informe de simulación adjunto[cite: 315, 321, 356].*

---

## Integrantes (Grupo No. 1)

- Alcivar Aguirre Scarlet Angeline
- Amaguaya Satan Angel Hernan
- Centeno Lozano Bryant Snayder
- Lavayen González Víctor Raul
- Rodríguez Ricardo Mike Wilson
- Velasco Guerrero Fernando David
- Velez Villao Ignacio Keyfer

---

## Recursos

- 📄 Documentación: [GPE - Grupo No.1 Proyecto Final (PDF)](Document/GPE%20-%20Grupo%20No.1%20Proyecto%20Final.pdf.pdf)
- 📊 Resultados (PDF): [Impresion.pdf](Simulacion/Impresion.pdf)
- 📈 Hoja de cálculo (Excel): [Simulacion resultados.xlsx](Simulacion/Simulacion%20resultados.xlsx)
- 🎥 Video de demostración: [WhatsApp Video 2026-02-10 at 3.25.01 PM.mp4](Simulacion/WhatsApp%20Video%202026-02-10%20at%203.25.01%20PM.mp4)
- 🔗 Repositorio: https://github.com/keyferv/GPE-Proyecto-Final
