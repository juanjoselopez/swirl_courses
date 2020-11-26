# Cursos con Swirl
*Traducción del paquete por Juan José E. López*

Esta es una colección de cursos de código abierto creados por la Universidad Johns Hopkins para funcionar con la paquetería [swirl R package](http://swirlstats.com). Aquí yacen las instrucciones de instalación, el equipo de la universidad esta constantemente mejorando y actualizando su contenido, con lo cual aceptan [sugerencias](https://github.com/swirldev/swirl_courses/issues/new).

para mayor información con respecto a swirl, visitar [swirlstats.com](http://swirlstats.com) o el [repositorio original en GitHub](https://github.com/swirldev/swirl). Si prefieren colaborar creando su propio contenido pueden visitar la [página de instructores](http://swirlstats.com/instructors.html) en el sitio web de swirl.

Realizaré la traducción de los cursos dispuestos originalmente por la universidad, manteniendo la política de código abierto y sin ningún fin económico detrás, sino más bien el propósito es llevar este contenido de calidad a todas las aulas de habla hispana del mundo. A continuación se enlistan los cursos según dificultad:

#### Introductorios

- **Programación en R**: Programación básica con lenguaje R.
<!-- - **Data Analysis**: Basic ideas in statistics and data visualization -->
<!-- - **Mathematical Biostatistics Boot Camp**: One- and two-sample t-tests, power, and sample size -->
<!-- - **Open Intro**: A very basic introduction to statistics, data analysis, and data visualization -->

\*\*\* *El curso fue modificado para notificar al instructor por email al finalizar el mismo, en el código original se generaba un key con créditos para la especialización en Coursera*

#### Intermedios

- **Modelos de Regresión**: Los modelos básicos de regresión en R.
- **Obtención y Limpieza de Datos**: Un curso escencial, pues gran parte del tiempo empleado en análisis se deriva a la obtención, la manipulación y la limpieza del dataset; se ven paqueterías como dplyr, tidyr, lubridate.

#### Avanzados

- **Estadística Inferencial**: Este curso fue pensado para complementar el curso
[Statistical Inference ](https://www.coursera.org/course/statinference) de la especialización de la Universidad Johns Hopkins en
[Data Science ](https://www.coursera.org/specialization/jhudatascience/1) para Coursera. Se introducen los conceptos básicos de inferencia estadística, como lo son las probabilidades, las pruebas de hipótesis, los intervalos de confianza y los p-valores. También se incluye una aproximación al Big Data y problemas del testeo múltiple y el "resampling".
- [**Programación Avanzada en R**](https://swirlstats.com/scn/arp.html)

Since our users come from a variety backgrounds, it's very hard to label material as **Beginner**, **Intermediate**, or **Advanced**. If you find something that is labelled **Beginner** to be challenging, please don't be discouraged. The first step of learning anything is to acknowledge that you are capable of understanding it. True understanding will come with time and practice.

## Instalar y Correr Swirl

**This is the preferred method of installing courses.** It automates the process by allowing you to do everything right from the R console.

1) Make sure you have a recent version version of swirl:

```
install.packages("swirl")
```

2) Enter the following from the R console, **substituting the name of the course** that you wish to install:

```
library(swirl)
install_course("Course Name Here")
swirl()
```

For example, `install_course("R Programming")` will install the R Programming course. **Please note that course names are case sensitive!**

If that doesn't work for you...

## Install and run a course manually

If the automatic course installation method outlined above does not work for you, then there's a simple alternative.

1. Find the course you want to install on the [Swirl Course network website](https://swirlstats.com/scn/title.html).
2. Follow the manual installation instructions on the course page.

If that does not work for you, consider taking a look at the 
[legacy manual install instructions](https://github.com/swirldev/swirl_courses/wiki/Legacy-Manual-Install-Instructions-for-Swirl-Courses).

## Uninstall a course

If you'd like to remove a course at any time, you can use `uninstall_course("Course Name Here")`.

## Using swirl in the classroom

Instructors around the world are using swirl in their classrooms. We think this is awesome. If you're an instructor, please feel free to do the same -- free of charge. While your students may be paying to take your course or attend your institution, we simply ask that you don't charge people *directly* for the use of our software or instructional content.

If you are not sure about a particular use case, don't hesitate to post a
question to our [Google Group](https://groups.google.com/forum/#!forum/swirl-discuss).
