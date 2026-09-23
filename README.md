# Modelado de Sistemas Fisiológicos

**Manual de prácticas y material de apoyo de la asignatura**

**Tecnológico Nacional de México — Instituto Tecnológico de Tijuana**  
**Carrera:** Ingeniería Biomédica  
**Clave:** IBF-1020  
**SATCA:** 3-2-5

---

## Descripción

El **Modelado de Sistemas Fisiológicos** constituye una herramienta fundamental en Ingeniería Biomédica, ya que permite representar, comprender, analizar, simular y predecir el comportamiento de diferentes procesos del cuerpo humano, así como contribuir al diseño y evaluación de estrategias de control, terapias y dispositivos médicos.

El modelado fisiológico consiste en la formulación de modelos matemáticos y computacionales capaces de representar la dinámica y las interacciones existentes entre variables y procesos biológicos y fisiológicos. Su desarrollo integra conocimientos de **Ingeniería de Control, Electrónica Analógica, Matemáticas, Ciencias de la Computación, Anatomía y Fisiología**, además de información experimental que permita describir cuantitativa y cualitativamente el sistema de interés.

Un elemento central de la asignatura es la construcción de **analogías entre circuitos eléctricos y sistemas fisiológicos** para formular modelos matemáticos, analizar su respuesta dinámica y diseñar estrategias de control mediante experimentación *in silico*.

---

## Objetivo de este repositorio

Este repositorio reúne el **manual de prácticas, material de apoyo, ejercicios, modelos y recursos computacionales** utilizados en la asignatura **Modelado de Sistemas Fisiológicos**.

Las prácticas tienen como propósito complementar los conocimientos teóricos adquiridos en el aula y favorecer el desarrollo de las competencias establecidas en el programa de estudio. Cada actividad busca integrar:

- fundamentos teóricos;
- formulación de modelos matemáticos;
- analogías entre sistemas físicos y fisiológicos;
- análisis en el dominio del tiempo y de Laplace;
- simulación computacional;
- experimentación *in silico*;
- análisis de estabilidad; y
- diseño y ajuste de controladores clásicos.

---

## Competencia general

> **Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico.**

A partir de esta competencia, la asignatura busca integrar principios de Ingeniería de Control, Electrónica Analógica y Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos, con la finalidad de **modelar, analizar, controlar, ilustrar y predecir su dinámica** tanto en el corto como en el largo plazo.

De acuerdo con el programa oficial de la asignatura, la competencia específica consiste en emplear el control clásico y las técnicas de modelado de sistemas para su aplicación en procesos fisiológicos.

---

## Competencias previas

Para desarrollar adecuadamente las actividades del curso se recomienda que el estudiante sea capaz de:

| Competencia previa | Área o asignatura relacionada |
|---|---|
| Aplicar las leyes de Kirchhoff, el teorema de superposición y la transformada de Laplace. | Mediciones Eléctricas / Electrónica Analógica |
| Resolver ecuaciones diferenciales, ecuaciones integro-diferenciales y sistemas de ecuaciones. | Ecuaciones Diferenciales / Métodos Numéricos |
| Utilizar amplificadores operacionales. | Amplificadores de Bioseñales / Electrónica Analógica |
| Comprender el funcionamiento de los principales sistemas fisiológicos. | Anatomía y Fisiología I / II |

---

# Contenido de la asignatura

## Unidad 1. Sistemas de control retroalimentados

**Competencia específica:** Comprende los conceptos básicos de la Ingeniería de Control, su respuesta en el tiempo y criterios de estabilidad.

### Temas

1. **Elementos de los sistemas de control**
   - Sistemas dinámicos.
   - Sistemas de control en lazo abierto.
   - Sistemas de control en lazo cerrado.
   - Retroalimentación.
   - Señal de referencia, salida y error.
   - Controladores y concepto de compensación.

2. **Función de transferencia**
   - Transformada de Laplace.
   - Obtención de la función de transferencia a partir de ecuaciones diferenciales.
   - Polos y ceros.
   - Orden de un sistema.
   - Interpretación física y matemática de la función de transferencia.

3. **Diagramas de bloques**
   - Representación de sistemas mediante bloques funcionales.
   - Puntos de suma y ramificación.
   - Función de transferencia en lazo cerrado.
   - Reglas de simplificación del álgebra de bloques.

4. **Respuesta ante señales de entrada**
   - Impulso unitario.
   - Escalón unitario.
   - Rampa.
   - Señales sinusoidales.
   - Respuesta transitoria y estado estacionario.
   - Características de la respuesta al escalón.

5. **Análisis del error**
   - Error dinámico y error en estado estacionario.
   - Relación entre entrada, salida y señal de error.

6. **Estabilidad**
   - Concepto de estabilidad.
   - Estabilidad absoluta y relativa.
   - Polos y estabilidad.
   - Criterios de estabilidad.

---

## Unidad 2. Modelado matemático

**Competencia específica:** Modeliza sistemas fisiológicos y biológicos mediante ecuaciones diferenciales, ecuaciones integro-diferenciales y funciones de transferencia para analizar su respuesta.

### Sistemas fisiológicos considerados

