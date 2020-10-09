---
layout: lesson
root: .

maintainers:
  - Henry Asencios
---

**Lesson Maintainers:** {{ page.maintainers | join: ', ' }}


El Módulo I: "Regionalización de modelos globales" forma parte del curso especializado denominado "Modelación Hidrológica de Recursos Hídricos Superficiales y Subterráneos" que ha sido diseñado por la [Facultad de Ingenieria Agrícola (FIA)](http://www.lamolina.edu.pe/facultad/agricola/) de la [Universidad Nacional Agraria La Molina (UNALM)](http://www.lamolina.edu.pe/) para los servidores de la [Autoridad Nacional de Agua (ANA)](https://www.ana.gob.pe/) que no presentan conocimientos de programación en los lenguajes **R** y **Python** para el manejo de series de tiempo hidrometeorológicas observadas y salidas de modelos de circulación global. Las lecciones tendrán una duración de 33 horas de trabajo y la finalidad de generar series de tiempo de precipitación y temperatura extrema historica y futura, para diversos modelos y escenarios, que sirvan como imputs de los subsiguientes módulos de curso.

En el nivel básico, se comenzará con una descripción general de **R** y **Python**. Se discutirá acerca de la importancia del uso de herramientas de programación para la sistematización de los procesos de análisis de series de tiempo hidrometeorológicas, sus ventajas y limitaciones, la forma correcta de instalar y configurar, se mostrará algunos ejemplos disponibles en la literatura para ahondar en el mundo de la programación. Se presentará las nociones básicas de **RStudio** y **Anaconda**. Una introducción al lenguaje **R** y **Python**, los tipos de datos (dataframes, listas, diccionarios, etc.), funciones definidas por el usuario, cómo leer y guardar información en archivos de texto o formato CSV, cómo generar gráficos, etc.

En el nivel intermedio, manipularemos las series de tiempo observadas (producto PISCO precipitación y temperatura) para determinar la climatología de las zonas de estudio y algunos estadísticos descriptivos. También se sistematizará la descarga de las salidas de diversos modelos de circulación global a través de la programación. 

Finalmente, en el nivel avanzado, se llevará a cabo la regionalización de las salidas de los modelos de circulación global en base a las series de tiempo observadas para nuestras zonas de estudio definidas en el nivel anterior. Se probarán diversas técnicas de downscaling estadístico y se realizará una crítica de los resultados. Asimismo, se guardarán las series de tiempo historicas y futuras para los escenarios analizados con la finalidad de utilizarlas en el siguiente módulo del curso.

> ## Antes de empezar
>
> Los participantes deberán utilizar sus propias computadoras con acceso a internet
> a fin de asegurar un correcto desarrollo del módulo.
> <br>**Estas lecciones asumen que los participantes no presentan conomientos previos de programación en R ni Python.**
>
> Para comenzar, seguir el procedimiento mostrado en la pestaña "[Episodios]"
> y descargar la data proporcionada para el desarrollo de los ejercicios.
>
> #### Prerequisitos
>
> Las lecciones requieren de conocimientos de **métodos de análisis en hidrología**, **variabilidad y cambio climático en recursos hídricos** y **sistemas de información geográfica**.
{: .prereq}

{% include links.md %}
