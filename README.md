# 01. Base de Análisis y Lógica Operacional en Hidrometalurgia

👋 **¡Bienvenidos a mi primer proyecto de IA aplicada a la minería!**

Este repositorio marca el inicio de mi inserción al área de programación con fines metalúrgicos. El foco inicial es establecer una base de programación robusta para tareas críticas en procesos hidrometalúrgicos como la dosificación de reactivos en lixiviación y problemáticas asociadas a procesos posteriores en SX/EW.

---

## Resolver problemas de planta con código

Antes de aplicar modelos complejos, se debe dominar el lenguaje para evaluar el rendimiento y ritmo de la operación.

**Hito 1:** Demostrar la capacidad de automatizar los cálculos de KPIs y las alertas de control, imitando la lógica que usaría un sistema en tiempo real.

### Lo que hay en este Notebook (`01_funciones_metalurgicas.ipynb`):

| Tarea Clave | ¿Qué se resuelve en planta? | Habilidad técnica demostrada |
| :--- | :--- | :--- |
| **Control de eficiencia y recuperación** | Evalúa el rendimiento en la extracción y recuperación del cobre y genera **alertas inmediatas** si este cae más de lo esperado. | Funciones (`def`), Lógica Condicional (`if/else`), Tipado de Datos (`float`). |
| **Monitoreo de consumo de ácido** | Revisa un historial de consumos de un periodo y detecta automáticamente **días anómalos** (consumo muy alto o muy bajo), que impactan directamente los costos del proceso. | Uso eficiente de Bucles (`for`), Acumulación (`+=`), Detección de *Outliers*. |

---

## Siguiente paso (Construir el Motor de IA)

El siguiente paso es equipar este análisis con la velocidad necesaria para manejar los datos de los sensores en tiempo real y acercarnos a la automatización.

Introducción a **NumPy**, el motor de cálculo vectorial, para manipular grandes volúmenes de mediciones de pH, flujo, o leyes.