- Sistema cardiovascular.
- Sistema endocrino.
- Sistema nervioso y sensorial.
- Sistema gastrointestinal.
- Sistema respiratorio.
- Sistema musculoesquelético.

El desarrollo de esta unidad se apoya en la construcción de analogías entre sistemas físicos y fisiológicos, particularmente mediante circuitos equivalentes **R, RC y RLC**, para establecer ecuaciones diferenciales, funciones de transferencia y representaciones computacionales.

---

## Unidad 3. Controladores

**Competencia específica:** Diseña controladores para sistemas mediante técnicas de control clásico.

### Temas

1. Tipos de controladores.
2. Diseño de controladores.
3. Métodos de ajuste y sintonización.
4. Control aplicado a sistemas fisiológicos.
5. Análisis de la señal de error.
6. Uso de herramientas computacionales para el análisis y simulación.
7. Sintonización de controladores mediante métodos clásicos, incluyendo Ziegler-Nichols.

---

## Unidad 4. Proyecto final

**Competencia específica:** Modeliza un sistema que describa un proceso fisiológico o biológico y diseña un controlador aplicable a dicho sistema.

El proyecto integrador considera cuatro etapas generales:

1. **Fundamentación:** construcción del marco teórico, conceptual y contextual del problema.
2. **Planeación:** definición del modelo, metodología, recursos y cronograma.
3. **Ejecución:** construcción, simulación y análisis del modelo propuesto.
4. **Evaluación:** análisis de los resultados, identificación de logros y aspectos susceptibles de mejora.

El producto final deberá integrar el **modelo matemático**, su **simulación**, el análisis de su dinámica y, cuando corresponda, el **diseño o implementación de una estrategia de control**, acompañado de un reporte técnico.

---

# Prácticas

Las actividades prácticas del curso se orientan al desarrollo progresivo de las competencias de modelado y control. Entre las actividades contempladas se encuentran:

- uso de software especializado para resolver problemas de modelado y control;
- obtención del modelo matemático de un sistema fisiológico;
- construcción y simplificación de diagramas de bloques;
- obtención de modelos matemáticos de sistemas físicos y análisis de su respuesta ante diferentes señales de entrada;
- simulación y verificación computacional de modelos;
- análisis de la respuesta temporal de sistemas fisiológicos;
- construcción de modelos presión–flujo para dinámica cardiovascular y biomecánica pulmonar;
- estudio de modelos de equilibrio, población o concentración;
- representación de fenómenos como cinética enzimática, potencial de membrana y propagación de señales;
- diseño y simulación de controladores;
- identificación y sintonización de controladores aplicados a sistemas fisiológicos; y
- elaboración de reportes técnicos.

---

## Metodología de trabajo

Las prácticas se desarrollan mediante una secuencia general de trabajo:

```text
Sistema fisiológico
        ↓
Identificación de variables y parámetros
        ↓
Analogía física / eléctrica
        ↓
Modelo matemático
        ↓
Ecuaciones integro-diferenciales
        ↓
Función de transferencia
        ↓
Simulación computacional
        ↓
Análisis de la respuesta
        ↓
Diseño y evaluación del controlador
```

Este enfoque permite relacionar la descripción fisiológica del problema con su representación matemática y computacional, favoreciendo la experimentación *in silico* antes de considerar implementaciones físicas.

---

## Evaluación de las actividades prácticas

De acuerdo con el enfoque por competencias de la asignatura, las evidencias pueden incluir:

- **conocimiento:** ejercicios, cuestionarios y evaluaciones;
- **producto:** prácticas, simulaciones, modelos, prototipos y reportes;
- **desempeño:** desarrollo correcto de procedimientos y cumplimiento de los objetivos de cada práctica;
- **actitud profesional:** responsabilidad, trabajo colaborativo, puntualidad y cumplimiento.

---

## Bibliografía

1. M. C. Khoo, *Physiological Control Systems: Analysis, Simulation, and Estimation*, 2nd ed., IEEE Press, 2018.
2. K. Ogata, *Ingeniería de Control Moderna*, 5.ª ed., Pearson Educación, 2010.
3. N. S. Nise, *Control Systems Engineering*, 8th ed., John Wiley & Sons, 2020.
4. A. Garfinkel, J. Shevtsov and Y. Guo, *Modeling Life: The Mathematics of Biological Systems*, Springer, 2017.
5. T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf and M. Verhaegen, "Estimation of three-and four-element windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, no. 7, pp. 1531--1538, 2010.
6. M. Tetschke, P. Lilienthal, T. Pottgiesser, T. Fischer, E. Schalk and S. Sager S, "Mathematical Modeling of RBC Count Dynamics after Blood Loss", Processes, vol. 6, no. 9, 157, 2018. doi: https://doi.org/10.3390/pr6090157


---

## Referencia del syllabus

> P. A. Valle, *Syllabus para Modelado de Sistemas Fisiológicos*, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2026.

---

## Institución

**Tecnológico Nacional de México**  
**Instituto Tecnológico de Tijuana**  
**Ingeniería Biomédica**

---

## Nota

Este repositorio tiene fines **académicos y educativos** y funciona como material complementario para los estudiantes inscritos en la asignatura. Los contenidos aquí incluidos no sustituyen el programa oficial de estudios ni las indicaciones proporcionadas por el docente durante el curso.
