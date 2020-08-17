---
layout: post
title: "Principales  modelos para el desarrollo de Software"
categories: junk
author:
  Tarea 2 
---

El proceso de desarrollo del software tiene como propósito la producción eficaz y eficiente de un producto software que reúna los requisitos del cliente. Un producto en software en si es complejo, es inviable conseguir un 100% de confiabilidad de un programa así sea pequeño.

No existe un proceso universal que sea efectivo para todos los contextos de proyectos de desarrollo, debito a esta diversidad es difícil automatizar todo un proceso de desarrollo de software, existe un conjunto de actividades fundamentales que se encuentran presentes en todos ellos.

## Modelo Cascada 

Es un proceso secuencial de desarrollo en el que los pasos de desarrollo son vistos hacia abajo a través de las fases de análisis de las necesidades, el diseño, implantación, pruebas, la integración, y mantenimiento.

Es el paradigma más antiguo y fue el más utilizado durante la hegemonía del método estructurado, el número de etapas propuestas varía de acuerdo al proyecto a desarrollar, aunque existen etapas comunes para este paradigma.

-   Definición de los requisitos. En este proceso se identifican las necesidades y requerimientos del cliente con respecto al software.
-   Análisis y Diseño. En el análisis se establece la viabilidad del software desde el punto de vista técnico y económico, se planifican las actividades y el presupuesto, en el diseño se centra en cuatro atributos de un programa: estructura de datos, arquitectura del software, representaciones de interfaz y detalle procedimental.
-   Codificación. Se traducir en forma legible por la máquina el modelo previamente diseñado. El paso de generación de código lleva a cabo esta tarea. Si lleva a cabo el diseño de una forma detallada, la generación de código se realiza mecánicamente.
-   Pruebas. El proceso de pruebas se centra en los procesos lógico interno del software, y en los procesos externos funcionales.  Se deben realizar las pruebas para detección de errores y asegurarse que las entradas definidas produzcan resultados reales que concuerden con los resultados requeridos.
-   Mantenimiento. El software indudablemente sufrirá cambios después de ser entregado al cliente. El mantenimiento vuelve a aplicar cada una de las fases precedentes a un programa ya existente y no a uno nuevo.

## Modelo de prototipo 

El modelo de prototipos permite desarrollar modelos de aplicaciones de software que permiten ver la funcionalidad básica de la misma, sin necesariamente incluir toda la lógica o características del modelo terminado. Permite al cliente evaluar en forma temprana el producto, e interactuar con los diseñadores y desarrolladores para saber si se está cumpliendo con las expectativas y las funcionalidades acordadas.

No poseen la funcionalidad total del sistema, pero si condensa la idea principal del mismo, Paso a Paso crece su funcionalidad, y maneja un alto grado de participación del usuario. El paradigma de construcción de prototipos comienza con la recolección de requisitos. El desarrollador y el cliente encuentran y definen los objetivos globales para el software, identifican los requisitos conocidos, y las áreas del esquema en donde es obligatoria más definición. Entonces aparece un “diseño rápido”.

##  Modelo Iterativo 

En un desarrollo iterativo e incremental el proyecto se planifica en diversos bloques temporales llamados iteraciones, las iteraciones se pueden entender como mini proyectos: en todas las iteraciones se repite un proceso de trabajo similar para proporcionar un resultado completo sobre producto final, de manera que el cliente pueda obtener los beneficios del proyecto de forma incremental.

Cada requisito se debe completar en una única iteración: el equipo debe realizar todas las tareas necesarias para completarlo (incluyendo pruebas y documentación) y que esté preparado para entregar al cliente con el mínimo esfuerzo necesario. De esta manera no se deja para el final del proyecto ninguna actividad arriesgada relacionada con la entrega de requisitos.

## Modelo componentes

Un diagrama de componentes es un diagrama representado en el Lenguaje Unificado de Modelado. Simboliza como un sistema de software es dividido en componentes y muestra las dependencias entre estos componentes.

Los componentes físicos incluyen archivos, cabeceras, bibliotecas compartidas, módulos, ejecutables, o paquetes. Estos diagramas prevalecen en el campo de la arquitectura de software, pero pueden ser usados para modelar y documentar cualquier arquitectura de sistema, debido a que los diagramas de componentes son más parecidos a los diagramas de usos, estos son utilizados para modelar la vista estática y dinámica de un sistema.

Muestra la organización y las dependencias entre un conjunto de componentes. No es necesario que un diagrama incluya todos los componentes del sistema, normalmente se realizan por partes y cada diagrama describe un apartado del sistema. 

##  Modelo orientado a objetos 

Los métodos de diseño estructurado surgieron para tutelar a los desarrolladores que intentaban construir sistemas complejos utilizando algoritmos como bloques fundamentales para la construcción de estos sistemas. Así, los métodos de diseño orientado a objetos han surgido para ayudar a los desarrolladores a explotar la potencia expresiva de los lenguajes de programación basados en objetos y orientados a objetos, utilizando las clases y los objetos como bloques básicos de construcción. La metodología orientada a objetos es un principio de desarrollo evolutivo, no revolucionario, porque no rompe con los avances del pasado, sino que los reestructura y los afianza de una forma que el desarrollo de aplicaciones o sistemas es mucho más sencillo y su proceso de desarrollo mucho más dinámico que con otras metodologías estructuradas.

El Diseño orientado a objetos (DOO) es el método que lleva una descomposición Orientada a Objetos, aplicando DOO, se crea software resistente al cambio y escrito con economía de expresión; se logra un mayor nivel de confianza en la corrección del software a través de la división inteligente de su espacio de estados y, en última instancia, se reducen los riesgos inherentes al desarrollo de sistemas.

## Modelo Espiral 

Tiene la finalidad de paliar los inconvenientes del modelo en cascada y adecuar el desarrollo por prototipos a problemas complejos, este paradigma combina el paradigma de cascada y el de construcción por prototipos, agregando una etapa de "análisis de riesgo".

Es un modelo de ciclo de vida orientado a riesgos que divide un proyecto software en mini proyectos y donde cada mini proyecto se centra en uno o más riesgos importantes hasta que todos estos estén controlados. Este modelo se realiza en varias iteraciones; se parte de una escala pequeña la cual comienza con la identificación de objetivos, alternativas y restricciones; en medio de la espiral, se localizan riesgos, se genera un plan para manejarlos, y a continuación se establece una aproximación a la siguiente iteración.

## Modelo Formal

Se usa para referirse a cualquier actividad relacionada con representaciones matemáticas del software, incluyendo la especificación formal de sistemas, análisis y demostración de la especificación, el desarrollo transformacional y la verificación de programas. Todas estas actividades dependen de una especificación formal del software.

Una especificación formal del software es una especificación expresada en un lenguaje cuyo vocabulario, sintaxis y semántica están formalmente bien definidos. Esta necesidad de una definición formal significa que los lenguajes de especificación deben basarse en conceptos matemáticos cuyas propiedades se comprendan bien. La rama de las matemáticas usadas es la de matemática discreta, y los conceptos matemáticos provienen de la teoría de conjuntos, la lógica y el álgebra.

En la década de los 80, muchos investigadores de ingeniería del software propusieron que el uso de métodos formales de desarrollo era la mejor forma de mejorar la calidad del software. Argumentaban que el rigor y el análisis detallado, que son una parte esencial de los métodos formales, podrían dar lugar a programas con menos errores y más adecuados a las necesidades de los usuarios.  Predijeron que, en el siglo XXI, una gran proporción del software estaría desarrollado usando métodos formales. Esta predicción no se ha hecho realidad por cuatro razones principales que son las siguientes.
