# 🚴‍♂️ Análisis de Inscripciones: Clásica de Triciclos & Bicicletas

##  Descripción del Proyecto
Este proyecto surge de la necesidad de realizar un seguimiento detallado y comparativo de las inscripciones para un evento deportivo con **35 años de trayectoria**. El objetivo principal fue validar si el ritmo de captación de participantes en **2025** superaba al de **2024**, proporcionando evidencia basada en datos para la toma de decisiones logísticas.

## 📊 Dashboard Final

![Análisis de Inscripciones 2024 vs 2025](<img width="1049" height="602" alt="dashboard" src="https://github.com/user-attachments/assets/937f168e-2799-44e0-80a6-919ddde5eca0" />)


---

##  Insights y Resultados Clave
* **Crecimiento Sólido:** Se alcanzó un incremento del **37.98%** en el total de inscritos frente al año anterior.
* **Eficiencia en el Proceso:** El análisis demostró un inicio de inscripciones más temprano y una fase final significativamente más dinámica en 2025.
* **Cierre Anticipado:** Los datos validaron que el cierre prematuro de inscripciones en 2025 se debió al éxito en la captación de participantes y no a una falta de tiempo.
* **Categoría Líder:** La categoría de **Bicicleta de Impulso (3 a 5 años)** presentó el mayor volumen de participación.

---

##  Herramientas y Metodología
### 1. Preparación de Datos (Excel)
* Limpieza de bases de datos de formularios.
* Anonimización de datos sensibles (cumplimiento de privacidad).
* Estructuración de tablas dinámicas para validación cruzada.

### 2. Visualización y Análisis (Power BI)
* **Modelado de Datos:** Conexión y transformación de fuentes mediante Power Query.
* **DAX (Data Analysis Expressions):** Creación de columnas calculadas para alinear cronológicamente ambos años (YoY) en un mismo eje temporal.
* **Diseño de UI/UX:** Creación de un dashboard ejecutivo enfocado en la legibilidad y el Storytelling de datos.

---

##  Desafíos Superados
Uno de los mayores retos fue la **alineación cronológica**. Dado que Power BI respeta el calendario real, fue necesario implementar una lógica en DAX para que las fechas de 2024 y 2025 se superpusieran visualmente, permitiendo una comparación directa "día a día" del ritmo de crecimiento.

---

##  Estructura del Repositorio
* `/Dashboard/`: Contiene el archivo `.pbix` del proyecto.
* `/Data/`: Archivos de datos (versión anonimizada).
* `/Screenshots/`: Capturas de pantalla del reporte.

---
**Proyecto realizado por:** Sebastian Rodriguez Cardenas
