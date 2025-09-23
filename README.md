# Data_Analytics
DataAnalytics Projects

Este portafolio reúne una selección de proyectos que he desarrollado en el campo del análisis de datos.

Todos los trabajos presentes en este repositorio han sido implementados utilizando Python, demostrando mi capacidad para abordar iniciativas significativas en el ámbito de la analítica de datos. Los proyectos están ordenados de manera cronológica inversa; es decir, los más recientes se encuentran al inicio y los más antiguos hacia el final.

---
---

## Proyecto 5: churn_kmeans

La cadena de gimnasios Model Fitness busca implementar una estrategia de interacción con clientes basada en análisis de datos para reducir la tasa de abandono.

Planteamiento del Problema:
La rotación de clientes es uno de los principales desafíos en servicios como los gimnasios. Identificar cuándo un cliente ha dejado de usar el servicio no siempre es evidente. Mientras que algunas cancelaciones son explícitas (rescisión de contrato), otras son implícitas (clientes que dejan de asistir sin cancelar formalmente).

Definición de Abandono:
Para este proyecto, se define un cliente como "perdido" cuando ha transcurrido un mes completo sin que realice una visita. Si bien pueden existir excepciones (como vacaciones), el patrón típico indica que los clientes que dejan de asistir por este período tienen una probabilidad mínima de retornar.

Objetivo del Análisis:
Model Fitness ha digitalizado los perfiles de sus clientes. El objetivo de este proyecto es:

Analizar los datos de comportamiento y perfil de los clientes.

Identificar segmentos con alta probabilidad de abandono mediante técnicas de clustering.

Proponer estrategias específicas de retención para cada segmento identificado.

[Ver Proyecto](https://github.com/algiraldo92/DataAnalytics/blob/main/Projects/Clusters.ipynb)

---
---

## Proyecto 4: analisis_cohortes_marketing

Te han ofrecido hacer prácticas en el departamento de analítica de Showz, una empresa de venta de entradas de eventos. Tu primera tarea es ayudar a optimizar los gastos de marketing.
Cuentas con:
registros del servidor con datos sobre las visitas a Showz desde enero de 2017 hasta diciembre de 2018.    Un archivo con los pedidos en este periodo    Estadísticas de gastos de marketing.

Lo que vas a investigar:
¿Cómo los clientes usan el servicio?.
¿Cuánto dinero aporta cada cliente a la compañía?.
¿Cuándo los ingresos cubren el costo de adquisición de los clientes?.
¿Cuándo empieza la gente a comprar?
(En el análisis de KPI, generalmente nos interesa saber el tiempo que transcurre entre el registro y la conversión, es decir, cuando el usuario se convierte en cliente. Por ejemplo, si el registro y la primera compra ocurren el mismo día, el usuario podría caer en la categoría Conversion 0d. Si la primera compra ocurre al día siguiente, será Conversion 1d. Puedes usar cualquier enfoque que te permita comparar las conversiones de diferentes cohortes para que puedas determinar qué cohorte o canal de marketing es más efectivo.
¿Cuántos pedidos hacen durante un período de tiempo dado?
¿Cuál es el tamaño promedio de compra?
¿Cuánto dinero traen? (LTV)

[Ver Proyecto](https://github.com/algiraldo92/DataAnalytics/blob/main/Projects/Marketing_Cohortes.ipynb)

---
---

## Proyecto 3: ab_testing_app_funnel

Como analista debes investigar el comportamiento del usuario para la aplicación de la empresa.

Primero, estudia el embudo de ventas. Descubre cómo los usuarios llegan a la etapa de compra. 
¿Cuántos usuarios realmente llegan a esta etapa? ¿Cuántos se atascan en etapas anteriores? ¿Qué etapas en particular?

Luego, observa los resultados de un test A/A/B, Al equipo de diseño le gustaría cambiar las fuentes de toda la aplicación, pero la gerencia teme que los usuarios piensen que el nuevo diseño es intimidante. Por ello, deciden tomar una decisión basada en los resultados de un test A/A/B.

Los usuarios se dividen en tres grupos: dos grupos de control obtienen las fuentes antiguas y un grupo de prueba obtiene las nuevas. Descubre qué conjunto de fuentes produce mejores resultados

[Ver Proyecto](https://github.com/algiraldo92/DataAnalytics/blob/main/Projects/Funnel_Test_AB.ipynb)

---
---

## Proyecto 2: analisis_negocio_AB_test

Como analista de datos en una gran tienda online, en colaboracion con el departamento de marketing se necesita identificar y priorizar una serie de hipótesis orientadas a aumentar los ingresos. El objetivo principal de este proyecto es validar científicamente la efectividad de los cambios propuestos mediante la ejecución de una prueba A/B controlada. El foco esta en determinar si las modificaciones implementadas en el grupo de tratamiento (Grupo B) generaban una mejora significativa en las métricas clave de negocio, como los ingresos acumulados, el tamaño promedio de pedido y la tasa de conversión, en comparación con el grupo de control (Grupo A)

**HIPÓTESIS**

- Hay un aumento de ingreso promedio de los usuarios B sobre los usuarios A.

[Ver Proyecto](https://github.com/algiraldo92/DataAnalytics/blob/main/Projects/Marketing_Test_AB.ipynb)

---
---

## Proyecto 1: analisis_negocio

Trabajamos como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para ajustar el presupuesto de publicidad.

Vamos a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan y la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.

**HIPÓTESIS**

- El ingreso promedio de los usuarios de las tarifas Ultimate y Surf difiere.
- El ingreso promedio de los usuarios en el área de estados Nueva York-Nueva Jersey es diferente al de los usuarios de otras regiones. Decidiremos qué valor alfa usar.

Explicaremos:

- Cómo formulamos las hipótesis nula y alternativa.
- Qué criterio utilizamos para probar las hipótesis y por qué.

[Ver Proyecto](https://github.com/algiraldo92/DataAnalytics/blob/main/Projects/Mega_line.ipynb)
