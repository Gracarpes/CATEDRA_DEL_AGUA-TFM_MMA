# 📑 Tutorización TFM: Modelado de Proceso de Digestión Anaerobia mediante Herramientas Abiertas

¡Bienvenido al repositorio de seguimiento de tu Trabajo de Fin de Máster! Este espacio es el canal principal para organizar tus entregas, revisar el código de simulación, compartir recursos y registrar el avance de la investigación.

*   **Convocatoria / Entrega:** Marzo 2027

## 🎯 Objetivos del TFM
El objetivo principal es desarrollar un modelo computacional abierto para el proceso de digestión anaerobia, evaluando su viabilidad técnica, económica y ambiental.
1.  **Revisión:** Analizar los modelos existentes de digestión anaerobia (ej. ADM1) y su integración en herramientas open-source.
2.  **Modelado Técnico:** Implementar el flujo del proceso utilizando la librería `BioSTEAM` en Python.
3.  **Evaluación de Sostenibilidad:** Incorporar análisis de ciclo de vida (LCA) y costes utilizando `QDSAN`.
4.  **Validación y Simulación:** Crear escenarios interactivos y reproducibles mediante Jupyter Notebooks.
5.  **Memoria:** Redactar el documento final del TFM detallando la metodología y los resultados obtenidos.

## 📅 Cronograma de Hitos (Meta: Marzo 2027)
*   [ ] **Fase 1: Estado del Arte y Configuración** (Límite: Octubre 2026)
    *   Definición del diagrama de flujo conceptual del proceso.
    *   Instalación del entorno de Python con `BioSTEAM` y `QDSAN`.
*   [ ] **Fase 2: Implementación de la Digestión Anaerobia** (Límite: Diciembre 2026)
    *   Definición de componentes químicos y propiedades termodinámicas.
    *   Programación del reactor de digestión anaerobia en Jupyter Notebooks.
*   [ ] **Fase 3: Análisis de Costes y Sostenibilidad** (Límite: Enero 2027)
    *   Configuración del análisis TEA (Tecno-Económico) con BioSTEAM.
    *   Configuración del análisis LCA (Ambiental) con QDSAN.
*   [ ] **Fase 4: Optimización y Escritura** (Límite: Febrero 2027)
    *   Simulación de escenarios óptimos y análisis de sensibilidad.
    *   Primer borrador completo de la memoria.
*   [ ] **Fase 5: Revisión Final y Defensa** (Límite: Marzo 2027)
    *   Correcciones finales del tutor y depósito del TFM.

## 🛠️ Tecnologías y Requisitos
El proyecto se desarrolla exclusivamente con herramientas de código abierto:
*   **Lenguaje:** Python 3.x
*   **Entorno:** Jupyter Notebooks (`.ipynb`)
*   **Librerías Clave:**
    *   `biosteam`: Diseño de procesos y análisis tecno-económico.
    *   `qdsan`: Análisis cuantitativo y diseño de sistemas de saneamiento (LCA).

## 🌿 Dinámica de Trabajo en Git
Para garantizar la reproducibilidad y el orden del código:
*   **Rama `main`:** Contiene únicamente las entregas oficiales y estables.
*   **Rama `develop`:** Rama de trabajo diario del alumno.
*   **Pull Requests (PR):** Cada vez que se termine una simulación o fase, el alumno abrirá un PR desde su rama hacia `develop` para que el tutor valide el código antes de integrarlo.
*   **Archivos pesados:** No subir datos crudos masivos al repositorio. Usar archivos `.csv` optimizados o enlaces externos si superan los 50MB.

## 📁 Estructura del Repositorio
```text
├── notebooks/       # Jupyter Notebooks con las simulaciones paso a paso
│   ├── 01_definicion_componentes.ipynb
│   ├── 02_modelo_reactor.ipynb
│   └── 03_analisis_tea_lca.ipynb
├── data/            # Datos de entrada para las simulaciones (parámetros kineticios, costes)
├── docs/            # Borradores de la memoria del TFM y gráficos generados
├── environment.yml  # Archivo de Conda para replicar exactamente el entorno de librerías
└── README.md        # Este archivo
```

## 📝 Registro de Tutorías

### 🕒 Reunión 1: Arranque y Alcance (DD/MM/2026)
*   **Acuerdos:** Confirmación del uso de BioSTEAM y QDSAN. Definición del residuo/sustrato base.
*   **Tareas Alumno:** Configurar el entorno virtual y replicar el tutorial básico de BioSTEAM.
*   **Tareas Tutor:** Facilitar artículos de referencia sobre parámetros de digestión anaerobia.
