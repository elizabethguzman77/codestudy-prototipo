# CodeStudy

### Prototipo de alta fidelidad de una plataforma de aprendizaje de programación

| | |
|---|---|
| **Universidad** | Universidad Internacional del Ecuador (UIDE) |
| **Carrera** | Ingeniería en Ciberseguridad |
| **Estudiante** | Mery Elizabeth Guzmán Ontaneda |
| **Asignatura** | Ingenería y Pensamiento Humano |
| **Docente** | Ing. Gabriela Estefanía Chiliquinga Jiménez |
| **Fecha** | 9 de agosto del 2026 |

---

## Tabla de contenidos

1. [Descripción general](#1-descripción-general)
2. [Problema que resuelve](#2-problema-que-resuelve)
3. [Público objetivo](#3-público-objetivo)
4. [Funcionalidades principales](#4-funcionalidades-principales)
5. [Fundamento teórico](#5-fundamento-teórico-teoría-de-la-autodeterminación)
6. [Aprendizaje y memoria](#6-aprendizaje-y-memoria)
7. [Prototipo interactivo](#7-prototipo-interactivo)
8. [Sistema de diseño](#8-sistema-de-diseño)
9. [Tecnologías utilizadas](#9-tecnologías-utilizadas)
10. [Estructura del repositorio](#10-estructura-del-repositorio)
11. [Instrucciones de ejecución](#11-instrucciones-de-ejecución)

---

## 1. Descripción general

CodeStudy es un concepto de plataforma orientado a estudiantes universitarios de carreras tecnológicas que busca resolver un problema común: la dispersión de recursos para aprender programación y la falta de un sistema que sostenga la motivación una vez que la novedad inicial del curso desaparece.

Este repositorio contiene el **prototipo de alta fidelidad** de la propuesta, desarrollado como entregable académico para evaluar la interfaz, el flujo de navegación y la fundamentación teórica del diseño.

## 2. Problema que resuelve

- Los recursos para aprender a programar suelen estar dispersos (videos, documentación, ejercicios sueltos), sin un espacio único que organice la práctica.
- La motivación inicial de un curso tiende a decaer con el tiempo, sin un sistema que la sostenga.
- Los sistemas académicos tradicionales evalúan con calificaciones puntuales, sin dejar evidencia acumulativa del progreso real del estudiante.

## 3. Público objetivo

Estudiantes de los primeros semestres de Ingeniería de Software y carreras afines que necesitan practicar programación de forma constante, no solo memorizar teoría.

## 4. Funcionalidades principales

| Funcionalidad | Descripción |
|---|---|
| Repositorios guiados por asignatura | Retos semanales organizados con dificultad progresiva. |
| Revisión entre pares | Sistema inspirado en los *pull requests* de GitHub, simplificado para estudiantes sin experiencia previa en control de versiones. |
| Panel de progreso | Combina un gráfico de actividad (heatmap), indicadores de dominio por tema, racha de participación y línea de tiempo de avances académicos. |

## 5. Fundamento teórico: Teoría de la autodeterminación

El diseño motivacional de CodeStudy se sustenta en los tres componentes de la teoría de la autodeterminación (Deci & Ryan):

| Componente | Aplicación en el diseño |
|---|---|
| **Autonomía** | El estudiante elige el orden en que resuelve los retos disponibles. |
| **Competencia** | Retroalimentación inmediata al ejecutar y enviar código. |
| **Relación social** | Revisión de código entre compañeros, con comentarios y aprobación. |

## 6. Aprendizaje y memoria

- **Aprendizaje**: favorece la práctica situada y el trabajo colaborativo mediante revisión de código real, en lugar de ejercicios aislados.
- **Memoria**: cada reto resuelto queda documentado en una línea de tiempo académica, lo que permite repasar el propio progreso como una forma de repetición espaciada.
- **Beneficio principal**: evidencia tangible y acumulativa del aprendizaje del estudiante, algo que suele perderse en sistemas académicos centrados únicamente en calificaciones puntuales.

## 7. Prototipo interactivo

El repositorio incluye dos archivos HTML independientes, autocontenidos (HTML + CSS + JavaScript), sin dependencias externas más allá de la tipografía web:

- **`Interfaz celular.html`** — presenta la app dentro de un marco de dispositivo móvil, con las 7 pantallas del flujo completo y su propia navegación inferior.
- **`Interfaz computador.html`** — vista de escritorio: junto al dispositivo se incluye un panel lateral de contexto que resume el producto, su fundamento teórico y su navegación.

### Pantallas del flujo

| N.º | Pantalla | Contenido |
|---|---|---|
| 1 | Login | Inicio de sesión con correo/contraseña o con Google / UIDE ID. |
| 2 | Home | Racha actual, resumen del día y cursos en progreso. |
| 3 | Cursos/Retos | Listado de retos con su estado (completado, en curso, disponible, bloqueado). |
| 4 | Editor de código | Enunciado del reto, código, casos de prueba y envío de solución. |
| 5 | Revisión entre pares | Código enviado, comentarios de un compañero y aprobación o solicitud de cambios. |
| 6 | Progreso | Mapa de actividad, dominio por tema, racha más larga y línea de tiempo académica. |
| 7 | Perfil | Datos del estudiante, estadísticas totales y logros desbloqueados. |

## 8. Sistema de diseño

- **Colores**: guinda/vino (`#800020`) como color principal, dorado (`#D4AF37`) como acento, sobre fondos claros neutros.
- **Tipografía**: Poppins para títulos, Inter para texto de cuerpo.
- **Componentes**: tarjetas, chips, badges, barras de progreso y navegación inferior tipo app nativa.

## 9. Tecnologías utilizadas

- HTML5
- CSS3 (variables/custom properties, sin frameworks)
- JavaScript (vanilla, sin librerías externas)

## 10. Estructura del repositorio

```
├── Interfaz celular.html
├── Interfaz computador.html
└── README.md
```

## 11. Instrucciones de ejecución

1. Clonar o descargar este repositorio.
2. Abrir `Interfaz celular.html` o `Interfaz computador.html` directamente en un navegador web (no requiere servidor ni instalación).
3. Navegar mediante la barra superior para saltar entre las 7 pantallas, o interactuar con los botones dentro del dispositivo como lo haría un usuario real.

---

*Prototipo desarrollado con fines académicos como parte de la asignatura indicada en la carrera de Ingeniería en Ciberseguridad, UIDE.*

## Evidencia visual de las interfaces:
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/e5168ad5-f13c-4735-866f-372a89d90c52" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/6c50e248-3536-4faf-ba38-f4d2c912668a" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/72b8f22c-90b3-4969-9c72-28f8de0baa84" />



