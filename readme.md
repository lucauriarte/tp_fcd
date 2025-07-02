
# FUNDAMENTOS DE COMUNICACIONES DIGITALES  
## TRABAJO PRÁCTICO

El trabajo práctico consiste en la simulación de sistemas de transmisión digital, utilizando preferentemente Python, o bien Matlab o C/C++ en el desarrollo de dos ejercicios:

- Uno relativo a la primera parte de la materia, sobre **transmisión Banda Base**
- Otro relacionado con la temática de los últimos capítulos, sobre el tema **transmisión digital modulada**.

---

## Ejercicio 1. Simulación de sistemas de transmisión digital en Banda Base

El ejercicio tiene tres niveles de desarrollo, con complejidad creciente.

### Nivel 1

Se propone una simulación de:

- Formas de onda en el tiempo
- Densidades espectrales correspondientes

De al menos **dos formatos de transmisión**, uno de cada uno de los siguientes grupos:

- **Grupo a**:  
  - Unipolar NRZ  
  - Unipolar RZ  
  - Polar NRZ  
  - Polar RZ  

- **Grupo b**:  
  - Mánchester  
  - AMI  
  - Formato M-ario  

También se debe simular qué sucede en los casos **UNRZ** y **PNRZ** si en lugar del formato rectangular se utiliza un **pulso de Nyquist**, incluyendo el extremo del pulso `sinc(rt)`.

---

### Nivel 2

Se propone una simulación similar al nivel 1, pero planteada como un **script genérico** donde se pueda elegir el formato a simular y luego mostrar:

- Características en el tiempo  
- Características en la frecuencia  

También se debe incluir el análisis con **pulso de Nyquist** (con `sinc(rt)`) para:

- UNRZ  
- PNRZ  
- M-ario  

---

### Nivel 3

Completar alguno de los dos niveles anteriores (1 o 2) con una de las siguientes opciones:

a. Simulación de la **tasa de error** del sistema, como **probabilidad de error en función del parámetro γ_b**  
b. Simulación del efecto de la **Interferencia Inter Simbólica (ISI)**

---

## Ejercicio 2. Simulación de sistemas de transmisión digital modulada y control de errores

También tiene tres niveles de complejidad creciente.

### Nivel 1

Se propone una simulación de:

- Formas de onda en el tiempo  
- Densidades espectrales correspondientes  

De al menos **dos formatos de transmisión pasabanda**, uno de cada grupo:

- **Grupo a**:  
  - 2ASK  
  - 2FSK  
  - 2PSK  

- **Grupo b**:  
  - MASK  
  - MPSK  
  - con valor de M tal que `M ≥ 4`, `M = 2^n`  

---

### Nivel 2

Simulación similar al nivel 1, pero en un **script genérico** que permita elegir qué modulación digital simular y mostrar sus características en el tiempo y la frecuencia.

---

### Nivel 3

Completar alguno de los dos niveles anteriores (1 o 2) con una de las siguientes opciones:

a. Simulación de la **tasa de error**, como **probabilidad de error en función de γ_b**  
b. Aplicar a un caso anterior algún tipo de **control de error**

---
