# desafio-lanzamiento
# 🚀 Misión Euler – Simulador de Cohete

## Descripción
Aplicación web desarrollada para la asignatura de Métodos Numéricos, inspirada en la película *Talentos ocultos*. Simula el lanzamiento vertical de un cohete mediante ecuaciones diferenciales.

## Funcionalidades
- Ingreso de parámetros del cohete.
- Cálculo mediante los métodos de Euler, Heun y Runge-Kutta (RK4).
- Cálculo de la solución analítica.
- Gráficas de velocidad y altura.
- Tablas de iteraciones y comparación de errores.
- Exportación de resultados a CSV.

## Tecnologías
- HTML5
- CSS3
- JavaScript

## Ejecución
1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en un navegador web.
3. Ingresar los parámetros y presionar **Ejecutar simulación**.

## Modelo matemático

El movimiento del cohete se representa mediante:

\[
\frac{dv}{dt}=\frac{T}{m}-g-\frac{k}{m}v
\]

\[
\frac{dy}{dt}=v
\]

Donde:
- \(T\): empuje del cohete.
- \(m\): masa.
- \(g\): gravedad.
- \(k\): coeficiente de resistencia.
- \(v\): velocidad.
- \(y\): altura.

## Objetivo
Comparar la precisión de los métodos numéricos con la solución analítica y analizar cómo influye el tamaño del paso de integración en los resultados.

**Proyecto académico – Métodos Numéricos.**
