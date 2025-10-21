# 01. Base de Análisis y Lógica Operacional en la Hidrometalurgia

👋 **Bienvenidos a mi primer proyecto de IA aplicada a la minería**

Este repositorio marca el inicio de mi inserción al área de programación con fines metalúrgicos. El foco inicial es establecer una base de programación robusta para tareas críticas en procesos hidrometalúrgicos como la dosificación de reactivos en lixiviación y problemáticas asociadas a procesos posteriores en SX/EW.

---

## Resolver problemas de planta con código

Antes de aplicar modelos complejos, me propuse dominar el lenguaje y evaluar el rendimiento junto al ritmo de la operación.

**Hito 1:** Demostrar la capacidad de automatizar los cálculos de KPIs y las alertas de control, imitando la lógica que usaría un sistema en tiempo real.

### Lo que hay en este notebook ('01_funciones_metalurgicas.ipynb'):

| Tarea clave | ¿Qué se resuelve en planta? | Habilidad técnica demostrada |
| :--- | :--- | :--- |
| **Control de eficiencia y recuperación** | Evalúa el rendimiento en la extracción y recuperación del cobre y genera **alertas inmediatas** si este cae más de lo esperado. | Funciones (def), lógica condicional (if/else), conversión de datos (float). |
| **Monitoreo de consumo de ácido** | Revisa un historial de consumos de un periodo y detecta automáticamente **días anómalos** (consumo muy alto o muy bajo), que impactan directamente los costos junto a la eficiencia del proceso. | Uso de bucles (for), acumulación (+=). |

---

**Hito 2:** Utilizar numpy arrays para el manejo de cientos de datos simultaneamente, lo que permite corregir o tratar con ellos de una manera mucho más rápida

### Introducción a **numpy**, el motor de cálculo vectorial, para manipular grandes volúmenes de datos y mediciones ('02_numpy_arrays_simulacion.ipynb'):

| Tarea clave | ¿Qué se resuelve en planta? | Habilidad técnica demostrada |
| :--- | :--- | :--- |
| **Creacion de miles de datos aleatorios de muestra** | Permite generar miles de datos aleatorios, lo que facilita la evaluación de cualquier parámetro requerido en un modelo. | Uso de funcion de generador de datos de numpy (np.random.uniform) |
| **Cálculo y características de los datos generados** | Calcula la desviación, promedio y entrega los datos anómalos encontrados en la totalidad de la muestra, entregando la cantidad de **dias con anomalías**. | Fuciones (mean() y std())|

